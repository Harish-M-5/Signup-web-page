### Signup-web-page
Modern two-page auth UI using html,tailwind css and JS.Clean login/signup screens with smooth navigation

---



### 🚀 Introduction

This project is a Two-Page Authentication UI built using React.js + Tailwind CSS.
It includes a Login Page and a Signup Page, smooth navigation between both screens, responsive layout, modern gradient backgrounds, and card-style UI components.


---

### 📘 Explanation

This UI template helps beginners understand how authentication pages are structured.
It demonstrates:

Navigating between multiple pages without Vite

Tailwind-based styling

Responsive design

Component splitting

Reusable classes


This project is frontend-only and does not include backend authentication logic.


---

### ⭐ Features

Modern Auth UI

Red & Orange Gradient Background

Glassmorphism Card Style

Login → Signup Page Navigation

Signup → Login Page Return

Fully Mobile Responsive

Clean Tailwind Utility Classes



---

### 🛠 Technology Used:

React.js – component-based UI

Tailwind CSS (CDN) – utility-first styling

HTML5 – structure

JavaScript (ES6) – interactive logic

React Router (optional) – page route handling



---

### 🧩 Code Explanation:

1. index.html

<script src="https://cdn.tailwindcss.com"></script>

✔ Loads Tailwind CSS directly
✔ No installation required



2. Background Container

className="min-h-screen bg-gradient-to-br from-red-500 to-orange-400 flex items-center justify-center"

min-h-screen: full height

bg-gradient-to-br: gradient background

from-red-500 to-orange-400: colors

flex items-center justify-center: centers the login card



3. Card Container

className="bg-white/20 backdrop-blur-lg p-8 rounded-2xl shadow-xl w-80"

bg-white/20: glass effect

backdrop-blur-lg: blur effect

rounded-2xl: rounded corners

shadow-xl: deep shadow

w-80: fixed card width



4. Input Box

className="w-full px-3 py-2 rounded-md bg-white text-gray-800 outline-none"

w-full: full width

px-3 py-2: padding

rounded-md: smooth corners

bg-white: input background

outline-none: removes default border




5. Button

className="w-full bg-red-600 hover:bg-red-700 text-white py-2 rounded-md"

bg-red-600 hover:bg-red-700: hover animation

rounded-md: smooth corners

py-2: height

text-white: button text color




6. Navigation Logic

const [page, setPage] = useState("login");

Maintains which page to show (login or signup)


{page === "login" ? <LoginPage setPage={setPage} /> : <SignupPage setPage={setPage} />}

If page = login → show login page

If page = signup → show signup page



7. Button Sending to Next Page

onClick={() => setPage("signup")}

✔ Moves to Signup page




8. Back Button Returning

onClick={() => setPage("login")}

✔ Comes back to Login Page



### 📂 Folder Structure

/Signup
 ├── index.html
 └── README.md 



---

### 📷 Output:
<img width="1920" height="1080" alt="Screenshot 2025-12-05 121042" src="https://github.com/user-attachments/assets/025dc711-632c-4b65-9d51-7d223b087cc3" />

<img width="1920" height="1080" alt="Screenshot 2025-12-05 121319" src="https://github.com/user-attachments/assets/2d698f16-9a24-455a-9bea-9b6d9f98c4b0" />

---

### 🎥Demo Video:


https://github.com/user-attachments/assets/cd40d1b6-1f00-49ff-8884-952db351f3ee

---

### 📜 License

This project is open-source under the MIT License.
You can use, modify, and distribute it freely.



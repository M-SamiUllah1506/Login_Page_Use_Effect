# React Authentication App

A simple React-based login/logout authentication application using localStorage to persist login state. This project demonstrates fundamental React concepts including state management, conditional rendering, reusable components, form validation, and hooks like `useState` and `useEffect`.

## 🚀 Features

- Login form with basic validation
- Protected content (visible only after login)
- Persistent login state using `localStorage`
- Logout functionality
- Clean and modular component structure

## 🛠️ Technologies Used

- React (Functional Components & Hooks)
- CSS Modules for component-scoped styling
- Local Storage API for session persistence



## 🧠 How It Works

- On loading the app, it checks `localStorage` for a login token.
- If found, it renders the Home component with a welcome message.
- If not logged in, the Login component is shown.
- Email must include "@" and password must be longer than 6 characters to enable the Login button.
- Once logged in, `localStorage.setItem("isLoggedIn", "Logged")` stores the login state.
- On logout, the state is cleared both from React and `localStorage`.

## 📸 Screenshots

### Login Screen
<img width="1903" height="994" alt="image" src="https://github.com/user-attachments/assets/f58e0e5a-f203-4c33-8074-1e5ed929f33e" />

### Home Screen (After Login)
<img width="1848" height="798" alt="image" src="https://github.com/user-attachments/assets/572686cd-d120-475e-9010-3afb34156753" />



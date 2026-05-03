# Login Authentication System

A simple login authentication system built with **HTML, CSS, and JavaScript** as part of the **AICTE OIB-SIP Web Development Internship**.

---

## Features

- **User Registration** — Create an account with name, email, and password
- **Secure Login** — Authenticate with email and password
- **Password Validation** — Minimum length and match checks
- **Session Management** — Uses `sessionStorage` to manage login state
- **Protected Dashboard** — Only accessible after login; redirects otherwise
- **Auto Redirect** — After login/register, user is redirected automatically
- **Clean UI** — Minimal, responsive design

---

## Tech Stack

| Layer    | Technology           |
|----------|----------------------|
| Markup   | HTML5                |
| Styling  | CSS3                 |
| Logic    | Vanilla JavaScript   |
| Storage  | localStorage / sessionStorage |

---

## Project Structure

```
login-auth/
├── login.html       # Login page
├── register.html    # Registration page
├── dashboard.html   # Protected dashboard (secured page)
├── style.css        # Shared styles
└── README.md
```

---

## How to Run

No installation needed! Just open the files in a browser:

1. Open `login.html` in any browser
2. Click **"Create one"** to register a new account
3. After registering, log in with your credentials
4. You'll be taken to the secured **Dashboard** page
5. Click **Sign out** to logout

---

## How It Works

1. **Register** → User details saved to `localStorage` with base64-encoded password
2. **Login** → Credentials checked against `localStorage`; session stored in `sessionStorage`
3. **Dashboard** → Checks `sessionStorage` for active session; redirects to login if not found
4. **Logout** → Clears `sessionStorage` and redirects to login

---

## Internship

This project was built as part of the **AICTE OIB-SIP (Oasis Infobyte Summer Internship Program)** — Web Development & Design Track.

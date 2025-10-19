# Password-Protected Page (Node.js + Express)

This is a simple Node.js web application that demonstrates a basic password protection using Express. Users enter a password on the homepage; if correct, they access a secret page. Otherwise, they are redirected back with an error.

---

## Technologies Used

- Node.js – JavaScript runtime  
- Express.js – Web server framework  
- body-parser – Middleware to parse form data  
- HTML – For frontend pages (no CSS included)  

---

## Project Summary

This project serves static HTML pages and handles form submissions. It checks the password entered by the user and either grants access to a secret page or redirects back with an error.

---

## Features

- Serves a login form (`index.html`)  
- Processes password via POST request  
- Validates password on the server (`BEAST`)  
- Redirects to `secret.html` on success  
- Redirects back with error on failure  

---

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/Rudhar-cmd/password-protected-site.git

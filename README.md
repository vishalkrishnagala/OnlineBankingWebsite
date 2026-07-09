# Paylum Bank

A modern Online Banking Website built using HTML, CSS, JavaScript and Supabase.

## Features

- User Registration
- User Login
- OTP Verification using EmailJS
- Password Reset
- Fund Transfer
- Transaction History
- Account Statement
- Kiddy Wallet
- Responsive UI

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Supabase
- EmailJS

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2. Open the project

Open the project folder in VS Code.

### 3. Configure Supabase

Open:

```
config/supabaseClient.js
```

Replace the following values with your own Supabase Project URL and Anon Key.

```javascript
const supabaseUrl = "YOUR_SUPABASE_URL";
const supabaseKey = "YOUR_SUPABASE_ANON_KEY";
```

### 4. Configure EmailJS

Open:

```
config/emailjs.js
```

Replace the following values:

```javascript
export const EMAILJS_PUBLIC_KEY = "YOUR_PUBLIC_KEY";
export const EMAILJS_SERVICE_ID = "YOUR_SERVICE_ID";
export const EMAILJS_TEMPLATE_ID = "YOUR_TEMPLATE_ID";
```

Create your own EmailJS account at:

https://www.emailjs.com/

### 5. Database

Create your own Supabase project and create the required tables.

## Important

This repository does **not** include my personal API keys.

Replace all placeholder values with your own before running the project.

## License

This project is for educational purposes.
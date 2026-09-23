WELCOME / SIGNUP / LOGIN WEBSITE
=================================

WHAT'S INCLUDED
----------------
- index.html    Homepage with a welcome message and two buttons: Sign up, Log in
- signup.html   Form for entering personal details (name, email, phone, DOB, password)
- login.html    Form for entering email and password
- style.css     Shared styling used by all three pages
- readme.txt    This file

HOW TO USE IT
--------------
1. Put all four files (index.html, signup.html, login.html, style.css) in the
   SAME folder — don't rename them, since the pages link to each other by
   these exact filenames.
2. Double-click index.html to open it in your browser. No server or
   installation is needed.

HOW IT WORKS
-------------
- Homepage (index.html): shows a welcome message with two buttons.
    - "Sign up" goes to signup.html
    - "Log in" goes to login.html
- Sign up page (signup.html): collects first name, last name, email, phone,
  date of birth, and a password. Submitting the form takes you back to the
  homepage, which shows a short "you're all set" confirmation message.
- Login page (login.html): collects email and password. Submitting the form
  takes you back to the homepage, which shows a "welcome back" message.
- Both back-to-homepage links also work without submitting the form, if you
  just want to return without finishing.

IMPORTANT NOTE — NO REAL BACKEND
----------------------------------
This is a front-end-only demo:
- Nothing is sent to a server, and no account is actually created.
- The form data is NOT saved anywhere except your first name, which is
  stored in your browser's local storage purely so the homepage can greet
  you by name after signing up or logging in.
- Any email/password will "work" on the login page, since there's no real
  authentication check — it simply returns you to the homepage.

If you'd like this connected to a real backend (actual account storage,
password checks, etc.), that would need a server and a database — let me
know and I can help you build that next.

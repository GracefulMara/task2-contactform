Task 2 – Tech Class Feedback Form 📝

This is a simple HTML feedback form created as part of the Upskill Web Development Track (Week 2).

It allows learners to submit structured feedback after a tech class session, including details like their learning track, satisfaction level, and suggestions for improvement.


🌐 Live Preview

> To test the form properly (including redirection), open it using Live Server in VS Code or host it via GitHub Pages.


🧩 Features

- Collects user info (Name, Email, Phone)
- Captures selected learning track (Radio buttons)
- Allows multiple improvement suggestions (Checkboxes)
- Feedback rating via dropdown
- Textarea for open feedback (likes & improvements)
- Clean redirect to a custom Thank You page after submission
- Accessible structure using `<fieldset>` and `<legend>`


📥 How It Works

The form uses [FormSubmit](https://formsubmit.co) to send form data to the developer’s email address without needing a backend.

```html
<form action="https://formsubmit.co/your-email" method="POST">
```

🔒 CAPTCHA is enabled to reduce spam.  
🚀 After submission, users are redirected to `Thankyou.html`.

---

✅ What I Learned

- Structuring HTML forms semantically
- Using radio buttons, checkboxes, and dropdowns effectively
- How to redirect users after form submission
- Basics of working with Git & GitHub for version control



🛠️ Author

Grace Aronu  
[GitHub Profile →](https://github.com/GracefulMara)
---

📌 Note

This project is part of an ongoing learning process. Suggestions and feedback are welcome!
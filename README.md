# Flask Web App Tutorial - BLOG

## Blog Webpage Features

This blog page is built using Flask and offers key features that enhance the user experience and authentication

📝 **User Authentication:**
- Users can sign up, log in, and manage their accounts securely.
- Passwords are hashed for security using Flask extensions like Flask-Bcrypt.
- Users can log out and view a secure area where they can interact with blog posts.



## Setup & Installation

Make sure you have the latest version of Python installed.

```bash
git clone <repo-url>
```


## Running The App

```bash
python main.py
```

## Viewing The App

Go to `http://127.0.0.1:5000`


# 💻 Start your backend journey Today!  

🎓 **From I dont know Backend...** I just got interest and started to explore backend too. Why should I say I dont know backend. Now I can say I know backend. **Everything starts from the spark. If you have that spark you will!**  

🚀 **Why Flask?**  
- 🚀 **Build Scalable Applications:** Flask allows you to create powerful, scalable backend systems with minimal complexity, making it ideal for both beginners and advanced developers.
- 🔧 **Flexible & Lightweight:** With its minimalist approach, Flask gives you full control over how your application is structured, without enforcing unnecessary constraints.
- 🌍 **Large Community & Resources:** Flask's active community ensures plenty of tutorials, plugins, and documentation, making learning and problem-solving easier than ever.
- 🔒 **Secure & Reliable:** Flask offers built-in tools and extensions to secure your application, enabling you to handle user authentication, form validation, and more with ease.

## Project Structure

Here's an overview of the key files in the project:

### app.py
This is the main file that runs the Flask app. It initializes the app, handles routes, and starts the server.

### model.py
This file defines the database structure. It uses SQLAlchemy to create and manage your database models, allowing you to store and retrieve data effectively.

### auth.py
Handles user authentication. This file includes functions for user login, registration, and managing sessions. It ensures that users can securely sign in and out of the app.

### views.py
Contains the code to delete file in the notes and to for other purpose.


One-Time Token (OTT) Authentication System

📌 Project Overview

This project implements a One-Time Token (OTT) Authentication System using Spring Boot and Spring Security. The system generates a unique token for users upon request, sends it via email, and allows them to authenticate using a magic link containing the token. This approach enhances security by enabling passwordless login.

🚀 How It Works

User Initiates Request:

The user requests a login via the OTT endpoint.

Token Generation:

A unique one-time token is generated.

Magic Link Creation:

The token is embedded in a URL, forming a magic link.

Email Notification:

The link is sent to the user's email using Spring Boot's email service.

User Authentication:

The user clicks the link, and the server validates the token.

Secure Access:

Once authenticated, the user gains access to the application.

🔧 Dependencies Used

The following dependencies are required to run this project:

Spring Boot Mail Starter

Spring Boot Security Starter

Spring Boot Web Starter

📧 Email Configuration

Ensure you have enabled App Passwords in Gmail and update your email configurations accordingly.

🏁 Getting Started

Prerequisites

Java 17+

Maven

Spring Boot 3+

Steps to Run

Clone the repository:

Configure Email:

Add your Gmail and App Password.

Build and Run the Application:

Access the App:

Test the OTT flow by navigating to the appropriate endpoint.

🔒 Security Configuration

The security is configured using Spring Security with in-memory user store for testing. Public and protected endpoints are properly defined.

📚 Resources and Documentation

Official Documentation

Spring Security Docs

Spring Boot Docs

Tutorials and Guides

Spring Boot Email Sending Tutorial

Spring Security In-memory Authentication

## 📸 Demo


Here's a preview of the OTT Authentication System in action:

![Result](path/to/your/image.png)

📬 Contact

If you have any questions or suggestions, feel free to connect with me:

LinkedIn: Nikhil Raj

GitHub: Nikhil Raj

Email: nikhilraj2277@gmail.com

✨ Conclusion

This One-Time Token Authentication System provides a secure and user-friendly way to authenticate users without relying on passwords. The project is designed with flexibility, making it easy to extend with JWT tokens, Redis caching, or microservices architecture.

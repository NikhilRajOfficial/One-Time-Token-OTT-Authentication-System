# One-Time Token (OTT) Authentication System

## 📌 Project Overview
This project implements a **One-Time Token (OTT) Authentication System** using **Spring Boot** and **Spring Security**. The system generates a unique token for users upon request, sends it via email, and allows them to authenticate using a magic link containing the token. This approach enhances security by enabling passwordless login.

---

## 🚀 How It Works
1. **User Initiates Request:**
   - The user requests a login via the OTT endpoint.
   
2. **Token Generation:**
   - A unique one-time token is generated.
   
3. **Magic Link Creation:**
   - The token is embedded in a URL, forming a magic link.

4. **Email Notification:**
   - The link is sent to the user's email using Spring Boot's email service.

5. **User Authentication:**
   - The user clicks the link, and the server validates the token.
   
6. **Secure Access:**
   - Once authenticated, the user gains access to the application.

---

## 🔧 Dependencies Used
The following dependencies are required to run this project:

- Spring Boot Mail Starter
- Spring Boot Security Starter
- Spring Boot Web Starter

---

## 📧 Email Configuration
Ensure you have enabled **App Passwords** in Gmail and update your email configurations accordingly.

---

## 🏁 Getting Started

### Prerequisites
- Java 17+
- Maven
- Spring Boot 3+

### Steps to Run
1. **Clone the repository:**
2. **Configure Email:**
   - Add your Gmail and App Password.
3. **Build and Run the Application:**
4. **Access the App:**
   - Test the OTT flow by navigating to the appropriate endpoint.

---

## 🔒 Security Configuration
The security is configured using Spring Security with in-memory user store for testing. Public and protected endpoints are properly defined.

---
## 📸 Demo


Here's a preview of the OTT Authentication System in action:

![Result](path/to/your/image.png)

---

## 📚 Resources and Documentation

### Official Documentation
- [Spring Security Docs](https://docs.spring.io/spring-security/reference/index.html)
- [Spring Boot Docs](https://docs.spring.io/spring-boot/docs/current/reference/html/)

### Tutorials and Guides
- [Spring Boot Email Sending Tutorial](https://www.youtube.com/watch?v=5hPVzjQSJt8)
- [Spring Security In-memory Authentication](https://www.youtube.com/watch?v=X80nJ5g2Lfo)

---

## 📬 Contact
If you have any questions or suggestions, feel free to connect with me:

- **LinkedIn:** [Nikhil Raj](https://www.linkedin.com/in/nikhilraj620/)
- **GitHub:** [Nikhil Raj](https://github.com/NikhilRajOfficial)
- **Email:** nikhilraj2277@gmail.com

---

## ✨ Conclusion
This One-Time Token Authentication System provides a secure and user-friendly way to authenticate users without relying on passwords. The project is designed with flexibility, making it easy to extend with JWT tokens, Redis caching, or microservices architecture.

---

Would you like to extend this with JWT tokens or Redis integration? Let’s build something even more powerful together! 🚀


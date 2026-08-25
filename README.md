# 🔐 Graphical Password Authentication

A **cybersecurity-focused authentication project** developed using **ASP.NET, C#, JavaScript, and Microsoft SQL Server**.

This project explores an alternative to traditional text-based authentication by implementing a **graphical password mechanism**. Instead of entering a conventional password, users authenticate by reconstructing an image from segmented fragments.

The system demonstrates concepts related to **user authentication, access control, graphical passwords, and credential security**.

## 🛡️ Security Features

* User registration and authentication
* Image-based graphical password mechanism
* Image segmentation and fragment storage
* Jumbled image fragments during authentication
* Image reconstruction-based verification
* Authentication validation and access control
* Invalid login attempt detection 
* Login attempt alerts

## 🔄 Authentication Workflow

1. The user registers and selects an image as a graphical password.
2. The system segments the image into multiple fragments.
3. The fragments and their original arrangement are stored for authentication.
4. During login, the image fragments are presented in a jumbled order.
5. The user reconstructs the image by arranging the fragments correctly.
6. The system verifies the authentication attempt.
7. Access is granted or denied based on the verification result.

## 🎯 Security Concept

Traditional authentication systems commonly rely on text-based passwords, which can be vulnerable to attacks such as password guessing and credential compromise.

This project explores **graphical authentication** as an alternative approach where authentication depends on the user's ability to recognize and reconstruct a selected image.

The project focuses on demonstrating:

* 🔑 Authentication mechanisms
* 🛡️ Access control
* 🖼️ Graphical password security
* 🔐 Credential protection concepts
* 🚨 Failed authentication monitoring

## 🛠️ Technologies Used

* **Frontend:** ASP.NET, JavaScript
* **Backend:** C#
* **Database:** Microsoft SQL Server
* **Development Environment:** Visual Studio

## 🚀 Getting Started

### Prerequisites

* Visual Studio
* ASP.NET / .NET
* Microsoft SQL Server

### Installation

```bash id="r85h3t"
git clone https://github.com/shain-sec/graphical-password-authentication.git
cd graphical-password-authentication
```

Open the project in **Visual Studio**, configure the database connection, and run the application.

## 🎓 Project Purpose

This project was developed as an academic cybersecurity project to explore **graphical password authentication** and alternative authentication mechanisms.

It demonstrates how image-based interaction can be incorporated into an authentication workflow instead of relying solely on conventional text-based passwords.

## 👨‍💻 Author

**Muhammed Shain**

## ⚠️ Disclaimer

This project was developed for **academic and educational purposes**. It demonstrates authentication and graphical password concepts and is not intended to be used as a production-ready security solution without additional security testing and improvements.

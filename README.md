# 🔐 Graphical Password Authentication

A web-based **Graphical Password Authentication System** developed as an academic project using **ASP.NET, C#, JavaScript, and Microsoft SQL Server**.

The system provides an alternative to traditional text-based passwords by using an image as a graphical password. During registration, the user's selected image is divided into multiple fragments. During authentication, the fragments are presented in a jumbled order, and the user must reconstruct the original image in the correct sequence.

## 📌 Overview

Traditional text-based passwords can be vulnerable to password guessing, credential reuse, keylogging, and other attacks. Graphical authentication provides an alternative approach based on visual memory and user interaction.

In this system, the user selects an image during registration. The image is divided into multiple segments using coordinate-based image segmentation. The segments are stored according to their original positions.

During login, the segments are displayed in a jumbled order. The user must arrange the fragments correctly to reconstruct the original image. The system verifies the selected sequence against the original arrangement.

- ✅ Correct sequence → Authentication successful
- ❌ Incorrect sequence → Authentication failed

Repeated failed authentication attempts can trigger login alerts and temporary account blocking.

## ✨ Features

- User registration and login
- Image-based graphical password
- Coordinate-based image segmentation
- Image fragment storage
- Randomized/jumbled image fragments
- Image reconstruction-based authentication
- Authentication attempt validation
- Login attempt alerts
- Temporary login blocking after repeated failures
- Microsoft SQL Server database integration

## 🔄 How It Works

### 1. Registration

The user registers with the system and selects an image to use as a graphical password.

### 2. Image Segmentation

The selected image is divided into multiple fragments using coordinate-based segmentation.

### 3. Fragment Storage

The generated fragments are stored according to their original positions.

### 4. Authentication

During login, the stored fragments are presented in a jumbled order.

### 5. Image Reconstruction

The user arranges the fragments in the correct order to reconstruct the original image.

### 6. Verification

The system compares the user's arrangement with the original fragment sequence.

If the sequence is correct, the user is authenticated. Otherwise, authentication fails.

## 🧩 Functional Modules

### Image Submission Module

Collects user information and the image selected as the graphical password.

### Image Fragmentation Module

Divides the selected image into multiple fragments using coordinate-based segmentation.

### Image Fragment Storage Module

Stores the generated image fragments and their corresponding positions.

### Image Jumbling Module

Randomizes the order of image fragments during authentication.

### Authentication Module

Verifies the user's selected fragment sequence against the original arrangement.

### Alert Module

Handles failed authentication attempts and login attempt alerts.

## 🔑 Authentication Concepts

The project explores multiple graphical authentication approaches, including:

- **Recognition-Based Authentication**
- **Recall-Based Authentication**
- **Cued Recall Authentication**
- **Colour Grade-Based Authentication**
- **Click-Point Authentication**
- **Alternating Session Passwords**

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **ASP.NET** | Web application development |
| **C#** | Application logic and authentication |
| **JavaScript** | Client-side functionality |
| **Microsoft SQL Server** | Database management |
| **IIS** | Web server |
| **Visual Studio** | Development environment |

### Installation

Clone the repository:

```bash
git clone https://github.com/shain-sec/graphical-password-authentication.git

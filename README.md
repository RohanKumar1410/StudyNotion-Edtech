
## 📚 StudyNotion – EdTech Platform

**StudyNotion** is a full-stack **EdTech platform** designed to provide students with an easy way to discover, purchase, and access online courses. It also provides instructors with tools to manage course content and receive feedback from students.

## 🚀 Project Overview

The goal of StudyNotion is to create a complete online learning platform that connects **students and instructors** in one place.

Students can explore available courses, purchase courses through an integrated payment gateway, and access learning content. Instructors can manage their course content and analyze student feedback through the course rating and feedback system.

The application was developed using the **MERN stack**, with React.js for the frontend and Node.js, Express.js, and MongoDB for the backend.

## ✨ Features

### 👨‍🎓 Student Features

* Browse and explore available courses
* View course details
* Purchase courses securely
* Access purchased course content
* Submit course feedback and ratings

### 👨‍🏫 Instructor Features

* Create and manage courses
* Upload course-related media
* Manage course content
* Receive student feedback and ratings
* Get useful insights from course reviews

### 🔐 Authentication & Security

* JWT-based authentication
* OTP verification
* Secure user onboarding
* Password and authentication management

OTP verification is implemented using **NodeMailer**.

### ☁️ Media Management

**Cloudinary** is integrated for handling course media, including:

* Uploading course content
* Storing media
* Retrieving media when required

### ⭐ Course Feedback & Rating

A feedback and rating system allows students to share their experience with courses and provides instructors with useful insights and analytics.

### 💳 Payment Integration

Integrated **Razorpay Payment Gateway** to enable secure transactions for purchasing courses.

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5
* CSS3
* Tailwind CSS

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB

### Authentication

* JWT
* OTP Verification
* NodeMailer

### Cloud Storage

* Cloudinary

### Payment

* Razorpay

### Development Tools

* Git
* GitHub
* VS Code

## 🏗️ Project Architecture

```text
                         ┌──────────────────┐
                         │      Users       │
                         └────────┬─────────┘
                                  │
                                  ▼
                         ┌──────────────────┐
                         │  React Frontend  │
                         │   StudyNotion    │
                         └────────┬─────────┘
                                  │
                             REST APIs
                                  │
                                  ▼
                         ┌──────────────────┐
                         │ Node.js +        │
                         │ Express.js       │
                         └───────┬──────────┘
                                 │
                   ┌─────────────┼─────────────┐
                   │             │             │
                   ▼             ▼             ▼
             ┌──────────┐  ┌──────────┐  ┌──────────┐
             │ MongoDB  │  │Cloudinary│  │ Razorpay │
             │ Database │  │  Media   │  │ Payments │
             └──────────┘  └──────────┘  └──────────┘
```

## 🔄 Application Flow

```text
User
 │
 ▼
Register / Login
 │
 ▼
OTP Verification
 │
 ▼
Browse Courses
 │
 ▼
Select Course
 │
 ▼
Razorpay Payment
 │
 ▼
Course Purchase
 │
 ▼
Access Course Content
 │
 ▼
Submit Rating & Feedback
```

## 🎯 Problem Statement

Traditional online learning platforms can make it difficult to manage the complete learning process in one place.

StudyNotion provides a unified platform where **students can discover and purchase courses**, while **instructors can manage educational content and receive feedback** from learners.

## 🎯 Project Objectives

* Build a complete online learning platform.
* Provide a responsive and user-friendly interface.
* Enable secure user authentication.
* Allow students to purchase courses online.
* Provide instructors with course management functionality.
* Enable secure media storage and retrieval.
* Collect course ratings and feedback.
* Provide secure online payment functionality.

## 🔑 Key Learning

Through this project, I gained practical experience in:

* Building reusable React components
* Developing RESTful APIs
* Connecting frontend with backend
* JWT authentication
* OTP-based verification
* MongoDB database operations
* Cloudinary integration
* Payment gateway integration
* Managing application state
* Building scalable full-stack applications

##Pages

```text
- Home Page
- Course Listing
- Course Details
- Login / Signup
- Student Dashboard
- Instructor Dashboard
- Course Management
- Payment Page
- Feedback & Rating
```

## 🔮 Future Improvements

* Add live classes and video conferencing.
* Add course progress tracking.
* Add certificates after course completion.
* Add advanced course search and filtering.
* Add personalized course recommendations.
* Add instructor analytics dashboards.

## 👨‍💻 Developer

**Rohan Kumar**

---

⭐ **If you find this project useful, consider giving the repository a star!**

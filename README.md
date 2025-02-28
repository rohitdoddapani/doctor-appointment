# 🏥 Doctor Appointment System

Welcome to our **Doctor Appointment System**, a comprehensive healthcare platform designed to provide a seamless experience for both users and doctors. This platform allows patients to **register, book appointments, update their profiles**, and receive **notifications** about their medical interactions. Additionally, **doctors** can apply for listings, manage appointments, and interact with patients. The **admin panel** ensures smooth operations by handling doctor approvals, managing users, and overseeing appointments.

---

## 🚀 Features

### **User Features**  
✅ **User Registration & Login** – Secure authentication for patients and doctors.  
✅ **View Available Doctors** – Browse and filter doctors based on specialization.  
✅ **Profile Management** – Update personal details, contact information, and medical history.  
✅ **Book Appointments** – Schedule appointments with preferred doctors.  
✅ **Contact for Queries** – Users can reach out for medical inquiries and support.  
✅ **Receive Notifications** – Stay updated on **appointment reminders**, doctor approvals, and system updates.  

### **Doctor Features**  
✅ **Doctor Application System** – Aspiring doctors can apply for listing on the platform.  
✅ **Manage Appointments** – Accept or decline patient bookings.  
✅ **Mark Appointments as Completed** – Keep track of finished consultations.  

### **Admin Features**  
✅ **Admin Dashboard** – Centralized system to manage users, doctors, and appointments.  
✅ **Approve/Reject Doctor Applications** – Ensure only qualified professionals are listed.  
✅ **User & Doctor Management** – Remove or deactivate accounts if necessary.  
✅ **Monitor Appointments** – Oversee booking trends and platform activity.  

### **Security & Data Storage**  
✅ **Access Control** – Restricted access to sensitive sections (profile, appointments, doctor applications).  
✅ **Secure Data Storage** – All information is securely stored in a **MongoDB** database.  
✅ **Role-Based Authentication** – Different access levels for users, doctors, and admins.  

---

## 🛠️ Technologies Used

This project is built using the following technologies:

- **Frontend:**
  - HTML5, CSS3, JavaScript
  - **React.js**
  - Redux Toolkit for state management

- **Backend:**
  - **Node.js** (Express.js framework)
  - **MongoDB** (Database)
  - Mongoose ORM

- **Authentication & Security:**
  - JSON Web Tokens (JWT) for authentication
  - Bcrypt for password hashing
  - Cloudinary for image uploads

---

## ⚙️ Installation & Setup

Follow these steps to set up the project locally:

### **Prerequisites**
Ensure you have the following installed:

- **Node.js** (v14+ recommended) → [Download here](https://nodejs.org/)
- **MongoDB** (or MongoDB Atlas for cloud-based storage)
- **Git** (optional, for version control)

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/yourusername/doctor-appointment.git
cd doctor-appointment
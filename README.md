## Prescription Management System

## 📌 Overview
The **Prescription Management System** is a web-based application that allows doctors to manage prescriptions and patients, pharmacists can access digitally.  
It reduces paperwork, improves accessibility, and ensures accurate prescription records.

## 🚀 Features
- **User Roles**: Doctor.
- **Digital Prescription Management**: Create, update, and retrieve prescriptions and sends prescription link and QR code SMS to patients mobile number.
- **Medicine Tracking**: Maintain medicine records and availability.
- **Authentication & Authorization**: Secure access using middleware.
- **Database Integration**: Store all records like Medicine,Prescriptions with user information persistently in a database.

## 🛠️ Tech Stack
- **Frontend**: React (inside `/frontend` folder)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT (JSON Web Token)
- **Tools**: Twilio to send Message, Cloudinary to store the precription created.
- **Environment Config**: `.env` for secure keys and DB connection

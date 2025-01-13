# Prescripto - Doctor Appointment Booking System

Prescripto is a feature-rich Full Stack Doctor Appointment Booking System designed to streamline the process of managing appointments, doctor profiles, and payments. Built using the MERN Stack (MongoDB, Express JS, React JS, Node JS), this project caters to the needs of patients, doctors, and administrators with dedicated functionalities for each user role.

## 🚀 Features

### 🌟 Patient Features
- **Seamless Registration and Login:** Easy access for patients to create and manage accounts.
- **Appointment Booking:** Effortlessly book appointments with doctors.
- **Appointment Management:** View, reschedule, or cancel booked appointments.
- **Secure Online Payments:** Pay appointment fees directly through the platform.

### 🌟 Doctor Features
- **Dedicated Dashboard:** View and manage upcoming appointments.
- **Earnings Overview:** Check earnings from appointments.
- **Profile Management:** Update personal and professional information.

### 🌟 Admin Features
- **Admin Dashboard:** Comprehensive control over the system.
- **Appointment Management:** View and manage all appointments.
- **Doctor Management:** Add, update, or remove doctor profiles.

### Additional Highlights
- **3 Levels of Authentication:** Separate access for Patients, Doctors, and Admins.
- **Online Payment Gateway Integration:** Secure and efficient payment system.
- Fully customizable for college projects or professional portfolios.

---

## 🛠️ Tech Stack

| Technology       | Purpose            |
|------------------|--------------------|
| **React JS**     | Frontend Framework |
| **Node JS**      | Backend Runtime    |
| **Express JS**   | Backend Framework  |
| **MongoDB**      | Database           |
| **Payment Gateway** | Online Payment Integration |

---

## 🏃‍♂️ Getting Started

### Prerequisites
- Node.js installed
- MongoDB installed or access to a cloud MongoDB instance

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/prescripto.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd prescripto
   ```

3. **Install dependencies:**
   - Backend:
     ```bash
     cd backend
     npm install
     ```
   - Frontend:
     ```bash
     cd ../frontend
     npm install
     ```

4. **Configure environment variables:**
   - Create a `.env` file in the `backend` directory with the following:
     ```
     MONGO_URI=your_mongo_connection_string
     JWT_SECRET=your_jwt_secret
     PAYMENT_GATEWAY_KEY=your_payment_gateway_key
     ```

5. **Run the application:**
   - Start the backend:
     ```bash
     cd backend
     npm start
     ```
   - Start the frontend:
     ```bash
     cd ../frontend
     npm start
     ```

6. **Access the application:**
   Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## 🌐 Project Demo

![Prescripto Screenshot](https://via.placeholder.com/800x400?text=Project+Demo)

_Link to live demo or video walkthrough._

---

## 📂 Folder Structure

```
prescripto/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
└── README.md
```

---

## 🚧 Future Enhancements

- Implement email and SMS notifications for appointment reminders.
- Add multi-language support.
- Expand analytics in the admin dashboard.

---


## 🙌 Acknowledgements

- Inspired by [YouTube Tutorial]([https://youtu.be/eRTTlS0zaW8?feature=shared]) .
- Special thanks to the open-source community for tools and libraries.

---

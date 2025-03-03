# AutoEntry - Smart Gate Access System 🚪🎓  

![MERN Stack](https://img.shields.io/badge/MERN-Stack-green)  
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen)  
![Node.js](https://img.shields.io/badge/Backend-Node.js-lightgrey)  
![React](https://img.shields.io/badge/Frontend-React-blue)  

## 📌 Overview  
AutoEntry is a **MERN stack-based** smart gate access system where security personnel **manually enter student IDs** to log entry/exit records in real time. The system fetches **student details (name, mobile number) from MongoDB** and records the **date & time** of each movement at the institute's gate.  

## 🚀 Features  
✅ **Manual Student ID Entry** – Security personnel enter student IDs manually.  
✅ **Real-Time Logging** – Automatically records entry and exit timestamps.  
✅ **Database Integration** – Fetches student details from **MongoDB**.  
✅ **User-Friendly Interface** – Simple and responsive web UI.  
✅ **Secure & Efficient** – Ensures accurate record-keeping.  

## 🛠 Tech Stack  
- **Frontend**: React.js ⚛️  
- **Backend**: Node.js, Express.js 🚀  
- **Database**: MongoDB 🍃   

## 📌 How It Works  
1️⃣ **Security personnel enters the student ID**.  
2️⃣ **Fetch student details** – The backend queries MongoDB.  
3️⃣ **Log entry/exit** – Date, time, and student info are recorded.  
4️⃣ **Display status** – Security personnel can see logs on the UI.  

## 🏗 Installation & Setup  
1. Clone the repository:  
   ```sh
   git clone https://github.com/yourusername/autoentry.git
   cd autoentry
   ```
2. Install dependencies:  
   ```sh
   npm install
   cd client
   npm install
   ```
3. Set up environment variables (`.env` file):  
   ```
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```
4. Start the backend:  
   ```sh
   npm start
   ```
5. Start the frontend:  
   ```sh
   cd client
   npm start
   ```

## 🤝 Contribution  
Feel free to contribute by improving security, UI, or adding new features. Fork the repository and submit a pull request.  

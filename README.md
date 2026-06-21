# 📍 Geolocation Based Attendance System

A smart **Geolocation-Based Attendance System** built with **React.js** that automatically verifies and marks student attendance based on their real-time GPS location.

The application uses the **Browser Geolocation API** to compare a user's current latitude and longitude with predefined campus coordinates, ensuring attendance is recorded only when the user is physically present within the authorized location.

---

# 🌐 Live Demo

🚀 **Application:**  
👉 https://geolocation-attendance.vercel.app/

---

# 📌 Project Status

**✅ MVP (Minimum Viable Product) | Portfolio Project**

---

# 🚀 Features

- 📍 Automatic attendance marking using GPS
- 🛰️ Real-time location detection using Browser Geolocation API
- 🎯 Campus boundary validation using latitude & longitude
- ⚡ Fast and responsive React interface
- 📱 Mobile-friendly design
- 🌐 Live deployment on Vercel
- 🔒 Secure location-based verification

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|--------------------------------|
| **React.js** | Frontend Development |
| **JavaScript (ES6)** | Application Logic |
| **HTML5** | Structure |
| **CSS3** | Responsive Styling |
| **Browser Geolocation API** | GPS Location Tracking |
| **Vercel** | Deployment & Hosting |

---

# 🏗️ System Architecture

```text
                  Student
                      │
                      ▼
        Browser Geolocation API
                      │
                      ▼
      Latitude & Longitude Fetch
                      │
                      ▼
      Campus Location Verification
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
 Inside Campus             Outside Campus
          │                       │
          ▼                       ▼
 Attendance Marked        Attendance Rejected
```

---

# 📸 Application Preview

## 🏠 Attendance Dashboard

![Attendance Dashboard](https://github.com/user-attachments/assets/a605721e-9f68-4c36-aede-5a4596f5abf2)

## 📍 Location Verification

> Replace the placeholder below with your second screenshot.

```markdown
![Location Verification](https://github.com/user-attachments/assets/your-second-image-id)
```

---

# 🎥 Project Demonstration

> Add your project demonstration video links below.

### ▶️ Demo Video 1

https://your-demo-video-link

### ▶️ Demo Video 2

https://your-demo-video-link

---

# ⚙️ How It Works

1. User opens the application.
2. Browser requests permission to access GPS location.
3. Current latitude and longitude are retrieved.
4. The application compares user coordinates with predefined campus coordinates.
5. If the user is inside the allowed radius, attendance is automatically marked.
6. Otherwise, attendance is denied.

---

# 🌟 Key Benefits

- Eliminates manual attendance processes.
- Prevents proxy attendance.
- Uses real-time GPS verification.
- Fast and easy to use.
- Accessible from desktop and mobile devices.
- Simple and scalable architecture.

---

# 📥 Installation

## Clone the Repository

```bash
git clone https://github.com/chandruch1/geolocation-attendance.git
```

## Navigate to the Project

```bash
cd geolocation-attendance
```

## Install Dependencies

```bash
npm install
```

## Run Development Server

```bash
npm start
```

or

```bash
npm run dev
```

The application will be available at

```
http://localhost:3000
```

or

```
http://localhost:5173
```

depending on your React setup.

---

# 📁 Project Structure

```text
geolocation-attendance/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── App.js
│   └── index.js
│
├── images/
├── package.json
├── README.md
└── LICENSE
```

---

# 🔒 Core Functionalities

- GPS-Based Attendance Verification
- Browser Geolocation Integration
- Campus Radius Validation
- Automatic Attendance Marking
- Responsive User Interface
- Real-Time Location Detection

---

# 🔮 Future Enhancements

- User Authentication
- Admin Dashboard
- Attendance Reports
- Google Maps Integration
- QR + Geolocation Hybrid Verification
- Firebase Backend Integration
- Push Notifications
- Progressive Web App (PWA)
- Face Recognition Integration

---

# ⚠️ Disclaimer

This project is developed for **educational, research, and portfolio purposes**. It demonstrates location-based attendance verification using browser geolocation technology and is intended as a proof of concept.

---

# 📄 License

This project is licensed under the **MIT License**.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the **"Software"**), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED **"AS IS"**, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

See the **LICENSE** file for complete details.

---

# 👨‍💻 Author

## CHANDRU.R

**Computer Science and Business Systems (CSBS) Undergraduate**

**Full Stack Developer | Java | Spring Boot | React | JavaScript | Geolocation Applications**

Passionate about building scalable, user-centric applications that leverage modern web technologies to solve real-world problems.

---

# 🤝 Contributing

Contributions, issues, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

⭐ **If you found this project useful, consider giving it a star on GitHub!**

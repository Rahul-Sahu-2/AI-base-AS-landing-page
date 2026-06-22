<div align="center">

<img src="https://ai-base-as-landing-page.vercel.app/static/img/logo.png" alt="SnapClass Logo" width="100"/>

# SnapClass AI 🎓

### AI-Powered Attendance System

**Revolutionizing the classroom with next-gen computer vision and voice biometrics.**  
Trusted by educators for speed, accuracy, and security.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit)](https://snap-class-ai-main.streamlit.app/)
[![Landing Page](https://img.shields.io/badge/Landing%20Page-Visit-6C63FF?style=for-the-badge&logo=vercel)](https://ai-base-as-landing-page.vercel.app/)
[![Built with Love](https://img.shields.io/badge/Built%20with-%E2%9D%A4%EF%B8%8F-red?style=for-the-badge)](https://github.com)

</div>

---

## 🌟 Overview

**SnapClass** is an AI-powered classroom attendance system that eliminates the hassle of manual roll calls. Using a combination of **Face Recognition** and **Voice Biometrics**, teachers can take attendance in seconds — from a single class photo or a quick voice roll-call.

Students enroll once via QR code, register their biometrics, and they're done forever.

---

## ✨ Features

### For Teachers
| Feature | Description |
|--------|-------------|
| 📸 **AI Face Analysis** | Advanced neural networks identify every student from a single class photo — instantly and accurately |
| 🎙️ **Sequential Voice ID** | Students say "Present" one-by-one; AI matches their unique voice biometrics in real-time |
| 📱 **QR-Driven Roster** | Generate unique QR codes per course for instant student enrollment |
| 📊 **Attendance Records** | Review historical logs, confidence scores, and track long-term trends |
| 🔐 **Secure Login** | High-security authentication with encrypted, synced data |

### For Students
| Feature | Description |
|--------|-------------|
| ⚡ **Instant Enrollment** | Join courses in seconds using a QR code or class link |
| 🪪 **Biometric Registration** | Register Face ID and Voice ID once — used for all future sessions |
| 📈 **Personal Dashboard** | Track attendance percentage across all subjects in real-time |

---

## 📸 Screenshots

### 🔐 Login Page
<img src="https://ai-base-as-landing-page.vercel.app/static/img/image-3.png" alt="Login Page" width="700"/>

> Secure login portal for teachers. Your data is encrypted and synced across all devices.

---

### 🏠 Teacher Dashboard
<img src="https://ai-base-as-landing-page.vercel.app/static/img/image.png" alt="Teacher Dashboard" width="700"/>

> Manage subjects, attendance logs, and student rosters from a single, unified dashboard.

---

### 📸 Face ID Attendance — Upload Photos
<img src="https://ai-base-as-landing-page.vercel.app/static/img/image-5.png" alt="Face Attendance" width="700"/>

> Add one or more class photos and let the AI identify every student automatically.

---

### 🎙️ Voice Attendance Modal
<img src="https://ai-base-as-landing-page.vercel.app/static/img/image-7.png" alt="Voice Attendance" width="700"/>

> Record students saying "I am present." AI matches voices and marks attendance with a confidence score.

---

### 📋 Attendance Records
<img src="https://ai-base-as-landing-page.vercel.app/static/img/image-10.png" alt="Attendance Records" width="700"/>

> View complete historical logs including timestamps, subject codes, and attendance statistics.

---

### 🔗 Share Class Link / QR Code
> Teachers can share a unique QR code or link for students to instantly join a course.

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| ⚡ **Frontend** | Streamlit + Flask | Reactive UI with a robust landing layer |
| 👁️ **Face Recognition** | FaceRecognition + Dlib | High-fidelity facial biometrics |
| 🎙️ **Voice Embeddings** | Resemblyzer + Librosa | Unique student voice signatures |
| ☁️ **Database** | Supabase (PostgreSQL) | Real-time cloud storage with secure auth |

---

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.9+
pip
```

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/snap-class-ai.git
cd snap-class-ai

# Install dependencies
pip install -r requirements.txt
```

### Environment Variables

Create a `.env` file in the root directory:

```env
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_anon_key
```

### Run the App

```bash
streamlit run app.py
```

---

## 📖 How It Works

### Teacher Workflow

```
1. Secure Login
       ↓
2. Create/Manage Subjects (generates QR codes)
       ↓
3. Take Attendance
   ├── 📸 Face Mode  → Upload class photo → AI identifies students
   └── 🎙️ Voice Mode → Record audio → AI matches voice signatures
       ↓
4. Review & Confirm attendance
       ↓
5. View Attendance Records & Analytics
```

### Student Workflow

```
1. Scan QR code / Use class link to join course
       ↓
2. Register Face ID (one-time photo)
       ↓
3. Register Voice ID (one-time voice sample)
       ↓
4. Attendance is marked automatically in every future session ✅
```

---

## 📁 Project Structure

```
snap-class-ai/
├── app.py                  # Main Streamlit application
├── pages/
│   ├── teacher_dashboard.py
│   ├── attendance.py
│   ├── manage_subjects.py
│   └── records.py
├── utils/
│   ├── face_recognition.py
│   ├── voice_recognition.py
│   └── supabase_client.py
├── requirements.txt
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Created with ❤️ by [Rahul Sahu](https://github.com/rahul-sahu)**

⭐ Star this repo if you found it helpful!

</div>

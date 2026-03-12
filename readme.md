📔 MyDiary — Encrypted Online Diary Web App

MyDiary is a secure, personal online diary web app that lets users write and store their daily entries with **end-to-end encryption**. It features a clean, responsive UI, mood and day tagging, and optional image uploads for creating memory collages.

🌐 Live URL: [https://mydiary.gt.tc](https://mydiary.gt.tc)

---

## ✨ Features 

- 🔒 **Secure Authentication** (Signup & Login)
- 📝 **Diary Entry Creation** with:
  - Encrypted text and metadata (mood, weather, energy, title, interaction)
  - Optional image uploads (1–4 images) for each entry
- 🔐 **End-to-End AES Encryption**
- 🎭 **User Mood/Day Follow-ups** after each entry
- 🖼️ **Collage Builder Page** using uploaded images
- 📱 **Fully Responsive Design**
- 💾 **MySQL Database Integration**

---
---

## 🆕 New Pages & Features

### 🏠 Home Dashboard
- 🧠 Daily Thought
- 🗂️ Total Memories Count
- 📅 New Entries This Month
- 🔥 Current Writing Streak
- 😊 Peak Mood Highlight
- 🌦️ Current Weather Display
- 🎯 Active Goal Tracker

### 👤 Profile Page Enhancements
- 📸 Profile Picture Upload
- 📧 Email Display
- 🕒 Started Diary At (Signup Date)
- 🌟 Auspicious Day (set once, uneditable)
- 📝 Last Entry Timestamp
- 🎯 Current Aim Display
- ✏️ “Change Aim” Button (restricted to once per month)

---


## 🛠️ Tech Stack

- **Frontend**: HTML, CSS (responsive with custom styling), JavaScript
- **Backend**: PHP (procedural)
- **Database**: MySQL (InfinityFree Hosting)
- **Encryption**: AES-256-CBC with unique IV per entry
- **Hosting**: [InfinityFree.net](https://infinityfree.net)

---

## ⚙️ Setup Instructions (Local or Hosting)

1. Clone or upload the project to your hosting server.
2. Create a MySQL database and import the `.sql` file.
3. Update `db.php` with your database credentials.
4. Ensure file permissions are correct for uploads (if using image upload).
5. Visit your hosted domain and register to begin!

---

## 🔐 Security Notes

- All diary entries and metadata (title, mood, etc.) are encrypted before being stored.
- A **master key** and **unique IV** per entry ensure security.
- Do **not change the master key** later or older entries won’t be decryptable.

---

## 🚀 Future Features (Planned)

- 📊 Analytics on mood and activity trends
- 🔔 Daily reminder/notification system
- 🧠 AI-assisted journal suggestions
- 🌙 Dark mode
- 📅 Calendar view of entries

---

## 👨‍💻 Project Developed By

**Yash Anil Patil**  
Contact: yash.patil.yp687@gmail.com  
**Divya chaudhari**
contact:divya351chaudhari@gmail.com
Project hosted at: [https://mydiary.gt.tc](https://mydiary.gt.tc)

---

## 📜 License

This project is for educational/personal use.  
Commercial or redistributed use is not allowed without permission.

# SmartTime – Student Time Management Assistant

SmartTime is a Java-based desktop application designed to help university students manage study time, academic goals, and performance metrics in a single integrated system.

The application combines study session tracking, GPA calculation, goal management, and weekly analytics into one productivity-focused desktop tool.

---

## 🎯 Project Purpose

University students often struggle with managing multiple deadlines, exams, and study sessions. SmartTime was developed to provide:

- Structured academic planning
- Study session tracking with focus models
- GPA and CGPA monitoring
- Weekly performance analytics

This project was developed as part of the **STAT 295 – Object Oriented Programming** course.

---

## 🧩 Core Features

### Study Session Tracking
- Pomodoro (25 min)
- Deep Work (60 min)
- Custom session duration (10–90 min)

Study data is stored locally using JSON logs.

---

### GPA & CGPA Tracking
- Previous CGPA and credits input
- Current term GPA calculation
- Automatic CGPA update using weighted average

---

### Goal Management
Users can manage academic goals such as:
- Exams
- Homework
- Projects

Each goal includes priority level, deadline, and completion status.

---

### Weekly Analytics
- Daily study duration visualization
- Weekly comparison (This Week vs Last Week)
- Motivational feedback based on daily performance

---

### Notifications
- High priority → Daily reminders  
- Medium priority → 7 / 3 / 1 day reminders  
- Low priority → 1 day reminder  

---

## 🏗 Technical Architecture

The application follows **Object-Oriented Programming principles** and modular Swing panel architecture.

Key Components:
- User Class → Stores GPA, goals, study logs
- Session Manager → Provides global user access
- Panel-based modular UI structure

---

## 💾 Data Management

Study data is stored locally:
- `study_log.json`
- Weekly summary JSON files

File reading is handled using:
- `java.nio.file.Files`

---

## 🛠 Technologies Used

- Language: Java (JDK 17+)
- UI Framework: Java Swing
- IDE: IntelliJ IDEA CE
- Libraries: Built-in Java APIs (+ optional JFreeChart)

---

## 👨‍💻 Contributors

- Aykut Ünyazıcı  
- Furkan Koç  
- Oğuz Sezgin  
- Rabia Demircan  
- Timuçin Eke  

---

## 📚 Academic Context

Developed for:
Middle East Technical University  
Department of Statistics  
STAT 295 – Object Oriented Programming

---

## 🚀 Future Improvements

- Database integration
- Cloud sync
- Mobile companion version
- Advanced analytics dashboard

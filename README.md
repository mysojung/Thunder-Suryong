# ⚡ Thunder-Suryong (벼락수룡)

A full-stack mobile application designed to help university students efficiently manage their schedules and implement cramming strategies ahead of midterm and final exams.

---

## 📌 Project Overview
- **Genre**: EdTech / Productivity Mobile Application
- **Description**: An intuitive exam management and cramming timer application. It features customized study tracking, a calendar interface, and registration pipelines tailored for students facing tight academic deadlines.
- **Objective**: Developed as a collaborative full-stack project to master cross-platform mobile development (React Native) and scalable enterprise backend architecture (Spring Boot).

## 🎮 Key Features
1. **Exam Schedule & Calendar Management**: Allows users to register, update, and track upcoming exam dates through an interactive calendar UI.
2. **Cramming Timer with Mascot Interaction**: Implements a dedicated study timer integrated with a gamified mascot character to boost engagement during high-pressure study sessions.
3. **Full-Stack User Authentication**: Features a robust user registration and login pipeline securely handling member data between the client and backend server.
4. **Data Verification**: Utilizes checkbox-based interactive terms of service and dynamic validation rules for user onboarding.

## 🛠️ Tech Stack & Architecture
- **Frontend**: React Native, TypeScript, Expo
- **Backend**: Java, Spring Boot, Spring Data JPA
- **Database**: H2 Database (In-Memory for development and testing)
- **Deployment & Workflow**: Gradle, npm / yarn

---

## 📂 Project Structure
```text
Thunder-Suryong/src/main/
 ├── frontend/             # React Native Mobile Client
 │    ├── app/             # Page components (Index, Login, Signup, etc.)
 │    ├── assets/          # Static assets (images, custom fonts)
 │    ├── components/      # Reusable UI components
 │    ├── constants/       # Global constant definitions and theme colors
 │    ├── hooks/           # Custom React hooks for state and side-effects
 │    └── scripts/         # Utility and helper scripts
 │
 └── java/com/byeraksuryong/ # Spring Boot Backend API
      ├── api/             # API Endpoints and authentication tokens
      ├── controller/      # URL mapping and request routing
      ├── domain/          # Core domain entities and database mapping
      ├── dto/             # Data Transfer Objects for secure data payload
      ├── repository/      # Database access abstraction layers (JPA)
      └── service/         # Core business logic implementation
```

---


## 🚀 How to Run

**0. Clone or pull the repository**

### 🖼️ Frontend Setup
    1. Package Installation
     ```bash
      npm install
      # or yarn
      ```

      2. Run Expo
        # Must be executed within frontend/
       ```bash
       cd npx expo start
       ```
       3. You can run it via the Expo Go app using the QR code, or check it instantly on a web simulator!

       
### 🌐️️️ Backend Setup

   1. [Install Java JDK 17 Version](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)      

   2. [Install H2 DB](https://www.h2database.com/html/download.html) and [Create Tables](https://github.com/real-jeongeun-park/Thunder-Suryong/tree/master/sql)

   3. Build and run the file at the following path within the directory:
      ```
      ./src/main/java/com/byearaksuryong/ByeraksuryongApplicaiton
      ```
---

## 🤝 Contributors

**Frontend**
    - [@hee5k](https://github.com/hee5k)
    - [@rhkrdori](https://github.com/rhkrdori)
    - [@mysojung](https://github.com/mysojung)

**Backend**
    - [@real-jeongeun-park](https://github.com/real-jeongeun-park)
    - [@hyejin-23](https://github.com/hyejin-23)


## 📌 Future Improvements (To-Do)

Integrate Firebase for push notifications and persistent cloud data synchronization.

Implement user-customized push alert systems based on dynamic exam countdowns.

Expand advanced study planner modules and analytics dashboards for long-term tracking.

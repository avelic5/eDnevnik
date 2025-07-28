# 📘 eDnevnik - Digital Classbook System

**eDnevnik** is a web-based application developed using **ASP.NET MVC** and **Microsoft SQL Server**, designed to digitalize and streamline educational administrative processes. The system is intended for use by educational institutions, offering tools for teachers, students, parents, and administrators to manage and monitor academic performance and classroom activities.

---

## ✨ Key Features

- 🔐 **User Role Management** – Admins can manage data related to students, teachers, and subjects (CRUD operations).  
- 📊 **Student Reports** – Students and parents can generate reports on grades, attendance, and behavior in **Excel format**.  
- 📅 **Activity Tracking** – Teachers can schedule upcoming exams, assignments, and school events.  
- 📬 **Notifications via Email** – The system automatically sends **email notifications** about upcoming activities, using smart rules (e.g., reminders before exams, instant alerts for competitions) via a built-in **email API**.  
- 📈 **Performance Analytics** – Displays GPA, subject averages, absence statistics (justified/unjustified), and behavior evaluations using dynamic calculation.  
- 📖 **Class Attendance Logging** – Teachers log lessons and student absences; data is stored securely in the database.  
- 💬 **Real-time Chat** – Asynchronous **chat** communication between students, teachers, and parents.  
- 📚 **Schedule Overview** – Students and teachers can view class schedules, filterable by subject, classroom, or teacher.

---

## 🛠️ Technology Stack

- **ASP.NET MVC 5** – Backend framework  
- **Microsoft SQL Server** – Relational database  
- **Entity Framework** – ORM for database interaction  
- **JavaScript + jQuery** – Frontend interactivity  
- **Bootstrap** – Responsive design  
- **SignalR** – For **asynchronous chat communication**  
- **EPPlus or ClosedXML** – For **generating Excel reports**  
- **SMTP or custom API** – For **sending email notifications**

---

## 👥 Team Members

| Name           | Index  |
|----------------|--------|
| Aldin Velić    | 19761  |
| Tarik Mujkić   | 19584  |
| Mirnes Fehrić  | 19733  |
| Emin Begić     | 19568  |

🔗 **Repository**: [Grupa7-Tim1 GitHub Repo](https://github.com/ooad-2024-2025/Grupa7-Tim1)

---

## 📌 System Purpose

> The eDnevnik system serves as a digital classbook for schools. Its goal is to modernize the tracking of educational activities while extending functionality beyond traditional paper-based records. Teachers can log attendance and class content, while class advisors manage behavior and presence. Students and parents gain insight into grades and attendance. The system simplifies school administration and improves transparency in the teaching process.

---

## 📸 Screenshots

<img width="1915" height="893" alt="Screenshot 2025-07-28 180602" src="https://github.com/user-attachments/assets/52a17b82-14a0-4cc0-8fde-c5dd3dd2a62d" />
<img width="1896" height="906" alt="Screenshot 2025-07-28 180646" src="https://github.com/user-attachments/assets/bcbc898e-c3ec-49cd-97cd-ca8ca0aa1963" />
<img width="1917" height="903" alt="Screenshot 2025-07-28 180717" src="https://github.com/user-attachments/assets/9405559a-b364-47b4-a507-fcb39e7c70d7" />
<img width="1919" height="806" alt="Screenshot 2025-07-28 180819" src="https://github.com/user-attachments/assets/e9d26c72-72d5-4c59-a940-6085760f5db0" />
<img width="1895" height="900" alt="Screenshot 2025-07-28 180833" src="https://github.com/user-attachments/assets/e1c50144-84b5-468a-9ee1-7943ee9eb8ff" />
<img width="1918" height="887" alt="Screenshot 2025-07-28 180857" src="https://github.com/user-attachments/assets/86a55baa-050d-479a-8b18-6fa5f33e4d72" />
<img width="1900" height="857" alt="Screenshot 2025-07-28 180925" src="https://github.com/user-attachments/assets/fadaeb2a-725e-4ee7-9f05-8303a74c0657" />
<img width="1890" height="850" alt="Screenshot 2025-07-28 181028" src="https://github.com/user-attachments/assets/0199b8d6-1959-4c1f-98b9-7a82ad0e9483" />
<img width="1910" height="872" alt="Screenshot 2025-07-28 181039" src="https://github.com/user-attachments/assets/45f85125-6d93-4388-8a61-c7c3adc1be9c" />

---

## ▶️ Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ooad-2024-2025/Grupa7-Tim1.git
   ```

2. Open the solution in **Visual Studio**.

3. Update `appsettings.json` or `Web.config` with your **SQL Server** connection string.

4. Run the app:
   ```bash
   Ctrl + F5
   ```

5. (Optional) Apply migrations if needed:
   ```bash
   Update-Database
   ```

---

## 📝 License

This project is for educational purposes – Faculty of Electrical Engineering Sarajevo, OOAD course.

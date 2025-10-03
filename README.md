# 📌 TeamTrack – Employee Management Platform  

[![.NET](https://img.shields.io/badge/.NET%208.0-blueviolet)](https://dotnet.microsoft.com/)
[![C#](https://img.shields.io/badge/Language-C%23-green)](https://learn.microsoft.com/en-us/dotnet/csharp/)  
[![Entity Framework](https://img.shields.io/badge/Entity%20Framework-Core-orange)](https://learn.microsoft.com/en-us/ef/core/)  
[![SQL Server](https://img.shields.io/badge/Database-SQL%20Server-red)](https://www.microsoft.com/en-us/sql-server)  

---

## 📖 Overview  
**TeamTrack** is a CRUD-based web application for managing employee data.  
It allows administrators to **Add, Update, View, and Delete** employee records through a **Razor Pages UI**.  

This project is built using **ASP.NET Core MVC, C#, EF Core, and SQL Server**.  

---

## 🚀 Features  
- ➕ Add new employee records  
- ✏️ Update employee information  
- 👀 View employee details in a structured list  
- ❌ Delete records securely  
- 🎨 User-friendly Razor interface  

---

## 🛠️ Technologies Used  
- **Framework:** ASP.NET Core MVC  
- **Language:** C#  
- **ORM:** Entity Framework Core  
- **Database:** SQL Server  
- **Frontend:** HTML, CSS, Razor Pages  

---

## 📂 Project Structure  
```plaintext
TeamTrack – Employee Management Platform/
│-- Controllers/        # Application controllers
│-- Models/             # Entity and data models
│-- Views/              # Razor views for UI
│-- Data/               # EF Core DbContext and migrations
│-- wwwroot/            # Static files (CSS, JS, Images)
│-- appsettings.json    # Database and app configuration
│-- Program.cs          # Application entry point
```
---

## 📌 Future Improvements

- 🔐 Authentication & Role-based access (Admin/User)
- 🔍 Employee search & filtering
- 📑 Pagination for employee list
- 📤 Export employee data (Excel/PDF)

---

## ⚙️ How to Run  

## 1️⃣ Clone the Repository  
```bash
git clone https://github.com/rakibul-10/TeamTrack-Employee-Management.git
cd TeamTrack-Employee-Management
cd TeamTrack – Employee Management Platform
```
## 2️⃣ Configure Database
Update the appsettings.json file with your SQL Server connection string:
```bash
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=TeamTrackDB;Trusted_Connection=True;"
  }
}
```
## 3️⃣ Apply Migrations & Update Database
```bash
dotnet ef database update
```
## 4️⃣ Run the Project
```bash
dotnet run
```

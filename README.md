# 📘 BulkyBook

BulkyBook is a simple CRUD application built using **ASP.NET Core 8**. This project demonstrates the implementation of basic Create, Read, Update, and Delete operations in a web application.

---

## 🚀 Features

- ✅ Basic CRUD operations for managing books
- ✅ Built with **ASP.NET Core 8**
- ✅ Utilizes **Entity Framework Core 8** for database interactions
- ✅ Responsive UI built with **HTML**, **CSS**, and **JavaScript**
- ✅ Clean and modular project structure

---

## 🛠️ Technologies Used

- [ASP.NET Core 8](https://dotnet.microsoft.com/en-us/aspnet/core)
- [Entity Framework Core 8](https://learn.microsoft.com/en-us/ef/core/)
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## 📂 Project Structure

```plaintext
├── BulkyBookWeb/          # Web application project
│   ├── Controllers/       # MVC Controllers
│   ├── Models/            # Entity models
│   ├── Views/             # Razor Views
│   └── wwwroot/           # Static files (CSS, JS, images)
├── BulkyBook.sln          # Solution file
└── README.md              # Project documentation
⚙️ Getting Started
1️⃣ Prerequisites
Ensure you have the following installed:

.NET 8 SDK

SQL Server or SQLite (depending on your preference)

2️⃣ Clone the Repository
git clone https://github.com/Riajul-Alam/BulkyBook.git
cd BulkyBook

3️⃣ Configure Database Connection
Update the connection string in appsettings.json:
"ConnectionStrings": {
  "DefaultConnection": "Server=localhost;Database=BulkyBookDb;Trusted_Connection=True;TrustServerCertificate=True;"
}
4️⃣ Apply Migrations
dotnet ef database update
5️⃣ Run the Application
dotnet run
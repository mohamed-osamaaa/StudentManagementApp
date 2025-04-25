
# 🎓 ASP.NET MVC Student Management System

A responsive web application built using **ASP.NET MVC**, **Entity Framework (EF)**, **SQL Server**, and **Bootstrap** to manage student information.

## 📌 Features

- **CRUD Operations** on Student data:
  - Add a new student
  - View list of students
  - View student details
  - Edit student information
  - Delete a student
- Responsive UI using Bootstrap
- Uses Entity Framework Code-First approach with Migrations
- SQL Server as the database

## 🛠 Technologies Used

- ASP.NET MVC
- Entity Framework (Code-First + Migrations)
- SQL Server / SQL Server Express
- Bootstrap 5
- Visual Studio 2022

## 🧩 Project Structure

- **Models/Student.cs**: Student model with properties
- **Controllers/StudentsController.cs**: Controller for handling all actions
- **Views/Students/**: Razor views for Index, Details, Create, Edit, Delete
- **App_Data**: SQL Server database integration

## 🧑‍🎓 Student Model

```csharp
public class Student
{
    public int StudentId { get; set; }
    public string Name { get; set; }
    public string Email { get; set; }
    public string Course { get; set; }
}
```

## 📄 Controller Actions

- `Index`: Display all students
- `Details(int id)`: Show details of a specific student
- `Create`: Add a new student
- `Edit(int id)`: Edit an existing student
- `Delete(int id)`: Delete a student

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/student-management-mvc.git
cd student-management-mvc
```

### 2. Open in Visual Studio

Open the solution (`.sln` file) in Visual Studio.

### 3. Apply Migrations

Open **Package Manager Console** and run:

```bash
Update-Database
```

This will create the SQL Server database with the `Students` table.

### 4. Run the Project

Press `F5` or click on **IIS Express** to run the application.

## 📌 Notes

- Ensure SQL Server / SQL Server Express is installed and running.
- Adjust the connection string in `Web.config` if needed.

## 📝 License

This project is licensed under the MIT License.

---

Made with ❤️ using ASP.NET MVC & Bootstrap

---


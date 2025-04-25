
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

## 📱 Screenshots

![Index](https://github.com/user-attachments/assets/0e10f63f-8bf7-4601-8d5f-84d92f98c629)
![Create](https://github.com/user-attachments/assets/cc8eff14-95eb-45e8-9327-ff0bb7ce3fca)
![Edit](https://github.com/user-attachments/assets/43f8645f-3649-41f8-921e-558885bc3a0e)
![Details](https://github.com/user-attachments/assets/cd6253b0-30f5-47c7-8709-b91a2bcd57bd)
![Delete](https://github.com/user-attachments/assets/bf3b4a3a-12e5-4bda-8f0b-5a2fe9c0990b)

## 📌 Notes

- Ensure SQL Server / SQL Server Express is installed and running.
- Adjust the connection string in `Web.config` if needed.

## 📝 License

This project is licensed under the MIT License.

---

Made with ❤️ using ASP.NET MVC & Bootstrap

---


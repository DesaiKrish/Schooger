# Course Management System with .NET Core MVC

Schooger is a website to manage courses, faculties and student enrollments for a course with a user friendly interface and highly scalable system. The database is designed keeping in mind all the cascades and faults a normal human can make, to roll back and retrieve important data.

Try your luck with the product and let us know suggestions, if any.

## Technologies

The project uses the following technologies:

- .NET Core MVC
- Entity Framework Core
- SQL Server Management Studio
- Bootstrap
- Auth0 authorisation and authentication
- jQuery

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the latest version of .NET Core SDK and SQL Server on your machine. (Optional: Try to work in Visual Studio 2022).
3. Update the connection string in the `appsettings.json` file with your SQL Server connection string.
4. Run the following commands in the root directory of the project to set up the database: `dotnet ef database update`
5. Run the following command to start the web application: `dotnet run` from root directory of project.


## Project Structure

- Controllers
- Views
- Data models
- ViewModels

## Features

The project includes the following features:

- Authentication and Authorization using OAuth and cookies
- CRUD operations for Students, Teachers, and Classes
- Search functionality for Students and Teachers

## Contributers

- Krish Desai
- Dhruvil Dhamsania
- Aryan Akola

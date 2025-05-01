Technologies Used
Framework: ASP.NET Core MVC (.NET 8 )

Language: C#

Architecture: MVC (Model-View-Controller)

Database: Entity Framework Core (ORM)(Code First Approach)

Dependency Injection: Built-in ASP.NET Core DI (evident from Service and Repository folders)

Frontend: Razor Views (from the Views folder)

Configuration: appsettings.json

📁 Key Project Folders
Controllers/

Contains C# classes handling HTTP requests and defining routing logic.

Models/

Defines domain models/entities (likely for employees or users).

Views/

Contains Razor (.cshtml) files for generating dynamic HTML pages.

Migrations/

Manages database schema changes using Entity Framework Core.

Repository/

Contains repository classes for abstracting data access logic (likely implementing the Repository Pattern).

Service/

Implements business logic, separated from controllers and data access.

🧱 Core Files
Program.cs: Configures and runs the web application, including middleware and services.

EmpMVC.csproj: Project configuration including dependencies.

appsettings.json: Central configuration for environment settings, connection strings, etc.

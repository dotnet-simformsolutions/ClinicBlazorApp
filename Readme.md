ClinicSolution Blazor Web Application
Welcome to the ClinicSolution Blazor Web Application! This project serves as a proof of concept(POC) for managing appointments, diseases, and patients in a clinic setting.

This application contains three modules as given below:
Client (ClinicSolution.Client)
The client-side of the application handles the user interface using HTML and CSS. It includes pages for managing Appointments, Diseases, and Patients. These pages allow users to perform CRUD operations on clinic data. The client-side code also utilizes HttpClient for making requests to the server-side API and IJSRuntime for interacting with JavaScript code.

Server (ClinicSolution.Server)
The server-side of the application hosts the business logic and data access layer. It follows the repository pattern, separating concerns into IRepository, Repository, IService, and Service components. The server communicates with a SQL Server database using Entity Framework Core for database operations. It includes controllers responsible for handling HTTP requests and serving data to the client.

Shared (ClinicSolution.Shared)
The shared component contains models shared between the client and server. These models include definitions for Appointment, Disease, and Patient entities, ensuring consistency across the application.

Development Environment
•	Microsoft Visual Studio Enterprice 2022 (64-bit)
•	SQL Server Express 2019 LocalDB
•	Blazor Web Assembly
•	.NET 8.0

Getting Started
1.	To get started with the project, follow these steps:
git clone https://github.com/manan-p-simformsolutions/ClinicSolution_Blazor.git

after cloning the repo, open it in visual studio and it will look like below image:
 
2.	Set Up the Database:
•	Ensure you have a compatible database server running (e.g., SQL Server).
•	Configure the connection string in appsettings.json file under Server project.
•	Run Entity Framework migrations to create the database schema:
	Ex. 	add-migration init
		Update-database
3.	Run the Application:


Technologies Used
•	Blazor: Microsoft's framework for building interactive web UIs.
•	Entity Framework Core: Object-relational mapping framework for .NET.
•	ASP.NET Core: Open-source framework for building web apps.



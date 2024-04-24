# Contact Manager ASP.NET Core MVC Application

This is a demo ASP.NET Core MVC application for managing contacts. It provides functionality for registering and authenticating users, creating, reading, updating, and deleting contact information, and exporting contact data in various formats.

## Features

### User Authentication
- User registration with role assignment (Admin or User)
- User login and logout
- Email uniqueness validation during registration

### Contact Management
- Create, read, update, and delete contacts
- Search and sort contacts
- Export contacts as PDF, CSV, or Excel files

### Admin Area
- Separate area for administrative tasks (accessible only to users with the "Admin" role)

## Controllers

1. **AccountController.cs**: Handles user registration, login, and logout operations. Assigns roles (Admin or User) during registration.

2. **CountriesController.cs**: Provides functionality to upload country data from an Excel file.

3. **HomeController.cs**: Handles error handling and renders the error view.

4. **PersonsController.cs**: The main controller responsible for CRUD operations on contacts. It also includes functionality for searching, sorting, and exporting contacts in various formats.

5. **HomeController.cs (Admin Area)**: Renders the admin area index view, accessible only to users with the "Admin" role.

## Dependencies

This application utilizes the following third-party libraries and packages:

- Microsoft.AspNetCore.Identity
- Rotativa.AspNetCore (for PDF generation)

## Setup and Installation

1. Clone the repository: `git clone https://github.com/your-repo-url.git`
2. Navigate to the project directory: `cd your-repo-name`
3. Restore NuGet packages: `dotnet restore`
4. Build the project: `dotnet build`
5. Run the application: `dotnet run`

## Contributing

Contributions are welcome! Please follow the contributing guidelines when submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to modify the README file according to your specific project requirements and add any additional sections or instructions as needed.

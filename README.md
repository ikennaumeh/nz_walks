# NZ Walks API

## Project Overview
NZ Walks is a simple web API project designed to demonstrate CRUD functionality, authentication, authorization, and image upload capabilities. The project serves as a learning tool for developers and is intended for the general public interested in working with APIs built using .NET and C#.

---

## Features
- **CRUD Operations**: Perform Create, Read, Update, and Delete operations on resources.
- **Authentication and Authorization**: Secured access using authentication mechanisms to ensure only authorized users can perform certain actions.
- **Role-Based Access Control**: Fine-grained access control based on user roles.
- **Image Upload**: Support for uploading images for specific resources.
- **Swagger UI**: An interactive web UI for testing and exploring the API endpoints.

---

## Installation Instructions

### Prerequisites
1. **Visual Studio 2022 or later**: Ensure you have Visual Studio installed on your system.
2. **.NET 8 SDK**: Download and install the .NET 8 SDK.
3. **MySQL Studio Manager**: Install MySQL Studio Manager to manage your database.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ikennaumeh/nz_walks.git
   ```
2. Open the project in Visual Studio.
3. Set up your database connection in the configuration file (`appsettings.json`):
   ```json
   "ConnectionStrings": {
       "DefaultConnection": "your-database-connection-string"
   }
   ```
4. Restore the dependencies:
   ```bash
   dotnet restore
   ```
5. Run the migrations to set up the database:
   ```bash
   dotnet ef database update
   ```
6. Start the project:
   ```bash
   dotnet run
   ```
7. Open the Swagger UI in your browser to interact with the API:
   ```
   http://localhost:<port>/swagger
   ```

---

## Usage

Once the project is running, the Swagger UI will be available at the provided URL. You can use the interactive interface to explore the following features:
- Test CRUD operations.
- Authenticate and generate tokens for secure access.
- Upload images to resources.

---

## Technologies Used
- **.NET 8**: Backend framework.
- **C#**: Programming language.
- **MySQL**: Database management system.
- **Swagger**: API documentation and testing.

---

## Contribution Guidelines
We welcome contributions to improve the NZ Walks API. To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request on the main repository.

---

## License
This project is licensed under the [MIT License](LICENSE).

## Future Plans
- Add more advanced authentication options (e.g., OAuth2).
- Expand CRUD functionality to support additional entities.

---

## Acknowledgments
- Thanks to the .NET and C# community for their excellent documentation and tools.


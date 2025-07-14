# SurveyBasket (.NET 9 Web API)

SurveyBasket is a modern backend API for survey and polling platforms, built with ASP.NET Core 9. The project is engineered for flexibility, scalability, and easy integration with web/mobile frontends.

---

## What SurveyBasket Covers

SurveyBasket delivers full implementations for advanced API features and modules:
- API Fundamentals & REST Principles
- CRUD Operations for surveys, polls, responses, users
- Model Binding, Mapping, Validation (FluentValidation, Mapster)
- Database Integration (EF Core, SQL Server)
- JWT Authentication & Authorization
- Application Options & Configuration
- Audit Logging (Serilog)
- CORS Support
- Comprehensive Error & Exception Handling
- Problem Details Standardization
- Logging & Caching
- Registration & User Management
- Background Jobs (Hangfire)
- Account, Roles & Permissions Management
- Pagination, Filtering, Sorting
- Health Checks & Rate Limiting
- API Versioning
- Swagger & OpenAPI Documentation
- Code Review, Deployment, and Project Management
- Integrated Email and WhatsApp notifications

All modules designed for best practices, extensibility, and real-world usage.

---

## Tech Stack

- ASP.NET Core 9
- Entity Framework Core + SQL Server
- JWT Authentication
- Serilog, Hangfire, FluentValidation, Mapster
- Swagger/OpenAPI, CORS, Modular DI

---

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/OmarDiv/SurveyBasket.git
    cd SurveyBasket
    ```
2. **Configure Database:** Edit `appsettings.json` for connection strings.
3. **Restore dependencies:**  
    `dotnet restore`
4. **Run migrations:**  
    `dotnet ef database update`
5. **Run the API:**  
    `dotnet run`
6. **Access Swagger UI:**  
    [https://localhost:5001/swagger](https://localhost:5001/swagger)

---

## Project Structure (Example)

```
SurveyBasket/
├── Controllers/
├── Models/
├── Persistence/
├── Services/
├── DTO/
├── Helpers/
├── Middlewares/
├── Program.cs
├── appsettings.json
├── SurveyBasket.csproj
...
```

---

## Contributing

- Fork, branch, and submit descriptive PRs.
- Follow .NET standards and write tests.

---

## License

MIT

---

## Contact

- **WhatsApp:** 01013762770
- **Email:** omaar88mohamed@gmail.com
- **LinkedIn:** [Omar Mohamed](https://www.linkedin.com/in/omar-mohamed-713b53265)

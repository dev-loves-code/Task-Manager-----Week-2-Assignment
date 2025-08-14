# Task Manager API

**ASP.NET Core 9 REST API** for managing tasks and notes (one-to-many) with full CRUD support, **Entity Framework Core**, **Mapster DTO mapping**, **Redis caching**, and **Serilog logging**.

---

## Prerequisites

* [.NET 9 SDK](https://dotnet.microsoft.com/download)
* SQL Server (local or containerized)
* [Docker](https://www.docker.com/) for Redis

---

## Setup & Run

1. **Database Migrations**

   ```bash
   cd api
   dotnet ef database update
   ```

2. **Start Redis via Docker**

   ```bash
   docker-compose up
   ```

3. **Run the API**

   ```bash
   dotnet run
   ```

> The default `appsettings.json` uses **Windows Authentication** for SQL Server.
> To use SQL username/password, update the `DefaultConnection` accordingly.

---

## Features

* Tasks & Notes CRUD (one-to-many)
* DTO mapping with Mapster
* Redis caching
* Logging with Serilog & `ILogger`
* Controller–Service–Repository architecture
* Full exception handling

---

If you want, I can also add **Markdown badges** for .NET, Docker, and EF to make it look extra professional on GitHub. Do you want me to do that?

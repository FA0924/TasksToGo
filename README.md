# TasksToGo


A simple task management web application built with ASP.NET Core MVC and Entity Framework Core.

## Overview

TasksToGo is a to-do list application that allows users to create, view, update, and delete tasks organized by categories.

## Tech Stack

- **Framework:** ASP.NET Core 8.0 (MVC)
- **Database:** SQL Server with Entity Framework Core 8.0
- **Frontend:** Razor Views, Bootstrap, jQuery

## Features

- Create, view, update, and delete tasks
- Organize tasks into categories
- Track task deadlines and completion status
- View task details with associated category information

## Project Structure

```
TasksToGo/
├── Controllers/
│   ├── HomeController.cs      # Task management
│   └── CategoryController.cs  # Category management
├── Models/
│   ├── TodoTask.cs            # Task entity
│   └── TaskCategory.cs        # Category entity
├── Views/
│   ├── Home/                  # Task views
│   ├── Category/              # Category views
│   └── Shared/                # Layout and partials
├── Context/
│   └── ApplicationDbContext.cs
└── Configurations/            # EF Core configurations
```

## Getting Started

### Prerequisites

- .NET 8.0 SDK
- SQL Server

### Setup

1. Clone the repository
2. Update the connection string in `appsettings.json`
3. Run database migrations:
   ```bash
   dotnet ef database update
   ```
4. Run the application:
   ```bash
   dotnet run
   ```

## License

This project is open source.

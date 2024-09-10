# Task Management Web App

## Overview

This is a simple Task Management Web App built with a .NET Core Web API backend, using Entity Framework Core with SQLite for data storage, and a frontend implemented in HTML/CSS with jQuery for interactivity.

## Design Decisions

### Backend (ASP.NET Core Web API)

- **.NET Core Web API:** Chosen for its robustness and ease of building RESTful services.
- **Entity Framework Core:** Used for ORM to interact with the SQLite database, simplifying data management and migrations.
- **SQLite:** Selected as the default database for simplicity and ease of setup. It’s lightweight and requires minimal configuration. SQL Server is also supported as an optional feature.
- **API Endpoints:** Implemented for CRUD operations:
  - **GET** `/api/tasks`: Retrieve all tasks.
  - **POST** `/api/tasks`: Add a new task.
  - **PUT** `/api/tasks/{id}`: Update an existing task.
  - **DELETE** `/api/tasks/{id}`: Delete a task.

### Frontend (HTML/CSS & jQuery)

- **HTML/CSS:** Utilized for the structure and styling of the web application. The design is responsive and user-friendly.
- **jQuery:** Chosen for handling asynchronous operations (AJAX) to interact with the Web API without page reloads, simplifying client-side logic and enhancing user experience.

## Setup Instructions

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (version 5.0 or higher)
- [SQLite](https://www.sqlite.org/download.html) (if using SQLite)
- [Visual Studio Code](https://code.visualstudio.com/) or any other IDE of your choice
- [Node.js](https://nodejs.org/) (for running the frontend if needed)

### Backend Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Ritej26/TaskManagemer.git
   cd TaskManagemerApp

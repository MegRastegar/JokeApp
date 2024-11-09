# JokeApp

## Overview
**JokeApp** is a web application built as part of my journey to learn ASP.NET Core. It serves as a simple joke database where users can view and contribute jokes. The project is a hands-on practice with the Model-View-Controller (MVC) pattern, user authentication, and database interactions in ASP.NET Core.

## Features
- **Browse Jokes**: View a list of jokes along with their answers.
- **User Registration**: Register an account to gain access to additional features.
- **Add New Jokes**: Registered users can contribute their own jokes.

## Tech Stack
- **Backend**: ASP.NET Core (MVC)
- **IDE**: Visual Studio
- **Database**: SQL Server

## Installation and Setup

### Prerequisites
- Visual Studio with .NET Core SDK
- Database setup

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/MegRastegar/JokeApp.git
   ```
2. Open the project in Visual Studio.
3. Restore dependencies:
   ```bash
   dotnet restore
   ```
4. Run the application:
   ```bash
   dotnet run
   ```

### Configuration
Make sure any required environment variables or database connection strings are set up in `appsettings.json`.

## Usage
- Navigate to `http://localhost:44316` in your browser to start the application.
- Register to create an account and start adding your own jokes.

## Contributing
Suggestions for new features and improvements are welcome! Please feel free to submit issues or pull requests.

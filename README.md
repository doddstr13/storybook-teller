# StoryBook Teller

A .NET 9 ASP.NET Core web application for creating and sharing interactive stories.

## Project Overview

StoryBook Teller is a web application that allows users to create, share, and explore interactive stories. Built with ASP.NET Core 9, this application demonstrates modern web development practices using the MVC architectural pattern.

## Features

- Create interactive stories with branching narratives
- Share stories with friends or publish to the community
- Explore stories created by other users
- User authentication and profile management
- Responsive design for mobile and desktop

## Technology Stack

- .NET 9 ASP.NET Core
- C# 12
- MVC Architecture
- Entity Framework Core (for future database integration)
- Bootstrap 5 for responsive UI
- JavaScript for client-side interactions

## Getting Started

### Prerequisites

- .NET 9 SDK
- Visual Studio 2022, Visual Studio Code, or JetBrains Rider

### Installation

1. Clone the repository
   ```
   git clone https://github.com/yourusername/StoryBookTeller.git
   ```

2. Navigate to the project directory
   ```
   cd StoryBookTeller
   ```

3. Restore dependencies
   ```
   dotnet restore
   ```

4. Run the application
   ```
   dotnet run
   ```

5. Open your browser and navigate to `https://localhost:7001`

## Project Structure

- `/Controllers` - MVC Controllers
- `/Models` - Data models
- `/Views` - Razor views
- `/wwwroot` - Static files (CSS, JS, images)
- `/Properties` - Application properties and launch settings

## Development

### Development Environment

The application is configured to run in development mode by default. You can modify the environment settings in `Properties/launchSettings.json`.

### Building the Project

```
dotnet build
```

### Running Tests

```
dotnet test
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- ASP.NET Core team for the amazing framework
- Bootstrap team for the responsive UI components
- All contributors who help improve this project

# StoryBook Teller

A modern ASP.NET Core 9 web application for creating and sharing interactive stories.

## Project Overview

StoryBook Teller is a web application that allows users to create, share, and explore interactive stories. Built with the latest ASP.NET Core 9 framework, it provides a robust and scalable platform for storytelling enthusiasts.

## Features

- Create interactive stories with branching narratives
- Share your stories with the community
- Explore stories created by other users
- User-friendly interface for both creators and readers

## Technology Stack

- ASP.NET Core 9.0
- C# 12
- MVC Architecture
- Bootstrap 5 for responsive design
- Entity Framework Core (for future database integration)

## Getting Started

### Prerequisites

- .NET 9 SDK
- Visual Studio 2022 or Visual Studio Code

### Installation

1. Clone the repository
   ```
   git clone https://github.com/yourusername/storybook-teller.git
   ```

2. Navigate to the project directory
   ```
   cd storybook-teller
   ```

3. Build the project
   ```
   dotnet build
   ```

4. Run the application
   ```
   dotnet run
   ```

5. Open your browser and navigate to `https://localhost:5001` or `http://localhost:5000`

## Project Structure

- **Controllers/** - Contains MVC controllers
- **Models/** - Contains data models
- **Views/** - Contains Razor views
- **wwwroot/** - Contains static files (CSS, JS, images)

## Development

### Development Environment

The application is configured to use different settings for development and production environments. The development environment provides more detailed error information and debugging capabilities.

### Adding New Features

1. Create appropriate models in the Models directory
2. Create controllers in the Controllers directory
3. Create views in the Views directory
4. Update routing in Program.cs if necessary

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Microsoft for the ASP.NET Core framework
- The open-source community for their valuable contributions

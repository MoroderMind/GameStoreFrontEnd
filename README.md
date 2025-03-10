# GameStore Frontend

A modern web frontend for a game store built with Blazor, demonstrating real-time updates and responsive design. This project showcases several modern .NET features including stream rendering and asynchronous operations.

## Features

- Real-time game catalog display using Blazor's stream rendering
- Async data fetching for optimal performance
- CRUD operations for game management
- Responsive Bootstrap-based UI
- Interactive modal dialogs for delete confirmation
- Clean separation of concerns with dedicated HTTP clients

## Technical Highlights

- Built with Blazor Server
- Uses `@attribute [StreamRendering]` for enhanced performance and user experience
- Implements async/await pattern for all data operations
- Bootstrap 5 for styling and components
- Integration with RESTful backend API

## Prerequisites

To run this frontend, you'll need:
- .NET 9.0 SDK
- A running instance of the GameStore Backend API
  - The backend API can be found at: [GameStore Backend Repository](https://github.com/YourUsername/GameStore-Backend)

## Getting Started

1. Clone this repository
2. Ensure the backend API is running (default: http://localhost:5219)
3. Update the `GameStoreApiUrl` in appsettings.json if needed
4. Run the frontend:
   ```bash
   dotnet run
   ```
5. Navigate to http://localhost:5122

## Acknowledgments

This project was created by following Julio Casal's excellent tutorial on building modern web applications with Blazor and .NET.


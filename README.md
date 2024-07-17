# Order API

## Description
A simple ordering system API built with .NET Core and a frontend using React.

## Prerequisites
- .NET Core SDK
- Node.js and npm

## Setup

### Backend
1. Navigate to the `OrderApi` directory.
2. Run `dotnet restore` to install dependencies.
3. Run `dotnet build` to build the project.
4. Run `dotnet run` to start the API.

### Frontend
1. Navigate to the `order-frontend` directory.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the React app.

## Running Tests

### Unit and Integration Tests
1. Navigate to the `OrderApi.Tests` directory.
2. Run `dotnet test` to execute the tests.

## API Endpoints
- `GET /api/orders` - Retrieves all orders
- `POST /api/orders` - Creates a new order
- `DELETE /api/orders/{id}` - Deletes an order by ID

## Frontend
The frontend provides a simple interface to add and view orders. It communicates with the backend API to perform CRUD operations.

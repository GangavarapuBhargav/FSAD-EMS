# Employee Management System

A full-stack Employee Management System built with Spring Boot and React.

## Features

- User Authentication (Login/Register)
- Employee CRUD Operations
- Pagination
- Sorting
- Responsive UI

## Technologies Used

### Backend
- Java 17
- Spring Boot 3
- Spring Security 6
- Spring Data JPA
- MySQL Database
- RESTful API

### Frontend
- React
- React Router
- Axios
- Bootstrap 4
- CSS

## Project Structure

The project is divided into two main parts:

1. **Backend (Spring Boot)**: Located in the `ems` directory
2. **Frontend (React)**: Located in the `frontend` directory

## Setup Instructions

### Prerequisites
- Java 17+
- Node.js and npm
- MySQL

### Database Setup
1. Create a MySQL database named `ems`
2. Update the database configuration in `ems/src/main/resources/application.properties` if needed

### Backend Setup
1. Navigate to the `ems` directory
2. Run the Spring Boot application:
   ```
   ./mvnw spring-boot:run
   ```
   
### Frontend Setup
1. Navigate to the `frontend` directory
2. Install dependencies:
   ```
   npm install
   ```
3. Start the React development server:
   ```
   npm start
   ```

## Usage

1. Access the application at `http://localhost:3000`
2. Register a new user account
3. Log in with your credentials
4. Start managing employees

## API Endpoints

### Authentication
- `POST /api/v1/auth/register` - Register a new user
- `POST /api/v1/auth/login` - Login a user

### Employees
- `GET /api/v1/employees` - Get all employees
- `GET /api/v1/employees/page/{pageNo}` - Get paginated employees
- `POST /api/v1/employees` - Add a new employee
- `GET /api/v1/employees/{id}` - Get an employee by ID
- `PUT /api/v1/employees/{id}` - Update an employee
- `DELETE /api/v1/employees/{id}` - Delete an employee # FSAD-EMS

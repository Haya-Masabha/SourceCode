# SourceCode
 Projects Source Code
# Business Card Application

## Description
This is a business card management application that allows users to upload, edit, and export business cards in various formats (CSV, XML).

## Features
- Upload business cards via file (CSV/XML)
- Export business card details to CSV or XML
- Encode and Decode photo (base64)
- CRUD operations for business cards

## Technologies Used
- ASP.NET Core Web API (.net 8)
- Angular for frontend
- Entity Framework Core
- ORACLE database
- Unit tests with XUnit/MSTest

## Setup Instructions

### Backend Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/Haya-Masabha/SourceCode.git
    ```
2. Navigate to the backend folder:
    ```bash
    cd BusinessCard_BACKEND
    ```
3. Restore the dependencies:
    ```bash
    dotnet restore
    ```
4. Update `appsettings.json` with your database connection string.

5. Run the application:
    ```bash
    dotnet run
    ```

### Frontend Setup
1. Navigate to the frontend folder:
    ```bash
    cd BusinessCardAngular_FRONTEND
    ```
2. Install the dependencies:
    ```bash
    npm install
    ```
3. Run the application:
    ```bash
    ng serve
    ```

## Running Unit Tests

To run the unit tests for the backend, navigate to the test folder and run:

```bash
dotnet test

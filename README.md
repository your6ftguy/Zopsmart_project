
# zopsmart-project
Simple Student Management REST API
This is a basic RESTful API built in GoLang using Gofr for managing student records. The API supports Create, Read, Update, and Delete (CRUD) operations.
Overview
This GoLang application is designed to handle student data through HTTP endpoints. It utilizes the gofr package for routing and HTTP request handling. The API provides endpoints for retrieving, creating, updating, and deleting student records.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/simple-rest-api.git
cd simple-rest-api
Install dependencies:

bash
Copy code
go get -u ./...
Build the application:



bash
Copy code
go build
Usage
Run the application after building:



bash
Copy code
./your-executable-name
The server will start on port 9092 by default.

Endpoints
GET /students/{id}: Retrieve information of a student by ID.
POST /students: Create a new student record.
PUT /students/{id}: Update an existing student record.
DELETE /students/{id}: Delete a student record.
Project Structure
The project structure is organized as follows:

datastore/: Contains the logic for data storage.
handler/: Includes request handlers for the API endpoints.
main.go: Entry point of the application.
Dependencies
gofr.dev/pkg/gofr: Go package used for routing and HTTP handling.
Contributing
Contributions are welcome! If you wish to contribute, please open an issue first to discuss potential changes/additions.

This project has been created for Zopsmart assignment project.

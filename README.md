# Swagger
#### OAS (Open API Specification)

OpenAPI Specification (formerly Swagger Specification) is an API description format for REST APIs. An OpenAPI file allows you to describe your entire API, including:

Available endpoints (/users) and operations on each endpoint (GET /users, POST /users)
Operation parameters Input and output for each operation
Authentication methods
Contact information, license, terms of use and other information.
API specifications can be written in YAML or JSON. The format is easy to learn and readable to both humans and machines. The complete OpenAPI Specification can be found on GitHub: OpenAPI 2.0 Specification, OpenAPI 3.0 Specification

# Swagger
Swagger is a set of open-source tools built around the OpenAPI Specification that can help you design, build, document and consume REST APIs. The major Swagger tools include:

Swagger Editor – browser-based editor where you can write OpenAPI specs.
Design, describe, and document your API on the first open source editor fully dedicated to OpenAPI-based APIs. The Swagger Editor is great for quickly getting started with the OpenAPI (formerly known as the Swagger Specification) specification, with support for Swagger 2.0 and OpenAPI 3.0.

Runs Anywhere: The Editor works in any development environment, be it locally or in the web
Smart Feedback: Validate your syntax for OAS-compliance as you write it with concise feedback and error handling
Instant Visualization: Render your API specification visually and interact with your API while still defining it
Intelligent Auto-completion: Write syntax faster with a smart and intelligent auto-completion
Fully Customizable: Easy to configure and customize anything, from line-spacing to themes
All About Your Build: Generate server stubs and client libraries for your API in every popular language


![image](https://github.com/vidhyapasupathy/Swagger/assets/17640144/5a4c88b4-155f-4221-bb8f-6a863bf98eb8)



# Employee Details API - README
This repository contains the Employee Details API, which is a RESTful API for managing employee information. The API allows users to perform CRUD (Create, Read, Update, Delete) operations on employee data.

# API Endpoints
The API provides the following endpoints:

GET /employees: Get a list of all employees.<br>
POST /employees: Add a new employee.<br>
GET /employees/{id}: Get employee details by ID.<br>
PUT /employees/{id}: Update an existing employee by ID.<br>
DELETE /employees/{id}: Delete an employee by ID.<br>

# Data Models
The API uses the following data models:

Employee: Represents the employee details.<br>
EmployeeInput: Represents the request body for adding or updating an employee.

API Documentation
For detailed information on how to use each endpoint and the expected request and response formats, refer to the API documentation. The API documentation is available in OpenAPI (Swagger) format and can be viewed using the Swagger UI.





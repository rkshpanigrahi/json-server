# JSON Server Example Project

This project demonstrates how to set up a simple API server using JSON Server. JSON Server allows you to quickly prototype and develop APIs using a JSON file as a data source.

## Getting Started

### Prerequisites

Before you begin, ensure you have Node.js and npm installed on your machine.

- Node.js: [Download](https://nodejs.org/)
- npm (comes with Node.js)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rkshpanigrahi/json-server.git
   ```

2. Navigate to the project directory:

   ```bash
   cd json-server
   ```

3. Install the dependencies:

   ```bash
    npm install
    ```

### Usage
1. Populate the db.json file with your desired data. This file acts as the database for your API.
2. Start the JSON Server:

   ```bash
   npm run json-server
   ```

The server will start at http://localhost:3000 by default.

3. You can now access your API endpoints:

* GET http://localhost:3000/employees to retrieve a list of employees.
comments.
* GET http://localhost:3000/employees/1 to retrieve a specific user with ID 1.
* POST http://localhost:3000/employees with JSON body to add a new employees.
* PUT http://localhost:3000/employees/1 with JSON body to update the employee with ID 1.
* DELETE http://localhost:3000/employees/1 to delete the employee with ID 1.

### Customization

You can customize the behavior of JSON Server by modifying the db.json file and adding routes, middleware, and other configurations as needed. Refer to the [JSON Server documentation](https://www.npmjs.com/package/json-server) for more information.



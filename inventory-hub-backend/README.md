# Inventory Hub Backend

## Overview
The Inventory Hub Backend is a Spring Boot application designed to manage inventory data. It provides RESTful APIs for interacting with inventory items and integrates with a SQL database for data persistence.

## Project Structure
```
inventory-hub-backend
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── inventoryhubbackend
│   │   │               └── Application.java
│   │   └── resources
│   │       ├── application.properties
│   │       └── schema.sql
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── inventoryhubbackend
│                       └── ApplicationTests.java
├── pom.xml
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd inventory-hub-backend
   ```

2. **Build the project:**
   ```
   mvn clean install
   ```

3. **Run the application:**
   ```
   mvn spring-boot:run
   ```

## Configuration
- Database connection properties and other configurations can be set in `src/main/resources/application.properties`.
- The SQL schema for the database is defined in `src/main/resources/schema.sql`.

## Testing
Unit tests for the application can be found in `src/test/java/com/example/inventoryhubbackend/ApplicationTests.java`. You can run the tests using:
```
mvn test
```

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
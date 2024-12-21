
```markdown
# RestCrudApplication

RestCrudApplication is a Spring Boot application that provides a RESTful API for managing products. It includes basic CRUD operations and is documented using OpenAPI 3.0 annotations.

## Features

- **Create a Product**: Add a new product to the database.
- **Update a Product**: Modify details of an existing product.
- **Delete a Product**: Remove a product from the database.
- **Fetch All Products**: Retrieve a list of all products.
- **Fetch Product by ID**: Get details of a specific product using its ID.

## Technologies Used

- **Java 17**: Programming language used for development.
- **Spring Boot**: Framework for building the application.
- **Spring Data JPA**: For database interactions.
- **OpenAPI 3.0**: For API documentation.
- **Jakarta Persistence**: For ORM.
- **Jakarta Validation**: For validating input data.

## Getting Started

### Prerequisites

- **Java 17**: Ensure Java 17 is installed on your machine.
- **Maven**: Build tool for managing dependencies and building the project.
- **Database**: A running instance of a database (e.g., H2, MySQL).

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/RestCrudApplication.git
   cd RestCrudApplication
   ```

2. **Configure the database**:
   - Update the `application.properties` file in `src/main/resources` with your database configuration.

3. **Build the application**:
   ```bash
   mvn clean install
   ```

4. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

### API Endpoints

- **POST /api/products**: Create a new product.
- **PUT /api/products/{id}**: Update an existing product.
- **DELETE /api/products/{id}**: Delete a product.
- **GET /api/products**: Fetch all products.
- **GET /api/products/{id}**: Fetch a product by ID.

### API Documentation

The API is documented using OpenAPI 3.0. You can access the API documentation by navigating to `/swagger-ui.html` in your browser after running the application.

```

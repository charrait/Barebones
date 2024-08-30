# TravelBuddy

TravelBuddy is a comprehensive web application designed to help users plan, manage, and share their travel experiences. Built with Java and Spring Boot, it offers a robust set of features for travel enthusiasts.

## Features

- User registration and authentication
- Trip planning and management
- Destination exploration and reviews
- Social sharing of travel experiences
- RESTful API for integration with other services

## Technology Stack

- Java 17
- Spring Boot 3.x
- Spring Security
- Spring Data JPA
- Hibernate
- MySQL 8.0+
- Thymeleaf
- HTML5, CSS3, JavaScript
- Maven

## Project Structure
## Getting Started

### Prerequisites

- JDK 17 or later
- Maven 3.6.x or later
- MySQL 8.0.x or later

### Installation

1. Clone the repository:
2. Navigate to the project directory:
3. Configure the database connection in `src/main/resources/application.properties`:
spring.datasource.url=jdbc:mysql://localhost:8080/travelbuddy
spring.datasource.username=your_username
spring.datasource.password=your_password
4. Build the project:
   mvn clean install
   Copy
5. Run the application:
   mvn spring-boot:run
   Copy
6. Access the application at `http://localhost:8080`

## API Documentation

- POST /api/users/register - Register a new user
- POST /api/users/login - User login
- GET /api/trips - Get all trips for the authenticated user
- POST /api/trips - Create a new trip
- GET /api/trips/{id} - Get details of a specific trip
- PUT /api/trips/{id} - Update a trip
- DELETE /api/trips/{id} - Delete a trip
- GET /api/destinations - Get all destinations
- GET /api/destinations/{id} - Get details of a specific destination
- POST /api/reviews - Create a new review for a destination

For detailed API documentation, please refer to the Swagger UI available at `http://localhost:8080/swagger-ui.html` when running the application.

## Testing

To run the tests, execute the following command:
mvn test
## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Spring Boot documentation
- MySQL documentation
- Thymeleaf documentation

## Contact

Project Link: https://github.com/charrait/Barebones.git

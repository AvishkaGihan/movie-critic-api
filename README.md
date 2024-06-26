# Spring Boot Movies API

This is a Spring Boot application that provides a RESTful API for managing movie data, including reviews and other related information.

## Features

- Retrieve a list of movies
- Get details of a specific movie by IMDB ID
- Add a new movie
- Update an existing movie
- Delete a movie
- Add a review for a movie
- Get reviews for a specific movie

## Technologies Used

- Java
- Spring Boot
- Spring Data MongoDB
- MongoDB

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or later
- MongoDB installed and running

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/spring-boot-movies-api.git
    ```

2. Navigate to the project directory:

    ```sh
    cd spring-boot-movies-api
    ```

3. Build the project:

    ```sh
    ./mvnw clean install
    ```

4. Run the application:

    ```sh
    java -jar target/movies-api.jar
    ```

The application will start running on `http://localhost:8080`.

## API Documentation

The API documentation is available at `http://localhost:8080/swagger-ui.html` when the application is running.

## Contributing

Contributions are welcome! Please follow the [contributing guidelines](CONTRIBUTING.md) when submitting a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

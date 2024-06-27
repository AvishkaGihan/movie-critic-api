# MovieCritic API

This is the backend for the MovieCritic application, a web application that allows users to browse and review movies. The backend is built using Spring Boot and provides a RESTful API for managing movie data, including reviews and other related information.

## Features

- Retrieve a list of movies
- Get details of a specific movie by IMDB ID
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
   git clone https://github.com/your-username/moviecritic-backend.git
   ```

2. Navigate to the project directory:

   ```sh
   cd moviecritic-backend
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

## Environment Variables

The application uses the following environment variables:

- `MONGODB_URI`: The connection string for the MongoDB database.

You can set these environment variables in a `.env` file in the project root directory, or set them directly in your system environment variables.

## Contributing

Contributions are welcome! Please follow the [contributing guidelines](CONTRIBUTING.md) when submitting a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

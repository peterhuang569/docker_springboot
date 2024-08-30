# Chat App with Socket and PostgreSQL

This is a chat application that uses WebSockets for real-time communication and PostgreSQL for message persistence. The application allows users to send and receive messages instantly, with all messages saved to a PostgreSQL database.

## Features

- Real-time chat with WebSockets
- Message persistence using PostgreSQL
- Basic user interface for sending and receiving messages

## Technologies Used

- **Spring Boot**: Framework for building the application
- **Spring Data JPA**: For interacting with the PostgreSQL database
- **PostgreSQL**: Database for storing messages
- **WebSockets**: For real-time communication

## Dependencies

The project includes the following dependencies:

- `spring-boot-starter-data-jpa`: For Spring Data JPA support
- `spring-boot-starter-web`: For building web applications
- `postgresql`: PostgreSQL JDBC driver (runtime scope)
- `spring-boot-starter-test`: For testing support (test scope)

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven
- PostgreSQL database

### Installation

1. Clone the repository:

    ```sh
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```sh
    cd <project-directory>
    ```

3. Update the `application.properties` file with your PostgreSQL database credentials:

    ```properties
    spring.datasource.url=jdbc:postgresql://localhost:5432/your-database
    spring.datasource.username=your-username
    spring.datasource.password=your-password
    ```

4. Build the project:

    ```sh
    mvn clean install
    ```

5. Run the application:

    ```sh
    mvn spring-boot:run
    ```

## Usage

Once the application is running, you can open your web browser and navigate to `http://localhost:8080` to start using the chat application.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


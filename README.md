# Build Your Own HTTP Server in Python

[![progress-banner](https://backend.codecrafters.io/progress/http-server/0c6ebda1-b0ec-45a4-8ab1-a7258484ffa4)](https://app.codecrafters.io/users/codecrafters-bot?r=2qF)

This project is a solution to the [Codecrafters HTTP Server Challenge](https://app.codecrafters.io/courses/http-server/overview), where you build a fully functional HTTP server from scratch in the programing language of your choice (this one is in Python). The challenge is designed to deepen your understanding of how HTTP servers work under the hood, focusing on real-world concepts like request parsing, routing, concurrency, and file handling.

## Project Journey

This repository tracks the step-by-step development of the HTTP server, as reflected in the commit history:

- **Gzip Compression**: Adds support for gzip-encoded responses.
- **Connection Management**: Implements keep-alive and connection close based on headers.
- **Refactoring**: Refactors server to use classes and routing for maintainability.
- **Concurrent Requests**: Adds support for handling multiple connections simultaneously.
- **Persistent connection**: Handle any subsequent requests on the same connection.
- **File Serving**: Implements file serving and refactors response handling.
- **POST/File Creation**: Adds support for file creation via POST and robust error handling.
- **Path Handling**: Handles different HTTP paths.
- **Basic HTTP Response**: Server responds with 200 OK.
- **Project Initialization**: Initial setup and test scaffolding.

## Usage

1. **Python version:** Ensure you have `python (3.13)` installed locally
2. **Run the server:**
    ```sh
    python app/main.py
    ```
3. **Test HTTP requests:**
    Use `codecrafters test`, curl, Postman, or your browser to interact with the server.

## About Codecrafters

Codecrafters offers real-world proficiency challenges for developers. Learn more at [codecrafters.io](https://codecrafters.io).

---

_This project was created as part of the Codecrafters HTTP Server Challenge. For more details and to try the challenge yourself, visit [Codecrafters HTTP Server](https://app.codecrafters.io/courses/http-server/overview)._

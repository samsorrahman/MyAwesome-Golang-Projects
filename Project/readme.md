
# Simple Web Server Example

This repository contains a basic example of a web server built using Go's `net/http` package. The server serves static files from the `static` directory, includes a simple form handling route, and a hello world route.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Static file serving using the `net/http` package.
- Form handling with a basic example form that accepts name and address inputs.
- A hello world route at `/hello`.

## Getting Started

1. Clone the repository:
2. Run the command : go run main.go


4. Access the server in your web browser at [http://localhost:8080](http://localhost:8080).

## Usage

1. Open your web browser and go to [http://localhost:8080](http://localhost:8080).
2. Explore the static files served from the `static` directory.
3. Visit [http://localhost:8080/hello](http://localhost:8080/hello) to see the "Hello World!" message.
4. Submit the form at [http://localhost:8080/form](http://localhost:8080/form) to see form handling in action.

## Contributing

Contributions are welcome! If you find any issues or want to enhance this project, feel free to open a pull request. Please follow the existing code style and guidelines.

## License

This project is licensed under the [MIT License](LICENSE).


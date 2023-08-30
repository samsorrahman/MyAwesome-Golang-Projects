<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <title>Simple Web Server Example</title>
</head>

<body>

    <h1>Simple Web Server Example</h1>

    <p>This repository contains a basic example of a web server built using Go's <code>net/http</code> package. The server serves static files from the <code>static</code> directory, includes a simple form handling route, and a hello world route.</p>

    <h2>Table of Contents</h2>

    <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#getting-started">Getting Started</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#contributing">Contributing</a></li>
        <li><a href="#license">License</a></li>
    </ul>

    <h2 id="features">Features</h2>

    <ul>
        <li>Static file serving using the <code>net/http</code> package.</li>
        <li>Form handling with a basic example form that accepts name and address inputs.</li>
        <li>A hello world route at <code>/hello</code>.</li>
    </ul>

    <h2 id="getting-started">Getting Started</h2>

    <ol>
        <li>Clone the repository:<br>
            <code>git clone https://github.com/your-username/simple-web-server.git</code>
        </li>
        <li>Navigate to the project directory:<br>
            <code>cd simple-web-server</code>
        </li>
        <li>Run the server:<br>
            <code>go run main.go</code>
        </li>
        <li>Access the server in your web browser at <a href="http://localhost:8080">http://localhost:8080</a>.</li>
    </ol>

    <h2 id="usage">Usage</h2>

    <ol>
        <li>Open your web browser and go to <a href="http://localhost:8080">http://localhost:8080</a>.</li>
        <li>Explore the static files served from the <code>static</code> directory.</li>
        <li>Visit <a href="http://localhost:8080/hello">http://localhost:8080/hello</a> to see the "Hello World!" message.</li>
        <li>Submit the form at <a href="http://localhost:8080/form">http://localhost:8080/form</a> to see form handling in action.</li>
    </ol>

    <h2 id="contributing">Contributing</h2>

    <p>Contributions are welcome! If you find any issues or want to enhance this project, feel free to open a pull request. Please follow the existing code style and guidelines.</p>

    <h2 id="license">License</h2>

    <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

</body>

</html>

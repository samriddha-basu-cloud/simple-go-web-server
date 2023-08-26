# Simple Go Web Server Example

This repository contains a simple example of a Go programming language application that creates a web server to serve static files and handle form submissions. The application demonstrates basic web server functionality using the `net/http` package.

## Features

- Serves static files from the "./static" directory.
- Handles form submissions with the "/form" route.
- Greets users with a "Hello!" message on the "/hello" route.

## Usage

1. Clone the repository:

   ```sh
   git clone https://github.com/samriddha-basu-cloud/simple-go-web-server.git
   ```

2. Navigate to the project directory:

   ```sh
   cd simple-go-web-server
   ```

3. Run the application:

   ```sh
   go run main.go
   ```

4. Access the application in your web browser:

   - Static Website: [http://localhost:8080](http://localhost:8080)
   - Form Submission: [http://localhost:8080/form](http://localhost:8080/form)
   - Greeting: [http://localhost:8080/hello](http://localhost:8080/hello)

## Files

- `main.go`: The main application file containing the Go code for the web server.
- `static/index.html`: HTML file for the root route, displaying a simple heading.
- `static/form.html`: HTML file for the "/form" route, containing a form for name and address submission.

## Contributing

Contributions are welcome! If you find a bug or want to enhance this example, feel free to open an issue or submit a pull request.


---

Created by [Samriddha Basu](https://github.com/samriddha-basu-cloud)

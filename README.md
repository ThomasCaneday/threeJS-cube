# Three.js 3D Cube

This is my first Three.js program, which displays a 3D cube on an HTML page.

## Project Structure

The project contains the following files:

- `index.html` - The main HTML file that renders the 3D cube.
- `main.js` - The JavaScript file that creates and animates the 3D cube using Three.js.
- `package.json` - The file that lists the project dependencies.
- `package-lock.json` - The file that locks the versions of the dependencies.

## Prerequisites

To run this project, you need to have [Node.js](https://nodejs.org/) installed on your machine.

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ThomasCaneday/threeJS-cube.git
    cd threeJS-cube
    ```

2. **Install the dependencies:**
    ```bash
    npm install
    ```

3. **Run the project:**

    You can use a simple HTTP server to serve the `index.html` file. For example, you can use the `http-server` package:
    ```bash
    npm install -g http-server
    http-server
    ```

    Alternatively, you can open `index.html` directly in a web browser, but using a server is recommended for working with Three.js.

4. **Open your browser:**

    After running the server, open your browser and navigate to the address provided by the server (typically `http://localhost:8080`).

## Features

- Displays a rotating 3D cube using Three.js.

## Dependencies

- **Three.js** - A JavaScript 3D library that makes WebGL simpler.

## License

This project is licensed under the MIT License.

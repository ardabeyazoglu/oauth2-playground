# Oauth 2.1 Playground

This repository contains a simple OAuth 2.1 playground application that demonstrates the implementation of OAuth 2.1 authorization flows. It is created to help developers test their OAuth2 server implementations quickly.

Note: It is mostly vibe coded with Gemini 3.

Try out the hosted version at <https://oauth2-playground.ardabeyazoglu.com>.

## Running Locally

You can clone the repository and run `index.html` inside a local web server.
You have multiple options to run a local web server. Here are a few examples:

1. Vscode Live Preview Extension
   - Install the Live Preview extension from the VSCode marketplace.
   - Open the cloned repository in VSCode.
   - Click on "Go Live" at the bottom-right corner to start the server.
2. Python HTTP Server

   - If you have Python installed, navigate to the cloned repository in your terminal.
   - Run the following command:

     ```bash
      python -m http.server 8000
     ```

     Open your browser and go to `http://localhost:8000` to view the application.

3. Node.js http-server

   - If you have Node.js installed, you can use the `http-server` package.
   - First, install it globally if you haven't already:

     ```bash
      npm install -g http-server
     ```

   - Then, navigate to the cloned repository in your terminal and run:

     ```bash
      http-server -p 8000
     ```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

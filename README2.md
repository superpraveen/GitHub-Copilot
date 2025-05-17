# E-commerce Web Application

This is a full-stack e-commerce web application built using React for the client-side and Node.js for the server-side. The application is designed primarily for mobile users, providing a seamless shopping experience.

## Project Structure

The project is organized into two main directories: `client` and `server`.

### Client

The `client` directory contains the React application.

- **public/index.html**: The main HTML file for the React application.
- **src/components/Navbar.jsx**: A functional component that renders the navigation bar.
- **src/pages/Home.jsx**: A functional component that displays the home page.
- **src/pages/Product.jsx**: A functional component that displays product details.
- **src/App.jsx**: The main component that sets up routing and includes other components.
- **src/index.js**: The entry point for the React application.
- **package.json**: Configuration file for the client-side application.

### Server

The `server` directory contains the Node.js backend.

- **src/controllers/productController.js**: Functions for handling product-related requests.
- **src/models/productModel.js**: Mongoose model defining the product schema.
- **src/routes/productRoutes.js**: Routes for product-related API endpoints.
- **src/server.js**: The entry point for the Node.js server.
- **package.json**: Configuration file for the server-side application.

## Deployment

The application is deployed to Azure Web App using GitHub Actions. The workflow configuration can be found in the `.github/workflows/azure-deploy.yml` file.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the client directory and install dependencies:
   ```
   cd client
   npm install
   ```

3. Navigate to the server directory and install dependencies:
   ```
   cd ../server
   npm install
   ```

4. Start the server:
   ```
   npm start
   ```

5. In a new terminal, navigate back to the client directory and start the React application:
   ```
   cd ../client
   npm start
   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features you would like to add.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
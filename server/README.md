# E-commerce Application Server

This is the server-side of the E-commerce application built using Node.js and Express. The server handles API requests related to products and serves as the backend for the client-side React application.

## Project Structure

```
server
├── src
│   ├── controllers        # Contains the logic for handling requests
│   │   └── productController.js
│   ├── models             # Contains the Mongoose models
│   │   └── productModel.js
│   ├── routes             # Contains the API routes
│   │   └── productRoutes.js
│   └── server.js          # Entry point for the server
├── package.json           # Server dependencies and scripts
└── README.md              # Documentation for the server
```

## Getting Started

### Prerequisites

- Node.js
- MongoDB (for database)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the server directory:
   ```
   cd ecommerce-app/server
   ```
3. Install the dependencies:
   ```
   npm install
   ```

### Running the Server

To start the server, run the following command:
```
npm start
```

The server will run on `http://localhost:5000` by default.

### API Endpoints

- `GET /api/products` - Retrieve all products
- `GET /api/products/:id` - Retrieve a product by ID

### Deployment

This application can be deployed to Azure Web App using GitHub Actions. Please refer to the `.github/workflows/azure-deploy.yml` file for the deployment configuration.

## License

This project is licensed under the MIT License.
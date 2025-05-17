# E-commerce Application

This is a mobile-targeted e-commerce web application built using React for the client-side and Node.js for the server-side. 

## Client-Side

The client-side of the application is developed using React. It is designed to provide a responsive and user-friendly interface for mobile users.

### Features

- **Home Page**: Displays a list of products and promotional content.
- **Product Page**: Shows detailed information about a specific product.
- **Navigation Bar**: Provides easy navigation throughout the application.

### Getting Started

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd ecommerce-app/client
   ```

2. **Install dependencies**:
   ```
   npm install
   ```

3. **Run the application**:
   ```
   npm start
   ```

   The application will be available at `http://localhost:3000`.

### Folder Structure

- `public/`: Contains the main HTML file and static assets.
- `src/`: Contains the React components and pages.
  - `components/`: Reusable components like the Navbar.
  - `pages/`: Different pages of the application.
  
### Deployment

This application is set up to be deployed to Azure Web App using GitHub Actions. Please refer to the `.github/workflows/azure-deploy.yml` file for the deployment configuration.

### Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

### License

This project is licensed under the MIT License.
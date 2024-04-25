# Foodmine!

This project is a comprehensive step-by-step guide for building a web application using Angular for the frontend and integrating it with a backend built with Express.js and MongoDB. It covers various aspects from basic setup to advanced functionalities like user authentication, cart management, and payment integration.

## Lessons

### 1. Introduction to the Course

Provides an overview of the project and its objectives.

### 2. Install Development Tools

Instructions for setting up the development environment.

### 3. Create Angular App

Guidance on setting up the Angular project structure and dependencies.

### 4. Add Header

Creating and styling a header component for the application.

### 5. List Foods

Setting up a list of food items with images and basic functionalities.

### 6. Search

Implementing search functionality for finding specific food items.

### 7. Tags Bar

Adding tags to categorize food items and filter them accordingly.

### 8. Food Page

Creating a detailed page for each food item.

### 9. Cart Page

Implementing a shopping cart feature to manage selected items.

### 10. Not Found!

Handling 404 errors with a custom Not Found component.

### 11. Connect To Backend

Setting up a backend server using Express.js and integrating it with the frontend.

### 12. Login Page

Creating a login page with user authentication using JSON Web Tokens.

### 13. Make Components For Login Page

Building reusable components for the login page interface.

### 14. Connect Login API To MongoDB Atlas

Connecting the login API to a MongoDB Atlas database for data storage.

### 15. Register User

Implementing user registration functionality.

### 16. Loading!

Adding loading indicators to enhance user experience during data fetching.

### 17. Checkout Page

Creating a checkout page for finalizing orders.

### 18. Payment Page

Integrating PayPal for handling payments.

### 19. Adding Paypal

Setting up PayPal integration for secure and convenient payments.

### 20. Order Track Page

Implementing a page for tracking order status.

### 21. Deploy On Heroku

Instructions for deploying the application on Heroku for production use.

### 22. Updating Packages (Optional)

Guidance on updating project dependencies for better performance and security.

## Usage

### Setup Instructions:

1. **Clone the Repository:**

   ```
   git clone <repository_url>
   ```

2. **Frontend Setup:**

   ```
   cd frontend
   ```

3. **Install Dependencies:**

   ```
   npm install
   ```

4. **Backend Setup:**

   ```
   cd ../backend
   ```

5. **Install Dependencies:**

   ```
   npm install
   ```

6. **Set Up MongoDB:**

   - Create a MongoDB Atlas account or use an existing one.
   - Create a new cluster and database.
   - Obtain the connection string for your database.

7. **Environment Setup:**

   - In the backend folder, create a file named `.env`.
   - Inside the `.env` file, add the following line with your MongoDB connection string:
     ```
     MONGODB_URI=your_mongodb_connection_string
     ```

8. **Start Backend Server:**

   ```
   npm start
   ```

9. **Start Frontend Development Server:**

   ```
   cd ../frontend
   npm start
   ```

10. **Access the Application:**
    - Open your browser and navigate to `http://localhost:4200`.

### Additional Notes:

- Ensure that both frontend and backend servers are running simultaneously for the full functionality of the application.
- You may need to adjust CORS settings on your backend server to allow requests from your frontend domain.
- Make sure to replace `your_mongodb_connection_string` in the `.env` file with your actual MongoDB connection string.
- Check the respective documentation for any additional configuration or dependencies required for specific functionalities, such as PayPal integration.

With these instructions, users should be able to easily set up and run your Angular project locally, along with configuring MongoDB for backend data storage.

## Contributors

- [Abhishek Singh](https://github.com/Abhisheksingh734) - Lead Developer

## License

This project is licensed under the [MIT License](link to license file).

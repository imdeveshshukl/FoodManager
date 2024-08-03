# FoodManager

## Concept Note: Food Management System

### Problem
- **Food Waste:** Large quantities of food are wasted daily due to inefficient management and lack of proper tracking.
- **Lack of Coordination:** Disjointed systems between donors, food banks, and distribution centers result in poor food allocation and delays.
- **Hunger and Malnutrition:** Many communities face food insecurity despite excess food availability due to inefficiencies in distribution and inventory management.

### Solution
- **Centralized Platform:** Develop a Food Management System (FMS) to streamline the donation, inventory, and distribution processes.
- **Data Analytics:** Utilize data analytics to predict food needs, optimize distribution routes, and minimize waste.
- **User Interface:** Create a user-friendly interface for donors, food banks, and distribution centers to manage contributions and monitor inventory.

### Donation Management
- **Online Portal:** Develop an online portal for easy registration and donations for food charity organisation.

### Inventory Management
- **Real-time Updates:** Maintain real-time updates of food inventory levels to prevent overstocking or shortages.
- **Categorization:** Organize inventory by categories such as perishables, non-perishables, and dietary needs to streamline distribution.
- **Expiry Tracking:** Implement expiry tracking to ensure food safety and reduce waste.

### Features
- **Login and Signup:** Secure authentication using JWT for user login and signup.
- **Donation Page:** A dedicated page for users to register and track food donations.
- **Inventory System:** Efficient management of food inventory with real-time updates and categorization.
- **Kitchen Analytics:** Data analytics to provide insights into food management and optimize operations.
- **Map Visuals On Donation Page:** Integration with OpenStreetMap API to view geolocation for better coordination and tracking.

### Deployment
- **Frontend and Backend Deployed on Render:**
    - [FoodManager Frontend](https://foodmanager-frontend.onrender.com/)
    - Backend is also deployed on Render.

### Conclusion
The Food Management System aims to create an efficient, transparent, and user-friendly platform to manage food donations and inventory, ultimately reducing waste and improving food distribution to those in need.

## Tech Stack Used
- **Frontend:** MERN (MongoDB, Express.js, React.js, Node.js)
- **Authentication:** JWT

## Steps to Run the Project

### Frontend
1. Navigate to the frontend directory:
    ```sh
    cd frontend
    ```
2. Install the dependencies:
    ```sh
    npm install
    ```
3. Start the development server:
    ```sh
    npm start
    ```

### Backend
1. Navigate to the backend directory:
    ```sh
    cd backend/node_js_server
    ```
2. Install the dependencies:
    ```sh
    npm install
    ```
3. Set up the environment variables (e.g., database connection string).
4. Start the backend server:
    ```sh
    npm start
    ```

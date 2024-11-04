# Online-Tyre-Shopping-System
The Online Tyre Shopping System is a web-based application that simplifies purchasing tyres online.

# Features

1. User-Friendly Interface: A responsive, easy-to-navigate frontend that allows customers to browse and purchase tyres across various devices. 
2. Product Management: Admin dashboard with functionalities for adding, updating, and deleting products.
3. Secure User Authentication: Account registration and login are required to access shopping features, ensuring data privacy and security.
4. Shopping Cart and Order Management: Customers can add tyres, view order summaries, and complete purchases.
5. Database Management: Powered by MongoDB Atlas, providing secure, scalable data storage for products, orders, and user information.

# Technologies Used

1. Frontend: Angular and Bootstrap for responsive and interactive design.
2. Backend: Node.js with Express framework for server-side logic.
3. Database: MongoDB Atlas manages product, order, and user data.
4. Authentication: JWT-based authentication to protect user data.

# Installation:

1. Clone the repository
   
   ` git clone https://github.com/yourusername/online-tyre-shopping-system.git `

2. Navigate to the backend folder and install dependencies
   
   `cd tyre-api-main`
    `npm install`
   
3. Create a .env file in tyre-api-main with necessary environment variables, such as database URI and JWT secret.
   
   `npm run dev`
   
4. Start the backend server
   `cd ../tyre-web-main`
    `npm install`
    `ng serve`
  
5. Navigate to the frontend folder, install dependencies, and start the server

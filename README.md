B2B Ecommerce Project
Logo

This B2B Ecommerce project is built using the MERN stack (MongoDB, Express, React with Node.js), providing a robust platform for businesses to engage in wholesale buying and selling. The application incorporates separate client and server directories. The server contains the backend code, which can be run using yarn dev or npm run dev, while the client can be started with npm run start or yarn start.

Features
Seller, Buyer, and Administrator Roles: The application supports three main user roles - Sellers, Buyers, and Administrators - each with distinct functionalities and permissions.

Seller Accounts and Shops: Sellers can create accounts and set up their online shops to showcase and sell their products. They have the ability to manage their shop details, product listings, and inventory.

Wholesale Buying: Buyers can access the platform and purchase products in bulk, availing themselves of wholesale pricing and bulk order options.

Product Approval Workflow: Before products become available for purchase, they must be approved by Administrators to ensure quality control and adherence to platform guidelines.

Financial Management: Administrators have access to manage and monitor the platform's financial transactions, including processing payments, handling refunds, and generating financial reports.

Product Categories and Search: Products are organized into categories to facilitate easy navigation and search, helping buyers find the products they need quickly.

Order Tracking: Buyers can track their orders, view shipment details, and monitor delivery status.

Technologies Used
Frontend: React (with Node.js for the client-side)

Backend: Node.js, Express.js

Database: MongoDB (NoSQL database)

User Interface: HTML, CSS, JavaScript

Installation
Clone the repository from GitHub:
bash
Copy code
git clone https://github.com/Masaab086/Ecommerce-BtoB.git
Save to grepper
Install the required dependencies for both the backend and frontend:
bash
Copy code
cd your_b2b_ecommerce_project
cd server
npm install

cd ../client
npm install
Save to grepper
Configure the MongoDB connection in the backend:

Open server/config/config.js and replace YOUR_MONGODB_URI with your MongoDB connection URI.

Start the development server:

bash
Copy code
cd server
npm run dev

cd ../client
npm run start
Save to grepper
Access the application in your web browser at http://localhost:3000.
Usage
Upon launching the application, users can register or log in, choosing from the roles of Seller, Buyer, or Administrator.

Sellers can create and manage their shops, adding product listings and updating inventory.

Buyers can explore the platform, search for products, and place wholesale orders.

Administrators have access to approve new products, manage financial transactions, and oversee the platform's overall operation.

The platform ensures a seamless B2B ecommerce experience, catering to the needs of sellers and buyers alike.

Contributing
Contributions to the B2B Ecommerce Project are appreciated! If you encounter any issues or have ideas for improvements, feel free to submit a pull request.

License
This project is licensed under the MIT License.

Contact
For any inquiries or suggestions, please email us at masaabgul086@gmail.com

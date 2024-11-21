# Food Delivery WebApp

A fully functional and modern web application for food delivery services, built using **ReactJS**, **Node.js**, **Express.js**, and **MongoDB**. This project showcases a seamless integration of frontend, backend, and payment gateway functionalities, optimized for performance and user experience.

**Live Demo**: [Food Delivery WebApp](https://food-delivery-webapp-frontend.onrender.com/)

---

## 🚀 Features

- **User-Friendly Interface**: Built with ReactJS and styled using Tailwind CSS for an engaging and responsive user experience.
- **Secure Payment Gateway**: Integrated with Stripe for hassle-free and secure transactions.
- **Backend API**: Developed using Node.js and Express.js, ensuring scalable and efficient backend services.
- **Database Management**: Utilizes MongoDB for handling data storage and retrieval.
- **Admin Dashboard**: Includes functionalities for managing orders, updating menus, and tracking user activity.
- **Performance Optimization**:
  - **Lighthouse Scores**: 
    - Performance: 74
    - Accessibility: 86
    - Best Practices: 90+
    - SEO: 90+

---

## 🛠️ Technologies Used

### Frontend:
- **ReactJS**
- **Tailwind CSS**
- **Axios** for API calls

### Backend:
- **Node.js**
- **Express.js**
- **MongoDB**

### Additional Integrations:
- **Stripe** for payment processing

---

## 💻 Setup Instructions

Follow these steps to set up the project locally:

### Prerequisites:
- Node.js (v14+)
- MongoDB (Local/Atlas instance)

### Clone the Repository:
```bash
git clone https://github.com/SSNegi23/Food-Delivery-WebApp.git
cd Food-Delivery-WebApp
```

### Backend Setup:
1. Navigate to the `backend` directory:
   ```bash
    cd backend
    ```
2. Install dependencies:
   ```bash
    npm install
    ```
3. Set up a `.env` file in the `backend` folder with the following variables:
   ```makefile
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```
4. Start the server:
   ```bash
    npm start
    ```

### Frontend Setup:
1. Navigate to the `frontend` directory:
   ```bash
    cd frontend
    ```
2. Install dependencies:
   ```bash
    npm install
    ```
3. Update the BASE_URL in src/config.js to match your backend server's URL.
4. Start the frontend:
   ```bash
    npm run dev
    ```

## 📂 Project Structure
```arduino
Food-Delivery-WebApp/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   └── App.js
```

### Key Directories and Files:
- **backend/models**: Contains schema definitions for MongoDB, defining the structure of data such as users, orders, and products.
- **backend/routes**: Defines the API endpoints used by the frontend to communicate with the backend (e.g., `/api/orders`, `/api/products`).
- **backend/controllers**: Contains the logic for managing business rules and data retrieval or updates. Each controller typically maps to an API route.
- **frontend/src/components**: Contains modular and reusable UI components like buttons, card items, and headers that are used across different pages.
- **frontend/src/pages**: Contains specific pages, such as the homepage, product listings, and checkout page.
- **frontend/src/hooks**: Custom hooks for managing state and interactions, allowing for cleaner and more maintainable code.

---

## 🖥️ Live Demo
Explore the deployed version here: [Food Delivery WebApp](https://food-delivery-webapp-frontend.onrender.com/)

## 🙌 Contribution
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Added new feature"
    ```
4. Push the branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
5. Open a pull request

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

You are free to use, modify, and distribute this project in accordance with the terms of the MIT License. Please review the full text of the license in the LICENSE file for more information.

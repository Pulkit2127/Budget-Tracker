# Budget Tracker

A comprehensive budget tracking application with a frontend built using HTML, CSS, and JavaScript, and a backend developed with Node.js and MongoDB. This project aims to help users manage their expenses and income effectively.

## Features

- User authentication and authorization
- Add, edit, and delete expenses and income entries
- Categorize expenses and income for better tracking
- Visualize financial data with charts and graphs
- Responsive design for both desktop and mobile devices

## Technologies Used

### Frontend

- HTML
- CSS
- JavaScript

### Backend

- Node.js
- Express.js
- MongoDB

## Installation

Follow these steps to run the project locally:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/budget-tracker.git
    ```

2. **Navigate to the project directory:**

    ```sh
    cd budget-tracker
    ```

3. **Install backend dependencies:**

    ```sh
    cd backend
    npm install
    ```

4. **Set up MongoDB:**

    - Make sure MongoDB is installed and running on your system.
    - Create a database named `budgetTracker`.

5. **Create a `.env` file in the `backend` directory and add your environment variables:**

    ```env
    PORT=3000
    MONGO_URI=mongodb://localhost:27017/budgetTracker
    SECRET_KEY=your_secret_key
    ```

6. **Start the backend server:**

    ```sh
    npm start
    ```

7. **Install frontend dependencies:**

    ```sh
    cd ../frontend
    npm install
    ```

8. **Start the frontend development server:**

    ```sh
    npm start
    ```

9. **Open your browser and navigate to:**

    ```
    http://localhost:3000
    ```

## Usage

1. **Register** for a new account or **log in** if you already have an account.
2. **Add** new income and expense entries through the dashboard.
3. **View** and **edit** your financial records.
4. **Categorize** your expenses and income for better tracking.
5. **Visualize** your financial data with the built-in charts.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

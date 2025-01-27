# GPUnearU

---

## Introduction

The GPU Stock Tracker is a web application that allows users to track real-time stock information for GPUs. This app dynamically fetches the list of available GPUs and their stock details, including their type, availability status, and store details. It's designed to ensure users always have the most up-to-date data.

---

## Features

- Dynamically fetches GPU models like RTX 5090, RTX 4080 SUPER, etc., from an API.
- Displays real-time stock data for each GPU, including:
  - Type (e.g., Founders Edition, ROG Strix OC)
  - Store name and icon
  - Current price and availability status
  - Last available timestamp
  - Purchase link to the retailer's website
- Simple and lightweight design.
- No database required; all data is fetched dynamically.

---

## Skills Used

### **Frontend**
- ![React.js](https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=white) **React.js**: For building the web interface.
- ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) **TypeScript**: To ensure type safety and cleaner code.
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) **Tailwind CSS**: For styling and responsive design.
- ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) **React Router**: For navigation and routing between pages.
- ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white) **Axios**: For making HTTP requests to the backend.

### **Backend**
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) **Node.js**: For handling server-side logic.
- ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) **Express.js**: To create RESTful APIs for the app.
- ![dotenv](https://img.shields.io/badge/dotenv-ECD53F?style=for-the-badge&logo=dotenv&logoColor=white) **dotenv**: To manage environment variables securely.

---

## Instructions to Download and Run

### Backend Setup

1. Clone the backend repository

2. Navigate to the backend directory:
   `cd gpu-stock-backend`

3. Install dependencies:
   `npm install`

4. Create a `.env` file and configure the following variables:
   ```
   PORT=5000
   API_BASE_URL=https://nowinstockapi.com/api
   ```

5. Start the backend server:
   `npm start`

6. The backend will run on `http://localhost:5000`.

### Frontend Setup

1. Clone the frontend repository

2. Navigate to the frontend directory:
   `cd gpu-stock-frontend`

3. Install dependencies:
   `npm install`

4. Start the frontend development server:
   `npm start`

5. Open your browser and navigate to `http://localhost:3000`.


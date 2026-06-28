# MedidorAir-E

MedidorAir-E is a personal electrical consumption monitoring web application specifically designed for users of the AIR-E energy service in Barranquilla, Colombia. The application allows users to log, track, and visualize their daily energy usage to better manage their consumption and estimate potential costs based on local energy strata.

## Features

- User Authentication: Secure login and registration using Firebase Authentication.
- Real-time Database: Secure and efficient storage of consumption logs using Firestore.
- Data Visualization: Interactive charts (built with Chart.js) to display energy consumption trends over time.
- Strata Calculation: Configurable electrical strata settings to estimate billing based on local Barranquilla rates.
- Responsive Design: A modern, glassmorphic UI optimized for both desktop and mobile devices.
- Turn-based Logging: Ability to log readings at different times of the day (Morning, Afternoon, Night) for accurate tracking.

## Technologies Used

- HTML5 / CSS3 (Vanilla)
- JavaScript (Vanilla)
- Chart.js (Data Visualization)
- Firebase (Authentication & Firestore)

## Setup and Installation

1. Clone the repository.
2. Open `index.html` in your preferred code editor.
3. Search for the `firebaseConfig` object and replace the placeholder values with your actual Firebase project credentials:
   ```javascript
   const firebaseConfig = {
     apiKey: "YOUR_API_KEY",
     authDomain: "YOUR_AUTH_DOMAIN",
     projectId: "YOUR_PROJECT_ID",
     storageBucket: "YOUR_STORAGE_BUCKET",
     messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
     appId: "YOUR_APP_ID",
     measurementId: "YOUR_MEASUREMENT_ID"
   };
   ```
4. Run the project locally using a development server (such as Live Server in VS Code) or deploy it to a static hosting service.

## Disclaimer

This project is not officially affiliated with AIR-E. It is an independent tool created to help users monitor their personal consumption.

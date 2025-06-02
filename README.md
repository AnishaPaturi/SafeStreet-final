# SafeStreet Project

## Project Overview
SafeStreet is an AI-powered road maintenance platform designed to streamline the detection, reporting, and management of road damages. It consists of two main parts:

1. **SafeStreetApplication**: A mobile app built with React Native (Expo) that allows users to upload images of road damages. The app uses an AI Vision Transformer (ViT) model to classify the type and severity of damage. It generates damage summaries, shares reports via email, and provides a user-friendly interface for image uploads and damage tracking.

2. **SafeStreetWeb**: A web application built with React and Node.js (Express) that serves as a management and insights platform for authorities. It provides user authentication, damage report management, email notifications, and an NLP-powered chatbot for user queries.

---

## SafeStreetApplication (Mobile App)

### Overview
- Built with React Native using Expo framework.
- Uses file-based routing with Expo Router.
- Supports image uploads for road damage detection.
- Integrates with a Python Flask backend for AI-powered damage classification and chatbot.
- Provides dark/light theme support and splash screen management.
- Uses React Navigation for app navigation with tab-based layout.

### Key Features
- Image upload and damage classification using AI.
- Chatbot powered by Google Gemini generative AI.
- Summary generation and email sharing.
- Backend APIs for authentication, uploads, and chat.

### Folder Structure
- `app/`: React Native app source code with screens and routing.
- `assets/`: Fonts and images used in the app.
- `backend/`: Python Flask backend with AI model integration, routes, and PDF reports.
- `components/`: Reusable React Native components.
- `constants/`, `hooks/`, `scripts/`: Supporting code and utilities.

### Setup and Running
1. Install dependencies:
   ```bash
   cd SafeStreetApplication
   npm install
   ```
2. Start the Expo app:
   ```bash
   npx expo start
   ```
3. Start the backend server:
   ```bash
   cd backend
   python app.py
   ```
4. Use the Expo app on Android/iOS emulator or physical device.

---

## SafeStreetWeb (Web App)

### Overview
- Built with React using Vite for fast development.
- Node.js backend with Express and MongoDB for data storage.
- User authentication with OTP verification via email.
- Damage report management with severity classification.
- Email notifications and logging.
- NLP chatbot using natural language processing for user queries.

### Key Features
- User registration and login with OTP.
- Damage report submission and status updates.
- Email sending and logging.
- NLP-based intent classification for chatbot.
- Responsive UI with sidebar and multiple pages.

### Folder Structure
- `src/`: React frontend source code with components and pages.
- `public/`: Static assets like images and PDFs.
- `backend/`: Node.js Express backend with routes, models, and email setup.

### Setup and Running
1. Install dependencies:
   ```bash
   cd SafeStreetWeb
   npm install
   ```
2. Start the backend server:
   ```bash
   cd backend
   node server.js
   ```
3. Start the React frontend:
   ```bash
   npm run dev
   ```
4. Access the web app at `http://localhost:3000` (or the port shown by Vite).

---

## Technologies Used
- React Native, Expo, Expo Router
- React, Vite, React Router DOM
- Node.js, Express, MongoDB, Mongoose
- Python, Flask, Google Gemini AI
- Nodemailer for email
- Natural for NLP classification
- Google Gemini generative AI for chatbot
- Various supporting libraries and tools

---

## Environment Variables
Both backends require environment variables for API keys and email credentials:

- For Python Flask backend (`SafeStreetApplication/backend`):
  - `GEMINI_API_KEY`: API key for Google Gemini AI

- For Node.js backend (`SafeStreetWeb/backend`):
  - `MONGODB_URI`: MongoDB connection string
  - `EMAIL_USER`: Email address for sending emails
  - `EMAIL_PASS`: Password or app-specific password for email

---

## Additional Notes
- The mobile app and web app are separate but complementary parts of the SafeStreet platform.
- The AI model integration is handled in the Python backend.
- The web backend manages user data, reports, and email notifications.
- The project uses modern React patterns and best practices for maintainability.

---

## Contact and Support
For questions or support, please contact the project maintainers or open an issue in the repository.

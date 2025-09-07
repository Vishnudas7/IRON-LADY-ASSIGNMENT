# IRON-LADY-ASSIGNMENT

Iron Lady Leadership Chatbot
This is a modern, interactive chatbot designed to answer frequently asked questions about the programs offered by the Iron Lady Leadership Academy. It provides a seamless, conversational experience for users seeking information about the academy.

Key Features
Conversational AI: The bot provides detailed, conversational responses using the Gemini 2.5 Flash API, offering a natural and engaging user experience.

Real-Time Messaging: All chat messages are stored and synchronized in real-time using Firebase Firestore, ensuring a persistent and reliable conversation history.

User-Friendly Interface: The design is colorful and attractive, featuring a smooth gradient header, subtle animations, and intuitive controls.

Interactive Elements: The interface includes a text input for free-form questions and quick-access buttons for common queries, making it easy for users to get information.

Fully Responsive: The layout is designed to be fully responsive, providing an optimal viewing experience on both desktop and mobile devices.

Technologies Used
Frontend: HTML, JavaScript, and Tailwind CSS for the UI and styling.

Backend & Database: Firebase Firestore for real-time message storage and authentication.

AI: Google's gemini-2.5-flash-preview-05-20 model, which powers the chatbot's detailed and conversational responses.

Hosting: The application is self-contained within a single HTML file, making it easy to deploy and share.

How It Works
The chatbot functions by sending a user's question to the AI model, along with a "system prompt" that contains a knowledge base about the academy's programs. The AI processes this information and generates a detailed, friendly response. The conversation, including both user and bot messages, is then saved to a private Firestore collection, ensuring the chat history is preserved.



Course Management App
This is a single-file web application for managing courses. It provides a full CRUD (Create, Read, Update, Delete) workflow with a user-friendly interface and a unique AI-powered feature.

Features
Create, Read, Update, & Delete: The app allows you to add new courses, view them in a real-time list, edit their details, and delete them when they are no longer needed.

Real-Time Data Sync: Courses are stored in a Firebase Firestore database, and the list updates automatically whenever a change is made.

AI-Powered Summarization: The application includes a button to generate a concise summary of any course's description, powered by the Gemini 2.5 Flash model.

Responsive Design: The layout is designed to be fully responsive, providing a seamless experience on both desktop and mobile devices.

Technologies Used
Frontend: HTML, JavaScript, and Tailwind CSS. All code is contained within a single HTML file for simplicity.

Backend: Firebase Firestore for database functionality.

AI: Google's gemini-2.5-flash-preview-05-20 model for summarizing course descriptions.

How It Works
The app authenticates users anonymously, giving them a unique ID for a private, dedicated space in the database. When you add or edit a course, the data is sent to Firestore. An onSnapshot listener keeps the displayed list in sync with the database at all times. The AI summarization feature works by taking the course description and sending it to the Gemini API, which then returns a concise summary to display in a modal.

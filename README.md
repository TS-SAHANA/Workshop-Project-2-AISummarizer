# Workshop-Project-2-AISummarizer

AI Summarizer is a web application that utilizes the Hugging Face API to summarize textual content. This project combines a backend server built with Node.js and Express for handling API requests and a frontend React application for user interaction.

## Overview

The AI Summarizer allows users to input text and receive concise summaries using the Hugging Face BART model. The backend server handles communication with the Hugging Face API, while the React frontend provides an intuitive user interface.

## Features

**Text Summarization:** Input text and receive summarized content.

**Loading Spinner:** Visual indication of summarization in progress.

**Adjustable Parameters:** Fine-tune summarization parameters such as max and min length.

## Project Structure

**backend:** Node.js and Express server for handling API requests.

**server.js:** Backend server code for summarization.

**.env:** Configuration file for environment variables.

**frontend:** React application for the user interface.

**App.js:** Main component for the React application.

**App.css:** Styling for the React components.

**index.html:** HTML template for the React application.

## Dependencies
- Node.js
- Express
- Axios
- React
- CORS

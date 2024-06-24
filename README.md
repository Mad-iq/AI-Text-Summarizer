# AI Text Summarizer Application

This is a full-stack application that leverages the Hugging Face BART model to provide concise summaries of large texts. The application includes a user-friendly interface for text input and output, ensuring a seamless and efficient user experience.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Installation](#installation)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)


## Features

- Text Summarization: Utilizes the Hugging Face BART model to generate summaries for long texts.
- User Interface: Simple and intuitive UI for easy text input and summary display.
- Error Handling: Comprehensive error handling to ensure a smooth user experience.
- Input Validation: Ensures input text meets length requirements (200-100,000 characters) before allowing submission.
- Secure API Integration: Securely integrates with the Hugging Face API using environment variables.

## Usage

1. Open your browser and navigate to `http://localhost:5173`.
2. Enter the text you want to summarize in the input box.
3. Click the "Submit" button.
4. The summarized text will be displayed in the output box below the input area.


## Installation

### Prerequisites

- Node.js and npm installed on your machine

### Backend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/ai-text-summarizer.git
    cd ai-text-summarizer/backend
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the `backend` directory and add your Hugging Face API access token:
    ```env
    ACCESS_TOKEN=your_huggingface_access_token
    ```

4. Start the backend server:
    ```bash
    npm start
    ```

    The backend server will be running on `http://localhost:3000`.

### Frontend Setup

1. Navigate to the `frontend` directory:
    ```bash
    cd ../frontend
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Start the frontend development server:
    ```bash
    npm run dev
    ```

    The frontend server will be running on `http://localhost:5173`.


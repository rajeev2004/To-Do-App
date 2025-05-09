# ToDo Application

A simple To-Do application built with React, designed to manage tasks, mark them as complete, and filter by various task states such as "All," "Complete," and "Important." The tasks are stored in the browser's local storage, so they persist even after page refreshes.

## Features

- **Task Management**: Add, delete, mark as complete, and mark as important.
- **Task Filters**: Filter tasks based on their completion status or importance.
- **Task Labeling**: Label tasks as "Indoor" or "Outdoor."
- **Weather Details**: If a task is labeled as "Outdoor," the application fetches and displays real-time weather details using       OpenWeatherMap API.
- **Local Storage**: Tasks are saved in `localStorage`, ensuring persistence across sessions.
- **Responsive UI**: Built using React and styled with CSS.

## Tech Stack

- **Frontend**: React.js
- **Styling**: CSS
- **State Management**: React useState, useEffect hooks
- **Routing**: React Router
- **Local Storage**: Tasks are stored in the browser’s localStorage.
- **Weather API**: OpenWeatherMap API for fetching weather details for outdoor tasks.

## Getting Started

### Prerequisites

Make sure you have Node.js and npm installed on your machine. If not, you can download and install them from [here](https://nodejs.org/).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rajeev2004/To-Do-App.git

2. Navigate into the project directory:
    
    ```bash
    cd To-Do-App

3. Install dependencies:

    ```bash
    npm install

4. Run the Application Locally

    ```bash
    npm run dev

5. Build the project:

    ```bash
    npm run build

6. Deploy the project:

    ```bash
    npm run deploy

7. Your app will be deployed at https://<your-username>.github.io/To-Do-App

## Demo

You can check out the live website [here](https://rajeev2004.github.io/To-Do-App/).

![ToDo Application Screenshot](https://raw.githubusercontent.com/rajeev2004/To-Do-App/refs/heads/main/src/assets/Screenshot%202025-01-16%20000057.png?raw=true)
# AI Code Refactoring Tool

![image](https://github.com/user-attachments/assets/9ebc2217-51dc-4bb0-8f0d-48820f66a2ed)


## Overview

This application uses AI to analyze and refactor code snippets, providing suggestions for improvements in readability, performance, and code quality. Users can submit code in various programming languages and receive detailed analysis and optimized versions of their code.

## Features

- **Code Analysis**: Submit code snippets for AI-powered analysis
- **Multiple Languages**: Support for JavaScript, Python, Java, and more
- **Quality Metrics**: Receive metrics on code complexity, maintainability, and performance
- **Improvement Suggestions**: Get specific suggestions with line references
- **Refactored Code**: View an optimized version of your code
- **History**: Access your previously analyzed code snippets

## Tech Stack

### Backend
- Flask (Python)
- PostgreSQL
- SQLAlchemy
- Flask-JWT-Extended for authentication

### Frontend
- React
- React Router
- CodeMirror (for code editing)
- Chart.js (for metrics visualization)

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js 14+
- PostgreSQL

### Installation

#### 1. Clone the repository

```bash
git clone https://github.com/devznsh/ai_code_refactoring.git
cd ai-code-refactoring
````


#### 2. Run the setup script
```bash 
powershell -File setup.ps1
```
#### 3. Start the Backend Server
```bash
cd backend
.\venv\Scripts\Activate.ps1
python app_simple.py
```
The backend will be accessible at: http://127.0.0.1:5000

#### 4. Start the Frontend Application

```bash 
cd frontend
npm start
```
The frontend will be accessible at: http://localhost:3000

Project Structure

```bash 
ai-code-refactoring/
├── backend/
│   ├── app_simple.py      # Main Flask application
│   ├── venv/              # Python virtual environment
│   └── .env               # Environment variables
├── frontend/
│   ├── public/            # Static assets
│   ├── src/               # React components and services
│   ├── package.json       # NPM dependencies
│   └── .env               # Frontend environment variables
└── setup.ps1              # Setup script
```

















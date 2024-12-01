##  Background and Problem Statement:

##  Impact and Proposed Solution:

##  Project Outcomes and Deliverables:

##  Instructions:

The repository is organised following thislayout:

BUILDERS ALLIANCE/
├── code/
│   ├── ai_api_and_deployment/
│   │   ├── app/          # Application logic
│   │   ├── dataset/      # Datasets used by the AI model
│   │   ├── model/        # AI models and logic
│   │   ├── __init__.py   # Initialization file
│   │   ├── main.py       # FastAPI entry point
│   │   ├── Dockerfile    # Dockerfile for containerized deployment
│   │   ├── .env          # Environment variables
│   │   └── requirements.txt   # Python dependencies
│   ├── webApp/
│       ├── chat.html     # Main frontend HTML file
│       ├── script.js     # JavaScript logic for the frontend
│       ├── styles.css    # Styling for the frontend
│       ├── requirements  # Backend dependencies for the web app
│       └── package.json  # npm dependencies
├── requirements.txt       # Main Python dependencies
├── .gitignore             # Ignored files and folders
├── README.md              # Project documentation


### Prerequisites

Before starting, ensure you have the following installed:
- **Python** (3.9 or later)
- **Node.js** (16.x or later) and **npm**
- **Docker** (optional, for containerized deployment)
- An internet connection to access the deployed AI API hosted on [Render](https://render.com) (free hosting).

---

### Installation and Setup

#### Clone the Repository

To begin, clone this repository to your local machine and navigate to the project folder:

```bash
git clone https://github.com/salmaelbarbori/2024-InnovAI-Hackathon/tree/main/BUILDERS%20ALLIANCE
cd 2024-InnovAI-Hackathon/BUILDERS%20ALLIANCE
```

#### Navigate to the **ai_api_and_deployment** folder:

```bash
cd builders/code/ai_api_and_deployment
```

Install the Python dependencies:

```bash
pip install -r requirements.txt
```

uvicorn main:app --reload

```bash
uvicorn main:app --reload
```

#### Navigate to the **webApp** folder:

```bash
cd ../webApp
```

Install npm dependencies:

```bash
npm install
```

Start the web application:

```bash
npm start
```

#### Run the Application

Install Python dependencies from the main requirements.txt:

```bash
Install Python dependencies from the main requirements.txt:
```

Navigate to the webApp folder and install npm dependencies:
bash

 ```bash
 cd builders/code/webApp
npm install
 ```
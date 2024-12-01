##  Background and Problem Statement:

##  Impact and Proposed Solution:

##  Project Outcomes and Deliverables:

##  Instructions:

The repository is organised following this layout:

```markdown

BUILDERS ALLIANCE/
├── code/
│   ├── ai_api_and_deployment/
│   │   ├── app/
│   │   ├── dataset/
│   │   ├── model/
│   │   ├── __init__.py
│   │   ├── main.py
│   │   ├── Dockerfile
│   │   ├── .env
│   │   └── requirements.txt
│   └── webApp/
│       ├── chat.html
│       ├── script.js
│       ├── styles.css
│       ├── requirements
│       └── package.json
├── requirements.txt
├── .gitignore
└── README.md

```

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
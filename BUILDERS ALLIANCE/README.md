# Terhal ✈️ 🇲🇦

<div align="center">
    <img src = "./Terhal_bot.png" alt = "terhal logo" width = "300px" height = "300px" >
</div>

##  Background and Problem Statement: 💢

Salma and Zineb wishes to travel to 5 Moroccan cities during their 1 week of vacations, but the first thing to do is to plan a their travel, yet this step requires around x3 times of prep compared to the travel itself. Based on their previous experiences in planning travels, they found out that 1 week of travel may need 3 weeks of research to find:

The best places to visit in each city.
As well as the transportation to consider.
among others they find it hard to search in foreign languages while they only master DARIJA.

They tried to solve this by consulting a guide but each city needs consultation with a guide, but they found it x5 expensive compared to their expectations and budget while the provided service was general more than personalized.

This bottleneck is now preventing them as well as 100 of their fellows  from taking the decision of traveling and discovering the country. This is impacting the country’s economy directly since  the tourism sector in Morocco provide  around 7% UDP.

**Do we need to spend weeks of preparation in order to travel for one week?** and, **do we need to master foreign languages in order to plan trips in our homeland ?**


##  Impact and Proposed Solution: 💡

**Terhal** is an AI Assistant that understands DARIJA perfectly, and who is **knowledgeable about the best places** to visit in Morocco, and that can help Zineb, Salma and their fellows **plan their trips in 10 minutes instead of 3 weeks**, while providing them with **personalized recommendations**. 

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
|
├── presentation.pdf
├── demo
├── Terhal Logo
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
node proxy-server.js
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
node proxy-server.js
 ```

 ## Pitch 

 ## Demo

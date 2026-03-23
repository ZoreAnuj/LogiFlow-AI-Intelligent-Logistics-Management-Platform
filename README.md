# LogiFlow AI: Intelligent Logistics Management Platform

LogiFlow AI is an experimental platform that applies multi-step AI agents and vector search to automate and optimize logistics operations. It explores how autonomous AI workers can enhance predictive maintenance, dynamic routing, and emergency response within supply chains.

## Key Features
*   **Multi-Step AI Agents** orchestrate complex logistics workflows like shipment tracking and issue resolution.
*   **Vector-Powered Search** enables semantic querying of logistics data using TiDB Serverless.
*   **Predictive Analytics** forecasts potential delays and recommends optimal delivery routes.
*   **Automated Emergency Response** triggers and manages contingency plans for disruptions.

## Tech Stack
*   **Backend:** Python, FastAPI
*   **AI/ML:** LangChain, OpenAI API
*   **Database:** TiDB Serverless (Vector Search)
*   **Infrastructure:** Docker

## Getting Started
1.  Clone the repo: `git clone https://github.com/zoreanuj/LogiFlow-AI-Intelligent-Logistics-Management-Platform.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Set your environment variables (e.g., `OPENAI_API_KEY`).
4.  Run the application: `uvicorn main:app --reload`
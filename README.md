# Logistics Agent Orchestrator

An intelligent logistics management platform exploring the automation of supply chain operations using multi-step AI agents. It leverages vector search for data intelligence to handle tasks like predictive maintenance and dynamic route optimization.

## Key Features
*   **Multi-Agent Orchestration:** Coordinates specialized AI agents for complex, sequential logistics workflows.
*   **Vector-Powered Intelligence:** Utilizes TiDB Serverless vector search for semantic data retrieval and analysis.
*   **Predictive Analytics:** Implements models for proactive maintenance and shipment delay forecasting.
*   **Dynamic Optimization:** Automates real-time route and load planning based on live constraints.

## Tech Stack
*   **Backend:** Python, LangChain/LlamaIndex
*   **Database:** TiDB Serverless (Vector Search)
*   **AI/ML:** OpenAI API, Scikit-learn
*   **Infrastructure:** Docker, Git

## Getting Started
1.  Clone the repo: `git clone https://github.com/zoreanuj/logistics-agent-orchestrator.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Set your environment variables (e.g., `OPENAI_API_KEY`).
4.  Run the main application: `python src/main.py`
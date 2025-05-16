# CrewAI RAG Chatbot

This repo contains a local implementation of a Agentic RAG Chatbot using: 
- **CrewAI** for agentic orchestration  
- **Chonkie** for document chunking  
- **Qdrant** as vector database  
- **DeepEval** for retrieval & generation evaluation  

## Installation

1. Create and activate a Python venv:  
   \`\`\`bash
   python3 -m venv venv
   source venv/bin/activate
   \`\`\`
2. Install dependencies:  
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`
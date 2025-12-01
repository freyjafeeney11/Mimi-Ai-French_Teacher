Mimi/                     # Root project folder
│── backend/              # AI model & API (PyTorch, FastAPI/Flask)
│   ├── models/           # Trained AI models
│   ├── scripts/          # Data processing/training scripts
│   ├── server.py         # API to communicate with the frontend
│   ├── requirements.txt  # Python dependencies
│── frontend/             # Godot interface
│   ├── assets/           # Pixel art, animations, UI elements
│   ├── scenes/           # Godot scenes (chatbox, menus, etc.)
│   ├── scripts/          # Godot scripts for UI logic
│   ├── main.tscn         # Main Godot scene
│── data/                 # Open-source books, film clips, etc.
│── notebooks/            # Jupyter Notebooks (for experimenting)
│── README.md             # Project documentation
│── setup.sh              # Setup script (optional)

# Mimi: AI French Teacher  
A friendly AI-powered French teacher with a chatbot interface.  

---

## Quick Start Guide  

### 1. Activate Virtual Environment  
Before running the project, activate the Python virtual environment:  

#### Mac & Linux  
```bash
cd backend
source venv/bin/activate
uvicorn server:app --reload
ollama run mistral 

godot frontend/main.tscn

# main files to edit: server.py, chatbox.gd

#### Progress
Need to continue working on prompt engineering, she doens't answer quite right.
Add UI and art elements
Add domain access free literature 
Set a global personality
Set safety rules

    # converned about storing too muhc history. maybe give it full memory? like chat gpt? right now its session per session, is it storing it?
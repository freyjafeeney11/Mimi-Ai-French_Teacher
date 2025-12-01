
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

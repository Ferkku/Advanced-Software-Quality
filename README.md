# Running

To setup the project, follow these steps:

1. Install Ollama
    1. https://ollama.com/download
    
2. Pull the qwen2.5 model
    1. ollama pull qwen2.5

3. Clone this repository
    1. git clone https://github.com/Ferkku/Advanced-Software-Quality.git

4. Create a .env file at the root of this repository
    1. Generate a personal access token for github
    2. Add the following lines to the .env file:
```
# If you want to test some other repository change the BASE_REPO
BASE_REPO = "kgabis/parson"
GITHUB_API_TOKEN="<YOUR_GITHUB_API_TOKEN>"
```

5. Run the Notebook cells
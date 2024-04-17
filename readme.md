(Docker setup)
- Do this only if you know howw docker compose work, for beginners use the normal desktop setup.
- Compose this file
>https://github.com/SudoSuMaster/docker-compose-files/tree/main/ollama-ai

(Normal desktop setup)
1. Download Ollama client
- https://ollama.com/download
>![image](https://github.com/SudoSuMaster/localAI/assets/75373825/60778203-4b32-45aa-96d5-8494d20647d4)

2. open cmd ollama run llama2 
>![image](https://github.com/SudoSuMaster/localAI/assets/75373825/7e720936-8ba0-4550-9f7d-b79fa1853532)

3. To install other models use the following command,
- ollama run (Model name)
- Example: ollama run llama2-uncensored
>![image](https://github.com/SudoSuMaster/localAI/assets/75373825/c056ac1a-b483-4894-b6e0-b8f5a01d8186)
Links to models:
- https://ollama.com/library
- https://huggingface.co/models

4. After you run the last command it will start a terminal prompt
>![image](https://github.com/SudoSuMaster/localAI/assets/75373825/20da8f1a-f937-41d0-a6e8-8b6969a6cde6)

6. If you want to use the webgui you need to install docker desktop and run the docker command
- https://www.docker.com/products/docker-desktop/
- docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
>![image](https://github.com/SudoSuMaster/localAI/assets/75373825/b6269ccf-190a-4833-92c2-69796e605765)
- You can go to the webgui page by clicking on de port numbers 300:8080
>![image](https://github.com/SudoSuMaster/localAI/assets/75373825/8c13d794-a6af-4e6e-a4fd-49318de88386)
- Signup (This is fully local)
![image](https://github.com/SudoSuMaster/localAI/assets/75373825/cd182c42-802a-4a92-bdb8-cdedd9091e7a)


7. Before you make prompt you need to select the model you want to use.
![image](https://github.com/SudoSuMaster/localAI/assets/75373825/dc1b8226-1079-4954-a5f9-4a7f82e93150)


# docker-compose for quickly starting ollama, n8n and open webUI

- run - docker compose up -d
- add model - docker exec -it ollama ollama pull llama3.2:1b
- check model - docker exec -it ollama ollama list
- actual ollama url for n8n - http://ollama:11434

## External links

- n8n - http://localhost:5678/
- open webUI = http://localhost:3000/
- ollama - http://localhost:11434

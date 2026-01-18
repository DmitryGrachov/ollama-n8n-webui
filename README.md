docker-compose for quickly starting ollama, n8n, and webUI

run - docker compose up -d
add model - docker exec -it ollama ollama pull llama3.2:1b
check model - docker exec -it ollama ollama list
actual ollama url - http://ollama:11434

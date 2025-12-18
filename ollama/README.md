## Ollama Cloud Models Setup

### Create API Key
Create an account and generate an API key at [ollama.com](https://ollama.com/settings/keys)

### Authentication
Sign in from within the Docker container:
```sh
docker exec -it ollama ollama signin
```

### Pull a Cloud Model
Browse available models at [ollama cloud models](https://ollama.com/search?c=cloud), then pull:
```sh
docker exec -it ollama ollama pull gemini-2.0-flash-exp:cloud
```

### Run a Model
```sh
docker exec -it ollama ollama run gemini-2.0-flash-exp:cloud
```
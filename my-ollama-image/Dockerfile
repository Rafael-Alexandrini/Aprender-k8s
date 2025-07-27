# Essa é uma imagem personalizada do ollama 
# É o ollama, mas com um modelo leve já baixado
# Na mesma pasta desse Dockerfile está uma pasta 'models'
# Com o modelo qwen3:0.6b dentro, baixado por uma instância do ollama

FROM  ollama/ollama:0.9.6

# copia o modelo qwen3:0.6b para a pasta de modelos
COPY ./models /root/.ollama/models

# inicia a api do ollama
CMD ["serve"]

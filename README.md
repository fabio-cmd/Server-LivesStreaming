# Servidor de Live Streaming com NGINX

Um servidor para live streaming simples, somente com o essencial para você transmitir e assistir 

## Requisitos

- Docker
- Extensão para o Chrome (ou safari) "Native MPEG-DASH + HLS Playback" 
- OBS

## Tecnologias

- Docker Compose
- NGINX

## Protocolos

- RTMP (Real Time Message Protocol)
- HLS (HTTP Live Streaming)

## Como Executar

1. Suba os containers utilizando docker compose:

```bash
docker-compose up --build
```

## Assistir a transmissão

No Chrome com a extensão "MPEG-DASH + HLS Playback" ou no Safari, acesse:

```bash
http://localhost:8081/live/.m3u8
```

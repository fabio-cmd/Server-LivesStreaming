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

Suba os containers utilizando docker compose:

```bash
docker-compose up --build
```

Abra o OBS > Configurações > Transmissão > Servidor

```bash
rtmp://localhost:1935/live
```
Clique em ok e depois clique em Iniciar transmissão


## Assistir a transmissão

No Chrome com a extensão "MPEG-DASH + HLS Playback" ou no Safari, acesse:

```bash
http://localhost:8081/live/.m3u8
```

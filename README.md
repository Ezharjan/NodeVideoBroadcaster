# WebRTC Video/Audio Broadcast

Sends a video from the broadcast page to all connected clients (watchers) over WebRTC PeerToPeer connections.

## Getting started

Start using Node

```bash
# Install dependencies for server
npm install

# Run the server
node server
```

Start using Docker

```bash
# Building the image
docker build --tag webrtcvideobroadcast .

# Run the image in a container
docker run -d -p 4000:4000 webrtcvideobroadcast
```


## How to use

1. Open 127.0.0.1:4000/broadcast.html in web browser to send live streamming video;

2. Open 127.0.0.1:4000/index.html in web browser to see the live video. 

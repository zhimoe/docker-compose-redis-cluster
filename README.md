# How to create local redis cluster

```bash
# macos > `en0` is your network interface that you're using right now.
ip=$(ipconfig getifaddr en0) docker-compose up -d --build

# ubuntu
ip=$(hostname -I | awk '{print $1}') docker-compose up -d --build

```

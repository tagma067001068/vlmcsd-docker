# VLMCSD for Docker

Deploy vlmcsd service on Docker container

```bash
git clone https://github.com/Wind4/vlmcsd-docker.git vlmcsd
cd vlmcsd

# Use docker-compose service
docker-compose up -d

# or docker build image
docker build -t vlmcsd .
docker run -idt -p 1688:1688 vlmcsd
```
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/tagma067001068/vlmcsd-docker)

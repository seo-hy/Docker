```
docker build -t seok02h/khu-dc-python-socket:1.0 .
docker run --name socket-test -d -p 4000:9000 seok02h/khu-dc-python-socket:1.0

docker push seok02h/khu-dc-python-socket:1.0

```
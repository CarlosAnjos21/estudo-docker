# estudo-docker

Estudos de Docker (Full Cycle, Módulo 01).

## flask-demo
```bash
cd flask-demo
docker build -t flask-demo:1.0 .
docker run -d -p 5000:5000 flask-demo:1.0
```

## node-demo
```bash
cd node-demo
docker build -f docker/Dockerfile -t node-demo:1.0 .
docker run -d -p 3000:3000 node-demo:1.0
```

# docker

## build your docker image with Dockerfile

```bash
docker build -t [your-image-name] .
```

# minikube

## start minikube
```bash
minikube start --driver=docker
```

## load your created docker image
```bash
minikube image load [your-image-name]
```

## tunnel your minikube with your local host
```bash
minikube tunnel
```

now you can access your site in http://127.0.0.1/

# kubectl

## apply your deployments yaml files
```bash
kubectl apply -f ./k8s
```
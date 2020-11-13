# Jupyter Lab

Jupyter Lab with Tensorflow and PyTorch docker image.

Build:
```
docker build -t bashkirtsevich/gpu-jupyter-lab .
```

Startup:
```
docker run -d -p 8888:8888 -v $(pwd)/notebooks:/tf/ --gpus all --name gpu-jupyter-lab bashkirtsevich/gpu-jupyter-lab
```

URL:
```
http://localhost:8888/
```

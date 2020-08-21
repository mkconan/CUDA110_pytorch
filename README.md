# Build and Run 
```
docker build --build-arg IMAGE_NAME=nvidia/cuda -t nvidia/cuda:torch .
docker run -it --gpus all nvidia/cuda:torch /bin/bash
```
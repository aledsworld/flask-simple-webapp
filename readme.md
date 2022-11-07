# Simple Flask Web App

## Build Image 
from the root directory run 
```
image build -t flask_docker .
```

## Run Container 

```
docker run -p 5000:5000 -d flask_docker
```
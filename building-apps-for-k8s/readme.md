# Building Applications for K8s
## Lesson 3. Building Container Images

1. Create main.go
2. Build main.go:

   ``` go build -o /server . ```
3. Test main.go:
   1. run ./server
   2. visit <http://localhost:8000>
4. Create DockerFile
5. Build Image:

   ``` docker build -t scooterjec/kubeacademy-building-apps:0.1 . ```
6. Log in to hub.docker.com, if necessary
7. Push Image:

   ```docker push scooterjec/kubeacademy-building-apps:0.1```

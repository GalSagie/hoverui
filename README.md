# Hover UI
![alt tag](https://cloud.githubusercontent.com/assets/15094187/19744811/ee431d0e-9b83-11e6-9f70-126c0f4fb50c.gif)
[Click here for sandbox](https://io-visor-hover.firebaseapp.com/)
## Deploying using Docker
  1. Clone hoverui git repository
  2. Install Docker
  3. Build Docker image
    * `docker build -t hoverui .`
  4. Run Docker image
    * `docker run hoverui`
  5. Open Hover UI in browser
    * Use `docker ps` and `docker network inspect bridge` to see what IP address the server is listening on
  

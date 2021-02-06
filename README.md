## Dash/Plotly deployment on server, simple example

This is a simple example of dash/plotly deployment on server using flask, gunicorn and docker

### Folder Structure 
```
+-- app
|   +-- app.py            // source code of dashboad application
|   +-- requirements.txt  // libraries
+-- .env                  // configuration about where the app runs
+-- docker-compose.yaml   // build instructions
+-- Dockerfile            // docker image instructions
```

### Commands
```
1. cd dash-deployment
2. docker-compose build
3. docker-compose up
```
Then, If you built it localy visit: 127.0.0.1:5000 otherwise, use your server ip xxx.xxx.xxx.xxx:5000 to see the dashboard.

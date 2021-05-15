# RTSP Module - Streaming & Object Detection using opencv & yolo model

Prerequisites: 
- Docker & Docker compose should be installed in the system

Below mentioned two docker images are used in this project.

1. Mongo [Used as datastore] - https://hub.docker.com/_/mongo
2. RTSP Module (Streaming and object detection implemented using Python & Opencv & YOLO. Developed by myself and pushed to docker hub) - https://hub.docker.com/repository/docker/gowthamgowti97/rtsp-module/general

Tools Used:
- Python
- Flask
- Opencv
- Yolo - Model for object detection
- Mongo DB

To run the application execute the below mentioned steps.

1. Navigate to the root of the current repository, where you can find docker-compose.yml & readme.me files
2. Run the below mentioned command.
    ```sh
    docker compose up -d
    ```

Application will start at localhost:5000. We can visit the same URL in the browser.

Below mentioned is the home page of the application.

```sh
http://localhost:5000/
```

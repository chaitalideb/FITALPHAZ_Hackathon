# FITALPHAZ using Posenet

## Contents

### Demo 1: Using Camera feed at realtime

This particular camera demo shows how to estimate poses in real-time from a webcam video stream. **This video is deplayed only for demostration purpose.** 
In FITALPHAZ, the kids/users will be the one who will perform action and the pose would be detected on realtime 

<img src="https://raw.githubusercontent.com/tensorflow/tfjs-models/master/posenet/demos/camera.gif" alt="cameraDemo" style="width: 600px;"/>




## Demo Setup

cd into the demos folder:

```sh
cd posenet/demos
```

Install dependencies and prepare the node_modules and build directory:

```sh
yarn or npm install -g
```

To run the demo, and launch a dev server. Change the default port to any custom and available port from the system and run the below command:

```sh
export PORT=8080 && npm run start
```

If you are running this project directly in Google cloud shell, then follow the below steps:

```
gcloud app deploy
```

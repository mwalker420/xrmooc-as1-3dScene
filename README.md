# xrmooc-as1-3dScene
XR MOOC - Assignment 1 - 3D Scene

## Install Dependencies (for server)
Modern browsers expect the vr experiences to be served via https so this project includes a server to allow local testing.
```
yarn install

# Create a directory to save the certificate
mkdir conf
cd conf
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
```

## Running a local server
From the project root directory run: 
```
yarn serve
```

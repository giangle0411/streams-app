## Setup the project

### Run the client app

`cd client`
`npm start`

### Run the json-server

`cd server`
`npm start`

### Setup RTMP Server (Real Time Messaging Protocol Server)

`cd rtmp-server`
`npm init` - Enter till the end
`npm start`
The RTMP Server will run on port 8000

### Install Open Broadcaster Software (OBS)

Download and Install [OBS](https://obsproject.com)

### Setup your stream

1. Launch OBS after installation
2. Settings -> Stream
   Stream Type: Custom Streaming Server
   URL: rtmp://localhost/live
   Stream key: (your stream id)
3. Add a new Scene (Bottom left hand side of the OBS Application)
4. Add a Video Source, select Display Capture, Setup the Display window with your personal references.
5. Add an Audio Source, select Audio Input Capture, select the Device that captures the audio.
6. Start/Stop recording on Control window (bottom right hand side of the OBS Application).

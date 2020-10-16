Live stream your screen or webcam, with OBS studio or another software installed

Instructions for OBS (after running client, api and rtmpserver):
1. Create your stream in livy, save your stream id (last number after "/" in the url of your stream).
2. Open OBS on your computer.
3. In the left corner, click the "+" button, to create a new scene and name it.
4. Click the next "+" button in "sources" section and select "Display capture", select your display and click "ok" button.
5. Click the same "+" button in "sources" section and select "Audio Input capture", select your microfone and click "ok" button.
6. Click the "settings" button in the right corner section an go to "Stream". In "service" select "custom", in server type "rtmp://localhost/live" and in 
"stream key" type your stream id and click "ok".
7. Now click the "start streaming" button and go to your stream in livy and click play. Now you're live!

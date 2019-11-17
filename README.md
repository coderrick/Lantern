# Lantern
CapitolRoyale360 Hackathon project provides an immersive Music experience for Drivers with AR and Bose


### Post a command through the Terminal using Hypno and plug in video
place the video that you want to upload from your desktop and send up to the cloud if your using MacOS.
Make sure you are inside your desktop in the terminal or wherever you may have the file

curl -F "camera=@input.mp4" https://cloud.hypno.com/jobs?packageId=5dd12c9b08d52f69905d16c9

### Retrieve the data or JSON API coming from Hypno and place inside browser

curl https://cloud.hypno.com/jobs/5dd12c9b08d52f69905d16c9


After submitting the video you can either run a curl command to check if the video uploaded properly, or just paste the url in the browser and render the file without the curl command.


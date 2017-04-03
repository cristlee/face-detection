# Facetrack

Facetrack can be used to track human faces in a video feed and store them in a directory.You can also search for a face and see if it had been detected.

 You can also:
  - Import and save files from GitHub, Dropbox, Google Drive and One Drive
  - Drag and drop markdown and HTML files into Dillinger
  - Export documents as Markdown, HTML and PDF

### Tech
Facetrack uses Opencv to work properly.Head to http://opencv.org/ to install it in your system.

## Installation

```sh
$ pip install -r requirements.txt
```

For production environments...

```sh
$ npm install --production
$ npm run predeploy
$ NODE_ENV=production node app
```
### How to run?
To start tracking use:
```sh
python facedetect.py
```
To check if a face is was detected pass the images as parameteters

```sh
python facedetect.py check_if_faces_in_this_image_was detected.jpg
```






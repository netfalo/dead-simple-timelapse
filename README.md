# Simple Timelapse creator

Pure html+js to create timelapses

Upload the images, once the upload finished the timelapse will start to
play. After the first run the video download will popup.

The rendering happens inside the browser. The images are drawn on a canvas
spaced 40ms apart(~24FPS), the "animations" from the canvas are recorded using
the MediaRecorder API to create the timelapse video.

# Foreground detection using OpenCV

Foreground detection is one of the most prominent applications in computer vision. Aside from the example of video calls, foreground detection may be used in finding and reading text in an image, determining where obstacles are in autonomous vehicles, and many other applications..

## Edge Detection and Contours

Edge detection, like the name implies, attempts to find the lines of contrast, or edges, in an image. This key first step pre-processes the image to help differentiate any objects. Several methods of edge detection exist, but the Canny method is both immensely popular and comes packaged with OpenCV.
Once the edges are found, finding contours become much easier and more accurate. In computer vision, contours are simply the continuous boundary lines between areas of contrasting color or intensity. Unlike edge detection, finding contours will find prominent shapes within the image.

### Noise Suppression
Noise suppression, when turned on by video owners, allows viewers to isolate speech from other sounds and music during playback. Noise suppression can be switched on or off for each newly-uploaded video.

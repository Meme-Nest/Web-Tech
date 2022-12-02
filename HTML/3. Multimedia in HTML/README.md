<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Multimedia in HTML](#multimedia-in-html)
  - [Note](#note)
    - [Unpaired Tag / Singleton Tag](#unpaired-tag--singleton-tag)
    - [Paired Tag](#paired-tag)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Multimedia in HTML

1. Image Tag

   - Image tag or \<img> is used to add the image to the webpage.
   - 'src' attribute in image tag is used to add the image source.
   - src stands for source.

   ```html
   <img src="img/note-taking.png" height="200" width="250" />
   <img
     src="https://clickup.com/blog/wp-content/uploads/2020/01/note-taking.png"
     height="200"
     width="250"
   />
   ```

   <img src='img/note-taking.png' height='200' width='250'>
   <img src='https://clickup.com/blog/wp-content/uploads/2020/01/note-taking.png' height='200' width='250'>

1. Audio Tag

   - Audio tag \<audio> is used to add audio file to the webpage.
   - In the audio tag "src" attribute is used tol add the audio source.
   - To get the audio controls like pause and play button, mute and un-mute button, download and playback speed option we have to add 'controls' attribute to the audio tag.

   ```html
   <audio src="img/Kannada-bgm.mp3" controls></audio>
   ```

   <audio src="img/Kannada-bgm.mp3" controls></audio>

1. Video Tag
   - video tag \<video> is used to add the video file to the webpage.
     "src" attribute in the webpage is used to add the video source to the video tag.
   - controls attribute in the video tag will add alt the video control like play and pause button, mute and un-mute button, download etc to the video in the webpage.
   ```html
   <video src="https://youtu.be/LJv-o3d96aQ" controls></video>
   ```
   <Video src='https://youtu.be/LJv-o3d96aQ' controls height='300' width='500'></Video>

---

## Note

### Unpaired Tag / Singleton Tag

- \<hr>
- \<br>
- \<img>

### Paired Tag

- \<head>\</head>
- \<u>\</u>
- \<audio>\</audio>

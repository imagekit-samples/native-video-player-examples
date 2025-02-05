# Native Video Player Examples

This repository contains simple HTML pages demonstrating different methods of creating native website video experiences. 

1. `yt_embed.html` - This file shows a video hosted on YouTube, embedded as an iframe on the page.
2. `video_embed.html` - This file shows a video delivered using the HTML5 `video` tag. It uses a video hosted on ImageKit for automatic video format optimization, compression, and progressive streaming.
3. `videojs_embed.html` - This file uses `video.js` for Adaptive Bitrate Streaming using HLS. ImageKit's Video API creates the HLS manifest with different representations to create the poster image.
4. `reels_interface.html` - This file creates an interface similar to modern applications like Instagram to demonstrate vertical video streaming. It uses ImageKit to create video thumbnails in vertical aspect ratio, video trims, and adaptive streaming manifests for vertical videos.

## How to run
Download the content of this repository, and inside the folder, start any simple HTTP server. For example, with Python installed, using `python3 -m http.server 9000`, you can start a server on port 9000. The files can then be accessed in any browser like `http://localhost:9000/yt_embed.html`. 
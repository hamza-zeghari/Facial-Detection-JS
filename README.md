# Facial Features Detector 

## Based on face api && models

To lunch project just lunch index.html file, best way use extention in VScode Live Server to lunch file from editor.

Live Server : https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer


## Low-end Devices Bug

The video eventListener for `play` fires up too early on low-end machines, before the video is fully loaded, which causes errors to pop up from the Face API and terminates the script (tested on Debian [Firefox] and Windows [Chrome, Firefox]). Replaced by `playing` event, which fires up when the media has enough data to start playing.

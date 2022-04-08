# flac-m3u
A repository for creating flac m3u playlists for albums in The Inernet Archive. The current m3u files listed on the Internet Archive only link to mp3 files. Hopefully this will please some of you audiophile archivists out there! 

I created these flac m3u playlist files by simply swapping the "mp3" with "flac" in all the song URLs in the original m3u files from The Internet Archive. 

I am happy to add any flac m3u files you build from The Internet Archive to this repository. Ideally The Internet Archive eventually finds this and takes the idea to heart and implements a lossless option to their offerings directly on the site. 


**Notes:**
- This approach is not elegant. I am just playing around to see if this is usable in anyway. If you have suggestions on how to make this better, please let me know!

- Tested with my Raspberry Pi 3 running Volumio3. The URL to the raw file content plays as a custom web radio channel in the Web Radio section of Volumio. 
  - You can skip forward in tracks with no problem, however trying to go back a track brings you to the beginning of song 1.
  - Hitting pause seems to crash the player's play/pause functionality. After hitting pause once, you can press play again and it will restart playing but your play buttons become unresponsive after that.   

- Also tested with VLC player. 
-   The 'raw' m3u links work as expected in this scenario, you can play/pause and skip/go back as much as you please. 

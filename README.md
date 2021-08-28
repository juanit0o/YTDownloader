# YTDownloader
A useful youtube downloader which you can use to download individual musics, playlists or even search by keywords

This application runs in your CLI and searches content on youtube either by a link or a name and it can
* Download videos
* Entire playlists

<p align="center">
       <img src="https://i.imgur.com/zoITFTW.gif" width="550" height="350" alt="Layout of the website">
</p>

The ffmpeg dependency is due to the fact that all of the progressive streams are limited to 720p and by downloading both video and audio separated and merging them afterwards using this library guarantees that you can download videos up to 2k and with high bitrate audio.

The downloads are saved in 2 folders which are created in the same directory that the script is run in (./Videos and ./Musics). 

If you want to change the path you can do so on the global variables on the top of the script as shown bellow.

<p align="center">
       <img src="https://i.imgur.com/rP3uzLh.png" width="500" height="100" alt="Layout of the website">
</p>


As of now, pytube has some problems in its regex searches and ability to search only by a keyword but it is being solved on their side

Hope you enjoy it and find it useful!

###### This was made using the pytube library and you have to have <a href=https://www.ffmpeg.org/>ffmpeg</a> installed and set in your ambient variables.

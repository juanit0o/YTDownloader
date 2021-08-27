# YTDownloader
A useful youtube downloader which you can use to download individual musics, playlists or even search by keywords

This application runs in your CLI and searches content on youtube either by a link or a name and it can
* download videos
* entire playlists

## This was made using the pytube library and you have to have ffmpeg installed => https://www.ffmpeg.org/ and set in your ambient variables.

The ffmpeg dependency is due to the fact that all of the progressive streams are limited to 720p and by downloading both video and audio separated and merging them afterwards using this library guarantees that you can download videos up to 2k and with high bitrate audio.

As of now, pytube has some problems in its regex searches and ability to search only by a keyword but it is being solved on their side

Hope you enjoy it and find it useful


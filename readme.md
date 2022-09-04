# yt-dlp config - downloading entire youtube channels for archival

# Readme

This repo contains a config file which makes it easy to download entire youtube channels, and also update them without having to re-download existing videos.

Update 2022-09: It has been a while since [youtube-dl](https://github.com/ytdl-org/youtube-dl) was updated, so I have updated all the commands and config to use the current most popular youtube video downloader: [yt-dlp](https://github.com/yt-dlp/yt-dlp).

# Usage

Edit channel urls in `yt-dlp-channels.txt`.

The empty file `yt-dlp-archive.txt` is used to store downloaded video ids.

## Linux

    chmod +x download_archive.sh

Run using `./download_archive.sh`

## Windows

Run `download_archive.bat`

## Thanks

Thanks to https://www.reddit.com/user/Stephen304 for creating the original config, on the since deleted post: https://www.reddit.com/r/DataHoarder/comments/858ny5/my_youtubedl_config_downloading_entire_channels/

There is an archive of the original post at: https://archive.ph/T4sa2

#!/bin/bash

sudo apt install youtube-dl ffmpeg mplayer --yes --fix-missing --fix-broken

youtube-dl --ignore-errors --format bestaudio --extract-audio --audio-format mp3 --audio-quality 160K --output "~/Music/%(title)s.%(ext)s" --yes-playlist $1
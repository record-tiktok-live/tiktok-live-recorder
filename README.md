<h1>Simplified App to Record TikTok Lives</h1>
<p>If you're looking for an app that does all of this for you, checkout the Rewatch LIVE app. It autorecords TikTok LIVEs and saves everything to the cloud for you.</p>
<a href="https://rewatchlive.com">Rewatch Live app site</a><br />
<a href="https://apps.apple.com/us/app/rewatch-live-save-live-stream/id647518956)">Rewatch Live iOS App</a><br />
<a href="https://play.google.com/store/apps/details?id=com.reactish.rewatchlive&hl=en&gl=US&pli=1">Rewatch Live Android app</a><br />
<br />
<br />
<img src="https://github.com/record-tiktok-live/tiktok-live-recorder/blob/11ff0e31f825a419fe0cde1d3ed266cb26d7531e/rewatchlivelogo.png" width="100px" alt="image" border="0">

<br />
<hr />

<div align="center">


<h1> TikTok Live Recorder🎥</h1>

<em>TikTok Live Recorder is a tool for recording live streaming tiktok.</em>

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

The TikTok Live Recorder is a tool designed to easily capture and save live streaming sessions from TikTok. It records both audio and video, allowing users to revisit and preserve engaging live content for later enjoyment and analysis. It's a valuable resource for creators, researchers, and anyone who wants to capture memorable moments from TikTok live streams.

</div>

<div align="left">


  <h1> How To Use </h1>

- [Install on Windows & Linux 💻](#install-on-windows--linux-)
- [Install on Android 📱](#install-on-android-)

</div>

<br>

## Install on Windows & Linux 💻

To clone and run this application, you'll need [Git](https://git-scm.com) and [Python3](https://www.python.org/downloads/) installed on your computer. From your command line:

<!-- <img src="https://i.ibb.co/8DkzXZn/image.png" alt="image" border="0"> -->

<be>

</div>

  ```bash
# Clone this repository
$ git clone https://github.com/Michele0303/tiktok-live-recorder
# Go into the repository
$ cd tiktok-live-recorder
# Install dependencies
$ pip install -r requirements.txt
# Run the app on windows
$ python main.py -h
# Run the app on linux
$ python3 main.py -h
  ```

## Install on Android 📱

<b>Install Termux from F-Droid:</b> <a href="https://f-droid.org/packages/com.termux/">HERE</a> - Avoid installing from Play Store to prevent potential issues.

From termux command line:

<be>

</div>

  ```bash
# Update packages
$ pkg update
$ pkg upgrade
# Install git, python3, ffmpeg
$ pkg install git python3 ffmpeg
# Clone this repository
$ git clone https://github.com/Michele0303/tiktok-live-recorder
# Go into the repository
$ cd tiktok-live-recorder
# Install dependencies
$ pip install -r requirements.txt
# Run the app
$ python main.py -h
  ```

<div align="left">


## To-Do List 🔮

- [x] Automatic Recording
- [x] Recording by room_id
- [x] Recoding by tiktok live url
- [x] Using a proxy to bypass login restrictions in some countries. (only to get the room_id)
- [x] Implement a logging system
- [ ] Improve the graphical user interface
- [ ] Add a feature to send recorded live streams to Telegram via the Telegram bot

## Legal ⚖️

This code is in no way affiliated with, authorized, maintained, sponsored or endorsed by TikTok or any of its affiliates or subsidiaries. Use at your own risk.

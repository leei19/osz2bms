# osz2bms

[Release] OSZ TO BMS GENERATOR - Automate your Muse Dash Custom Charts!

Hello everyone!

I am excited to introduce the OSZ TO BMS GENERATOR, a Python and FFmpeg-based tool that automatically creates a complete template file just by importing an .osz file.

As many of you know, Osu! has the most extensive library of custom songs. Osu! mappers have already done the hard work of setting up BPM timings, music files, and cover images. I started this project with the idea that if we could convert these files directly into templates for Muse Dash customs, it would save charters a massive amount of effort.

How to use:

Find the song you want at osu.ppy.sh/beatmapsets and download the .osz file.

Run OSZ2BMS and select the downloaded file.

Note: The tool includes features for info.json settings and demo.ogg cutting. (If you don't configure them, default values will be used.)

Click the green "Generate BMS Package" button.

Please wait a moment for the conversion. Once finished, a complete template folder with all BPMs filled in will appear on your desktop.

Just drag in an .osz file and hit generate—annoying tasks like BPM timing, cover trimming, and demo cutting are automated like magic!

✨ Special Feature: Smart BPM Algorithm
Due to the limit of 255 BPM timing points in mdbmsc, complex songs (e.g., Parallel Universe Shifter) were previously impossible to chart.
I have implemented a special algorithm that automatically reduces BPM timing points to under 255. Crucially, this algorithm maintains a timing error of less than 1ms. Now, complex songs like Parallel Universe Shifter can be successfully converted and charted!

CREDITS
This program was developed entirely with the assistance of Gemini. I do not have a background in coding. I am releasing the source code in the hopes that capable developers in the community will contribute to its future development.

I hope this tool helps bring many great songs with complex timings to life as Muse Dash charts.

Thank you!

Best regards,
MaxCur_14

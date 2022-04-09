# Roblox-FPS-Unlocker
Usage
Download the latest release from https://github.com/oxstin/Roblox-FPS-Unlocker/releases/tag/rbxfpsunlocker
Extract rbxfpsunlocker-x64.zip or rbxfpsunlocker-x86.zip into a folder
Run rbxfpsunlocker.exe before or after starting Roblox
Enjoy those beautiful frames 👌
Alternatively, RFU is available on Scoop. 1

Submitting an Issue
NOTICE: Issues are currently closed due to spam and the number of non-issues or low quality submissions. They will be reopened once I have the time and capacity to moderate them. Sorry!

Before submitting an issue, please:

Make sure you submit an issue or suggestion
Make sure your question or problem cannot be answered in the FAQ below
Please read previous issues to make sure your question was not asked before
Be as informative as possible: issues with ambiguous titles and missing/low-quality descriptions will be deleted
Include a copy of RFU's console (tray icon->Toggle Console). You can censor any personal information (file paths and so on)
Include steps on how to reproduce the issue, if possible
Include on what platform(s) the issue occurs (normal client, Windows 10 Roblox app, Roblox Studio)
If relevant, include system specifications (e.g. GPU model) and monitor refresh rates
Issues submitted not attempting to follow these guidelines will be closed or deleted.

FAQ
Roblox is force-closing, files are being deleted, and/or my anti-virus is detecting rbxfpsunlocker as malware. What do I do?
All detections are false positives. Internally, RFU "tampers" with running Roblox processes in order to uncap framerate and can appear as suspicious to an anti-virus. For reasons unbeknownst to me, 32-bit builds of RFU garner many more false positive detections than 64-bit builds and are no longer included in new releases. If you don't trust me, feel free to download the repository, review the source code, and compile the project yourself with Visual Studio 2019. Otherwise, add an exception to your anti-virus for rbxfpsunlocker.exe (or the folder it is in).

How can I see my FPS?
Press Shift+F5 in-game to view your FPS. In Roblox Studio, go to View->Stats->Summary.

How do I resolve choppiness and input lag at high framerates?
Try entering fullscreen using Alt+Enter.

I used this unlocker and my framerate is the same or below 60. Why?
I say with great emphasis, as this seems to be a common misconception, that Roblox FPS Unlocker is an FPS unlocker and not a booster. It will not boost Roblox's performance in any way and only removes Roblox's 60 FPS limit. To take advantage of RFU, a computer powerful enough to run Roblox at more than 60 FPS is required.

This being said, if you know your computer is powerful enough but still aren't seeing higher framerates with the unlocker, feel free to submit an issue.

Can I set a custom framerate cap?
You can create your own list of FPS cap values by editing the FPSCapValues array inside the settings file located in the same folder as rbxfpsunlocker.exe.

Does this work for Mac?
No. Roblox FPS Unlocker was written only for the Windows platform and I currently have no plans to change this. However, those more experienced and with Mac hardware are free to port this project to Mac!

Why do I get a "Failed to connect to Github" error?
This error means Roblox FPS Unlocker could not connect to the Internet to check for updates. This may be due to your anti-virus, computer firewall, network firewall, or etc. blocking the request. The error can be safely ignored by pressing "Ok".

Why do I get a "Variable scan failed" error?
This means RFU was unable to find the internal variable responsible for uncapping Roblox's framerate. This might happen if another program has already edited the value (e.g. an exploit). Please verify that your framerate is at a stable ~60.0 FPS (Shift+F5) before using the unlocker. If it is and the error still occurs, please submit an issue.

How do I uninstall Roblox FPS Unlocker?
RFU does not install itself anywhere. It can be deleted by simply exiting the program if it is open (tray icon->Exit) and deleting rbxfpsunlocker.exe.

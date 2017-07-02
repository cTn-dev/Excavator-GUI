# Excavator GUI by cTnko
Excavator GUI is built for Excavator GPU miner by NiceHash (mining various altcoins).

### How to get started?
1. [Download](https://github.com/nicehash/excavator/releases) Excavator by NiceHash
2. [Download](https://github.com/cTn-dev/Excavator-GUI/releases) Excavator GUI by cTnko
3. Unpack Excavator GUI to any folder you like
4. Unpack Excavator to "excavator" folder you find inside the Excavator GUI
5. Start GUI.bat

### How to use?
After first successful Excavator GUI start you will be presented with Overview window containing an Example Job, all you need to do is click "Add GPU", select which GPUs you want to use for this job and add them, afterwards click "Start Job" and you should be mining!<br />
Both Pools and Wallet windows contain an example Pool and Wallet which should help you get started, all of them can be simply removed by clicking the delete button.

## Warning
Excavator GUI supports overclocking on Nvidia cards. Use overclocking at your own risk as it may PERMANENTLY DAMAGE YOUR COMPUTER HARDWARE!!!

### What are the advantages of using the GUI instead of the command file?
1. You don't have to use command file at all, you don't have to restart the miner for the new settings to take effect.
2. Flexibility, you are able to add/remove jobs, devices & workers on the fly.
3. You can setup Overclock for your hardware on the fly (Using MSI afterburner or EVGA precision is recommended to first find the best core/memory overclock, then use GUI to automatically apply them each time it starts).
4. Many other advantages (please see the Features section)

### Features
No need to use command files.<br />
Built in auto-restart script that will bring Excavator back to life if it crashes.<br />
Add/Remove pools/wallets/jobs/algorithms/devices/workers on the fly!<br />
Easy to setup dual mining.<br />
Overclocking (adjusting core/memory delta, TDP % and fan speed), this feature is currently available only on Nvidia cards.<br />
Saved Overclocking will be automatically applied when GUI starts and automatically restored to defaults when GUI closes.<br />
Adding device (GPU) to specific automatically adds recommended amount of workers depending on the algorithm and hardware used.<br />
Adding device to algorithm which isn't supported on this hardware will be automatically blocked (great for beginners).<br />
Jobs that are currently running will be remembered even when the GUI closes or machine shutsdown, next time the GUI is started it will automatically resume all active jobs (great for machines that run 24/7 and automatically power on after power outtage, just add shortcut to GUI.bat to your Windows startup folder).<br />

## Disclaimer
Excavator GUI contains 1% developer fee<br />
The developer fee only gets applied after extensive period of time, any short time mining sessions won't be affected by this fee at all.<br />
There will be a clear visual indication in the GUI when the 1% fee will be mined.<br />
If you don't agree with this, please don't use it!<br />

### TODO List
1. Backup Pools (automatic switch in case pool goes down)
2. Confirmation dialogs for removing jobs/pools/wallets
3. Better support for AMD cards - i currently don't own an AMD card, so this might take a while, sorry :(
4. Have a feature idea? Let me know through the Issue section [here](https://github.com/cTn-dev/Excavator-GUI/issues)

### Changelog
02.07.2017 @ 0.1 - First public release

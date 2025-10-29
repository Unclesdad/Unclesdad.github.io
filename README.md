# Unclesdad.github.io

## Welcome, welcome!
Here is the central portal for my coding projects.

### [FRC1155 Codebase](https://github.com/SciBorgs/Reefscape-2025){:target="_blank"}
My [FRC Team's](https://github.com/SciBorgs){:target="_blank"} codebase for the 2025 FRC game, Reefscape. 
I also made contributions to the [2024 repository](https://github.com/SciBorgs/Crescendo-2024), with some alignment and general debugging, but it wasn't crazy significant.

### [NeuroKairos](https://github.com/SjulsonLab/irig_unix_timecodes){:target="_blank"}
A universal solution to a timing synchronization problem that neuroscience labs commonly face. 
A Raspberry Pi, synchronized to GPS satellites with an M8T GNSS HAT, can be used to give time through NTP (as a chrony server) by acting as a time server on the local network. 
Any Pi at the experimental site can be set up to also broadcast IRIG timecodes with sub-millisecond accuracy that any piece of equipment can record to combat desynchronization.

### [Whiteboard Eraser](https://github.com/Unclesdad/whiteboard-eraser){:target="_blank"}
The codebase for the whiteboard eraser. It includes the following:
1. The computer vision algorithm, which uses brightness filtering to find irregularities in the whiteboard surface
2. A library for the hardware I used: the N20 motors+their encoders (which required polling for the encoders), the gyro, the servo, and the camera (just a pi camera module 3)
3. the simple pathfinding algorithm the pi runs on. 

### [CharlieGPT](https://github.com/Unclesdad/CharlieGPT){:target="_blank"}
A codebase to fine-tune a Large Language Model on your messages. 
I fine-tuned it on mine, by using [DiscordChatExporter](https://github.com/Tyrrrz/DiscordChatExporter){:target="_blank"} for discord messages, and requesting a copy of my data from Meta for Instagram messages.
The codebase processes this data and then allows you to train a model on it. I used Qwen 2.5 3B, but hypothetically you can use whatever so long as you have enough computational power.
I used the trained model as a discord bot so my friends could mess with it. Worth the 72 hours it took to train. I also gave it image generation because I felt like it, but that's not trained on anything; I just used a pretrained model.
By the way, the inference+bot can be run on a regular RPi5 CPU (which is kinda crazy). Make sure to get an active cooler though, whoo boy. 

### [Mind-controlled drone](https://github.com/DoubleABattery08/EEG-EMG-Transceiver-Drone){:target="_blank"}
An EEG-controlled drone I'm making with some friends. I helped set it up and gave my knowledge on Raspberry Pis, as well as contributing some ideas (like the cylindrical coordinates) and writing a bit to the repository myself. 
It uses a Mindwave Mobile to "read your mind" which it connects to via bluetooth, and then connects to the drone via wifi. 

### This isn't everything I've done! 
You can find more stuff by looking through [my profile](https://github.com/Unclesdad){:target="_blank"}!

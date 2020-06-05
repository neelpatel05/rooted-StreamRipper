# rooted-StreamRipper
Exploits the buffer overflow vulnerability prevailing in the StreamRipper that records internet radio to mp3 for Windows system. Uses "jmp esp" assembly instruction to leverage the execution of payload.

Finding offsets
![offsets](https://raw.githubusercontent.com/neelpatel05/rooted-StreamRipper/master/screenshots/offsets.png)

Overwriting the instruction pointer (eip) with B's
![Overwriting the instruction pointer (eip) with B's]https://raw.githubusercontent.com/neelpatel05/rooted-StreamRipper/master/screenshots/overwriting%20eip%20with%20B's.PNG)

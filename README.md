# gr-soundboard
Simple keyboard-operated soundboard software, made in Javascript/HTML5.

**Notice: due to a Webkit-based feature, this program is only guaranteed to work in** [Google Chrome](http://chrome.google.com).

### File Operation

Please place each of your sound cues in a designated folder in a place you will remember.
Each cue must have a filename consisting of a number or lowercase letter, followed by ".wav".

Any of the following are valid:
* 1.wav
* a.wav
* h.wav

But these are *not*:
* A.wav
* j.mp3
* knock.wav

The filename will determine which key on the keyboard will trigger the sounds.
	
### Play Modes
	
There are two play modes: TRIGGER and TOGGLE.

The *TRIGGER* mode will play the sound from the beginning every time you press the button, and play until completion.
The *TOGGLE* mode will play the sound from the beginning, and pressing the button again will stop the sound as it is playing.

If you have any songs or sound effects that are NOT a .wav file, please convert them using [Audacity](http://audacityteam.org/download/). If the file does not show up in the soundboard list when you select the folder, it either is not a WAV file, or has an incorrect file name.
To convert an audio file to WAV, simply drag the audio into Audacity, click the "Stereo" text on the left side of the audio track, go to File -> Export Audio, and make sure the filetype is set to WAV 16-bit.

### Troubleshooting

If there are still issues loading sounds, try moving the soundboard program or sound effects to different locations.

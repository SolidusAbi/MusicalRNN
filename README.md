### ABC Music Format

The ABC Music format is a text-based music format. 

Here's one such tune, called **Julia Delaney** in ABC format: [See a youtube sample here: https://www.youtube.com/watch?v=DUZ6zei3fRU]
```
X:174
T:Julia Delaney
Z: id:dc-reel-161
M:C
L:1/8
K:D Minor
A|dcAG F2DF|E2CE F2DF|dcAG F2DF|Add^c defe|!
dcAG F2DF|E2CE F2DF|dcAG F2DF|Add^c d3:|!
e|fede fagf|ecgc acgc|fede fagf|edcA Adde|!
fede fagf|ecgc acgc|fedf edcA|Add^c d3:|!
```

As can be seen, the format is incredibly compact. Each line begins with a single letter field (except for notes). ABC notation for music (link: http://abcnotation.com/) 

- X denotes a reference number
- M denotes Meter
- K denotes the Key
- L denotes the beats
- T denotes the Title
- Z denotes the transcription The rest are notes that denote the melody for the song.

As one can see, this text data is useful to train an RNN to generate a similarly structed .abc, which can then be converted into .MIDI format, and from there to .WAV or .OGG format to play.
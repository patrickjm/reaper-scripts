# Insert new track with two-way midi/audio send to selected track

![Video](https://i.imgur.com/yblMNqN.gif)

Mostly helpful to users of multi-instrument VSTs like Kontakt or EW PLAY.

**For this to work, you need to enable  Project Settings -> "Allow feedback in routing"**. Personally, I also disable *Master Send* on the multi-instrument track.

1. Select your Kontakt/multi-instrument track and execute this action. 
2. A new track is created
3. New track gets a new MIDI send to your multi-instrument
4. Multi-instrument track gets a new audio send to your new track

Except a few edge cases, now your new track will behave like it's actually hosting the instrument! You can put effects on it, create sends, etc. One limitation: you cannot folder these new tracks beneath the multi-instrument track due to the way feedback works in Reaper.

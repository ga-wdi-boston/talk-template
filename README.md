[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Audio Processing

Before the 1980’s audio processing was almost exclusively done manually or with hardware.  If you wanted to play something in reverse, say backward masking on a song, you literally had to play the tape backwards and record it. Reverb and echo were either accomplished by careful studio manipulation or with sound pedals and effects racks.

A pure tone is represented by a sine wave.  Each point on the wave has two values -  a height and point in time.  The height represents the volume. The distance between peaks is the tonal frequency or pitch.

Take a group of musicians as an example, and put a microphone in front of them.  The recording won't be a perfect wave but will isntead be a series of peaks, valleys, and squiggles.

In the days of analog tapes they used magnetized bits of metal to capture the sound.  If there is no sound to capture the head still passes over the bits of metal.  That's tape noise.

Digital recording with a program takes samples of the sound and asks questions to determine the samples value at any given moment.  It first asks if the above the halfway point.  If so it records a '1'. It will then cut the value in half and ask again.  Above is 1 and below is 0.  It continues on until it arrives at a value.  CD quality sound is 16 bits which means the program asks 16 questions to come up with a 16 but binary number (a series of 1s and 0s).  24 bit programs ask 24 questions which makes it 256 times more accurate....you can do the math.

## Late 1980's

By the late 1980’s personal computers like those produced by Apple had the power capable of handling some more advanced digital audio editing chores.  An early example of this was MacroMedia’s SoundEdit


## Digital Studios

When Pro Tools was released it kicked off a digital studio trend that quickly evolved to become almost standard.

The true magic comes with audio processing.   I’m going to focus on a local audio tech company from Cambridge called iZotope.  iZotope as a company launched in 2001.


## iZotope

iZotope has fast made a name for itself with products used to produce music, audio, film, and TV productions.  I personally use the RX5 audio editing software for everything now.

The RX5 Audio Editor has been used to edit the sound on GOT, Mad Men, Star Wars, Daredevil and many of the Marvel movies.  In 2013 they won an Emmy Award for Outstanding Achievement in Engineering Development. What they really excel at is removing audio.

The Deconstruct Tool (as included in RX5):

https://www.izotope.com/en/community/blog/tips-tutorials/2016/09/rx-tips-and-tricks-removing-tonal-noise-with-deconstruct.html


## Voice Manipulation

There can be a dark side to all of this. With the proliferation and buzz around fake news there are opportunitues to take advantage of the technologies being developed to further this practice.

There is software being developed by Adobe called VoCo and also Google’s DeepMind Division that can analyze your voice and allow someone to type text which can then be conveyed in your voice. It’s pretty near ready for market.  The goal of the software is  to negate the need to have voiceovers or narration redone.  If there’s a line in a movie that needs to be redone they studio doesn't have to call the actor back - which can be expensive when it comes to studio time.  Now they can use this software to ‘fill in’ for the actor or actress if needed.

http://motherboard.vice.com/read/after-20-minutes-of-listening-new-adobe-tool-can-make-you-say-anything


## Additional Resources

- [iZotope](https://www.izotope.com/)
- [Techcrunch article on Adobe's VoCo](https://techcrunch.com/2016/11/03/adobes-project-voco-lets-you-edit-speech-as-easily-as-text/)
- [DeepMind](https://deepmind.com/)



## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.

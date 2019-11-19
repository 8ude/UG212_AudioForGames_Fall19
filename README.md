# NYU Game Center UG212_AudioForGames_Fall19
Repo for the 2019 class of audio for digital games

See the [Wiki](https://github.com/8ude/UG212_AudioForGames_Fall19/wiki) for Syllabus, Helpful Links, and Assignment Details

FINAL PROJECT - AUDIO ONLY GAME
------

Your final project for this class is going to be to make an **audio only game** - as in, a game that has no visual feedback.

If you need some inspiration, [here is a website dedicted to audio-only games](https://audiogames.net/list-games/)

You can work in groups (no more than 3 please), and you can use Unity and whatever tools you've used in the class.

On **Tuesday Dec 3** I will be doing a progress check, and would like to hear something playable!

You will present your games at the last class on **Friday Dec 13** 

Put your final build together with a text or pdf file that contains:
- your game name
- your team members names
- instructions on how to play

And upload a compressed file [HERE](https://drive.google.com/drive/folders/1C0pWb5ouLrxaaEbeJQix8bRc6VGTRd4N?usp=sharing)


WEEK 11 ASSIGNMENT - MUSIC
------

Pick a screenshot or box art from [HERE](https://drive.google.com/open?id=12qiPQRp3esnnQXWAuZJFnsE81Eehc0lp) as a point of inspiration!  You can find your own, but it will help if you don't already know the music!

Make 2 sections of music - think of them as an "A section" and a "B section."  Here's a [Sample Reaper Project with some instruments set up](https://drive.google.com/file/d/1T7Pv7u1g1VZosPoHqLuHV9vSawDRu1ma/view?usp=sharing). If you don't like working in Reaper, I recommend trying something like [Bosca Ceoil](https://boscaceoil.net/) or [BandLab](https://www.bandlab.com/)

You can make use of some of the apps and plugins on the [Musical Resources Page](https://github.com/8ude/UG212_AudioForGames_Fall19/wiki/Musical-Resources)

Bring the Stems (Melody, Bass, Percussion, etc) into FMOD and add some interactivity that you connect to a parameter.  If you need some reference on how to do this, [here's the example projet I made during class](https://drive.google.com/open?id=12fZsPawPdgs0_fECeIlIjPi6iZxvF4so)

Some ideas (just suggestions, use what works for your music):
- have instruments fade in/out based on a "PlayerStatus" parameter
- change song sections based on a "PlayerLocation" parameter
- make some ambient fragments, then use the ScattererInstrument to trigger them at random

When you're done, zip your FMOD Project and [UPLOAD IT HERE](https://drive.google.com/drive/folders/1AuNa0kngBf8degvQV2KMKCGPsMr4G_Nz?usp=sharing)

WEEK 9 ASSIGNMENT - 3D SOUNDSPACE
------
Due Tuesday, Nov 12

Using Resonance Audio and Unity, create a sonic environment/walking simulator that makes use of the following:

- ~~At least one ambisonic file~~ (no longer a requirement, but let me know if you want to make one and need help!)
- At least 5 audio sources that make use of the resonance audio features (directionality, occlusion, etc)
- At least 3 distinct reverb spaces

I recommend starting from the ResonanceAudioDemo scene in the unity package.

[Upload your builds here when you're done](https://drive.google.com/drive/folders/1QAqkLe09Uu9ftI0hfBujlyQ3d99V4DdB?usp=sharing) (Windows preferred)


WEEK 7/8 ASSIGNMENT - 3D RESKIN
------
The game *Otto the Combo Butler* is filled with placeholder sounds, and needs new audio!  Clone the repo, open the Otto Project in both Unity and FMOD, and replace the audio.

There will be a **progress check on October 25** - aim for about half of the sounds in the game.  Builds will be due on **Nov 5th**

A lot of the work is going to be done in FMOD studio.  You may need to work in Unity a bit to make more emitters, or to code additional parameters if you choose.

You must use **at least 3 sounds that you've recorded yourself.**  Additionally, you can use:
* Whatever you find on the internet, or in the Audio for Digital Games Library
* Any effects.


I'm essentially looking for the same thing with the 2D game:

* clarity of actions (can I tell what's going on based on sound?) 
* consistency (does the sound seem to match with the visuals and animations?)
and, most importantly, 
* a sense of style/aesthetics (are the sounds augmenting the game in a way that gives it life and character?).

But now, you have the added challenge of:
* making distinctive/believable spaces

You will lose points for:
* Any Unmodified samples.  You need to modify and/or layer the sounds from freesound in some way (changing pitch, stretching, adding effects, etc).
* Repeating sounds for different actions  Again, treat your samples like ingredients.
* Sounds that start "late" - your sounds should have little to no silence (0.01 seconds max) at the beginning
* (an exception to this may be the door sounds, which we will talk about in class)
* Sounds that end "early" - your sounds should always fade to silence.
* Loops with clearly audible seams (I can tell when the loop repeats)


WEEK 6 ASSIGNMENT- Recording
------

Make **3 sound effects** from recordings.  These can either be from the foley studio (we will have access from 5 pm until 6:40 on Friday), or that you record yourself.  Try to do some noise removal in reaper or audition.  

Then, name them with the material, the type of motion used, and whether there is one sound or multiple.  For example: WoodCrashMultiple.wav

Upload the [SFX HERE](https://drive.google.com/drive/folders/1bxTBICuxTP3LAHdhUkgpVgHjwvpqQTKK?usp=sharing)

In addition, **record 3 ambiences** from interesting spaces (They **cannot** be spaces at the game center, and only one of them can be the subway!).  Your phone will work fine for this, but keep your headphones on when you're recording - your microphone is not hearing the same thing as your ears.

Upload the [ambiences HERE](https://drive.google.com/drive/folders/1Dg6QkHwijHuIQ4RKWVfICd6CPoehCPs3?usp=sharing)


WEEK 5 ASSIGNMENT- 2D reskin part 2
------
Your creative director applauds your efforts, but wants to go in a different direction for the audio design.  

They've provided you with a small sample library [HERE](https://drive.google.com/open?id=1gTzzobw4IQcwLJIKrsFeFn536grhg8uY)

You can do whatever you want with these samples, but cannot use audio from anywhere else!

When you're done, please [UPLOAD YOUR BUILDS HERE](https://drive.google.com/open?id=1IA6SpDKDv2q87_Z3L-OjIF8Wn2oItwgF)


WEEK 4 ASSIGNMENT- 2D reskin part 1
------


Gabe Cuzzillo's wonderful game "Block Dog" is silent.  Clone this repo, open BlockDog in Unity Hub, and give it sound!

You should be working in the Scene called "Block Dog", on the Prefab called "AudioDirector."  Your work begins at the header **Game Sound Effects**. The minimum is to create **13** assets for the game.  2 of these are loops - the Danger Loop and the Background Music ( which could also be background ambience, if you prefer)

You can use:
* Whatever you find on the internet, or in the Audio for Digital Games Library.
* Anything using synthesis, if you wish.  Time permitting, I would like to cover a bit of synthesis during Friday's Lab.
* Any effects, including vst plugins that you find on the internet.  For example, [this](https://glitchmachines.com/products/fracture/) is a free one that was used a lot on the game Prey, and can mangle sounds into something completely different!
* If you want to record sounds, you can do that too.

You are free to make any code modifications... as long as they only affect the audio!

You will lose points for:
* Any Unmodified samples.  You need to modify the sounds from freesound or the library in some way (changing pitch, layering, stretching, adding effects, etc).  The sounds in the library were not made for this game.  That's like serving a raw egg on a plate for dinner.
* Repeating sounds for different actions (for example, using the same sound for "jump" as for "throw").  I will frequently re-use *portions* of a sound in other sounds.  Again, treat your samples like ingredients.
* Sounds that start "late" - your sounds should have little to no silence (0.01 seconds max) at the beginning
* Sounds that end "early" - your sounds should always fade to silence.  
* Clicks/Pops in your loops

Aim for 
* clarity of actions (can I tell what's going on based on sound?) 
* consistency (does the sound seem to match with the visuals and animations?)
and, most importantly, 
* a sense of style/aesthetics (are the sounds augmenting the game in a way that gives it life and character?).


WEEK 3 ASSIGNMENT
------

[Choose 3 animated gifs from this directory](https://drive.google.com/open?id=1KtKVr2g5EDVzZFDWw0WlUdZo5YfYev41).  If you want, you can find or make your own, provided that they are roughly 10 seconds long and contains a significant amount of motion.

Add sound effects to accompany the gifs.  The goal for the first pass is to have a distinct sound for every distinct motion - try to make it believable, as if the motions in the gif are producing the sound. 

Then, do a "second pass."  Choose different source material, and take a different artistic direction.  Try to still have sound for almost every motion. 

Render these (there should be 6 total)as WEBM videos and [upload them here when you're done](https://drive.google.com/drive/folders/1_NTeqrtVU8Dj2K09JdBUYNX1nlUfO-sr?usp=sharing).  Make a sub-folder with your name   

WEEK 2 ASSIGNMENTS
------

Reading - the reading from week 1 is posted on the syllabus.  You don't need to revisit it, if you think you understood it the first time.  The Transforms and Notations section has some interactive Fourier transform things, but I personally like this website better (courtesy of Mai Hou) - http://www.jezzamon.com/fourier/index.html

Sound Collage - Create a 3-5 minute “story” (whatever that means to you) using samples sourced from the Audio for Digital Games Library or Freesound.org.  Experiment with different sample rates, bit depths, and sculpting using filters and EQ. [Render and upload your Sound Collages here](https://drive.google.com/drive/folders/1RujiXd8HTTlCmF6821k2iVFov2_y94d1?usp=sharing) when you're done!

Also, Mai posted this in the Slack - https://learningsynths.ableton.com

Try going through it!  We're going to be doing a bit with synthesis in Reaper, but this is a much more fun walkthrough.



WEEK 1 ASSIGNMENTS
------

Reading - [Seeing Circles Signs & Signals: “Intro, Signals & Sound” & “Sines & Sampling”](https://jackschaedler.github.io/circles-sines-signals/); please finish reading by Tuesday, September 10

Active Listening Response - with a partner, play a game from the provided list, [available here](https://docs.google.com/spreadsheets/d/1edCiqyz_i7B_XNmNsx9mYHWyKcveCXDQyfskvkeFy5Q/edit?usp=sharing), or make a case for a different game (do NOT watch a Let’s Play).  List every sound that you hear in the game.  How would you describe the overall audio aesthetic, mood, or feeling of the game?  What do you think are the most important sounds, and why?  How do sounds change in response to player action (some sounds may be randomized, or connected to in-game physics in interesting ways)?  Look up some facts about the creation of the game audio - what’s interesting about the techniques or technology used?

You will be presenting a brief (~7 minute) presentation during a lab time, at some point in the semester. 

For Friday’s Lab section, bring in 3 sounds from a game project that you’ve worked on.


This project was forked from milenniummike/soundstagevr
Updated work with SteamVR 1.8.21 and Unity 2019.2.0f1 



# SoundStage VR

SoundStage VR is a virtual reality music sandbox built specifically for room-scale VR. Whether you're a professional DJ creating a new sound, or a hobbyist who wants to rock out on virtual drums, SoundStage gives you a diverse toolset to express yourself.

## Latest Features

* Uses valve renderer adaptive MSAA
* Added a realtime camera feed - this needs to be enabled in Steam - useful for seeing external instruments.
* Added a spotlight that can be triggered using a pulse.

## Proposed Roadmap
# visuals
 * mesh / fbx viewer
 * particle generator

# enhancements
 * mixer aux to headphones
 * drum velocity
 * teleport
 * environment selector

# instruments
 * chord sequencer - simple buttons with chords in chosen key
 * physics ball - creates pulse on collision
 * video loop and scrubber


## Requirements
* An HTC Vive or Oculus Touch running SteamVR
* Unity 5.5.5f1 if you'd like to modify the project

## Setup
The Unity project can run without any additional components - just open the main scene to get started. 

That being said, the project is missing two third-party components available in the Unity Asset Store:

* [SE Natural Bloom & Dirty Lens](http://u3d.as/7v5) creates the glow and bloom effects seen in the released software
* [Runtime AudioClip Loader](http://u3d.as/hEP) enables MP3 sample loading and improves the performance of all sample loading

To use each of these assets, add the full asset package to the *third_party* folder. If they are not automatically replaced, remove the corresponding placeholder scripts in that same folder.

A full build of the project with the third-party components is included in the *bin* folder.

### Credits
###### CREATED BY
Logan Olson

###### SOUND DESIGNER (SAMPLES)
Reek Havok

###### PROGRAMMING CONSULTANT
Giray Ozil <-iumlat

###### MUSIC CONSULTANT
Ron Fish

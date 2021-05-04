# InvestigationVR

## Developed by Mitchell Perez and Shayne Sendera as a Capstone Project for Monmouth College

InvestigationVR is a playable Virtual Reality(VR) simulation that revolves around a simplified version of forensic science and problem solving.
The simulation takes place in a scene that is set in a science lab and police station where the player is a forensic analyst that carries out
various tasks to determined who committed a murder. The player is given a few pieces of evidence that spawn on a counter top in which will be
used in carrying out three forensic science based tasks.
These tasks include:
  - Fingerprint Analysis via the cyanoacrylate method (Super Glue Method)
  - Hair Analysis via a microscope
  - Blood Analysis via Polymerase Chain Reaction (PCR)

After the player has completed the aforementioned tasks, there are three buttons located in front of a criminal lineup in the police station
of the set scene in which the player can push to choose a proper or wrongful conviction of the murderer. These verdict buttons are locked
until the player has completed all of their given forensic tasks which can be completed with the aid of the begginer toggle button next to
the spawn location. Using the resulting data that appears on a whiteboard in between the lab and police station, the player can correlate
their results with data given on criminal profiles that are also located on the whiteboard to solidify their verdict.

# Installation Instructions

To install and run InvestigationVR the following applications and hardware will be needed:
  - An Oculus Rift headset (PC Windows) or an Oculus Quest (Standalone)
  - Oculus VR Software (Needed for any VR game to be played on the Oculus)
  - Unity 2020.1.6f1 (Can be found on Unity's Website)

 ## Oculus Rift Windows Installation Build.
  - Make a fork of the InvestigationVR repository and open the project using Unity Version 2020.1.6f1
  - Open Unity Hub and add the project using the correct version.
  - Upon opening Unity Project go to file->build settings
  - Under Build Settings Select "PC, Mac & Linux Standalone"
  - Make sure the target platform selected is Windows and the archetecture is set to x86
  - Click Build and save any build files to the diectory InvestigationVR is saved to on your PC.
  - With the Oculus Rift setup and Oculus software running open the "TechTalkDemo" Build file that was generated.
  - Enjoy the InvestigationVR experience! :)


## Oculus Quest Standalone Installation Build.
  - Make a fork of the InvestigationVR repository and open the project using Unity Version 2020.1.6f1
  - Open Unity Hub and add the project using the correct version.
  - Upon opening Unity Project go to file->build settings
  - Under Build Settings Select "Android"
  - Since the project was not originally created with Android capability, click "Install with Unity Hub"
  - Add the Android module to the project and build the project with the default settings selected.
  - Save the build to the project folder.
  - Using the same method of installation to install games on the Oculus Quest, install InvestigationVR by transfering the game to the Quest via cable connection.

  ### Note that InvestigationVR was made to run on the Oculus Rift and RiftS as they utilize a PC to emulate the simulation. These are the general instructions
  ### of how to install a Unity VR project onto an Oculus Quest and there is no guarantee that the project build will function properly. This method has not been
  ### tested as we the developers only have access to an Oculus Rift S.


## Git LFS Info

version https://git-lfs.github.com/spec/v1
oid sha256:e92aa4ff1876797f56d7dbde4287938a9a00df7e50dec5ac92998d91d80aa978
size 35

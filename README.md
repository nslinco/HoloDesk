# HoloDesk
A custom-built desk with an integrated transparent display &amp; Kinect for AR interaction
###### Or: Why purchase a PC case with a built-in transparent LCD side panel for $200 when you can build your own for $600?

## Preview
![HoloDesk_Censored_lg](https://user-images.githubusercontent.com/28934246/175425778-929780d0-7a81-493c-91ac-ae94240da9af.gif)

###### A real Rubik's cube placed within the desk is mapped to a virtual space, allowing users to manipulate digital clones of the real object. The digital clones are then projected to the user through the transparent display based on their pose relative to the desk.

## Motivation
Despite the monumental performance improvements of VR and AR over the years, comfort levels have stagnated at uncomfortable levels and headset manufacturers are stuck converging towards the local maximum of miniaturizing existing display technology. While VR/AR headsets certainly have their use cases, I wish to explore the idea of AR as ***an adaptive wearable-free environment that intuitively responds and interacts with users***.

## Summary
At its core, the HoloDesk is composed of:
- The desk
- A transparent display
- A Kinect
- A computer for running Unity3D (I used a 2013 iMac with a 1GB NVIDIA GeForce GT 755M)

The desk itself will serve as an empty space within which real objects can be placed and digital objects can be projected. The digital analog of this physical space I call HolOS, a sandbox emvironment compatible with assets straight from the Unity Asset Store. This digital analog is displayed to the user through a transparent LCD which doubles as a glass top for the desk and is calibrated to align perfectly with objects in the physical space. The Kinect is used to calculate the position of the user's eyes in order to compute a projection matrix which displays the corresponding view on the transparent display.

## Stack
-     Hardware
      - Sensor: Kinect V2
      - Desk: Designed using Autodesk Inventor and built using 80/20 aluminum extrusion
      - Display: LCD Panel from an old 32" LG TV
-     Software
      - Tracking: Kinect SDK
      - Graphics: Unity3D (C#)

## More Information
I have multiple private Medium articles written about every aspect of this project, but they're all 10+ min reads and need some final touches. While I finish those full-length reports, you can check out [a presentation that I gave](https://docs.google.com/presentation/d/1NgHVJ2ZgubVowgmFwHPnFupF3CSk7Qui_3qMVY2N-YY/edit?usp=sharing) for a computer graphics class about the underlying technique that is described in Robert Kooima's [Generalized Perspective Projection](http://160592857366.free.fr/joe/ebooks/ShareData/Generalized%20Perspective%20Projection.pdf).

![HoloPipeline_Boomerang](https://user-images.githubusercontent.com/28934246/175425068-711cbd81-4df6-4d5d-8584-4e7569e7a413.gif)

## Next Steps
- Add 🦿🦿
- Upgrade the decade-old Kinect and computer for instant performance & response rate improvements
- HolOS can be expanded using digital content creators to create new apps and convert existing apps
- Enhance the 3D effect using a stereographic display to render a different view for each eye
- Sensors can be placed within the desk to automate the mapping of physical objects
- Hydraulic arms would protect the glass top from repetitive movement

## Comments? Questions? Concerns? Just want to chat?
My inbox is always open and I'd love to hear your thoughts. You can find my email [on my profile](https://github.com/nslinco).

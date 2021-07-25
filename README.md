# CS/ECE4795 GPU Programming for Video Games

This repository contains supplemental material for the Georgia Tech class CS/ECE 4795, GPU Programming for Video Games by Prof. Aaron Lanterman. The main lectures can be found at this YouTube playlist: 

https://www.youtube.com/playlist?list=PLOunECWxELQQwayE8e3WjKPJsTGKknJ8w

The material shown here is relevant to both the Summer 2020 and Summer 2021 offerings of the class; any year 2020 material listed here is being reused in the 2021 version of the calss, and will probably work in versions of Unity from 2019.4 up to 2021.1 (and hopefully later, but who knows). Some minor tweaking may be needed.

GPU20IntroShaders.unitypackage corresponds to Lectures 16 through 24; GPU20EnvMapShaders.unitypackage corresponds to Lecture 25; GPU20ProjTexShaders.unitypackage corresponds to Lecture 27; GPU21PostProcDefRendBuiltInDIY.unitypackage corresponds to Lecture 32; and GPU21PostProcStackBuiltInRP.unitypackage corresponds to Lectures 33 and 34. 

When trying out one of the unitypackages, start with a blank vanilla "3D" project, and drag the unitypackage onto the Assets folder. If it gives you a warning about a scene file changing on disk or something like that, don't worry about it, just click through the warning. The assets will then be loaded, but you won't see anything new in the scene; you need to go to the scene folder and double-click on one of the particular scenes to load it.

For the PostProc package, you will FIRST want to install Post-Processing Stack (v2) from the Unity Package manager and THEN import the package. You can load them in the opposite order, but then you will also need to invoke "Reimport All" to get everything to work.

# HAL-Webinar
Webinar – Creating a Hardware Abstraction Layer in LabVIEW

How To: 

1- Apply the VI Package Configuration using VI Package Manager (vipm.jki.net) for LabVIEW 2015
2- Open HAL Webinar.lvproj in LabVIEW 2015 IDE
3- From the project environment, Run "Microscope.TestLauncher.vi"
4- Click on wells to see the XYStage move to that location and capture a simulated image.

*To use Camera.IMAQdx class, you will require a valid Vision RunTime License or Vision Development License from National Instruments (ni.com)

Settings files: 
- You can edit "simulated.ini" file provided to change the relative path to images folder and use your own images
- You can edit "hal.ini" file provided to use a more specific camera (IMAQdx code provided).

To add your own camera or XYStage classes derived from these base classes, open "Microscope.lvclass:enumerateStaticDependencies.vi" and modify the configuration-driven dependency injection and add your specific class in the appropriate case structure.

If you have any questions, please contact JKI at jki.net or create an issue on this thread.
I hope you enjoy trying the code and creating awesome Hardware Abstraction Layers for your projects!

Francois Normandin
Staff Engineer, Systems Architect
JKI

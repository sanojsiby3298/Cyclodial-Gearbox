# Cyclodial-Gearbox
Here begins the attempts for my Cyclodial Gearbox!!!
Here is a picture with general terminology I will use throughout the page.
<p align="center">
  <img width="500" src="https://github.com/user-attachments/assets/5016b5b1-4755-42c4-9be2-ce9936ec3871" />
  <br/>
  <em>General terms.</em>
</p>


V1 the overscoping failure(Solidworks):

Why the cyclodial gearbox? I became fascinated with eccentric movement and change from traditional gears after watching videos of Aaed Musa of his internal cyclodial actuator and mainly this video by Cinema Mechanics (https://youtu.be/cvuBCdxfGDg?si=A72qymCflEV3_1Sm) and its accompanying research paper (https://www.researchgate.net/publication/235992854_A_New_Design_of_a_Two-Stage_Cycloidal_Speed_Reducer) with a cyclodial gearbox that seemed to be a possible next step to improving the functions of traditional cyclodial gearboxes and using the second disk in the gearbox as a second stage rather than just a way to offset the moment formed by the first disk. 
<p align="center">
  <img width="500" src="https://github.com/user-attachments/assets/05feb723-38f5-43fc-857b-3fbef9600eda" />
  <br/>
  <em>V1</em>
</p>
As seen in this picture below, my first attempt was a mess but here are some of the reasons if it wasn't clear:
1. Requires the use of bearings, a fact I grew to learn was a bad idea not only in design but also assembly, following the universal rule of KISS, Keep it Simple Stupid, adding too many moving parts exponentially increases the change of failure, especially in a gearbox where everything except the housing is moving. I learn to abandon the bearings by V5 after actually building a prototype.
2. The bearing OD for the ring roller pins was way too high which resulted in parameters that made it hard to keep it small and efficient.
3. The output shaft was placed in the middle of the gearbox which made it harder to design the surface in which the gearbox would be tested.

The reason I call it an overscoping failure is that I tried to recreate the gearbox from the video and paper immediately without going for the basics which was to build a working physical version that was tried and tested. Overall I didn't learn most of these mistakes till later versions but this first prototype in Solidworks gave me a foundation on how to design one from scratch. Used the equation driven curve function and tested different parameters and made a simple python cyclodial gearbox equation generator as I kept switching around the parameters a lot, its on this github page and called Cyclodial disk equation generator. Solidworks was the software I used for V1 to V3 as I played around with different designs and took my time researching different ways to build and test it. Came across this great website that could simulate the disk at certain parameters and gave the pressure angle. The pressure angle essentially corresponds to angle between the normal at point of contact and velocity direction at that point. The website explains it better than I can (https://mevirtuoso.com/gears/what-is-pressure-angle-and-why-its-important-cycloidal-drives/) but you essentially want to keep it low which is where having the large ring bearings fell short as it limited to the parameters of the cyclodial disk by making it too large or have a high pressure angle which would increase the risk of failure aka the disk breaking. 

Heres V2 and V3, not much different except trying to strengthen pins by enveloping them with the 3d printed housing, was playing around with different ratios to decrease size of the gearbox.
<table>
  <tr>
    <td><img width="500" src="https://github.com/user-attachments/assets/7f5b1e4b-1c05-4ad4-bf2d-50a69155cf16" /></td>
    <td><img width="500" src="https://github.com/user-attachments/assets/61343278-ac32-4c0a-b361-5c07cd97e33e" /></td>
  </tr>
</table>

3 months later...

V4 the first physical working prototype

This version was the one where I finally made the move to Fusion360 from Solidworks. I had been debating this swtich since the beginning as this one youtuber Howey (https://www.youtube.com/watch?v=rycKyqU1btg&t=631s) had a great video on how to design one from scratch but I had been debating switching since I had limited Fusion360 experience but in the 3 months gap, I had began using Fusion a lot more for its CAM program to use the CNC for the FRC team I mentor so I finally made the switch and it was worth it. Fusion360 has a built in python program far from the one I made where it displayed different cyclodial disk parameters as a sketch which was everything I needed and more. Fusion360 is also really similar to the first CAD software I got familar with, Onshape, and has a really great history and design workflow I came to enjoy. And after a few days of design and testing, I finally came up with design where it finally felt like something that would physically work. 
<table>
  <tr>
<img width="700" src="https://github.com/user-attachments/assets/a61e041f-abd0-43ac-a700-6d0b46b53b87" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="220" src="https://github.com/user-attachments/assets/7d51262b-be61-4e2a-98b4-5a13e540b243" />
 </tr>
</table>








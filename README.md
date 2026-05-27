# Cyclodial-Gearbox
Here begins the attempts for my Cyclodial Gearbox!!!
Here is a picture with general terminology I will use throughout the page.
<img width="2133" height="1500" alt="image" src="https://github.com/user-attachments/assets/5016b5b1-4755-42c4-9be2-ce9936ec3871" />


V1 the overscoping failure:

Why the cyclodial gearbox? I became fascinated with eccentric movement and change from traditional gears after watching videos of Aaed Musa of his internal cyclodial actuator and mainly this video by Cinema Mechanics (https://youtu.be/cvuBCdxfGDg?si=A72qymCflEV3_1Sm) and its accompanying research paper (https://www.researchgate.net/publication/235992854_A_New_Design_of_a_Two-Stage_Cycloidal_Speed_Reducer) with a cyclodial gearbox that seemed to be a possible next step to improving the functions of traditional cyclodial gearboxes and using the second disk in the gearbox as a second stage rather than just a way to offset the moment formed by the first disk. 
<img width="1451" height="1155" alt="image" src="https://github.com/user-attachments/assets/05feb723-38f5-43fc-857b-3fbef9600eda" />
As seen in this picture below, my first attempt was a mess but here are some of the reasons if it wasn't clear:
1. Requires the use of bearings, a fact I grew to learn was a bad idea not only in design but also assembly, following the universal rule of KISS, Keep it Simple Stupid, adding too many moving parts exponentially increases the change of failure, especially in a gearbox where everything except the housing is moving. I learn to abandon the bearings by V5 after actually building a prototype.
2. The bearing OD for the ring roller pins was way too high which resulted in parameters that made it hard to keep it small and efficient.
3. The output shaft was placed in the middle of the gearbox which made it harder to design the surface in which the gearbox would be tested.

The reason I call it an overscoping failure is that I tried to recreate the gearbox from the video and paper immediately without going for the basics which was to build a working physical version that was tried and tested. Overall I didn't learn most of these mistakes till later versions but this first prototype in Solidworks gave me a foundation on how to design one from scratch. Used the equation driven curve function and tested different parameters and made a simple python cyclodial gearbox equation generator as I kept switching around the parameters a lot, its linked and called 



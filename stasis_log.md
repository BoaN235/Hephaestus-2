# Initial work before This event started also explains what I want more for this project
Hephaestus-1v2
title: "Hephaestus-1v2" description: "A Core XY Printer with a z axis tilt" Made by : Boa_N

Total Time: 7 hours

Goals and Requirements
Idk if i wanna do 235x235 or 220x220
CoreXY
Enclosed
Z Tilt bed
Compressed into a small footprint ~360x360x470 mm or ~14.17x14.17x18.5 in
I would like to design a pcb for this project
info
This version was built with the old parts of Hephaestus-1 an broken Ender 3V3 and a few new parts

<img width="787" height="841" alt="image" src="https://github.com/user-attachments/assets/5ae01c51-54b5-4a76-904f-1a75f1615d66" />


<img width="502" height="466" alt="image" src="https://github.com/user-attachments/assets/d1c38720-c9a6-4e35-adae-184e4b2e94f4" />


# log
Feb 21st - Feb 24th Toolhead Work Time: 2.5 hours
Feb 25th - Mar 1st Main Body Overall Design Time 3.5 hours

## Belt Paths & setting up for bed movement
The main thing I worked on was the belt paths for the 3d printer. These will allow the head of the 3d printer to move around in the normal coreXY way.

<img width="546" height="513" alt="image" src="https://github.com/user-attachments/assets/21862ef9-509e-4c87-baf3-e82d3f10e118" />


I also added the parts that will eventually be used for the z-axis kinematic system. Each of the 3 points has a servo moter that will be able to turn a screw. With a three point system it allows the bed to tilt.

<img width="624" height="787" alt="image" src="https://github.com/user-attachments/assets/80672dd5-2110-4870-abe6-6ffbc7b76b84" />


## Belt Holder Design W/ Tensinor 
I had multiple different ideas however this is the final one I found that would work the best. It allows for me to put a nut and tension the belt. This will help to make assembly easier and fix a main problem in the original version with problems in the belts.

<img width="612" height="448" alt="image" src="https://github.com/user-attachments/assets/bc161e03-490f-4b4e-8b4a-0ab440aa4e89" />


This shows a design I chose not to move on with because it did not give me the ability to tension it well

<img width="395" height="513" alt="image" src="https://github.com/user-attachments/assets/3faa460a-7cdf-485c-a557-1fde83313a92" />

## Gantry System & Toolhead Belt connection
I setup the first design of the gantry system. It will allow for the belts to pull the toolhead and gantry. currently it may change in location as I think if I change the belt system it would work better.

<img width="372" height="306" alt="image" src="https://github.com/user-attachments/assets/3d430205-ed89-4e75-abb0-1178f10f4bc3" />
I also worked on a connection to the belt system that part will probably be finished last because
<img width="474" height="393" alt="image" src="https://github.com/user-attachments/assets/b21ff5ca-324e-4ff7-8916-689c0b1a48d4" />

## Belt System & Bed
I finished the belt system which will pull the gantry it looks like it isn't connected because I wanted to build it with tolerances in mind. The entire belt system has tolerance built in so I can adjust it to make installation easier.

<img width="451" height="452" alt="image" src="https://github.com/user-attachments/assets/7aee58e9-6444-4252-aeff-a7bd3e84127f" />


This is what the printer looks like currently. I think it is looking much better than the original and the newer features such as a kinematic z axis make the printer much more unique.
<img width="747" height="770" alt="image" src="https://github.com/user-attachments/assets/4abfbf13-e4d1-44cf-b5b6-7fef7a653f8e" />

## Z-axis system
I worked on starting to create the z-axis movement system. this took a while because I had to get the exact measurements of the piece however they are located in the correct locations. Next I want to work on the semi-universal joints to make connect to the center bed area.

<img width="583" height="513" alt="image" src="https://github.com/user-attachments/assets/42ef9d64-08b8-46fe-923b-137a4c306773" />

<img width="582" height="747" alt="image" src="https://github.com/user-attachments/assets/15bd6617-4ea0-421d-a593-a6779927dfc5" />

## Tool Head Fixes & Toolhead Belt attachment
Today I fixed some of the small problems on the toolhead. However the main thing I worked on was the back piece for the belt connecter. My idea is that it screws on however this will probably change later. For now I think it will work.
<img width="636" height="681" alt="image" src="https://github.com/user-attachments/assets/64ef4b2a-6400-4b26-9fdb-2ff356911a6c" />
<img width="861" height="803" alt="image" src="https://github.com/user-attachments/assets/931a34be-3c4d-4b4e-9b56-77d5557bbd83" />

## Bed improvements
I designed the bed connections. The Kinematic Z axis will be later on in the future because I need to ensure that the printer works well first.

<img width="738" height="744" alt="image" src="https://github.com/user-attachments/assets/aad4e1ec-2408-4c91-8992-fd2dc9b782ba" />


Other than improvements in the toolhead the printers design is complete. I hope to get started with the build process mid may.

<img width="763" height="774" alt="image" src="https://github.com/user-attachments/assets/9df79372-8266-40c7-9ffa-cba7be0f9f3c" />

## Kinematic Bed System
I have mainly been working on the bed system

<img width="715" height="817" alt="image" src="https://github.com/user-attachments/assets/ff0b584d-f399-431d-8396-5a6806d7d01a" />


I decided to switch to a four point system because it will improve stability and allow me to use advanced Klipper features. Also it helps me to make the parts the exact same so I just have to print two sets of the same ones.

The bed works with a balls that allow it too tilt.

<img width="732" height="429" alt="image" src="https://github.com/user-attachments/assets/aebeb825-1f70-449d-bfeb-f82e0367594c" />


Most of the time was taken up on the 3 point design however I decided that it wasn't going to work as well as a 4 point design.

<img width="538" height="500" alt="image" src="https://github.com/user-attachments/assets/d1654469-0395-428b-b2d3-b9c122e4deff" />


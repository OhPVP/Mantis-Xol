# MantisXOLBuildGuideREADME
This is a Short walk through for building a Mantis XOL Hotend Cooling Setup (With DFA Coming soon)



** NOTE DFA VARIANT Only Supports RAPIDO Currently. ***


 Printed Parts.
1) Mantis Xol - Ducts - Tri-Vane Asym.Stl
2) Mantis Xol - Face Plate.stl
3) [a] Mantis Xol - M2x10 Saver_2x.stl
4) Mantis Xol DFA - Carriage - MGN12 Euclid.stl    (insert alternate variant here for different extruder or euclid/klicky)
5) Mantis Xol DFA - Hotend Mount - Rapido.stl (insert alternate variant here for different hotend / extruder combo)
6) (DFA SPECIFIC) Mantis_Xol - DFA Bottom.STL
7a) (DFA SPECIFIC) https://github.com/Annex-Engineering/Folded_Ascender-Extruder  (PRINT EVERYTHING FROM THIS REPO EXCEPT Bottom_centered_x1_Rev1.stl) 
7b) (Sherpa Mini ) https://github.com/Annex-Engineering/Sherpa_Mini-Extruder/tree/master/STLs/FDM_STLs
8) [a] Mantis Xol - DFA -Hartk3_mounting_plate_Strain_relief (EBB36) can be found in the HartK PCB Mount folder of Main Mantis-Xol stl folder.
9) (Optional) 17/20mm Motor spacers if necessary.
10) [a] Mantis Xol - DFA - Pcb Stabilizer.stl

Now you've got all your hardware. And all your parts.

Lets get to assembling.

Using 2 Heatsets begin by pressing 2 Heatsets into your Hotend Mount. See Pictures Below.
![IMG_1686](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1686.JPG)
![IMG_1687](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1687.JPG)
![IMG_1688](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1688.JPG)

Next we will Prep the Carriage (I use Euclid Variant.) 4 heatsets for the front, and 3 for the top. See Pictures Below.
![IMG_1689](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1689.JPG)
![IMG_1691](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1691.JPG)
![IMG_1696](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1696.JPG)
![IMG_1690](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1690.JPG)
![IMG_1694](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1694.JPG)
![IMG_1695](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1695.JPG)
Following Carriage Setup the Rapido Must be prepped for Rigid Mounting, (Remove the 2 Screws Holding the Bowden connector on.) See Picture Below
![IMG_1698](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1698.JPG)
Using the 4 Screws supplied with your Rapido. mount your Hotend inside of the Hotend Mount. See Pictures Below 
Note I oriented my wires to the back left (Metal wire router towards back left corner of Hotend mount)
![IMG_1699](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1699.JPG)
![IMG_1700](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1700.JPG)
Mount Euclid Hotend Side PCB to Carriage using 2xM2.5 screws, Route wires through provisioned hole for Probe. See Pictures Below
![IMG_1701](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1701.JPG)
![IMG_1702](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1702.JPG)
![IMG_1703](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1703.JPG)
Run wires for X-Endstop through Provisioned hole, and Screw Endstop down with 1xM2.5 Screw See Picture Below (sorry i didn't get one of it mounted here)
![IMG_1704](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1704.JPG)



I deleted a few images... That i should've kept.... 

Mount the carriage like normal (Route belts, fasten with 4X M3x6 Bolts)

Fasten 30x10MM 24V DBB Radial Fan to Hotend Mount (4x M3x14 is what i used here) (Only attach top 2 now, as you'll install bottom 2 later)

Fasten Hotend Mount to Carriage -> 2x M3x6 , 2x M3x20) 

The top 2 screws use the M3x20; and the bottom 2 attach using M3x6

I'll get some better pictures of this and update in a day or two.
Doodled picture below LEGEND = Red (3x20MM) , Green (3x14mm) , Blue (3x6MM i could only circle one.)

![IMG_DOODLED1742](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_DOODLED1742.JPG)


 *************************** KEEP READING BEFORE YOU MESS UP  ****************************
*** WARNING PAY CLOSE ATTENTION TO THE ASSEMBLY STEPS OF THE NEXT PART FAILURE TO DO SO WILL RESULT IN HAVING TO REPRINT PARTS****
DO NOT ATTACH FANS FIRST < OR YOU WILL END UP WITH MISALIGNMENT AND IT WILL NOT FASTEN TOGETHER PROPERLY> 

PLEASE ASSEMBLE LIKE THE PICTURES BELOW SO AS TO AVOID DAMAGING YOUR PRINTED PARTS.

![IMG_1738](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1738.JPG)
![IMG_1737](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1737.JPG)
Once this plate is fastened together like above. MOVE on to FAN Installation for Part Cooling. 4x M2.5 Screws See Pictures BELOW 
(Only Fasten the bottom 2 screws on each fan for now)
![IMG_1741](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1741.JPG)
![IMG_1740](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1740.JPG)

Remove 2 Lower Hotend cooling fan bolts to attach Ducting to Hotend. See below for removal.
![IMG_1742](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1742.JPG)
Attach your Duct using the 2 removed screws from the hotend cooling fan.
Afterwards you can use 4x M2.5 Self tappers and 2X Fan Savers to finish attachment. SEE BELOW
![IMG_1744](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1744.JPG)
![IMG_1743](https://github.com/OhPVP/Mantis-Xol/blob/e7a19bf6e4b88e8d4ff494b5ff778e6ffcae3977/Images/IMG_1743.JPG)

MOST of this guide should be interchangeable with MINI sherpa; I do have a mini sherpa built, But the carriage/hotend mount printed parts do change.
If someone does picture their build and would like me to update this i will. 

All thats left is to fasten the extruder (will update with pictures Hopefully before i leave sunday for Work Conference)

At this point re-wire everything and you should be good to go. I will update this guide further once i finish my DFA assembly. (Misumi slowed me down)

CHECK ALL ENGAGEMENTS FOR DOCK/ATTACHING OF PROBE BEFORE JUMPING STRAIGHT INTO PRINTING. I CANNOT BE HELD RESPONSIBLE FOR ANY DAMAGES TO YOUR MACHINE AS MY MACHINE MAY DIFFER IN DOCK LOCATION. IF YOU ARE UNCOMFORTABLE AND NEED HELP PLEASE REACH OUT TO ME ON DISCORD OhPVP#7217

I do apologize for any poor quality prints; All of this was done on my V0.1 with fast speeds and not enough tuning. Please note my ducts have since been reprinted with the Seam alignment corrected.


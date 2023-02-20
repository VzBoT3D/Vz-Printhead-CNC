Assembling the print head is straight forward.

# Step 1 : Mounting the Fan and Cable holder.
![image](https://user-images.githubusercontent.com/37383368/144164913-77f6e690-bd68-4acc-98df-f23f697ef434.png)
## BOM needed:
- 4xM3 6mm Ultra low profile bolts or button head (Button head should allow more tolerance between 2 bolt heads)
- cable holder (printed)

# Step 2 : Assembling the carriage
- Install the top plate on the X MGN9 slider
- Install the back, front, and bottom plates
![image](https://user-images.githubusercontent.com/37383368/144165073-5143faec-5863-466d-8608-cd1a1402f1c1.png)

## BOM needed:
- 12xM3 6mm Ultra low profile bolts (For all 8 corners and MGN9 bloc). For F3D printhead
- For Mellow kit, it needs 4x5mm or 4x4mm bolts for the MGN9 bloc. Kit should include M3 4mm.


# Step 3: Mounting the the X stop switch (Optional: if you don't use sensorless homing)
![image](https://user-images.githubusercontent.com/37383368/144165516-71b350dc-e5e7-4ad3-9994-2b5eeb7d3ebf.png)
### Rat Rig Vcore3 users: You will need to add this X stopper to your Left Xy joiner. STL found [here](https://github.com/VzBoT3D/Vz-Printhead/blob/main/STLs/Vcore3%20specific/Vcore3_X_stopper.stl) 
Please note that you will need a 15mm M5 bolt instead of a 12mm
![image](https://user-images.githubusercontent.com/37383368/166172614-6126112e-fe90-472b-8d7b-c416a6c2a4d1.png)

Also, you can re-use the Vcore original X switch with this [mount](https://github.com/VzBoT3D/Vz-Printhead/blob/main/STLs/Vcore3%20specific/X-endstop-mount.stl)

## BOM needed:
- 2 x M3 6mm Ultra low profile bolts
- 2 x M2 screws (not included in the kit)
- Microswitch https://s.click.aliexpress.com/e/_AL9anj
- Switch mount (Printed)

# Step 4: Install the rear adjustable fan mount
![image](https://user-images.githubusercontent.com/37383368/144165782-2720e21d-af35-439d-a1e4-e043f39f8716.png)
## BOM needed:
- 2 x M3 8mm Ultra low profile bolts (or 2x6mm for the new version of the mount that has a groove for the M3 nuts)
- 2 x M3 Nuts

# Step 5: Install the belts.
- make sure motor mounts are a lowest tension possible first.
- Start by the front. Insert the end of the belt through the side slot and loop the belt on itself. Insert a piece of filament (6mm) in the loop and then slowly pull the belt back in the slot until secures in place.
- For the back, simply loop the belt arround the pillar, and give it a pre-tention on the belt, then attach it with a zip tie, or a printed belt clip (Found in the [STL](https://github.com/VzBoT3D/Vz-Printhead/tree/main/STLs) folder) . [belt clip](https://github.com/VzBoT3D/Vz-Printhead/blob/main/STLs/Belt_clip.stl)
- [![belts-installation](https://user-images.githubusercontent.com/37383368/146992012-26b7d4e9-f979-4afb-9dfe-6e3e31b0ecac.jpg))](https://youtu.be/Ibi27Toh-pg)
- (For Vz235, you can use 2 techniques described here in this [video](https://www.youtube.com/watch?v=lP59PClF_PU&t=3334s). For the optional 2 piece clips, here they [are](https://github.com/VzBoT3D/VzBoT-Vz235/tree/main/Assemblies%20%26%20STL/Gantry/Misc))




# Step 5.1
Take a rum shot. This step is definately needed after the belts job. It takes a bit of patience to route the belts in the front idlers, with a small screw driver, its very doable

# Step 6: Install the fan duct
![image](https://user-images.githubusercontent.com/37383368/144167630-18dacba9-8475-4689-8376-9929f1c42db1.png)
## BOM needed:
- 2 x M3 10mm bolts
- 2 x M3 Nuts
- Upper fan duct (printed)
- Lower fan fuct (printed)

# Step 7: Install your favorite extruder/hotend combo.
Refer to the "Configuration" sections above (or links down below)for instructions and BOM
- [BOWDEN](https://github.com/VzBoT3D/Vz-Printhead/tree/main/Configurations/BOWDEN)
- [Direct Drive](https://github.com/VzBoT3D/Vz-Printhead/tree/main/Configurations/Direct%20Drive)

# Step 7.1
Take a second well deserved rum shot. Please note that beer can be used in this step.

# Step 8 : Adjust the fan height
Loosen the 2 M3 8mm bolts, and ajust height according to your Hotend
![image](https://user-images.githubusercontent.com/37383368/144168574-4e82006d-b79b-4e37-b99f-34f7c00d5af3.png)

# Step 9 : Install the 5015 fan  (BL touch is not recommended anymore on VzBoT)
![image](https://user-images.githubusercontent.com/37383368/144168824-7156b8d9-2fe7-4098-915b-31f145dcd3d1.png)

## BOM needed:
- 1 x M3 20mm bolt - (For right side of the fan when you face printer )
- 1 x M3 25mm bolt - (for left side  Please note the left side bolt orientation is different to clear the belt)
- 1 M3 8mm (upper fan duct brace)
- 3 x M3 Nuts

# Optional : Tri horn fan duct with brace (useful when running a z probe sensor)
If you find that your fan duct is not stiff enough and move after a while, this mod of the fan [duct](https://github.com/VzBoT3D/Vz-Printhead/blob/main/STLs/fan%20duct%20lower%20body-trihorn%20with%20brace.stl) is for you. Scale the [spacers](https://github.com/VzBoT3D/Vz-Printhead/blob/main/STLs/fan%20duct%20lower%20body-brace%20Z%20scalable%20spacers.stl) according the the height needed.
![image](https://user-images.githubusercontent.com/37383368/176760266-9fbbe036-2285-433d-9bbc-f1edfe9d210f.png)
(If you wish to run CPAP, refer to the CPAP section)


# Optional : Rear pillar brace
If you do not need to bring the fan all the way down, you can print and install this little [BRACE](https://github.com/VzBoT3D/Vz-Printhead/blob/main/STLs/Rear%20pillar%20brace.stl) that will help secure the cable mount in place
![image](https://user-images.githubusercontent.com/37383368/173377071-cb560330-bb4c-449d-8ee5-06435b12b3f9.png)

# Optional : PROBE  see all options [here]([/tree/main/STLs/Probe%20mounts](https://github.com/VzBoT3D/Vz-Printhead-CNC/tree/main/STLs/Probe%20mounts)

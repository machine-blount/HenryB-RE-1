#SRM-20
***bringing a forgotten machine back to life***

The SRM-20 is an isolation milling machine that remained unused for most of my time at The Delta School. I have always wanted to use this machine to make prototype PCB’s, but never got the chance to since most of the software is deprecated and the machine had some issues in the hardware. 

As a part of my subtractive manufacturing resident expert I wanted to fix this machine to accept Kicad files and mill them out on a standard board of FR-4 copper clad. Doing this required me to sift through as much SRM-20 documentation as possible to find anything that was relevant to my main goals. In the process I found a program called Mods.CE which is a node based editor for CNC machines like laser cutters and isolation mills like the SRM-20. 

<img src="https://github.com/user-attachments/assets/1247dede-ea45-4498-b154-6e804b7556ee" width="200">

By experimenting with the software and continuing to search for any online resources I was successfully able to mill out a line test and custom design from Kicad later on. 

<img src="https://github.com/user-attachments/assets/fd20dfd2-844f-4e72-ab47-ecdbe2551df3" width="200">

#Frameoko 
***Probably the first open source Shapeoko 4 enclosure that can be milled by the same Shapeoko 4***

This year I have been looking to upgrade my CNC setup, in the past I just relied on a shop vac for all of the sawdust, and whatever other material byproduct. This proved difficult for the most part since the shop vac would often fail to up material sometimes resulting in compressed saw dust on the v rails which would disrupt the shapeoko’s travel. This is especially the case if your machine is near other shop tools where sawdust can be ejected right onto your CNC’s gantries and other useful parts.

<img src="https://github.com/user-attachments/assets/3bfa7c13-dbe1-463f-aaec-7a71ca1bb33c" width="200">
A desperate attempt to sweep sawdust off of the v-rails. 

I started by looking at if there were any existing enclosures for my Shapeoko, but the only ones I could find were for Shapeoko XL and XXL’s. On top of this all of them required shop tools like table saws, hand routers, drills, and such. Because of the situation with my highschool, I lacked this equipment so I wanted an enclosure that could be milled just with my Shapeko alone and could be easily assembled and configurable for future requirements. 

I had done some research on which type joinery would be ideal for this sort of design. This wasn't a challenging task but I eventually just created my own version of lapped joinery since the outside surfaces need to be flush so panels can be easily mated to the frame. I also was aiming to have the design be made out of thin ⅛” material and milled using the stock ¼” endmill so anyone that got a Shapeoko 4 could easily throw a few panels on the machine and run of the cuts for a quick enclosure to get the machine up and going. I figure this would be a useful first cut for a beginner or a user in a rush that just needs a quickly deployable design. 

<img src="https://github.com/user-attachments/assets/f40d5ac4-2b82-4b25-96bd-ac58247cd99c" width="200">

To finish off my design I added ribs on the inside for support and added dogbones on the joinery so the pieces would nicely fit together. With this the first version is complete, of course I am still in the process of improving the design and documenting everything on github for others to use. In reflection I had done external research on the proper joinery to use and if there was already a solution like this that existed. In closing here is the current design 

<img src="https://github.com/user-attachments/assets/82ea135a-8a22-4951-9fa7-c02061df3550" width="200">


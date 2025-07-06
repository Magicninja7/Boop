This is a devlog for this 3d printer im making!
(im keeping this casual)

# Day 0 (24-25.05.25) ~15 hours
Today i did research, setup fusion, and started making a scetch for the base!
After that, i started making the polar mechanism itself, designing the gears and belt. Now if gear A (the small one) is spun, gear B spins too. On the left, seperated for now, is a part of the printbed and elemesnts allowing it to spin (atleast they will in the future).
![spinny_gears](https://hc-cdn.hel1.your-objectstorage.com/s/v3/46f31857100da145e59373f068723aabe83ce7d8_image.png)

# Day 1 & 2 (27 & 29.05.2025) ~2.5 hours
With exams, i didn't have time to do much. I did do one thing though, draw out the design on my whiteboard. I also found a good extruder to use (sherpa mini), paired with the XC1 hotend and a dragon burner. I have already gotten the cads for them, and only need to assemble them within fusion.
And more research on how to do the z axis. The problem with the design in the video, is that it shakes, and like a lot. To solve it, im considering adding another arm, on the other side of the cartridge. This would substantially minimalise shaking, but slightly increase the price. I think its a good trade, as the other way involves getting rid on the cantileverian design.


# Day 3 (13.06.2025) ~0 hours lmao
Thank god i passed everything, finally have got time to continue this project. 

# Day 4 (20.06.2025) ~3 hours
I completed the whole extruder part, by using the sherpa mini with the xc1 hotend, combined with the dragon burner. Starting on the x axis, i have completed the design on paper, now i only need to bring it onto fusion. I also will be using a 2x sliding rods, and 2x lead screws for the y axis, but i will add that after i finish the x axis.
![making x axis](https://hc-cdn.hel1.your-objectstorage.com/s/v3/372ce80ef81b43cca59c0e1061b319702543520d_image.png)

# Day 5 (21.06.2025) ~5 hours
Im continuing my work on the x axis. Found and added pulleys needed for the design (6 total), added the vrail and carriage). All designed by me, its why it took soo long
![carriage](https://hc-cdn.hel1.your-objectstorage.com/s/v3/70aa4703986988fba9e1ea713c8fe4a804063fc4_image.png)

# Day 6 (25.06.2025) ~6 hours
Today i added a pulley at the end of the vrail (it isnt connected yet tho, im yet to do that). I also added a second pulley at the other end, it will be moving the extruder. In here, i created a part that will hold it, it fit snugggly into the vrail, with 0.1mm margin. It also will have a whole in the middle (through the whole thing, including the vrail), to slide in a blot, so the whole thing doesnt move or shake. It also has 2 ball bearings, with inside diamater of 20mm, the same as the pulley.
![wroom](https://hc-cdn.hel1.your-objectstorage.com/s/v3/41f6263157ca5974daddcb895f60e29b0f53bf99_image.png)
![up!](https://hc-cdn.hel1.your-objectstorage.com/s/v3/1a3e2a0ae8ec6cad5d7c275875ece0b456965c45_image.png)

# Day 7 (26.06.2025) ~5 hours
I added the holder for the bottom pulley, and redid the holder for the front pulley (it had 0 margin, and not it has 0.05 margin. Idk if its the gap is big enough, but its a cheap 3d printed part, so no big deal). I also did research on how exactly a mount should look, since i need one to connect my sherpa with xc1. I decided on the 4010 axial to provide general flow onto the heatsink, and a radial fan (5015) for the tip of the nozzle. I will want to make it as light as possible, but will likely need an airduct to channel the air, but since its plastic it shouldnt add much.
![the rail n carriage n pulley](https://hc-cdn.hel1.your-objectstorage.com/s/v3/d8acca0592458ddcab6f053c99e62bb08ce66d61_image.png)

# Day 8 (26-27.06.2025) ~6 hours
I created the mount, connecting the 4010 fan, with the sherpa and hotend. The blank space opposite of the fan, will be filled by a material mesh i have at home. It currently doesnt have a mount, since i plan to add another part, made with cnc, or bought online, where i will insert the 20mm diamater rod, and then screw it to the mount.
![fan view](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2508f1e8695fd41765b368e827479a59f9b342d5_image.png)
![other view](https://hc-cdn.hel1.your-objectstorage.com/s/v3/9592b0fc1e683cba7c2001ac31872d8cbccd3126_image.png)

# Day 9 (03.06.2025) ~5 hours
I made a mount, however its horrible. takes up too much space.
![mount](https://hc-cdn.hel1.your-objectstorage.com/s/v3/e07c699659f6525c0f1d4e2080aa7bc1544b1b38_image.png)

Now it looks like this! It has a space to screw it in, on its 4 corners, and a screw to fit into the rod, which is also custom made!
![mount_only](https://hc-cdn.hel1.your-objectstorage.com/s/v3/9e69a03c5e762875b92929ab0fd76a3cacce132a_image.png)

I also atlast connected it to the rod, and the x axis is completed!
![whole thing](https://hc-cdn.hel1.your-objectstorage.com/s/v3/76bc2263e75de2e0db6af93f68954d17262a0670_image.png)

# Day 10 (06.06.2025) 
Now i added a belt and created new pulleys for the x axis!
![belt](https://hc-cdn.hel1.your-objectstorage.com/s/v3/36cc73dc3064dfa2324cb673c559887b671a4b2e_image.png)






## Parts

Extruder:
 - Sherpa mini
 - Dragon burner
 - XC1 hotend

Base:
 - 1x Nema 17
 - 200mm diamater float glass

mount scherpa x xc1:
 - 4010 axial fan (heatsink)
 - 5015 radial fan (nozzle tip)

x axis:
 - 1x [v-rail](https://us.openbuilds.com/v-slot-20x20-linear-rail/)
 - 2x [v-rail carriage](https://us.openbuilds.com/mini-v-gantry-kit/?searchid=0&search_query=v+rail)
 - 8x8x24 ball bearing [(back pulley)](https://modelemax.pl/en/bearings/19394-ball-bearing-8-24-8mm-628zz)
 - 20x12x42 ball bearing [(front pulley)](https://www.fallshaw.com.au/products/SPBRGQ6004X20)
 - 20mm diamater rod (front pulley causes spin)

y axis:
 - 2x [lead screw](https://us.openbuilds.com/8mm-metric-lead-screw/)
 - 2x [nut block](https://us.openbuilds.com/anti-backlash-nut-block/)
 - 2x  sliding rod
 - 



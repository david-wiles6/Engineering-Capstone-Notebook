# Engineering Capstone Onshape

## Caster

### Base

This was a simple rectangle with 7 holes, 5 of those holes were patterned off of the sixth, and the 7th was in the middle of the left four holes as shown in this picture: 

![The Caster Base](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-09-29%20at%203.26.07%20PM.png)

As you can see, I didn't draw the rectangle centered on the origin, so instead of putting the hole on the origin, I drew two lines for construction that were coincident with the top left and middle bottom holes and top middle and left bottom holes and put the hole on that intersection.

Onshape Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/c66bf4462c2602e2562c989a

### Mount

This was a part that was based on the geometry of the base. The mount was a square with 5 holes in it, 4 in the corners and 1 in the middle. This part was made 3 different ways: one was making an entirely new part and drawing all of the holes in the same sketch as the square. The second was drawing the square first, then making the holes with two cuts and a pattern, this is the way I would do it in SolidWorks. The third was to use the geometry of the base and make an extrusion in the base part studio, and extrude it as new. 

![The seperate mount studio](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-01%20at%2012.22.18%20PM.png)


![The mount built on top of the base geometry](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-01%20at%2012.22.06%20PM.png)

Onshape Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/2355ca0c53de52c0cd40471b


### Fork

This part was a circle with two prongs coming off the bottom, and one circular prong coming off the other side. In this part, I learned about how to do fillets.

![The Caster Fork](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-02%20at%202.09.44%20PM.png)

Onshape Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/96520cf51c97581a20f9a886 

### Tire

This part was a torus with the middle curve removed so the inside was flat. This was achieved by making a trapezoid and revolving it around an axis. This part taught me about doing revolves, which is significantly easier in Onshape than in SolidWorks. 

![The Caster Tire](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-02%20at%202.09.54%20PM.png)

Onshape Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/74fd5b2ae4b690f0fc874601

### Wheel

This part was a rim. It was an I revolved around the origin. It had 5 holes cut in it. It was a bit tricky to do the circular pattern because I made a couple of silly mistakes, but otherwise it was pretty smooth sailing.

![The Caster Wheel](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-02%20at%202.10.28%20PM.png)

Onshape Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/866ac1b79a9e265aa5eaaebd

### Axle, Collar, Bearings

These parts were pretty easy, the axle was a cylinder with a notch cut into the top, the collar was on the end of the axle. One of the bearings went on the wheel, so I just used the wheel geometry to make a new part on top. Notably, I didn't have to make a new sketch for it which was cool, I just had to click the face, and extruded it as new to make the bearing. The other bearing I just made in a new part studio, this bearing goes on top of the fork, so I'm sure that I could have used the fork's reference geometry to make it if I wanted to.

![Axle and Collar](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-02%20at%202.10.52%20PM.png)


![Bearing on the wheel](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-02%20at%202.10.40%20PM.png)


![Bearing for the Fork](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-02%20at%202.11.10%20PM.png)

Axle/Collar Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/84beaf12966b01008c868d96

Bearing/Wheel Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/866ac1b79a9e265aa5eaaebd

Fork Bearing Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/01e75ca72050d0708f30e045

### Sub-Assembly

This assignment was to put the wheel, tire, the axle, and two bearings together. I learned about mate connectors and revolute and fasten mates, which made it easier to mate the componenets together.

![Sub-Assembly](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-02%20at%203.05.08%20PM.png)

Onshape Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/8702fb5b47958e0df2c39e0c

### Complete Assembly

This assignment was pretty easy after all of the Onshape experience in the previous videos. One notable thing was that I used a fasten mate to mate the axle to the collar, and the two rotated together and the hole on the collar stayed over the flat portion of the axle. I'm not sure if something special happened, but it did work on both collars, so I'm not sure. I also really like onshape's standard parts library and how it works because it makes it much easier than solidworks to actually put the parts in the assembly. All in all, it was a cool project to build this caster and learn about onshape.

![Final Assembly](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Screenshot%202020-10-02%20at%203.29.53%20PM.png)

Onshape Document: https://cvilleschools.onshape.com/documents/07a84ca6bfb48144a93a34ac/w/c54cdb9d66c7e7f71c75caa3/e/df7821e44ddfb195c7b9f83a


## Onshape Challenge 

This assignment consisted of 3 parts, a square with rods coming off the sides, two spinners, and a rack to hold them all together. The rack was probably the weirdest part for me because I couldnt figure out the thin feature. What I ended up doing was extruding the line as a surface, then using the thicken function to make it a solid. This produced some weird effects that had to be fixed. One was that when I filletted the edges, the middle corner where the surface was stuck out, and I actually had to fillet that corner as well, which was weird. 

![Animated Spinner](https://github.com/david-wiles6/Engineering-Capstone-Notebook/blob/master/pictures/Challenge%20_%20Assembly%201.gif)

Onshape Document: https://cvilleschools.onshape.com/documents/aab081aaac488ae87e849b1c/w/aaf11e78a0736de854e19acf/e/a2e2364a02dcda34904dce5a

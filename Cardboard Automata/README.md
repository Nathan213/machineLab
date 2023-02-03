# Project Documentation
## Final Result



https://user-images.githubusercontent.com/77680363/216601517-4a7f4f54-bdb7-4eaf-94c1-5555d29aa075.mp4



This project was very fun to make. Building and visualizing cams and cranks were very helpful in theoretically understanding how they work. Some of the main chalenges I encountered in this project had to do with stability. I will detail each instance below. 

## First Failure
The first issue I identified and fixed was the instability of the crank shaft. Because the motor was moving so fast, the horizontal section of the shaft was being pushed and pulled too violently, causing the tip of the shaft to tilt up. Here is a short demonstration of the issue:


https://user-images.githubusercontent.com/77680363/216602980-af98cd1f-d324-4697-bd64-7385be234047.mp4



To fix this issue, I decided to attach a gate-like structure on the crank platform to limit the movement of the shaft. It worked initially, although the extra friction between the shaft and the gate put more stress on the motor and wheel. After around half a minute of testing, the connection between the driving shaft and the wheel broke apart. Here is the video of when it happened:


https://user-images.githubusercontent.com/77680363/216603519-88735bdf-7800-455a-8c2c-bce0633568c2.mp4


I made three adjustments to rectify this issue. First, I rebuilt the limiting gate. The first one was a bit too tight around the crank shaft, producing too much friction. I remade one that gave more leeway. Second, I taped the crank shaft with a tape that had a smooth surface, further reducing the friction. These changes can be seen here:

![Vertical limitations](https://user-images.githubusercontent.com/77680363/216605518-d6c4803a-9e5b-405d-ad57-70ac26a8b86d.png)

Finally, I rebuilt the connection between the wheel and the driving shaft. In my initial design, I first glued a flat piece of cardboard to the wheel to give it a flatter surface. Then, I glued four triangles to the driving shaft and glued the other side of the triangles to the wheel's cardboard surface. The triangles were not able to hold the wheel in place when stress came from the crank shaft. In my second design, I copied the design I had for the other side of the driving shaft. (Where the driving shaft was attached to the crank) Because my driving shaft is very skinny, any attempts to glue directly to it will probably break under pressure. Therefore, I decided to glue two large pieces of cardboard onto the driving shaft. The two cardboard pieces were glued to each other, with the shaft in the middle. Like this:

![Wheel Attachment](https://user-images.githubusercontent.com/77680363/216605095-e23f9322-b43a-42be-a131-4953989b3de9.png)

I then flexed the two cardboard pieces that were not glued outwards, and glued the wheel to the unglued surfaces. This allowed for a much larger connection area. 

These fixes seemed to have solved the issue, and the automata was able to run smoothly for a full minute. 

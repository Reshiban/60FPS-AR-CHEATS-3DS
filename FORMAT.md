# Why this file ?
I want a specific presentation for this project, to be as clean and consistent as possible between each files.<br>
This is a model for me and you, so you can understand how the cheats files are built, and I can remember the format easily.<br>
**THIS HAVE TO BE USED ON A REAL 3DS WITH CTRPF**

# Format
### Cheats names
In basic files, there is 3 cheats:<br>

-60FPS (Hold R button for 30FPS)<br>
-60FPS<br>
-30FPS<br>



# Examples
```
[60FPS (Hold R button for 30FPS)]
D3000000 XXXXXXXX  //Set offset
XXXXXXXX YYYYYYYY  //ADDRESS VALUE for 60FPS
DD000000 00000100  //Button to hold for 30FPS (R button here)
XXXXXXXX YYYYYYYY  //ADDRESS VALUE for 30FPS
D0000000 00000000  //End "if" condition
```

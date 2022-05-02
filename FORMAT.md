# INTRODUCTION
`FORMAT.md` explain the syntax used for the cheats of this repo.<br>
You can use it to make a cheat for this repo<br>

### (WARINING: **REAL 3DS + CTRPF NEEDED**)

# Format
## Cheats names
For this repo, the .txt cheat files basical structure is:

### Basical structure
```
./
./[60FPS (Hold R button for 30FPS)]
./FPS/
./FPS/[60FPS]
./FPS/[30FPS]
```

\*insert a picture\*
<br>
A game could have some versions. In this case, some changes are applied:

### Version structure
```
./
./[60FPS v1.x (Hold R button for 30FPS)]
./FPS/
./FPS/[v1.0]/
./FPS/[v1.0]/[60FPS]
./FPS/[v1.0]/[30FPS]
./FPS/[v1.x]/
./FPS/[v1.x]/[60FPS]
./FPS/[v1.x]/[30FPS]
```

### Cheat descriptions



# Examples
```
[60FPS (Hold R button for 30FPS)]
D3000000 XXXXXXXX  //Set offset
XXXXXXXX YYYYYYYY  //ADDRESS VALUE for 60FPS
DD000000 00000100  //Button to hold for 30FPS (R button here)
XXXXXXXX YYYYYYYY  //ADDRESS VALUE for 30FPS
D0000000 00000000  //End "if" condition
```

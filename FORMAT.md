# INTRODUCTION
`FORMAT.md` explain the syntax used for the cheats of this repo.<br>
You can use it to make a cheat for this repo<br>

### (WARINING: **REAL 3DS + CTRPF NEEDED**)

# Format
## Cheats names
In this repo, the .txt cheat files basical structure is:<br>

```
./
./FPS/
./FPS/
./

```

- _**root**_ folder:
  - _**60FPS [Hold R button for 30FPS]**_ cheat
- _**FPS**_ folder:
   - _**60FPS**_ cheat
   - _**30FPS**_ cheat


Like this (picture):<br>
\*insert a picture\*


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

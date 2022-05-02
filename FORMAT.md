# INTRODUCTION
`FORMAT.md` explain the syntax used for the cheats of this repo.<br>
You can use it to make a cheat for this repo<br>

### ⚠WARNING: **REAL 3DS + CTRPF NEEDED**⚠<br>
# Cheats structure

## Basical structure
The basical cheat structure is:
```
./
./[60FPS (Hold R button for 30FPS)]
./FPS/
./FPS/[60FPS]
./FPS/[30FPS]
```

\*insert a picture\*<br>
<br><br>
## Version structure
A game could have some versions. In this case, some changes are applied:
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

\*insert a picture\*<br>
<br><br>

## 30FPS/60FPS structure

# Cheats code

## [60FPS (Hold R button for 30FPS)]
```
[60FPS (Hold R button for 30FPS)]
D3000000 XXXXXXXX  //Set offset
XXXXXXXX YYYYYYYY  //ADDRESS VALUE for 60FPS
DD000000 00000100  //Button to hold for 30FPS (R button here)
XXXXXXXX YYYYYYYY  //ADDRESS VALUE for 30FPS
D0000000 00000000  //End "if" condition
```


# Cheats description

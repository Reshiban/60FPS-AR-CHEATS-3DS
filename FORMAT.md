# INTRODUCTION
`FORMAT.md` explain the syntax used for the cheats of this repo.<br>
You can use it to make a cheat for this repo<br>

### ⚠WARNING: **REAL 3DS + CTRPF NEEDED**⚠<br>
# Cheats structure

## Basical structure
The basical cheat structure is:
```
./
./[60FPS (Hold R button for 30FPS)] ▣
./FPS/
./FPS/[60FPS] ▣
./FPS/[Default 30FPS] ▣
```
The game runs 30FPS by default.

\*insert a picture\*<br>
<br><br>

## 30FPS/60FPS structure
Examples **above** are for **30FPS -> 60FPS**<br>
Some games are 60FPS by default, and cheats turn them to 30FPS, in this case:
### 60FPS -> 30FPS
```
./
./[30FPS (Hold R button for 60FPS)] ▣
./FPS/
./FPS/[Default 60FPS] ▣
./FPS/[30FPS] ▣
```
If _Default_ isn't precised, this means the default FPS isn't yet determinated.

\*insert a picture\*<br>
<br><br>

## Version structure
A game could have some versions. In this case, some changes are applied:
```
./
./[60FPS v1.x (Hold R button for 30FPS)] ▣
./FPS/
./FPS/[v1.0]/
./FPS/[v1.0]/[60FPS] ▣
./FPS/[v1.0]/[Default 30FPS] ▣
./FPS/[v1.x]/
./FPS/[v1.x]/[60FPS] ▣
./FPS/[v1.x]/[Default 30FPS] ▣
```

\*insert a picture\*<br>
<br><br>

## Author structure
Sometimes, some people find different working cheats for the same game.<br>
In this case, the structure will be:
```
./
./[60FPS Author A (Hold R button for 30FPS)] ▣
./[60FPS Author B(Hold R button for 30FPS)] ▣
./FPS/
./FPS/[Author A]/
./FPS/[Author A]/[60FPS] ▣
./FPS/[Author A]/[Default 30FPS] ▣
./FPS/[Author B]/
./FPS/[Author B]/[60FPS] ▣
./FPS/[Author B]/[Default 30FPS] ▣
```

\*insert a picture\*<br>
<br><br>

## Global structure
In the case all these conditions are applied, it should looks like that:
```
./
./[60FPS Author A v1.x (Hold R button for 30FPS)] ▣
./[60FPS Author B v1.x (Hold R button for 30FPS)] ▣
./FPS/
./FPS/[Author A]/
./FPS/[Author A]/[v1.0]/
./FPS/[Author A]/[v1.0]/[60FPS] ▣
./FPS/[Author A]/[v1.0]/[Default 30FPS] ▣
./FPS/[Author B]/
./FPS/[Author B]/[v1.x]/
./FPS/[Author B]/[v1.x]/[60FPS] ▣
./FPS/[Author B]/[v1.x]/[Default 30FPS] ▣
```

\*insert a picture\*<br>
<br><br>

# Cheats codes

## [60FPS (Hold R button for 30FPS)]
```
[60FPS (Hold R button for 30FPS)]
D3000000 XXXXXXXX  //Set offset
XXXXXXXX YYYYYYYY  //ADDRESS VALUE for 60FPS
DD000000 00000100  //Button to hold for 30FPS (R button here)
XXXXXXXX YYYYYYYY  //ADDRESS VALUE for 30FPS
D0000000 00000000  //End "if" condition
```


# Cheats descriptions

##

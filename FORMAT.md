# Why this file ?
This `FORMAT.md` file is here to set and understand the syntaxe of this project.<br>
This been set by myself and nothing else.<br>
Use it if you want to make a cheat for this repo<br>
<br>Thanks :)<br>
<br>
### (---> **NEEDS REAL 3DS + CTRPF** <---)

# Format
## Cheats names
In this repo, the .txt cheat files basical structure is:<br>

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

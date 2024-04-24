# Custom SeWiesa
# For german keyboard 
also include keymap_german.h in the file lily58.c
## File location
splitkb/aurora/lily58/keymaps
## compile
````qmk bash 
qmk compile -kb splitkb/aurora/lily58 -km JJW -e CONVERT_TO=liatris
````
## flash
````qmk bash
qmk flash -kb splitkb/aurora/lily58 -km JJW -e CONVERT_TO=liatris
````

##layout
![img.png](imgs/layer0.png)
##layer 1
![img.png](imgs/layer1.png)
##layer 2
![img.png](imgs/layer2.png)
##layer 3
![img.png](imgs/layer3.png)
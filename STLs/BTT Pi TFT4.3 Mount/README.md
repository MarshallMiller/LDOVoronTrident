## Touchscreen Mount for BigTreeTech Pi TFT4.3
This is a remix based on the [Waveshare 4.3 touchscreen mount](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/jeoje/4.3_Inch_Touchscreen_Mount/STL/2.4) by jeoje. 
Print the faceplate in the accent colour of your choice. The mount uses M3 brass heatset inserts and M3x8(or M3x10) screws to fasten the faceplate on each side. 
Use the screws provided in the BTT touchscreen packaging to fasten the screen to the mount.

### Fastener Count  
- 4 M2.5x6 (included with BTT screen)
- 5 M3x8 
- 3 M3 roll-in nut
- 2 M3 heatset insert

### Configuration

Edit /boot/config.txt

- Remove `dtoverlay=vc4-kms-v3d`
- Add `dtoverlay=vc4-kms-dsi-lt070me05000-v2`
- To rotate display add `display_rotate=2`
- To rotate touchscreen add `lcd_rotate=2`

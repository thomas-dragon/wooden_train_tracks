# Überschrift Ebene 1
 div. 3D Druckteile für eine CNC3018Pro Fräse

## Überschrift Ebene 2
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

Pfad: /images/xxx.png
![Bildtext](/images/cable_mount_b2.png)

### Video als Gif
![Bildtext](/video/car_01_hoches_chassis_v62(1).gif)

### Überschrift Ebene 3

### Ordnerstruktur
| Verzeichnis    | 	usage |
| ------------- | ------------- |
| images | rendered |
|  stl  | stl 3d printer files |
|  fusion 360  | cad   |
|  step  | cad files|
|  dxf  | lasercut |
|  pdf  | drawing |



### Tabelle
### File formats

| format    | 	usage |
| ------------- | ------------- |
|  stl  | 3d print, cad |
|  step  | cad |
|  dxf  | lasercut |
|  pdf  | drawing |
|   png | rendered |
|  fusion 360  | cad  |
### Material properties:  

- Acrylic with 5 mm thickness is sufficiently stable for 3D printers and can be processed well with the laser cutter.
- Transparent or transparent material leaves fingerprints, at the same time the correct position of the nuts is clearly visible.


| Propertie     | value |
| ------------- | ------------- |
| material      | 5mm acrylic/plexi glas or 3mm aluminium  |
| processing    | laser cut   |
| diameter hole  | 5mm for M5 |
| standard grid hole spacing | 20mm  |

### Screws for t slot profile 20x20 

- t slot nut deep 5,5 mm

| material     | screw length |
| ------------- | ------------- |
| acrylic/plexi glas 5mm | 8...10 mm   |
| aluminium 3mm    | 6...8 mm |

### Beispiel externes Bild
### Aluminium Slot 6 T-Nut profil

- Example: Motedis Profile 20x20 B-Type slot 6 


<img src="https://www.motedis.com/shop/images/product_images/popup_images/1_1.JPG" width="600"  title="Motedis Profile 20x20 B-Type slot 6">

### Aluminium Slot 6 T-Nut profil

### Beispiel externer Link
Prototyping Board 270-Point Breadboard
https://www.pololu.com/picture/view/0J3852

### Code

``` cpp
// A dual extruder that uses a single stepper motor
//#define SWITCHING_EXTRUDER
#if ENABLED(SWITCHING_EXTRUDER)
  #define SWITCHING_EXTRUDER_SERVO_NR 0
  #define SWITCHING_EXTRUDER_SERVO_ANGLES { 0, 90 } // Angles for E0, E1[, E2, E3]
  #if EXTRUDERS > 3
    #define SWITCHING_EXTRUDER_E23_SERVO_NR 1
  #endif
#endif
```

 Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
 
 Here's a sample video:

![Sample Video](video/car_01_hoches_chassis_v62.mp4)
![Sample Video](video/car_01_hoches_chassis_v62.avi)
 
 >>>
If you paste a message from somewhere else 
that
spans
multiple lines,
you can quote that without having to manually prepend `>` to every line!
>>>

- {+ additions +}
- [+ additions +]
- {- deletions -}
- [- deletions -]

- [x] Completed task
- [ ] Incomplete task
    - [ ] Sub-task 1
    - [x] Sub-task 2
    - [ ] Sub-task 3


<a href="http://www.youtube.com/watch?feature=player_embedded&v=7p0hrpNaJ14
" target="_blank"><img src="http://img.youtube.com/vi/7p0hrpNaJ14/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="480" height="360" border="10" /></a>

 <a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
 
 
# pointabella

A pointer device peripheral test bench.


### design principles
- symmetrical
- 3 buttons
- no visible screws
- ligthweight
- small footpirnt
- low profile
- zmk firmware


### gallery

<p float="left">
<img src="./imgs/a.jpeg" height="200">
<img src="./imgs/1.jpeg" height="200">
<img src="./imgs/2.jpeg" height="200">
<img src="./imgs/tball-40mm.png" height="200">
<img src="./imgs/tball-20mm.png" height="200">
<img src="./imgs/tpoint.png" height="200">
<img src="./imgs/tpad.png" height="200">
<img src="./imgs/base.png" height="200">
<img src="./imgs/rear.png" height="200">
</p>


### parts
|unit|item|
|-|-|
|1*|pixart pwm3610 optical sensor. breakout board module: [badjeff](https://github.com/badjeff/pmw3610-pcb) /  [siderakb](https://github.com/siderakb/pmw3610-pcb)|
|1*|pixart paw3395 optical sensor. breakout board module: [badjeff](https://github.com/badjeff/paw3395-pcb)|
|1*|avago adns9800 optical sensor. breakout board module: [pigboard](https://oshwlab.com/pigboard/adns9800board) (See [reddit post](https://www.reddit.com/r/Trackballs/comments/ledoxb/adns_9800_board_finally_ready_project_link_in/))|
|1**|40mm or 20mm trackball. or, pom ball from ebay/aliexpress|
|3**|static ceramic bearings; 2.5mm for 40mm trackball mount, 2.0mm for 20mm trackball mount|
|3**|roller bearings; mr52zz（2x5x2.5mm）|
|1*|lenovo t440 trackpoint (plus 2x m1.5 screws)|
|1*|35mm cirque glidepoint circle trackpad tm035035|
|1|seeed studio xiao ble (nrf52840)|
|3|cherry mx/ kailh choc v1/v2 switches (14x14mm). or, kailh cmi627301d07 6x6x7.3mm silent micro switch|
|1|msk-1153 6 pins power switch|
|1|3.5x6x2mm tact switch turtle switch|
|1|m2 screw boxset (3-10mm)|
|1|601230 lipo battery (plus connector)|
|1|28/26 awg silicone wire|

*: choose either one;
**: for trackball mount only;


### building guide / tips

nope. easy enough.


### firmware

zmk firmware config repository can be find at [badjeff/zmk-config/tree/main/config/boards/shields/corne36](https://github.com/badjeff/zmk-config/tree/main/config/boards/shields/corne36).


### license

available under the [cern-ohl-p v2](/LICENSE) permissive license.

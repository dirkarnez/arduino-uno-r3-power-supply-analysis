arduino-uno-r3-power-supply-analysis
====================================
[Schematics](https://docs.arduino.cc/resources/schematics/A000066-schematics.pdf)

### Notes
- `TP` stands for Test Point

### Notepad
```
USB -> Fuse -> USBVCC -> UVCC

(VCC-AVCC -> +5V ->  NCP1117ST50T3G) / (DC Jack -> Diode)-> VIN

(has Vin ? Vin : USBVCC) -> lp2985-33dbvr -> 3V3
```
### Tutorials
- [**Arduino UNO R3: Complete and detailed hardware review - YouTube**](https://www.youtube.com/watch?v=U8SgBDKu_Gs)
- [Arduino Uno R3: Directly supply regulated 5V to 5V pin? - Electrical Engineering Stack Exchange](https://electronics.stackexchange.com/questions/65576/arduino-uno-r3-directly-supply-regulated-5v-to-5v-pin)

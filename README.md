# Waveform Generator V1

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/drcyberg/Waveform_Generator_V1)](https://github.com/drcyberg/Waveform_Generator_V1/releases/tag/V1.2)  [![GitHub](https://img.shields.io/github/license/drcyberg/Waveform_Generator_V1)](https://github.com/drcyberg/Waveform_Generator_V1/blob/master/LICENSE)  [![GitHub release (by tag)](https://img.shields.io/github/downloads/drcyberg/Waveform_Generator_V1/V1.2/total)](https://github.com/drcyberg/Waveform_Generator_V1/archive/master.zip)  ![Website](https://img.shields.io/website?up_message=Waveform_Generator_V1&url=https%3A%2F%2Fdrcyberg.github.io%2FWaveform_Generator_V1%2F)(https://drcyberg.github.io/Waveform_Generator_V1/)  [![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/drcyberg?tab=repositories)  [![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/drcyberg)  [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/Kunee82)  [![GitHub followers](https://img.shields.io/github/followers/drcyberg?style=social)](https://github.com/drcyberg?tab=followers)

---

## Description:

This Waveform Generator is a Hungarian [DIY](https://en.wikipedia.org/wiki/Do_it_yourself "Wikipedia") prototype version Arbitrary Waveform Generators and described here is based on AD9850, a CMOS, 125MHz, and Complete DDS Synthesizer. The AD9850 is a highly integrated device that uses advanced DDS technology coupled with an internal high speed, high performance, D/A converter and comparator, to form a complete digitally programmable frequency synthesizer and clock generator function. All the external components which are needed are integrated on the board and the designer don’t need to care more about the detailed design of AD9850. The designer only needs to add the power and control signals to driver this module.

![](/pictures/wfg_logo.jpg)

## Specifications:

- Signal Frequency output range: 0-40MHz
- 4 Signal outputs: 2 sine wave outputs and 2 square wave outputs
- DAC SFDR > 50 dB @ 40 MHz AOUT
- 32-Bit Frequency Tuning Word
- Simplified Control Interface: Parallel Byte or Serial Loading Format
- Phase Modulation Capability
- +3.3V or +5V Single Supply Operation (AD9850 Module)
- Low Power: 380mW @ 125 MHz (+5V)
- Low Power: 155mW @ 110 MHz (+3.3V)
- Power-Down Function
- Power Supply Adapter: 9-12V 500mAh

---

## Extra Additionals:

- Reset button
- DC socket
- ICSP, UART connection headers (programming interface)
- DC Jack Socket
- Power SPDT Switch toggle
- Sine and Square BNC output connectors
- Based on Atmega328P chip
- 1,8" TFT Display (ST7735) connection interface
- 2x rotary encoder buttons (to Sine and Square)
- Flashing mode slide switch (V1.1)

---

## Applications:

- [x] Frequency/Phase–Agile Sine-Wave Synthesis
- [x] Clock Recovery and Locking Circuitry for Digital
- [x] Communications
- [x] Digitally Controlled ADC Encode Generator
- [x] Agile Local Oscillator Applications

---

## Changelogs:

### V1.2

- Changed power SPDT switch toggle to sliding switch
![](/pictures/9.jpg)

### V1.1

- Added slide switch for enable easier standalone flashing/debug mode with only DC 5V input power (support many [flashing USB keys](https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20200810135246&SearchText=ftdi+usb "Aliexpress")), say Thee not necessary  any more external power
![](/pictures/8.jpg)

---

## Samples:

![](/pictures/presentation.jpg)
![](/pictures/samples.jpg)
![](/pictures/samples2.jpg)

---

## Firmwares:

- [Without Bootloader](https://github.com/drcyberg/Waveform_Generator_V1/blob/master/firmware/wfg_v1.hex "Firmware") (Development users)
- [With Bootloader](https://github.com/drcyberg/Waveform_Generator_V1/blob/master/firmware/wfg_v1_with_bootloader.hex "Firmware") (Normal users)

---

## How to flash:

- [Guide](https://www.arduino.cc/en/Guide/ArduinoISP "Guide")
- [Tutorial](https://www.arduino.cc/en/tutorial/arduinoISP "Tutorial")

---

## BOM (Bill Of Materials): [View](https://htmlpreview.github.io/?https://github.com/drcyberg/Waveform_Generator_V1/blob/master/bom/wfgbom.html "View")

---

## PCB Gerber file: [Download](https://github.com/drcyberg/Waveform_Generator_V1/blob/master/manufacturing/wfg_v1_2.zip "Download")

- Dimensions: 95x80mm
- Layers: 2lv

---

## 3D Models:

![](/pictures/Assembled.jpg)

- [Base](https://github.com/drcyberg/Waveform_Generator_V1/blob/master/stl/base.stl "Base")
- [Frame](https://github.com/drcyberg/Waveform_Generator_V1/blob/master/stl/frame.stl "Frame")
- [Stand](https://github.com/drcyberg/Waveform_Generator_V1/blob/master/stl/stand.stl "Stand")
- [Top](https://github.com/drcyberg/Waveform_Generator_V1/blob/master/stl/top.stl "Top")

## Required other parts:

- 4x M4 45mm screw
- 4x M4 nut
- 4x M3 10mm screw
- 4x M3 nut

---

## Thingiverse: [Link](https://www.thingiverse.com/thing:4544577 "Link")

---

## If you want to support me: [Donate](https://www.paypal.me/Kunee82 "Donate")

---

## Have a nice day!

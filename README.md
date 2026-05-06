# ESP32 Pocket Camera (DIY)

A compact, portable DIY digital camera built using the **Seeed Studio XIAO ESP32-S3** , a **Waveshare ST7789 SPI LCD Display**, and a **3.7 LiPo Battery**.

This project is a hands on project that combines both hardware and software, that will essentially give me a greater sense of the integration between software and hardware within a project. It should capture images, saves images to microSD card, and displays them on a small LCD screen with button-based navigation. The decive will also feature a **custom-designed 3D printed enclosure**, that I am creating though AutoCAD.

## 🚀 Features
- Captures photos using onboard OV5640 Camera
- Saves images to microSD card
- Displays images on TFT Screen
- Button-controlled interface
- Portable / durable casing
- Caseing Desgined in AutoCAD

## 🧩 Hardware
### Core Components
- Seeed Studio XIAO ESP32-S3 Sense
- Waveshare 1.69" ST7789 SPI Display (240x280)
- MicroSD Card
- 3.7 LiPo Battery
- Buttons
- SPDT Switch

##Enclosure Design
- Designed in AutoCAD
- Optimized for compact layout
- Built to hose all hardware components.
  ### Planned Design Features
  - Front-facing display window
  - Camera Cutout
  - Front-mounted buttons (except shoot which will be on side)
  - USB-C access for charging
  - Internal mounts for components
 
## Wiring Overview 
 Waveshare 1.69" LCD (ST7789V2) + XIAO ESP32S3

| LCD Pin | XIAO ESP32S3 |
|--------|--------------|
| VCC    | 3V3 |
| GND    | GND (direct, not via breadboard) |
| DIN (MOSI) | D10 |
| CLK (SCK)  | D8 |
| CS     | D7 |
| DC     | D6 |
| RST    | D5 |
| BL     | 3V3 |

### ⚠️ Notes

- **Breadboard only used for 3.3V split (VCC + BL)**
- SPI pins should be **direct wired** (no breadboard)
- Keep wires **short**

## Software Setup -> Coming soon (debating on using arduino IDE versus PlatformIO
## Development Progress
* [x] ESP32 setup
* [x] Display working
* [ ] Button input
* [ ] SD card write
* [x] Camera capture
* [ ] Image display
* [ ] Gallery navigation
* [ ] Battery integration
* [ ] Enclosure design (AutoCAD)
* [ ] 3D printing + assembly

## Acknowledgments
* Seeed Studio (XIAO ESP32-S3 Sense)
* Waveshare (display modules)
* ESP32 community

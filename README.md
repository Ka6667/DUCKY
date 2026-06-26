# DUCKY
<img width="1410" height="2000" alt="mENG-Gotchi" src="https://github.com/user-attachments/assets/4d40949e-d448-4810-8079-413145143689" />

## Table of Contents
* [What is DUCKY?](#what-is-ducky)
* [Why did I build it?](#why-did-i-build-it)
* [How to use DUCKY](#how-to-use-ducky)
* [Schematics](#schematics)
* [PCB Design](#pcb-design)
* [Assembly Instructions](#assembly-instructions)
* [3D Model](#3d-model)
* [BOM](#bom)
---

## What is DUCKY?
Ducky is my custom smart alarm and personal assistant!
Ducky lives on a little screen and she takes her job very seriously. She can set a time. if you ignore her alarm, and she will absolutely let you know she's disappointed. She's got feelings, okay?!!!!
When you want to listen to music, Ducky can help you with. When it's late at night, she's already sleeping, because unlike you, she has great sleep hygiene. And when you actually wake up on time? She will be so happy so don't let her down.
I used xiao esp32c, a tiny TFT screen, and way too much love to design it, Ducky is a smart alarm clock, timer, stopwatch, and music companion all in one. She syncs her time from the internet so she's always right, and she will remind you of that.
## Why did I build it?
I’m constantly missing school because my old alarm is totally unreliable and sometimes it doesn't even go off. I tried buying a new one, but I’m still having the same problem and just can’t seem to wake up. So I’ve decided to build my own smart alarm. I want it to actually interact with me like with changing her mood. let me know if the the time and day, and play music or rain sounds to help me crash at night. Basically, it’s going to be a calendar and my music box, and 100% better at getting me out of bed on time with her loud alarm sound!.

## How to use DUCKY?
Clock Mode is the default. She shows the time and date.<br>
During the day she blinks happily. After 10 PM she goes to sleep.<br>
Press once → Timer Mode<br>
Turn the knob to pick minutes, then press again to start.<br>
If the alarm fires and you don't respond in 30 seconds, she gets sad  <br>
Press twice quickly → Stopwatch Mode<br>
Press to start and stop. Turn the knob to set a lap alert interval.<br>
Hold for 0.5 seconds → Music Mode<br>
Press to play or pause. Turn the knob to change the volume.<br>
Hold for 2 seconds → Go back to Clock Mode from anywhere.<br>
The knob always does something useful depending on the mode, brightness in clock mode, minutes in timer, lap interval in stopwatch, and volume in music mode.<br>
The music is saved in the SD Card of the DFplayer!! make sure to download the music and the loudest alarm sound on the SD card or Ducky will be silent the whole time!<br>
## Schematics
<img width="909" height="811" alt="Screenshot 2026-06-20 142048" src="https://github.com/user-attachments/assets/573eb68e-ee52-42a1-82b0-8cf7b47815c3" />

## PCB Design
<img width="650" height="650" alt="Screenshot 2026-06-20 142647" src="https://github.com/user-attachments/assets/ea37b5ba-111f-4660-84d1-3f4442ed9905" />
<img width="650" height="600" alt="Screenshot 2026-06-20 142706" src="https://github.com/user-attachments/assets/892551c8-d6dd-412d-98f3-fbff3b4de833" />
<img width="650" height="553" alt="pcb2" src="https://github.com/user-attachments/assets/e8b886ac-4a88-4b38-bb16-084703376e3b" />

## Assembly Instructions
it is so simple just add four screws to the four mounting holes inside the case to attach the PCB to the case as you can see here (just use Socket Head Cap Screws):
<img width="1561" height="637" alt="Screenshot 2026-06-24 122957" src="https://github.com/user-attachments/assets/f12c1747-66a6-4c4d-9d43-459fb159cea7" />
<img width="1149" height="737" alt="Screenshot 2026-06-24 123532" src="https://github.com/user-attachments/assets/eb795384-2e25-4367-8e02-8889d7b8023f" />
<img width="1022" height="709" alt="Screenshot 2026-06-24 132547" src="https://github.com/user-attachments/assets/0024c349-7a41-47b5-84bf-109a4a7b1994" />



Then there are three screws for the outer mounting for the face of the case. I extened the holes a little bit outside the case to make it more stable (also use Socket Head Cap Screws):
<img width="723" height="684" alt="Screenshot 2026-06-24 135621" src="https://github.com/user-attachments/assets/9f439874-b408-4d97-8d79-72b409cd6377" />
<img width="852" height="671" alt="Screenshot 2026-06-24 135604" src="https://github.com/user-attachments/assets/f2d445ec-28d2-4e71-b2a9-52ab2f972c41" />

you can still use a washer if you want to install any other screws that has small heads. just make sure to keep everything fixed in its place!! 

## 3D Model
<img width="776" height="702" alt="Screenshot 2026-06-20 111535" src="https://github.com/user-attachments/assets/e60838f6-59e8-4291-bf87-b20242077e03" />
<img width="1153" height="716" alt="Screenshot 2026-06-20 112222" src="https://github.com/user-attachments/assets/4dac1cf3-4417-4331-a332-926478bf7dbd" />
<img width="1614" height="766" alt="Screenshot 2026-06-20 143159" src="https://github.com/user-attachments/assets/6614b905-cf99-41a8-9611-623f68053b11" />

The small little cylinder on the right side is a body that will be used as a knob extender for the potentiometer (The hole on the side and the knob's postition, lenght and width are accurate based on the data sheet of the potentiometer)! The CAD desgin of the potentiometer is not present because I can't find a good one that will really looks like the real potentiometer that I will use in this project (it's not a big deal because I used the potentiometer data sheet to know the exact measurements to make the knob and its hole!!!).

## BOM
| Part | Amount | Price | Link |
| :--- | :---: | :---: | :--- |
| XIAO-ESP32C3 | 1 | $11.21 | [Temu Link](https://temu.com/ul/kuiper/un9.html) |
| TFT LCD Display Module | 1 | $7.34 | [Amazon Link](https://www.amazon.eg/-/en/TFT-Display-Module-Interface-Inch/dp/B0CJ851LDT/) |
| DFPlayer Mini MP3 | 1 | $2.54 | [Temu Link](https://www.temu.com/ul/kuiper/un9.html) |
| Speakers | 1 | $4.94 | [Temu Link](https://www.temu.com/ul/kuiper/un9.html) |
| LIPO-Battery | 1 | $1.10 | [Makers Electronics Link](https://makerselectronics.com/product/rechargeable-400925-lipo-battery/) |
| 1000K Ohm resistor | 1 | $0.05 | [Amazon Link](https://www.amazon.eg/-/en/Resistor-1K-ohm-4W-2pcs/dp/B0CJQ3M5J1/) |
| Screws | 4 | $1.50 | [Temu Link](https://www.temu.com/ul/kuiper/un9.html) |
| Push-buttons | 1 | $0.04 | [Temu Link](https://www.temu.com/eg-en/10pcs-6x6x5mm--tactile-tact-push-button-micro-switch-mini-micro-momentary-tactile-push-button-switch--x-5mm-g-605681855863393.html) |
| Potentiometer | 1 | $0.34 | [Amazon Link](https://www.amazon.eg/-/en/Generic-414999-483-Potentiometer-10K-Ohm/dp/B091DX3483/) |
| PCB | 1 | $2.00 | [JLCPCB Link](https://cart.jlcpcb.com) |
| **Total** | | **$31.06** <br>*(shipping not included)* | |

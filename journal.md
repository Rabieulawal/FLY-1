---
title: "FLY-1"
author: "rabie ul awal"
description: "A universal flight controller platform"
created_at: "26 july 2026"
---

# Juny 26th: doing some reserch

So i started off by just looking for some ideas and on the start i planed to use an esp so i did some reserch for like 25 mins 



<a href="https://lapse.hackclub.com/timelapse/rsHg7rv10Z8p">lapse here</a>

**Total time spent: 25min**

# Juny 27th: made the schematic

So i decided to use the stm32 h7 but then decided to use 2 different mcus i planed to use the rp2350 as the navigation MCU and the STM32 f4 as the main MCU i wanted this to b powered by lipo batterys and those battrys should be able to have multipule cells so i added a buck converter which can acecpt upto 60v so you can plug in any battery you want. after all this when i as abt 6hrs in my laptop randomly blue screened :( which restarted it and i lost all my unsaved work. thankfully i knew the connections and did not have to find the parts again and stuff and i was back to where i was before in less then 30 mins :) . so i made the schematic of the rp2340 power and the bcuk converter     

<img width="732" height="644" alt="image" src="https://github.com/user-attachments/assets/ac7017b5-7ce6-481b-9a08-36d91df10c8a" />

<img width="853" height="496" alt="image" src="https://github.com/user-attachments/assets/d3c7a20b-2f03-47c1-a612-f06572eab3a4" />



<a href="https://lapse.hackclub.com/timelapse/BbA9C7VE1qBu">lapse here</a>

**Total time spent: 8.5hr**

# Juny 28th: Finishing the schematic and making the pcb

SO i added the stm F4 and its conections i conected both MCUs with SPI and wired the IMU with SPI too and also added a Manometer and Barometer which are connected using I2c and GPS which is connected using URAT.
i also wred the stm and added usb conections for the MCUs as well then i made the pcb i speedran routing the pcb and wrote the journals and uploaded all teh files to GitHub

<img width="756" height="505" alt="image" src="https://github.com/user-attachments/assets/1fcb13f6-0d3f-43e8-9e0c-66a649dac6c5" />

<img width="754" height="489" alt="image" src="https://github.com/user-attachments/assets/69810942-114a-4b89-8299-8bbacf43e06b" />

<img width="719" height="481" alt="image" src="https://github.com/user-attachments/assets/b760e7fb-b6eb-4dea-9be9-bb34e0e2062f" />

<img width="929" height="587" alt="image" src="https://github.com/user-attachments/assets/7f5c22d6-d549-4d80-a74c-857b3258f494" />

<a href="https://lapse.hackclub.com/timelapse/R3qTmDXOXc7E">lapse here</a>


**Total time spent: 5.5hr**






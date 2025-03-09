# e.MMC-Test-Board

<img src="https://github.com/eletronicaTL/e.MMC-Test-Board/blob/main/tlmoto_logo.png" alt="TLMOTO" width="300">

# Introduction
We are a student-led team, TLMoto, from Instituto Superior T´ecnico, in Lisbon, Portugal. Our goal is to build an electric motorbike to compete at MotoStudent, in Aragon, Spain. Recently, we decided to further develop our telemetry system, and implement a better memory to gather the data collected. For that purpose, we selected an e.MMC — embedded MultiMediaCard — and designed this PCB, to be able to reliably test it, and later implement the same principles on the real bike.

# e.MMC
- Micron ® MTFC8GAMAL
- JEDEC/MMC standard version 5.1-compliant (JEDEC Standard No. JESD84-B51)
- ×1, ×4, and ×8 I/Os
- 8 GB Capacity
- 40 MB/s Sequential Write
- 280 MB/s Sequential Read

# Components

Reference | Value | Footprint | Quantity | 
--- | --- | --- | --- |
R1, R13 | 22 Ω | R 0805 2012 | 2 |
R2-R11 | 50 kΩ | R 0805 2012 | 10
R12 | 10 kΩ | R 0805 2012 | 1
C1, C3, C5 | 100 nF | C 0805 2012 | 3
C2 | 1 μF | C 0805 2012 | 1
C4, C6 | 2.2 μF | C 0805 2012 | 2
IC1 | MTFC8GAMALNA-AAT | TBGA100 NA MT | 1

# Schematic and PCB Design

You can download both files from this repository.

# How to Order the PCBs

It is now time to place the order for our PCBs. For that, we have got the help of [JLCPCB](https://jlcpcb.com/?from=STU) and is also a sponsor of this project. 

In their website, you just need to click on the “QUOTE NOW” button. You can order a minimum of 5 PCBs for just $2. To get the PCB manufactured, upload the Gerber files that you can obtained from PCB Design file. Upload the .zip file or you can also drag and drop the Gerber files. After uploading the .zip file, you’ll see a success message at the bottom of the file, meaning that it has been successfully uploaded. Review the PCB in the Gerber viewer to make sure everything is good — both the top and bottom of the PCB. After making sure your PCB looks good, you can now place the order at the reasonable price mentioned above. Furthermore, if it is your first order, you can get 10 PCBs for $2. To place the order, click on the “SAVE TO CART” button. The PCBs took 2 days to get manufactured and arrived within a week using the DHL delivery option. PCBs were well packed and the quality was really good.

![JLCPCB](https://github.com/eletronicaTL/e.MMC-Test-Board/blob/main/jlcpcb_logo.png)


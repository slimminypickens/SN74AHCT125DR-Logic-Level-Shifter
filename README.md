# SN74AHCT125DR-Logic-Level-Shifter
Logic Level Shifter for WLED using the SN74AHCT125DR

## ⚠️ Warning
- I've never designed a PCB before, and so it's very possible it's total trash!
- In saying that, it's working for me, so do with that what you will :)
 
 ## 🟡 Source for circuit diagram
- https://kno.wled.ge/basics/compatible-hardware/#levelshifters
- In particular, the 'SN74AHCT125; example: two outputs' diagram

-  ## 📲 Making your own
- All the files needed for having JLCPCB make the circut boards are included.
- The .csv file also has the bill of materials. I purchased the compnents separately from LCSC https://lcsc.com/ but you can just have JLCPCB place the components and I think might actually work out to be more cost effective once shipping etc is factored in.
- You don't actually need to connect the ground pin on the output, just FYI (and no +5V on the output side, either!)
- The WLED wiring guides are super helpful - https://kno.wled.ge/basics/wiring-guides/
- The gerber file will open in easyEDA if you want to improve the PCB. For some reason I couldn't get it to import to KiCad.



![20250522_151423](https://github.com/user-attachments/assets/48f1d4fa-85fa-4a30-9e30-0917841d0317)

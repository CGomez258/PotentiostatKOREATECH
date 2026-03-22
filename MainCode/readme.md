This Zip file contains the Arduino code for the potentiostat circuit

Requirements: 
1. Arduino IDE 2
2. STM32CubeProgrammer


Add in the program access, add the STM32 programmer: C:\Program Files\STMicroelectronics\STM32Cube\STM32CubeProgrammer\bin 


In Arduino:

1. Go to File → Preferences
2. Find “Additional Boards Manager URLs”  and add this URL (keep others, separate with commas if needed): https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json
3. Click OK 


Now install the core: 

1. Go to Tools → Board → Boards Manager…
2. In the search box, type: stm32
3. Find “STM32 MCU based boards” by STMicroelectronics
4. Click Install 
That gives Arduino IDE support for STM32F4, including the Black Pill. 

Configure the Arduino board as follows:

<img width="491" height="372" alt="image" src="https://github.com/user-attachments/assets/c588a7af-09ed-474c-ae26-70e74d36745a" />


# ErgoDecks not ErgoDOX
- ## Featuring
  - ### Two independent Bluetooth halves.
  - ### 3d printed case
  - ### Custom PCB
  - ### Kalih Choc switch compatibility.

**BOM**

| Item |Quantity |Total price+Shipping|Use in project|Item source|
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Pcb  | 5x (minimum order) |$22.31|Mount Everything to this|JLCPCB|
| NRF52840	  | 2x |$10.77|Drive the boards|[Aliexpress](https://www.aliexpress.us/item/3256807018711621.html?spm=a2g0o.productlist.main.1.5a6eie0Hie0H9D&aem_p4p_detail=202505281428561705173893544160001721434&algo_pvid=e8c677b1-5ee7-4a06-9cf3-86530aadc628&algo_exp_id=e8c677b1-5ee7-4a06-9cf3-86530aadc628-0&pdp_ext_f=%7B%22order%22%3A%22307%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%214.39%214.39%21%21%2131.45%2131.45%21%402101c71a17484677363603280ed1bd%2112000039797470328%21sea%21US%214381910819%21X&curPageLogUid=OhOCTEVGrX7q&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202505281428561705173893544160001721434_1)|
|Kalih Choc 10pc	|4x|$31.00|Be switches|[Little Keyboards](https://www.littlekeyboards.com/collections/keyboard-switches/products/kailh-choc-low-profile-switches)|
|Filament of your choice|an amount|0$|make the case|wherever you buy filament ( I have this)|
|301230 lithium battery|2x|$8.76|Power The boards|[Aliexpress](https://www.aliexpress.us/item/3256806602655947.html?spm=a2g0o.productlist.main.3.1f175238MrCTZJ&algo_pvid=eaa25171-69cd-4b4e-b96e-f3d39bffa79c&algo_exp_id=eaa25171-69cd-4b4e-b96e-f3d39bffa79c-2&pdp_ext_f=%7B%22order%22%3A%2274%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%218.10%214.70%21%21%2157.98%2133.63%21%402103205117484706855838784ee72d%2112000038305675270%21sea%21US%214381910819%21X&curPageLogUid=6xafRV7sUtxr&utparam-url=scene%3Asearch%7Cquery_from%3A)|
|1N4148 Diodes 100pc|1x|$9.26|be diodes|[Aliexpress](https://www.aliexpress.us/item/3256806058794623.html?spm=a2g0o.productlist.main.2.76fa3771JY9hHq&algo_pvid=3d141e2c-c612-4dda-8ee7-d81e18ab9714&algo_exp_id=3d141e2c-c612-4dda-8ee7-d81e18ab9714-1&pdp_ext_f=%7B%22order%22%3A%22914%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%211.84%211.28%21%21%2113.14%219.15%21%402101c80217484699707521224ee30c%2112000036448323916%21sea%21US%214381910819%21X&curPageLogUid=FxGJkqmD4E5N&utparam-url=scene%3Asearch%7Cquery_from%3A)|
|Keycaps 1u 10pc|x4|$21.11|be keycaps|[adafruit](https://www.adafruit.com/product/5737)|
|Keycaps 1.5u 2pc|x2|$4.66|be keycaps|[Aliexpress](https://www.aliexpress.us/item/3256805730011012.html?spm=a2g0o.productlist.main.8.4ba31a67KZIfyi&algo_pvid=95a4ad10-6234-413b-ba30-70ed94a3c48a&algo_exp_id=95a4ad10-6234-413b-ba30-70ed94a3c48a-7&pdp_ext_f=%7B%22order%22%3A%2263%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%212.33%212.33%21%21%212.33%212.33%21%40210337bc17484682352145208eab6e%2112000034838215571%21sea%21US%214381910819%21X&curPageLogUid=KAtk70CozSZd&utparam-url=scene%3Asearch%7Cquery_from%3A)|
|Everything||$95.88|||

## **Download Gerbers.zip for the gerbers and ErgoDecksVx.3mf/.step/.f3z for the case!**
- ## **Assembly**
  - Solder diodes onto the PCB.
  - Solder switches onto the PCB.
  - Solder microcontrollers onto the pcb.
  - Solder the battery to the bat terminals on the mcu.
  - Attach the battery using double sided tape to the bottom half of the case in the battery area.
  - ![image](https://github.com/user-attachments/assets/371abf3e-b6f9-4f95-85ed-9dc5b281bec2)
  - Use m3 bolts to secure the pcb and top case to the bottom half of the case.

- ## **Software**
  - Install/configure [ZMK](https://zmk.dev/docs/user-setup) 
  - Follow those instructions until you get to User Config Setup Script
  - For keyboard selection, select Helix
  - For MCU board select nRFMicro 1.3/1.4
  - Answer yes to copy in stock keymap for customization
  - Follow the ZMK documentation from Installing the Firmware onwards

![image](https://github.com/user-attachments/assets/49c8ae91-7437-4b8a-8b07-92a017c727ab)
![image](https://github.com/user-attachments/assets/4712b373-c182-4556-9e80-d0b9a6c7b6ed)
![image](https://github.com/user-attachments/assets/04a16e00-8f62-4c53-ae3c-68ec50fd374b)
![image](https://github.com/user-attachments/assets/054641cc-98f3-42de-8c28-08df6e4e4228)


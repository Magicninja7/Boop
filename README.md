Description: Its a polar, 4axis, cantivileerian 3d printer! It uses a unorthodox aproach to rotate the hotend in b axis, and y axis, using only 2 motors and being pretty cool! The printbed is also backlit!! :3
WHy? idk, felt like it tbh. Saw a cool video on yt, thought: i wanna do that. And then highway happened. And then this happened.

## Cad 
![looks kinda sick ngl](https://hc-cdn.hel1.your-objectstorage.com/s/v3/92f0838f625e418168fee1eab7b1775033f23e40_image.png)

## PCB
![this took more time than you think](https://hc-cdn.hel1.your-objectstorage.com/s/v3/0c06b2732530efd255b6a5e69aeb491063b424a8_image.png)

## Diagram

Power Supply (LRS-350-24) Connections

LRS-350-24:

    AC Input L (Live): → Mains AC Hot
    AC Input N (Neutral): → Mains AC Neutral
    AC Input Ground: → Mains AC Ground
    +V (24V): → SKR3 VIN terminal
    -V (Ground): → SKR3 GND terminal
    +V (24V): → LED Strip positive terminal
    -V (Ground): → LED Strip negative terminal

SKR3 Main Board Connections
Stepper Motor Drivers

SKR3:

    Driver Socket X: → X-axis stepper driver (TMC2209/TMC2226)
    Driver Socket Y: → Y-axis stepper driver (TMC2209/TMC2226)
    Driver Socket Z: → Z-axis stepper driver (TMC2209/TMC2226)
    Driver Socket E0: → Extruder stepper driver (TMC2209/TMC2226)

Endstop Switches

SKR3:

    X-STOP pin 1 (Signal): → X endstop switch NO (Normally Open)
    X-STOP pin 2 (GND): → X endstop switch COM (Common)
    Y-STOP pin 1 (Signal): → Y endstop switch NO (Normally Open)
    Y-STOP pin 2 (GND): → Y endstop switch COM (Common)
    Z-STOP pin 1 (Signal): → Z endstop switch NO (Normally Open)
    Z-STOP pin 2 (GND): → Z endstop switch COM (Common)

Hotend (XC1) Connections

SKR3:

    HE0 pin 1 (+): → XC1 hotend heater cartridge positive
    HE0 pin 2 (-): → XC1 hotend heater cartridge negative
    TH0 pin 1 (Signal): → B57560G1104F000 thermistor pin 1
    TH0 pin 2 (GND): → B57560G1104F000 thermistor pin 2
    FAN0 pin 1 (+): → XC1 cooling fan positive (24V)
    FAN0 pin 2 (-): → XC1 cooling fan negative

Print Bed Connections

SKR3:

    HE1/BED pin 1 (+): → Print bed heater positive
    HE1/BED pin 2 (-): → Print bed heater negative
    THB pin 1 (Signal): → Bed thermistor positive (if separate)
    THB pin 2 (GND): → Bed thermistor negative (if separate)

LED Strip Connections

SKR3:

    FAN1 pin 1 (+): → LED strip positive (via MOSFET if needed)
    FAN1 pin 2 (-): → LED strip negative



## Parts

| Part | Qty | total$ | link |
| ---- | --- | ----- | ---- |
| sherpa mini | 1 | 24 | [Ali]([https://pl.aliexpress.com/item/1005002487727392.html](https://pl.aliexpress.com/item/1005002487727392.html?gatewayAdapt=glo2pol)) |
| vslot rail | 2 | 16 | [Ali](https://pl.aliexpress.com/i/1005003311298946.html?gatewayAdapt=glo2pol)
| nema17+screw | 2 | 20 | [Ali]([https://www.aliexpress.us/item/1005005575285492.html?mp=1&gatewayAdapt=glo2usa](https://pl.aliexpress.com/item/1005007426592105.html?algo_exp_id=d4f99488-a359-4cc0-aea8-116da59cf138-8&pdp_ext_f=%7B%22order%22%3A%224%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!USD!10.46!10.46!!!10.46!10.46!%40211b441e17540107414063539ecc76!12000040714239435!sea!PL!6049391261!X&curPageLogUid=FYGczgJ1ZQe4&utparam-url=scene%3Asearch%7Cquery_from%3A))
| nema17 | 3 | 15 | [Ali](https://pl.aliexpress.com/item/1005003874936862.html?algo_exp_id=3ed336f1-a880-4dbb-8a6d-b39768883712-2&pdp_ext_f=%7B%22order%22%3A%222105%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!USD!5.93!5.64!!!5.93!5.64!%402103956b17540107983124197e982d!12000036219123370!sea!PL!6049391261!X&curPageLogUid=upzex6yVWPUB&utparam-url=scene%3Asearch%7Cquery_from%3A)
| skr3+drivers | 1 | 77 | [Ali](https://www.aliexpress.com/item/1005007540045155.html?algo_exp_id=db2c2344-aa37-43bd-b1af-e7c3de7a9108-0&pdp_ext_f=%7B%22order%22%3A%22145%22%2C%22eval%22%3A%221%22%2C%22orig_sl_item_id%22%3A%221005007540045155%22%2C%22orig_item_id%22%3A%221005006043539516%22%7D&pdp_npi=4%40dis!USD!68.46!76.98!!!489.02!549.81!%40211b804117531342587678427e9c93!12000041211841733!sea!PL!6049391261!X&curPageLogUid=EAQ1yuQyuRXg&utparam-url=scene%3Asearch%7Cquery_from%3A)
| lrs-350-24 | 1 | 35 | [Ali](https://www.aliexpress.com/item/1005006104414563.html?algo_exp_id=ed786665-9417-44ed-91e2-d2bbe9810003-0&pdp_ext_f=%7B%22order%22%3A%22145%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!USD!35.47!35.47!!!253.36!253.36!%40211b628117531347833686697e80ff!12000035765142564!sea!PL!6049391261!X&curPageLogUid=mk6m5iFwq7MV&utparam-url=scene%3Asearch%7Cquery_from%3A)
| pillow-bearing | 2 | 12 | [Ali](https://pl.aliexpress.com/item/1005008115694493.html?aem_p4p_detail=202507081114222547105643252920009348574&algo_exp_id=7769a70f-dea9-412a-9511-ebeb2c50ad36-0&pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!PLN!43.90!22.39!!!84.80!43.25!%402103985c17519984621601810e1f54!12000043851029398!sea!PL!0!ABX&curPageLogUid=DwaALHE42JiJ&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202507081114222547105643252920009348574_1)
| pulley | 2 | 3 | [Ali](https://www.aliexpress.us/item/1005004314084512.html?pdp_npi=4%40dis!USD!US%20%241.33!US%20%241.13!!!1.33!1.13!%402101585f17218179467507717e6f09!12000034179345936!sh!HK!3408833611!X&gatewayAdapt=glo2usa%5D)
| pulley no-teeth | 4 | 12 | [Ali](https://www.aliexpress.us/item/1005004314084512.html?pdp_npi=4%40dis!USD!US%20%241.33!US%20%241.13!!!1.33!1.13!%402101585f17218179467507717e6f09!12000034179345936!sh!HK!3408833611!X&gatewayAdapt=glo2usa%5D)
| back-pulley-xaxis | 1 | 2 | [Ali](https://www.aliexpress.us/item/32817328238.html?algo_exp_id=2e5559f6-0e2b-4699-af66-2900a6241a77-0&pdp_npi=4%40dis!USD!0.83!0.80!!!0.83!0.80!%402141069c17218103868312197ecd23!12000030774036536!sea!HK!3408833611!&curPageLogUid=WzjkJAxiIMiS&utparam-url=scene%3Asearch%7Cquery_from%3A)
| big-xaxis-pulley | 1 | 5 | [Ali](https://www.fallshaw.com.au/products/SPBRGQ6004X20)
| bearing-uni | 4 | 5 | [Ali](https://modelemax.pl/en/bearings/19394-ball-bearing-8-24-8mm-628zz)
| gantry_vslot | 2 | 18 | [Ali](https://pl.aliexpress.com/item/4000252044823.html?gatewayAdapt=glo2pol)
| 4010 fan | 1 | 4 | [Ali](https://pl.aliexpress.com/item/1005003462239029.html?aem_p4p_detail=202507211504023798993448239120006157034&algo_exp_id=70593ec9-93e4-496f-9f99-32fa072602fd-1&pdp_ext_f=%7B%22order%22%3A%22406%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!USD!3.11!3.11!!!3.11!3.11!%402101d9ef17531354426868570e953a!12000032185228739!sea!PL!6049391261!X&curPageLogUid=K5zZeirITV9z&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202507211504023798993448239120006157034_2)
| sliding rod | 1 | 3.2 | [ali](https://pl.aliexpress.com/item/1005006293171727.html?aem_p4p_detail=202507311723285856898193446300001240080&algo_exp_id=ada9f015-4615-4818-b9c0-808a02b69883-0&pdp_ext_f=%7B%22order%22%3A%223284%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!USD!0.98!0.98!!!0.98!0.98!%402103891017540078085294971eadc0!12000036638889760!sea!PL!6049391261!X&curPageLogUid=w5frZXLep9fc&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202507311723285856898193446300001240080_1)
| lm8uu bearing | 2 | 3 | [ali](https://pl.aliexpress.com/item/1005007070280422.html?algo_exp_id=2b87c25e-3c10-4f6d-b47d-1b26296c8bf4-2&pdp_ext_f=%7B%22order%22%3A%22348%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!USD!2.99!2.99!!!21.37!21.37!%4021038df617540078206205146e0ed2!12000039307639550!sea!PL!6049391261!X&curPageLogUid=f3G75FMtuKwk&utparam-url=scene%3Asearch%7Cquery_from%3A)
| m4 screws+nuts | 36 | 8 | local_shop
| m3 screws+nuts | 25 | 8 | local_shop
| m2 wcrews+nutss | 4 | 1 | local_shop
| m2.5 screw | 2 | 1 | local_shop
| m5 screws+nuts | 35 | 4 | local_shop
| m8 screws+nuts | 5 | 4 | local_shop
| B57560G1104F000 thermistor | 2 | 8 | [mouser](https://eu.mouser.com/ProductDetail/EPCOS-TDK/B57560G1104F000?qs=%2FsLciWRBLmAyaJsNOAuWiw%3D%3D)
| leds4printbed | 75 | 15 | [piekarz🔥](https://www.piekarz.pl/37911-dioda-led-worldsemi-ws2812b-v4/)
| gt2 belt | 1 | 8 | [Ali](https://www.aliexpress.us/item/10000115962505.html?algo_exp_id=3e07768a-d464-400f-8013-e23772bbed3e-1&pdp_ext_f=%7B%22order%22%3A%2231%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!USD!11.41!11.41!!!11.41!11.41!%402101c5bf17531364982723715eb8ce!12000025023391194!sea!PL!6049391261!X&curPageLogUid=kVrNqzgCRbOD&utparam-url=scene%3Asearch%7Cquery_from%3A)
| nutblock | 2 | 6 | [Ali](https://pl.aliexpress.com/item/1005004033091930.html?aem_p4p_detail=2025072115104714766776210775120006156124&algo_exp_id=6acb0970-a436-473f-83ce-022215f6bc8f-5&pdp_ext_f=%7B%22order%22%3A%2230%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!USD!2.58!2.58!!!18.45!18.45!%402103247417531358475558797efead!12000027807086483!sea!PL!6049391261!X&curPageLogUid=3HUxqKNu2SHZ&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=2025072115104714766776210775120006156124_6) 
| xc1 hotend | 1 | 2 | [Ali](https://pl.aliexpress.com/item/1005007319888761.html)
| jumper cables (m2m & f2f & m2f) | 40 each | 8 | [Botland](https://botland.com.pl/przewody-polaczeniowe-zensko-meskie/19621-zestaw-przewodow-polaczeniowych-justpi-zensko-meskie-20cm-40szt-5903351243025.html) note: after customs aliexpress is actually more expensive + m2m and f2f connectors cost the same - ~2.5$)
| endstop switches | 3 | 4 | ![ali](https://pl.aliexpress.com/item/1005008640444653.html?aem_p4p_detail=202507301707192219225324436200002745373&algo_exp_id=9b59729d-3d9c-4253-85cd-cfaa75983ca0-1&pdp_ext_f=%7B%22order%22%3A%2221%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis!USD!3.83!3.83!!!27.34!27.34!%402101ec1f17539204388924775e059e!12000046058656660!sea!PL!6049391261!X&curPageLogUid=3gTfpksfMGAi&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202507301707192219225324436200002745373_2#nav-specification)  
| pcb | 1 | 20 | [jlcpcb](https://jlcpcb.com/)

holy fuck 
its actually exactly 350$ 
wtf
nicee
i though i was gonna pay from pocket

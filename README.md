# PAPR (Powered Air-Purifying Respirator)
DIY PAPR for health workers [wiki](https://en.wikipedia.org/wiki/Powered_air-purifying_respirator). 

<img src="https://raw.githubusercontent.com/HighTemplar-wjiang/PAPR/master/prototype.jpg" alt="prototype" height="250">

## Update on 21st May.
- Uploaded source files, finalizing design and test.

## Update on 16th April.
- Battery test using a 20,000 mAh power bank -- 9 hours 4 minutes. 

## Update on 15th April. 
- Now using a 20,000 mAh [power bank](https://www.jaycar.com.au/20-000mah-power-bank-with-dual-type-a-quick-charge-and-type-c-power-delivery-usb-ports/p/MB3797) that is smaller, cheaper and easier to get. 
- Testing enclosure using 6mm Acrylic + 3D print fan blower adapter. 

## Update on 13th April.
- Tested a 12.8V 7.5Ah [lithum battery](https://www.jaycar.com.au/12-8v-7-5ah-lithium-deep-cycle-battery/p/SB2201), the fan worked for 15 hours, with less than 25% volume left.
- Tested an all 3D print enclosure, the cost was ~300 AUD. Changed to 3D print + laser cutting scheme. 

## Update on 11th April.
- Tested PC fan (1200 RPM), the static pressure was not sufficient. Probably a high speed fan is required.
- Changed design to [blower fan](https://www.jaycar.com.au/97mm-x-94mm-12v-dc-blower-fan-ball-bearing-2-wire/p/YX2532) which has higher static pressure. 

## Specifications ([ref](https://www.3m.com.au/3M/en_AU/company-au/all-3m-products/~/3M-Jupiter-PAPR-Helmet-JTM-406C/?N=5002385+8711017+3293696209&rt=rud))
- **Battery life**: > 8 hours (preferred 10 hours or longer)
- **Capacity per Minute (Metric)**: 150 to 230 litres per min (2.5 - 3.8 L/sec or 5.3 - 8.12 CFM)
- **Resistance to flow (N95 filter)**: 
  - 0.56 cmH<sub>2</sub>O @1L/sec, 0.74 cmH<sub>2</sub>O @5L/sec, <1.50 cmH<sub>2</sub>O @ 14L/sec.
  - or 55 Pa @1L/sec, 73 Pa @5L/sec, < 147 Pa @14 L/sec.
  
## Materials
- **[Blower fan](https://www.jaycar.com.au/97mm-x-94mm-12v-dc-blower-fan-ball-bearing-2-wire/p/YX2532)**
  - Air volume: 0.74 m<sup>2</sup>/min (26.13 CFM).
  - Static pressure: 1.0 inchH<sub>2</sub>O (2.54 cmH<sub>2</sub>O or 248.84 Pa).
  - Power consumption: 12 V x 0.86 A = 10.32 Watts (12.4 V x 0.38 A = 4.712 Watts as measured).
  - 3D-printed adapter [[in progress]()]. 
- **[Power bank](https://www.jaycar.com.au/20-000mah-power-bank-with-dual-type-a-quick-charge-and-type-c-power-delivery-usb-ports/p/MB3797)**
  - Capacity: 20000 mAh.
  - Voltage regulator: USB 12V step-up [power cable](https://www.jaycar.com.au/universal-usb-12v-step-up-power-cable/p/PP1978).
  - Slide [switch](https://www.jaycar.com.au/miniature-dpdt-panel-mount-switch/p/SS0821).
- **[CPAP/BiCAP bacteria filter](https://www.google.com/search?q=bacteria+filter&newwindow=1&rlz=1C1CHBF_en-GBAU878AU878&sxsrf=ALeKk00tQMjTFyXqZiyXmlXnysL8wDm1-g:1586943680106&tbm=isch&source=iu&ictx=1&fir=CWFMSYPq2Sse6M%253A%252Cul_TTRfInZ_iRM%252C_&vet=1&usg=AI4_-kTNiGZukLHlwl-E7zovhjH9Xxoe-Q&sa=X&ved=2ahUKEwjH9dLykeroAhV3wTgGHakdCnQQ9QEwBXoECAcQJw#imgrc=CWFMSYPq2Sse6M:)**
  - In-flow diameters: 22 mm inner, 26 mm outer.
  - Out-flow diameters: 19 mm inner, 22 mm outer. 
  - 3D-printed filter adapter [[in progress]()].
- Laser cutted pannels for enclosure
  - 6 mm Acrylic. 
  - M3 screws x 2.
  - Silicone glue. 
  - Silicone tape.

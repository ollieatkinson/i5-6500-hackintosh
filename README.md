# macOS Catalina on Intel i5 6500, Gigabyte Z170X-UD5 TH with a RX 5700

**Do not use this repository, follow the [official guide](https://dortania.github.io/OpenCore-Desktop-Guide/) to setup your hackmac**

### Working

- [x] iMessage
- [x] Handoff
- [x] DRM (Netflix)
- [x] DRM (Apple TV+)
- [x] Sleep

### Not working
- [ ] Sidecar. I had to disable the iGPU for the machine to boot.

## Configuration

| Specifications | Detail                                           |
| ------------------- | ------------------------------------------- |
| Motherboard         | [Gigabyte Z170X-UD5 TH](https://www.gigabyte.com/uk/Motherboard/GA-Z170X-UD5-TH-rev-10#ov)                       |
| Processor           | [Intel i5 6500](https://www.amazon.co.uk/Intel-Processor-BX80662I56500-6M-Certified-Refurbished/dp/B07PBX9636/ref=sr_1_1?dchild=1&keywords=Intel+i5+6500&qid=1592038749&s=computers&sr=1-1)                               |
| Memory              | 2 x 8GB @ 3000MHz & [2 x 16GB @ 3200MHz](https://www.amazon.co.uk/gp/product/B016ORTNI2/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)                  |
| Hard Disk           | [Samsung SSD](https://www.amazon.co.uk/gp/product/B078WST5RK/ref=crt_ewc_title_dp_2?ie=UTF8&psc=1&smid=A3P5ROKL5A1OLE)                                 |
| Graphics Card       | [MSI RADEON RX 5700 8G](https://www.amazon.co.uk/gp/product/B07TSKR17S/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)                       |
| Monitor             | [Dell U3415W 34-inch IPS Monitor](https://www.amazon.co.uk/Dell-34-inch-Monitor-Response-Integrated/dp/B00R420VAG/ref=asc_df_B00R420VAG/?tag=googshopuk-21&linkCode=df0&hvadid=310818959688&hvpos=&hvnetw=g&hvrand=16851882154730264494&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1006766&hvtargid=pla-716693714872&psc=1)  |
| Wireless & Bluetooth Card       | [Broadcom BCM943224PCIEBT2](https://www.aliexpress.com/item/32849220309.html?src=google&src=google&albch=shopping&acnt=494-037-6276&isdl=y&slnk=&plac=&mtctp=&albbt=Gploogle_7_shopping&aff_atform=google&aff_short_key=UneMJZVf&&albagn=888888&albcp=9317296204&albag=99548979972&trgt=296730740870&crea=en32849220309&netw=u&device=c&albpg=296730740870&albpd=en32849220309&gclid=CjwKCAjw8pH3BRAXEiwA1pvMsfO7BfRKbEsK003sikci-M6snagtrAsKpEYncCnB7BqkR1v-pXsL3xoCiDYQAvD_BwE&gclsrc=aw.ds)                         |

## Software

| Software | Version                                           |
| OpenCore | 0.5.9 |
| VirtualSMC | 1.14.0 |
| Lilu | 1.4.5 |
| WhateverGreen | 1.4.0 |
| AppleALC | 1.4.5 |
| IntelMausiEthernet | 1.0.2 |
| USBInjectAll | 0.7.5 |

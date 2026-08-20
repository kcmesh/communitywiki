# Solar Node Build Guide

General build instructions are inspired from [this video from Hacncrap](https://www.youtube.com/watch?v=eXMlvGiI7Hs).

## Materials Needed

!!! note "main build doc"
    The materials needed are based on the [following google doc](https://docs.google.com/spreadsheets/d/1maEK8LzIw5OsZczc4BbTVaiMq3ccHK3XibDCWRuzyDw/) that may be more updated with links than this guide.
    with helpful info

Note that this equipment list has both a RAK module option and a Seeed XIAO option for the LoRa board to install Meshtastic/Meshcore on. You will only need one of these LoRa boards. 

| Name | Price | Note | Link |
| --- | --- | --- | --- |
| Solar Light | $14.98 | Was 9.98 on sale | [https://www.lowes.com/pd/Harbor-Breeze-60-Lumens-1-Watt-Black-Warm-White-Solar-LED-Spot-light/5018244381](https://www.lowes.com/pd/Harbor-Breeze-60-Lumens-1-Watt-Black-Warm-White-Solar-LED-Spot-light/5018244381) |
| 5dBi 915MHz antenna and pigtail | $16.95 | antenna with 8 inch pigtail | [https://www.amazon.com/dp/B0GSB5XKLF](https://www.amazon.com/dp/B0GSB5XKLF) |
| Alt 5dBi 915MHz Antenna | $12.95 | knockoff ALFA AOA-915-5ACM | [https://www.amazon.com/dp/B0DS7XRHP5](https://www.amazon.com/dp/B0DS7XRHP5) |
| Alt u.fl to N type pigtail | $7.47 |  | [https://www.amazon.com/dp/B08ZYK5SL9](https://www.amazon.com/dp/B08ZYK5SL9) |
| Battery Protection Module | Unavalible | 12 pack | [https://www.amazon.com/dp/B0F6955QR1](https://www.amazon.com/dp/B0F6955QR1) |
| Alt Battery Protection Module | $5.99 | 10 pack | [https://www.amazon.com//dp/B0B4D1D74V](https://www.amazon.com//dp/B0B4D1D74V) |
| Battery wires | $7.99 | 15 pack | [https://www.amazon.com/dp/B088NFRNZ2](https://www.amazon.com/dp/B088NFRNZ2) |
| Solar Pannel wires | $7.99 | 10 pack | [https://www.amazon.com/dp/B06XYR8LQ1](https://www.amazon.com/dp/B06XYR8LQ1) |
| 3d Printed mount (PETG, ASA, PC) | Varies | local library's makerspace may have a 3d printer | [https://www.printables.com/model/1748950-26-harbor-breeze-solar-mesh-node-mounts-meshtastic](https://www.printables.com/model/1748950-26-harbor-breeze-solar-mesh-node-mounts-meshtastic) |
| Wireless Kit RAK Mini baseboard | $13.94 | Smallest RAK baseboard | [https://store.rokland.com/collections/rakwireless-products/products/rak-wireless-wisblock-mini-base-board-rak19003-ver-b-pid-306024](https://store.rokland.com/collections/rakwireless-products/products/rak-wireless-wisblock-mini-base-board-rak19003-ver-b-pid-306024) |
| RAK nRF module | $19.94 |  | [https://store.rokland.com/collections/rakwireless-products/products/rak-wireless-rak4631-nordic-nrf52840-ble-core-module-for-lorawan-with-lora-sx1262](https://store.rokland.com/collections/rakwireless-products/products/rak-wireless-rak4631-nordic-nrf52840-ble-core-module-for-lorawan-with-lora-sx1262) |
| Alternate Wireless Kit Seeed nRF kit | $13.49 | Cheaper, connect solar to Vin/USB and GND | [https://www.seeedstudio.com/XIAO-nRF52840-Wio-SX1262-Kit-for-Meshtastic-p-6400.html](https://www.seeedstudio.com/XIAO-nRF52840-Wio-SX1262-Kit-for-Meshtastic-p-6400.html) |

- Total estimate price for RAK build: $67.74
- Total estimate price for Seeed build: $47.35

## Instructions
TODO
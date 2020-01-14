# David's Hackintosh Setup
I built a Hackintosh. Why? Because ever since I was introduced to the world of Macs, I've wanted a powerful Mac desktop computer -- but have never been able to afford the cost of purchasing one. I decided to build a Hackintosh as a means of bridging that gap. Plus, I could choose the hardware I put inside the computer!

## Hardware

| Type           | Component                                   |
|----------------|---------------------------------------------|
| CPU            | Intel 9700k, 8-core, 3.60GHz                |
| Motherboard    | Gigabyte Z390 AORUS PRO (BIOS Rev. F11)     |
| Graphics       | Sapphire AMD Radeon RX580 8GB NITRO+        |
| RAM            | Corsair DDR4 Vengeance 3200MHz 8x4GB (32GB) |
| Boot Drive     | Samsung MZ-V7E500BW 970 EVO 500GB           |
| WiFi/Bluetooth | Broadcom BCM94360CD                         |
| PSU            | EVGA 600W 80+                               |
| Cooler         | Corsair Hydro H100x 240mm AIO cooler        |

Buy hardware that guarantees maximum compatiability with macOS. This motherboard in particular works well with 9th generation Intel CPUs and macOS, although it lacks native NVRAM.

## Patching ACPI Tables
I decided to go down the more complex route of patching my motherboard's ACPI tables. While more challenging, the end result is a more stable system with fewer quirks/issues. As far as I am aware, everything is working as it would on a normal Mac.

I don't recommend using the patched DSDT and SSDT files I have used. Patch your own; ask [MaLd0n](https://www.olarila.com) for help. Even though you are using similar hardware, there are differences (even changing a single BIOS setting can mess things up). Be careful.

## Credits
My setup was based upon the guide provided by [AudioGod](https://www.insanelymac.com/forum/topic/339980-audiogods-aorus-z390-pro-patched-dsdt-mini-guide-and-discussion/). It is thorough and I highly recommend trying it out. My thanks also to MaLd0n for helping with the patching of my DSDT and SSDT. Thank you.
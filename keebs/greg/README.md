## BOM
| Name | Qt | Link |
| :--- | :---: | :--- |
| Cases | 02 | [(mirror for left half)](/keebs/greg/case/) |
| 6mm M2 Screws | 18 | [ali](https://www.aliexpress.us/item/3256802343690897.html) |
| M2 Heatsets | 18 | [ali](https://www.aliexpress.us/item/3256803396040989.html) (get 3.2mm od) |
| 1N4148 Diodes | 40 | [ali](https://www.aliexpress.us/item/2255800939822415.html) |
| 1208YD Power Buttons | 02 | [ali](https://www.aliexpress.us/item/3256801267126259.html) |
| Nice!nano v2s or Clones | 02 | [ali](https://www.aliexpress.us/item/3256806085566324.html) |
| MX Switches | 40  | duh |
| 1u MX Keycaps | 40 | duh |
| Lipos | 02 | so i went to a smoke shop and they let me have [these](https://www.lostmary.com/product/MT15000-TURBO.html) used vapes for free that i cracked open for lipos (you need to solder on a [bms](https://www.aliexpress.us/item/2251832487705010.html) btw)|
| Colored Stranded Wire | idk | |
| Bare Copper Wire | idk | |
| Heatshrink | idk | |

## Build Guide
Wire the matrix like this (you should probably use solid copper for the rows instead of diode legs like I did):

![wiring](/keebs/greg/img/wiring.jpg)

From top left to bottom right on the matrix: row pins are D10 to D15, columns are D4 to D9 on the left half and D9 to D4 on the right.

![pinout](/keebs/greg/img/pinout.png)

## Firmware
Copy [greg/](/keebs/greg/firmware/) to your zmk-config or clone [my repo.](https://github.com/tangyboi3/zmk-config)

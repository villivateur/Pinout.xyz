<!--
---
name: Ground
class: interface
type: pinout
description: Raspberry Pi Ground Pins
pincount: 1
pin:
  '6':
  '9':
  '14':
  '20':
  '25':
  '30':
  '34':
  '39':
-->
# 地线

树莓派上所有地线引脚在电路上都是连在一起的，所以如果想供电的话，无论哪一根引脚都是一样的。

通常情况下，插线的时候怎么方便怎么来，选择最靠近其他接线的地线引脚即可，或者选择最靠近供电引脚的地线。

比如，在进行 SPI 通讯时，使用物理引脚 17 和 25 进行 3v3 供电是最好不过的，因为这两个引脚最靠近 SPI0 的引脚。

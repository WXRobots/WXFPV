# WXFPV
A FPV project for BF &amp; INAV

It include 2 parts for now：
Core Board and Main Board

## Core Board

Core Board is an exchangeable part to apply different MCUs for your ESC，such as AT32F421G8U7，EFM8BB21F16I etc.
The size of this circuit board is fully compatible with mtbsk8's design.
(https://oshwhub.com/mtbsk8/ji-yu-blheli-gu-jian-de-si-he-yi-wu-shua-dian-ji-dian-diao-esc-30-5mm-ban-ben)

EFM8BB21F16I's version can use BLHeli_S firmware
AT32F421G8U7's version can use AM32 firmare

## Main Board

Main Board is an 2in1 board，it include a flight controller and a 4in1 ESC in One Board.
It is designed to allow for splitting into two pieces for use,for better flexibility,replaceability and maintainability
It can use STM32F405RGT6 or APM32F405RGT6

It is additionally designed with 2 servo PWM interfaces and 3 high-power LED interfaces，so you can connect your servo or filament(or anything you want)to it

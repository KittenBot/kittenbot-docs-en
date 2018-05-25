# The infi RGB ring

## 8字灯环硬件示意图

The infi RGB ring may also plug into the adapter board.

Here we use the same wiring scheme as ultrasonic module.

Adapter-Mainboard

- V —— 5V
- 1 —— D2
- G —— GND
- 2 —— D3

The pixel arrangement shown in the pic below

![](./images/c09_02.jpg)

## Blocks for RGB pixels

Here we have more than two pixels, and more freedom of coding. The blocks for RGB are the same as chapter 5.

![](./images/c05_02.png)

## Testing the rgb module

We make a simple blinking testing programme to loop between RGB colors. Please note that a **Black** actually means turn the RGB off.

![](./images/c09_04.png)

**Make sure you have restored the firmware before using online mode**

Then we translate it to arduino code and download.

![](./images/c09_07.png)


## The final effect

![](./images/c09_08.png)












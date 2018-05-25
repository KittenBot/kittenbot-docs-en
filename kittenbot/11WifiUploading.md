# Wifi Module

Why put the wireless connection tutorial here is that we have found may users try to use the wifi module the first time got the kit, before they can wiring correctly or drag a working code.

It could be a mass if you can't find a clue which parts go wrong, most of the time it is not the communication go fails but the origin wiring or coding is not correct.

If you got here we are confident you have already mastered the core of graphical coding and hardware wiring. Check if your robot works with a USB cable connection before putting it on air.

## The working modes of wifi module

There is two working mode of wifi module.

1. AP mode, the status **blue led** will be **always on**, and blink every 3 seconds.
2. Station mode, the status **blue led** will be **always off**, and blink every 3 seconds.

![](./images/c11_00.png)

### AP Mode

AP mode means the wifi module act as an accessing point and you may find AP node starts with **ESP_XXXXXX** and without password in default.

![](./images/c11_01.png)

### Station Mode

Station mode means that the module has joined your home/workspace router, you may find your wifi module in Kittenblock if successfully make it join your local network.

![](./images/c11_02.png)

We always recommend using wifi module in station mode, as it is more stable and may access to even more advanced functions like App, IoT, roaming etc.

## Join wifi module to your local network

There is two method to join the wifi module to your LAN, the first one to use the web page to config.

### Join LAN with the web page

Connect wifi module's access point with any device with a browser, like your laptop or mobile phone. In the browser type **http://192.168.4.1** you may find the config page below.

![](./images/c11_03.png)

Navi to **Wifi Station** page by clicking the corresponding button on the left panel.

You may find a list of access points near around. 

![](./images/c11_04.png)

If you can't find the searching list, please switch to **STA** or **AP+STA** mode.

![](./images/c11_05.png)

Check your router's tag and enter the password then click **connect**.

![](./images/c11_06.png)

Wait a while, if everything goes fine you may find your device disconnected from the wifi module. And the LED of wifi module **became off** and blick every 3 seconds.

Now open kittenblock and you may find the wifi module in your LAN.

![](./images/c11_07.png)

Most thing you do with a USB cable will work with a wifi connection.

### Join LAN with our app

You may also let the wifi module join your LAN with the help of our app. Try search **Kittenbot** in the iOS app store or google play, download and install it.

You may find a term **Join Your Home LAN** on the info page, which will start the **Smart Config** process.

![](./images/c11_08.png)

Follow the instructions in the app to complete the rest process.

## Use wifi module for online mode

After successful join your wifi module to LAN, you may connect to the robot via its network IP address.

Let's try a very basic blink code to see if the wireless communication works:

![](./images/c11_09.png)

You may also restore the firmware or upload any arduino sketch via the wifi module.

![](./images/c11_10.png)

## Notice on using wifi module

The wifi module may consume much more power than the mainboard, around 100mA to 300mA after power on. So your 6xAA battery may die very quickly, try using an external power resource or use a portable power source.

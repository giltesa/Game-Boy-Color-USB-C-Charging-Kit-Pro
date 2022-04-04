# Game Boy Color USB-C Charging Kit PRO

The **Game Boy Color USB-C Charging Kit PRO** is the new circuit for **Nintendo Game Boy Color**. This time is all in one circuit and includes not only the **charging controller** but also a **boost converter** and **audio amplifier**.

The modern **IPS displays** with background light require more energy than the stock display. Also, **the flash cards** to load tons of games consume the battery very fast. If you really want to enjoy the games, the best way to do it is using a li-ion battery instead of AA batteries.

However, that is not enough because a higher consume is forcing the original electronic to strive more than it can. That may cause noise in the speaker or headphones.

Typical solution has been adding a charging circuit for the battery and a power converter to replace the old and not efficiently one which is included in the GBC. Some people also add an audio amplifier to hear better the speaker sound. All these things make the GBC perfect, however the installation require a lot of cables and can not be easy for some people without enough knowledge.

Typical installation of the 3 modules:
![GBC](https://raw.githubusercontent.com/giltesa/Game-Boy-Color-USB-C-Charging-Kit-Pro/master/5.%20Photos/main/Sascha.jpg)
*(Thanks Sascha for the photo of his installation!)*

For resolving that, this new **Game Boy Color USB-C Charging Kit PRO** include the three circuits in one, everything wired each other, and you will just need to solder a few points to the GBC board.
![GBC](https://raw.githubusercontent.com/giltesa/Game-Boy-Color-USB-C-Charging-Kit-Pro/master/5.%20Photos/v1.0/IMG_20220306_161632.jpg)
![GBC](https://raw.githubusercontent.com/giltesa/Game-Boy-Color-USB-C-Charging-Kit-Pro/master/5.%20Photos/v1.0/2022-03-06%2017_08_10.jpg)

... in progres ...

New v1.1:

![GBC](https://raw.githubusercontent.com/giltesa/Game-Boy-Color-USB-C-Charging-Kit-Pro/master/5.%20Photos/v1.1/Game%20Boy%20Color%20USB-C%20Charging%20Kit%20PRO%20-%20top%20v1.1.jpg)
![GBC](https://raw.githubusercontent.com/giltesa/Game-Boy-Color-USB-C-Charging-Kit-Pro/master/5.%20Photos/v1.1/Game%20Boy%20Color%20USB-C%20Charging%20Kit%20PRO%20-%20bottom%20v1.1.jpg)

... in progres ...


## This board includes:

**Li-ion battery charger chip MCP73833:**

The MCP73833 is a battery charger which allows to charge a single-cell Lithium Ion or Lithium Polymer battery of 3.7/4.2v

It chargers the battery in three stages: First a preconditioning charge, then a constant-current fast charge at 1000mA and finally a constant-voltage trickle charge to keep the battery topped-up.

The board includes two status light indicators: one in red color for charging status and another one in green color when charging is complete.


**Boost Converter chip TPS61202:**

The TPS61202 is a boost converter or also called DC to DC converter. It takes the input voltage from the battery and increase it to 5V, which is the necessary voltage to make the GBC works.

It has an [efficiency between 80 to 90%](https://www.pololu.com/product/2564#lightbox-picture0J4685), which depends on the battery load and current required from the GBC (IPS screen, flash card, other addons, etc.)


**Audio Amplifier chip TPA2005D1:**

The TPA2005D1 is a high-efficient audio class D amplifier which can make your GBC speaker sound louder. It comes preconfigured to increase the volume to the double, however, soldering the jumpers SJ2 and SJ3 you can increase the volume to triple.

It can drive an 8-Ohm speaker at up to 1.4 Watts. It’s recommendable to change the [speaker](https://www.aliexpress.com/item/1005002313603099.html) for a new one if you think yours is too old.

The audio amp is going to increase any sound from the audio output, that means that if your GBC makes noise, maybe because the capacitors are old, the noise is going to sound louder too. It’s strongly recommended to change the [capacitors](https://www.aliexpress.com/item/1005002727830780.html) with new ones.


## Would you like it?

Please, let me know if you may be interested on it:
https://forms.gle/kAVVn7HgGxtpDnhy7


## More

- [giltesa.com](https://giltesa.com/en/nintendo-usb-c-charging-kit "giltesa.com")
- [twitter.com](https://twitter.com/giltesa/status/1503669454852481024 "twitter.com")


## License

This project is licensed under a **Creative Commons** license:
**[Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) ](https://creativecommons.org/licenses/by-nc-sa/4.0/)**

Check the [LICENSE.md](LICENSE.md) for more information.
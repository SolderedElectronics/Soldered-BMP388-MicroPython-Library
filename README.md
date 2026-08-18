# Soldered BMP388 MicroPython Library

| ![BMP388 Temperature and Pressure Sensor Breakout](https://soldered.com/cdn/shop/files/333316_featured-photo_82b34c.jpg?v=1785233814&width=3840) |
| :--------------------------------------------------------------------------------------------------------------------------------: |
|                       [BMP388 Temperature and Pressure Sensor Breakout](https://soldered.com/products/bmp388-temperature-and-pressure-sensor-breakout)                        |

Based on Bosch Sensortec's BMP388, this breakout delivers high-precision barometric pressure sensing (300-1250 hPa, ±8 Pa accuracy) with ultra-low power draw as low as 3.4 µA at 1 Hz. It features an I2C interface, dual Qwiic connectors for solder-free daisy-chaining, configurable oversampling, an internal IIR filter, and a 512-byte FIFO with a dedicated interrupt pin for data-ready/FIFO events. Part of the [Qwiic ecosystem](https://soldered.com/collections/qwiic-ecosystem).

## How to install

---

After [**installing the mpremote package**](https://docs.micropython.org/en/latest/reference/mpremote.html), install the library on your board using the following command:

```sh
  mpremote mip install github:SolderedElectronics/Soldered-BMP388-MicroPython-Library
```
Or, if you're running a Windows OS:

```sh
  python -m mpremote mip install github:SolderedElectronics/Soldered-BMP388-MicroPython-Library
```

### Repository Contents

- **bmp388.py** - MicroPython driver class
- **bmp388_constants.py** - register/constant definitions
- **package.json** - mip install manifest
- **/Examples** - examples for using the library

### Hardware design

You can find hardware design for this board in the BMP388 hardware repository.

### Documentation

Access library documentation [here](https://docs.soldered.com/bmp388/how-it-works/).

### About Soldered

![Soldered Logo](https://raw.githubusercontent.com/SolderedElectronics/Soldered-Generic-Arduino-Library/dev/extras/Soldered-logo-color.png)

At Soldered, we design and manufacture a wide selection of electronic products to help you turn your ideas into acts and bring you one step closer to your final project. Our products are intented for makers and crafted in-house by our experienced team in Osijek, Croatia. We believe that sharing is a crucial element for improvement and innovation, and we work hard to stay connected with all our makers regardless of their skill or experience level. Therefore, all our products are open-source. Finally, we always have your back. If you face any problem concerning either your shopping experience or your electronics project, our team will help you deal with it, offering efficient customer service and cost-free technical support anytime. Some of those might be useful for you:

- [Web Store](https://www.soldered.com/shop)
- [Tutorials & Projects](https://soldered.com/learn)
- [Documentation](https://docs.soldered.com)

### Open-source license

Soldered invests vast amounts of time into hardware & software for these products, which are all open-source. Please support future development by buying one of our products.

Check license details in the LICENSE file. Long story short, use these open-source files for any purpose you want to, as long as you apply the same open-source licence to it and disclose the original source. No warranty - all designs in this repository are distributed in the hope that they will be useful, but without any warranty. They are provided "AS IS", therefore without warranty of any kind, either expressed or implied. The entire quality and performance of what you do with the contents of this repository are your responsibility. In no event, Soldered (TAVU) will be liable for your damages, losses, including any general, special, incidental or consequential damage arising out of the use or inability to use the contents of this repository.

## Have fun!

And thank you from your fellow makers at Soldered Electronics.

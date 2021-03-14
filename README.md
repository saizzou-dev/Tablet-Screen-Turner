# Tablet Screen Turner Chuwi X10HI 

The ScreenTurner Script will Turn your Chuwi X10 Hi Screen on Linux OS Systems. This is usefull for Linux Distros which are under the Kernel 5.10! After Kernel 5.10 the Turning function should be automatically working. Still the Touch Screen is not full functionaly! 

You can also use the Scripts "horizontal.sh" and "vertical.sh" without Installing the Service function.

The Script will work when you attach or detach your Keyboard. It should be work on Bluetooth or USB Keyboards too!

## For Kernel 5.10+ Users!

Change The ScreenTurner.sh Script if you have Kernel 5.10+ on your system. Just delete the "xrandr" lines inside the Script. I will add a check Kernel function soon!

## Installation

You can install the Script as a Service which should Start on Start. The Script will copy the Shell Script into your /etc folder and also add a .service into the /usr/lib/systemd/ folder which will start all services.
```bash
chmod +x install.sh
sudo ./install.sh
```

## Usage without Installation

```bash
./horizontal.sh
./vertical.sh
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Tested On:

Kali Linux V2020.2-2021.1 \
Linux Mint 20 \
Ubuntu 20.04 LTS 

Please give a feedback if it works on other Distros too!

## My Web Site
My Web-Site for Educational Purpose [on Turkish](https://koddunyam.net/)

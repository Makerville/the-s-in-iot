# the-s-in-iot

> The S in IoT stands for security

Security on resource constrained devices is tough. Even more so when business models have not evolved, and people are not making enough money to not cut corners.

Recently, a lot is being discussed about in the context of fixing this - checklists, certifications enforced by governments and so on. It would be a cool idea to have a free (as in freedom) tool to help one build, test and develop more secure connected devices.

## Building blocks

#### Hardware

[PocketC.H.I.P. by Next Thing Co](https://github.com/NextThingCo/PocketCHIP-PCB) is an open source Linux field terminal. It comes with Bluetooth and Wi-Fi on board. The most interesting part is the exposed pin headers as shown below

![PocketC.H.I.P.](./assets/pocket-chip.png)

#### Software
- The [software that comes with the PocketC.H.I.P.](https://docs.getchip.com/pocketchip.html#license) is pretty standard too - U-Boot, mainline Linux 4.3, Debian 8. There are some parts which might not be ```such FOSS, much AWESOME```, but those could be removed easily. 
- More tbd

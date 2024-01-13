# Let's make your external display work!

_**Please confirm that the following conditions apply to you:**_
* you have a _**laptop**_
* your laptop currently running _**Linux**_
* your integrated graphics processor is an _**AMD Radeon**_
* your system is running on the _**X11**_ window server
* the latest Nvidia _**proprietary drivers**_ for your discrete graphics card are _**already installed**_

---

## Just a few steps to fix it...

1. Clone this repository:

        git clone https://github.com/NeuroSan/nvidia-linux-eDisplay-fix

2. Move config file **as root** into X11 configs directory:

        sudo mv -v nvidia-linux-eDisplay-fix/00-nvidia-edisplay-fix.conf /etc/X11/xorg.conf.d/00-nvidia-edisplay-fix.conf

4. Remove the cloned repository directory:

        rm -rv nvidia-linux-eDisplay-fix

5. Reboot:

        sudo reboot

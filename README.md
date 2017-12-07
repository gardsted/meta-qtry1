This layer depends on

    https://github.com/jumpnow/meta-rpi
    branch: rocko
    revision: HEAD
    commit: 681ed4c

And everything used by above meta-rpi

It follows the tutorial here  reasonably close, make sure to increase gpu_ram in config.txt as specified (I used 256 to be safe)

    http://www.jumpnowtek.com/rpi/Raspberry-Pi-Systems-with-Yocto.html

and uses settings from this in order to enable qtwebengine

    http://www.jumpnowtek.com/rpi/Enabling-Qt5-WebEngine-in-Yocto-Builds.html

it should leave a program to run here:

    /opt/dualbro/bin/dualbro



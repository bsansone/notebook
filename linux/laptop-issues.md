# Laptop Issues

## Unresponsive touchpad scrolling

Source: [Ubuntu bug report](https://bugs.launchpad.net/ubuntu/+source/linux/+bug/1722478/comments/16)

    sudo modprobe -r psmouse
    sudo modprobe psmouse

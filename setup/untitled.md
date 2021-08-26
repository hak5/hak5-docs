---
description: >-
  This guide teaches the basics of connecting to the WiFi Pineapple on
  Linux-based operating systems.
---

# Connecting to the WiFi Pineapple on Linux

## Configuration via GUI

To configure the WiFi Pineapple's USB Ethernet interface, you can use the NetworkManager GUI commonly included in Linux distributions.

1. Connect the WiFi Pineapple to your computer via the USB-C cable.
2. Once the device has fully booted, open your computers networking settings.
3. Find the new USB Ethernet device, and configure it to use the following IPv4 settings:
   1. IP: 172.16.42.42
   2. Netmask: 255.255.255.0
   3. Gateway: Unset, or 0.0.0.0

![](../.gitbook/assets/image%20%282%29.png)

{% hint style="info" %}
You may need to disconnect and reconnect the interface for your changes to take place.
{% endhint %}

## Configuration via CLI

To configure the WiFi Pineapple's USB Ethernet interface via the command line, you can make use of the `ip` tools commonly included in Linux distributions.

1. Connect the WiFi Pineapple to your computer via the USB-C cable.
2. Once the device has fully booted, open the Terminal emulator and run the following:

```text
$ sudo ip link set eth0 down
$ sudo ip addr add 172.16.42.42/255.255.255.0 dev eth0
$ sudo ip link set eth0 up
```




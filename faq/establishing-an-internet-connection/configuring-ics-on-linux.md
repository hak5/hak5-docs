# Configuring ICS on Linux

ICS, or **Internet Connection Sharing**, can be used to share internet from your computer to the attached WiFi Pineapple, over it's USB-C Ethernet connection.

On Linux, this is easy to accomplish with the use of the WiFi Pineapple ICS Script, referred to as **wp7.sh**. It is a shell script that will guide you through the ICS setup process.

### Getting Started

Start by opening the Terminal emulator for your Linux distribution. On Ubuntu, Gnome Terminal can be found by searching for "Terminal".

Once the Terminal is open, get the WP7.sh script, and mark it as executable with `chmod`.

![](<../../.gitbook/assets/image (36).png>)

Once you've done that, execute the script as root, with `sudo ./wp7.sh`.

![](<../../.gitbook/assets/image (34).png>)

### Guided Setup Mode

In this mode, the ICS script will try to automatically determine which interface is the WiFi Pineapple, and what your current network settings are. To do this, press **G** on your keyboard and follow the on-screen instructions.

![](<../../.gitbook/assets/image (35).png>)

Now you can press **C** to connect.

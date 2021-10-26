# Configuring ICS on Windows

On Windows, Internet Connection Sharing is achieved by using Window's "Network Sharing" feature, by sharing one internet-enabled interface to the WiFi Pineapples.

{% hint style="info" %}
The following guide is designed to work on Windows 11, although the same or similar steps apply to Windows 10/8.1/8/7 too.
{% endhint %}

### Configuring the Internet facing interface

Start by opening the **Network & Internet** settings in the Windows settings application. Scroll down to **Related settings** and click **More network adapter options**.

![](<../../.gitbook/assets/image (37).png>)

In the new window, **right-click the Internet facing adaptor, and select "Properties".** In this guide, the Internet facing adaptor is the interface named **Ethernet**.

Once you're in the properties window, select the **Sharing** tab, and then check the box to allow other users to connect. Then, **select the WiFi Pineapple adaptor** and click **OK**.

![](<../../.gitbook/assets/image (34).png>)

Next, configure the WiFi Pineapple adaptor by **right clicking and selecting "Properties".** In the new window, select the text that says **Internet Protocol Version 4 (TCP/IPv4)** and select **Properties**.

![](<../../.gitbook/assets/image (35).png>)

Finally, set the adaptors IP settings as follows:

* IP Address: **172.16.42.42**
* Subnet Mask: **255.255.0.0**
* Default Gateway: **Blank**
* Preferred DNS: **8.8.8.8**
* Alternate DNS: **8.8.4.4**

![](<../../.gitbook/assets/image (33).png>)

{% hint style="info" %}
You may set your own preferred and alternate DNS servers if desired, but Google's DNS is recommended.
{% endhint %}

After clicking **OK** to save the settings, your WiFi Pineapple will now be able to access the internet through the USB-C interface connected to your computer.

![](<../../.gitbook/assets/image (36).png>)


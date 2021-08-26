---
description: Recon is the WiFi landscape scanning tool incorporated into PineAP.
---

# Recon

## Scanning

On the main Recon page, you can see an at-a-glance overview of the current wireless landscape, with a list of discovered APs and their associated clients, unassociated clients, and clients that have gone out of range in table form.

To change to a mobile friendly view, select the card button next to the table icon in the **Access Points & Clients** card.

![](../.gitbook/assets/image%20%281%29.png)

{% hint style="info" %}
You can change Recon settings, such as scan location and displayed table columns, by selecting the Settings icon on the right side of the **Settings** card.
{% endhint %}

By clicking on an AP or Client in the list, a side menu will slide out from the right. From here you can select options specific to the type of device you selected, such as capturing handshakes or cloning, or adding MAC addresses to the Filters.

![](../.gitbook/assets/image%20%2812%29.png)

## Handshakes

Switching to the Handshakes tab allows you to view any captured handshakes. Handshakes are captured in **PCAP** and **Hashcat's 22000** format.

Handshakes that list **Recon Capture** as the source show that they were captured during a Recon scan or a Recon handshake capture. Handshakes captured from the Evil WPA AP show as **Evil WPA/2 Twin**.

![](../.gitbook/assets/image%20%2810%29.png)

{% hint style="info" %}
You can specify the Handshake save location by clicking the Settings icon.
{% endhint %}


# Port forwarding, a guide.

## Requirements

1. An unholy desire to port forward.<br>
2. Time<br>
3. Access to your router settings, and a working internet connection.<br>
4. A PC<br>

## Setting things up on your torrent client.

I'll be using [Qbittorrent](https://www.qbittorrent.org/) for this demonstration, you may follow along at home with any other client, but the instructions may vary slightly.

* Step 1: Fire up qBittorrent and open the settings(You'll find it on the top bar under Tools > Options). You should be presented with [this](https://nyaa.nothing-to-see-he.re/5DjxRu.png). There are many buttons and settings and some might not look like yours, but don't panic.

* Step 2: Navigate to the "Connections" tab, using big buttons on the [left](https://i.imgur.com/6336zjQ.png). You should see [this](https://i.imgur.com/i4R2Yqy.png). Panic not again. You only need to look at [this](https://i.imgur.com/w7Gxbu6.png) part.

* Step 3: Make sure "Enabled Protocol" is set to TCP/μTP. Uncheck "Use different ports on each startup" and check "Use UPnP/NAT Port Forwarding from my router". Next, hit the "random" buttton or enter a port number(make sure no other program is using that port).

* Step 4: Click on "Apply" at the bottom and exit the settings.

## Router setup

`WARNING: MAKE SURE TO BACKUP YOUR ROUTER SETTINGS BEFORE ATTEMPTING A PORT FORWARD.`

Follow instructions given [here](http://portforward.com/). In case you don't have the setting on your router, you may need to get a different router or upgrade your router software.

## Check

Go [here](http://www.canyouseeme.org/). The IP should be filled up. Type in the port you assigned to the torrent client in there and hit check. If you see [this](https://i.imgur.com/6GQf4wh.jpg), congratulations! You have successfully forwarded your port.

## Help! I can't forward!
Don't worry, in some ISPs, "dual-level Routers" are a thing, therefore, you will be unable to forward unless you contact your ISP. In this case, a "Port Forwarding VPN" will be a good option to invest in.

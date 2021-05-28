# How to torrent(u/V_Sharp) [CC-BY-SA]

## Requirements:-
1. Atleast 1 brain cell(essential).
2. An internet connection.
3. A device(preferably a PC) and average knowledge on how to use it.
4. Time.

## Introduction.

You might've heard of "torrents". Is that a new buzzword that kids use nowadays? What the f@&% is it? Well, your friend [REDACTED] is here to answer everything you possibly want and more!

### What is torrenting?

Chances are, if you've heard of torrenting, it'd mostly have been in a negative or not-so legal context, but let me assure you that torrents are perfectly legal. It's just a medium/method to transfer files. A tool is neither good or bad, but the purpose it is put to use for earns it a tag. The same way, torrenting is legal(no wonder clients exist) but the files transferred by it may vary. Now, coming back, torrenting is a **peer-to-peer** file transfer system, meaning that files are not served/transferred from a centralised, single server to your computer, but rather by a **decentralised** network of "peers". There are many advantages to this as you can choose what files to download, and downloads can be resumed easily. Further, you need not depend on the uptime of a server. Some disadvantages also exist such as when there are no peers(or they are offline) on a torrent, so it becomes unavailable for you to download. Obviously, the merits outweigh the demerits, and hence it's widespread popularity.

## How do torrents work and what are some "buzzwords" associated with it?

The file to be distributed is split into "pieces" and distributed to the swarm and the size of the piece depends on the file size. Each peer only uploads his/her particular piece to the rest of the swarm and simultaneously downloads other pieces from the swarm. The pieces are then assembled back into the full file. Each piece is guarded by a cryptographic ["hash"](https://en.wikipedia.org/wiki/Cryptographic_hash_function) to prevent tampering.

Further reading:-
[Wikipedia](https://en.wikipedia.org/wiki/BitTorrent). Worth a read as it's explained more in-depth here.

Please refer to the "glossary" section for the "buzzwords" and what they mean.

## Alright, enough intros. How do I torrent?

First, you go get a bittorrent client. This is basically a program that takes care of connecting and communicating with the tracker and piecing together the pieces you downloaded, so you can sit back and just monitor the progress. There are many clients available and the choice of client is entirely up to the reader. [Here](https://www.reddit.com/r/animepiracy/wiki/faq#wiki_torrent_faq)'s some recommendations.


```
WARNING!
Before you proceed to the next step, please do check your local laws about the legality of downloading copyrighted material. The author disclaims any responsibility for any legal trouble the reader may get themselves into. If you're unsure, use a VPN(Virtual Private Network) to "hide" or "mask" your IP(internet protocol) address from the authorities and also "enrypt" or "mask" the information being transferred. Always use a VPN that doesn't keep logs. For more information, refer [here](https://www.reddit.com/r/animepiracy/wiki/faq#wiki_vpn_faq). Your IP Address is visible to all the members of the swarm, and there is a possibility of your IP being logged and your Internet Service provider being sent a notice.
```


Then you find a suitable torrent tracker. There are many available, so it'd be tedious(and potentially illegal) to list all of them. Just find them on r/Piracy's [megathread](https://www.reddit.com/r/piracy/wiki/megathread). Once you find a file you like, you're probably going to have 2 options- magnet link, .torrent files. It doesn't really matter which, but if you're sensitive about bloating up your hard drive with a large number of files(a torrent file is a small file, so it will take up negligible storage), magnet links might be an option.

Copy the magnet link or download the torrent file. You should have the magnet link in your clipboard or torrent in a folder you remember. The author will be using the client [Qbittorrent](https://www.qbittorrent.org/) for demonstration, but it should be similar for other clients too.

Step 1: Open your torrent client. You should see something like [this](https://files.catbox.moe/y0m598.JPG). I have quite a few files downloaded, hence there are a lot of entries. As you can see, there's a lot of information, so let's look at it one-by-one.

The main window:- The entire central section that I've censored the name section of. This is a list of all the torrents you have downloaded.<br>
The torrent detailed information window:- The section right below the main window. It has further information such as the number of peers, pieces, availability, upload/download speed, amount uploaded, amount downloaded, number of pieces, save path and other information.<br>

Step 2: Look at the [top bar](https://files.catbox.moe/dexwsf.JPG). Depending on whether you've chosen a torrent file or a magnet link, step(s) may vary.

Magnet link:- 

>Select the first "link" icon.
You should see [this](https://files.catbox.moe/el0n6p.JPG).
>Paste your magnet link in the text box and and click "Download".

.torrent file:-

>Select the second "file" option. A file navigation window will appear, navigate to your .torrent file, select it and click "Ok".

Step 3: Regardless of which route you chose in the previous step, you should see [this](https://files.catbox.moe/vgakcw.JPG). The only relevant bit here is selecting your download location using the red highlighted button. You may also use the checkboxes to choose files to skip downloading, if the torrent has multiple files. Once that's done, you can choose "OK" to start torrent download.

Step 4: Congratulations! The torrent should now start downloading if there are peers. Click on the torrent listing in the main window to see additional information.

## What do I do after my file is done downloading?

You allow it to **seed** for a while. Seeding is the way you give back to the swarm you leech from. It's all a matter of personal preference on whether to seed and how much to seed, and thus a system called **ratio** has been introduced. Ratio is a number you obtain by dividing the amount uploaded by the amount downloaded. A ratio of 1 implies that you seeded as much as you leeched. Further, you may be seeding parallelly as you download, as you only require to possess the particular piece to upload.



## Troubleshooting:-

### My torrent doesn't start downloading or my torrent stays "stalled".

Please check the number of peers you are connected to. The number outside the bracket is the number of peers you are connected to, currently, while the one inside the brackets is the number that are available totally. If the number is 0, please wait a while, or find another source. Also check whether you're done downloading.

### My upload speed is always 0. Am I seeding?

You are available to seed, but there might be other peers with faster connections that are uploading pieces to leechers.

## Frequently Asked Questions/Additional Information.

### What is "Port Forwarding" and what does it mean to be "connectable"?

Without going into too much detail, when you connect to the internet, your computer is assigned an [IP](https://en.wikipedia.org/wiki/IP_address)(Internet Protocol) address. This IP may either be Static(meaning your IP won't change when you disconnect and re-connect, usually used by websites, and might cost money) or Dynamic(meaning your ISP(Internet Service Provider) will assign you one everytime you connect). Now, even in your LAN(Local Area Network), there is another set of IP addresses being assigned by your router. On your computer, programs which want to interact/connect with the internet have to connect through a "[port](https://en.wikipedia.org/wiki/Port_(computer_networking))". 
<br><br>
Now, what is port forwarding? It is directly assigning a port of a machine on the internal IP to one on the external "visible" IP. What are the implications? Well, it just means that it facilitates more efficient and 2-way connections between the program(in this case, your torrent client) and the swarm and tracker, so your seeding efficiency or upload speeds are enchanced. In essense, if a request is sent to the external, forwarded port, it's transferred to the internal port which was assigned. However, the ports are not forwarded by default to due some security lapses arising from certain ports being open(for example, port 23, which is assigned to Telnet, is exploitable). However, forwarding a torrent client port is safe, and can lead to better communication with the swarm, which is what it means to be "connectable". Forwarding a port is not really necessary for the average user, but is recommended for private tracker users. Guide for qbittorrent to be added [here](https://github.com/R3D4CTED/piracy-basics/blob/main/portforwarding.md) soon.

Use [this](http://portforward.com/) site for instructions on how to port forward for your router. Use [this](http://www.canyouseeme.org/) to check if the port of your torrent client is forwarded.

### What is a seedbox?

A seedbox is a service that leeches torrents for you and provides the files in a direct download format, or uploads them to a cloud drive of your choice. They also seed the torrents, and have high upload speed, so are used by Private Tracker users. Since the seedbox has a high upload speed compared to regular peers in the swarm, it is more likely to be chosen to upload pieces.

## Glossary
>Peer = Any person who is downloading or has downloaded a torrent.<br>
>Swarm = The entire set of peers.<br>
>Tracker = A server that keeps track of the swarm and what pieces each peer is assigned and facilitates the interaction of peers. It is also the site that lists torrents in a searchable manner.<br> 
>Hash = It is a randomly generated "key" to some data.<br>
>Leeching = The act of downloading a torrent.<br>
>Seeding = The act of uploading your assigned piece.<br>

# TO-DO

>Remove informal language.<br>
>Explain the rest of the tabs in the client.<br>
>~~Explain the importance of **connectability** and **port-forwarding**~~.<br>
>Add information for Advanced Users.<br>
>Add a tl;dr.<br>
~~>Explain Seedboxes.~~<br>
>"Further Reading" section.<br>
>More sources for VPN information.<br>
>Explain trackers in detail(including private and public)<br>

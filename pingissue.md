**ping 5.135.143.217**

*Pinging 5.135.143.217 with 32 bytes of data:*
*Reply from 5.135.143.217: bytes=32 time=278ms TTL=38*
*Reply from 5.135.143.217: bytes=32 time=281ms TTL=38*
*Reply from 5.135.143.217: bytes=32 time=276ms TTL=38*
*Reply from 5.135.143.217: bytes=32 time=280ms TTL=38*
*Ping statistics for 5.135.143.217:*

    *Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),*

*Approximate round trip times in milli-seconds:*

    *Minimum = 276ms, Maximum = 281ms, Average = 278ms*

#### **it used to be below 160, mostly in between 150-160 (packet loss from your side)**
nslookup 5.135.143.217

*Server:  vip6-safenet-kmd01.wlink.com.np*

*Address:  2400:1a00:0:32::165*

*Name:    ns3020544.ip-5-135-143.eu*

*Address:  5.135.143.217*

#### **(Please kindly look at your backend of your routes)**

**ping google.com**

*Pinging google.com \[2404:6800:4002:831::200e] with 32 bytes of data:*

*Reply from 2404:6800:4002:831::200e: time=25ms*

*Reply from 2404:6800:4002:831::200e: time=22ms*

*Reply from 2404:6800:4002:831::200e: time=23ms*

*Reply from 2404:6800:4002:831::200e: time=23ms*



*Ping statistics for 2404:6800:4002:831::200e:*

    *Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),*

*Approximate round trip times in milli-seconds:*

    *Minimum = 22ms, Maximum = 25ms, Average = 23ms


I also have a Linux machine and its same, use your worldlink dns to check ping yourself! : 

**vip6-safenet-kmd01.wlink.com.np**

**worldlink.com.np***


##### ***This has to be inside 15ms, basically Google has 26 servers all over the world, and when you ping it's domain, it checks your location and ping you to nearest server for better response, same logic goes for Facebook, Instagram, Netflix, and discord (discord has 4 servers in total).***


##### **While I watching Instagram reels, it only load those videos which is saved as cache, you may say to clear cache from phone, I formatted my phone today and re-tested it.**

# **AGAIN, IT'S YOUR INTERNET ISSUE.** 

# ** What is ping and how it effects?**
- Ping is simply the response time between your device and the server. For example, if you’re in Nepal and playing on a UK server, your ping might be around 150ms because of the distance and routing. In other words, Ping is the time delay between sending a signal to a server and getting a reply back.
- It’s measured in milliseconds (ms).

- Even if you have 1 Gbps speed, if your ping is 300ms, real-time activities like video calls, online gaming, or remote work will feel laggy.
## Here’s why:
- Voice Delay => You speak, but your friend hears you after 0.3–0.6 seconds. That delay makes conversations awkward.
- Video Freezes => Packets arrive late, so your video stutters while the app waits for missing frames.
- Connection Timeout => If packets take too long or get dropped, the call might briefly disconnect.
- Buffering => Streaming or video calls need a constant flow. High ping means inconsistent flow, so you see pauses even though your internet speed is fast.

# ** Why ping is not based calculated using Internet Speed? **
- Ping is latency, not bandwidth.
- Internet speed (bandwidth): how much data per second your line can carry (e.g., 1 Gbps).
- Ping (latency): how long a single packet takes to travel to the server and back.
## A real example to understand this theory in better ways:

- A wide highway (1 Gbps) can carry many cars (data) at once.
- But if the highway is long (UK server), it still takes 300ms for the first car to arrive, no matter how wide the road is.

## So, ping is determined by:
- Distance (Nepal ↔ UK is far).
- Routing (the internet path your ISP uses).
- Network congestion / packet handling on the way.

# **Difference between Internet speed and Ping**
- Ping (latency) measures how long it takes for a packet to travel from your device to the server and back. It’s mostly affected by physical distance, routing, and network congestion along the path. For example, if you connect from Nepal to a UK server, your ping might be around 150ms because of the long distance.
- Internet speed (bandwidth), like 10 Mbps or 250 Kbps, defines how much data can be transferred per second. It affects download and upload speeds, streaming quality, and how fast files load. However, bandwidth doesn’t directly change latency.


# **Why ping also effects jitter and packet loss?**
- Packet loss: Some data packets never reach the server which causes video/voice to skip or freeze.
- Jitter: Variation in packet arrival time which causes choppy (laggy) audio/video even if ping is low.
- Both are independent of speed, just like ping.



---
title: "The Myth of Untraceable Transactions Shattered: Bitcoin's Anonymity Revealed in Recent Paper"
date: 2025-01-10T01:07:31.511Z
updated: 2025-01-15T16:30:20.117Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://thmb.techidaily.com/ea5e8021512da560143621a6e45ed4b3d646d858089a4c1425190ddca7b5f2e2.png
---

## The Myth of Untraceable Transactions Shattered: Bitcoin's Anonymity Revealed in Recent Paper

![crypto-mining.jpg](https://www.zdnet.com/a/img/resize/9f8b9119a90c2a50fa28a57c841d1010cb02395e/2021/10/18/020be019-67fa-40c2-acb0-0a825ec1c582/crypto-mining.jpg?auto=webp&width=1280)

By Jiap -- Shutterstock

It has been a totem of the cryptocurrency community that the numeric addresses of Bitcoin and other wallets will protect the identity of those using them to buy and sell. 

A new paper, released this week by researchers at Baylor College of Medicine and Rice University, has shattered that presumed anonymity. Titled "Cooperation among an anonymous group, protected Bitcoin during failures of decentralization," the paper is now posted on the [researchers' server](https://aidenlab.org/bitcoin.pdf). 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best crypto credit cards Enjoy enhanced rewards and low fees with these five cryptocurrency credit cards.  Read now](https://www.zdnet.com/article/best-crypto-credit-card/)

Lead researcher Alyssa Blackburn of Baylor and Rice, along with team-mates Christoph Huber, Yossi Eliaz, Muhammad S. Shamim, David Weisz, Goutham Seshadri, Kevin Kim, Shengqi Hang, and Erez Lieberman Aiden, used a technique called "address linking" to study the Bitcoin transactions in the first two years of its existence: January of 2009 to February of 2011\. 

Their key discovery is that, in those first two years, "most Bitcoin was mined by only sixty-four agents \[…\] collectively accounting for ₿2,676,800 (PV: $84 billion)." They are referring to the process of minting new coins by solving computer challenges. 

That number -- 64 people in total -- "is 1000-fold smaller than prior estimates of the size of the early Bitcoin community (75,000)," they observe. 

Those 64 people include some notable figures that have already become legends, such as Ross Ulbricht, known by the handle Dread Pirate Roberts. Ulbricht is the founder of Silk Road, a black-market operation that used Bitcoin for illicit means -- until it was shut down by the FBI. 

"Fig 1\. Sixty-four agents mined most of the bitcoin between bitcoin's launch and when it achieved price parity with the US dollar. We exploited data leakage to construct a map of the blockchain in early 2011, in which bitcoin are arranged according to the agent that mined them."

Blackburn et al.

For Blackburn and team, the point was to study the effects of people participating in game-theoretic situations as anonymous parties. Surprisingly, they found early insiders like Ulbricht could have exploited the relative paucity of participants by undermining Bitcoin to double-spend coins, but they did not. They acted "altruistically" to maintain the integrity of the system.

That's intriguing, but a more pressing discovery is that addresses can be traced and identities can be revealed. 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best crypto hardware wallets If you're serious about keeping your cryptocurrency secure, then you need a bitcoin hardware wallet.  Read now](https://www.zdnet.com/article/best-crypto-wallet/)

To find out who was doing those early transactions, Blackburn and team had to reverse-engineer the entire premise of Bitcoin and of all crypto: anonymity. 

As outlined in [the original Bitcoin white paper](https://bitcoin.org/bitcoin.pdf) by Satoshi Nakamoto, privacy was to be preserved by two means: anonymous public key use and creating new key pairs for every transaction:

> _The traditional banking model achieves a level of privacy by limiting access to information to the parties involved and the trusted third party. The necessity to announce all transactions publicly precludes this method, but privacy can still be maintained by breaking the flow of information in another place: by keeping public keys anonymous. The public can see that someone is sending an amount to someone else, but without information linking the transaction to anyone. This is similar to the level of information released by stock exchanges, where the time and size of individual trades, the "tape", is made public, but without telling who the parties were._ 
> 
> _As an additional firewall, a new key pair should be used for each transaction to keep them from being linked to a common owner. Some linking is still unavoidable with multi-input transactions, which necessarily reveal that their inputs were owned by the same owner. The risk is that if the owner of a key is revealed, linking could reveal other transactions that belonged to the same owner._ 

Blackburn and team had to trace those key pairs to reveal early Bitcoin's transacting parties. To do so, they developed what they called a novel address-linking scheme. 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### More Crypto Coach

* [How do I buy Bitcoin? Here's how it works](https://www.zdnet.com/article/how-do-i-buy-bitcoin-the-crypto-coach-shows-you-how/)
* [How to protect your seed phrase](https://www.zdnet.com/article/crypto-coach-how-to-protect-your-seed-phrase/)
* [How to stay warm during a crypto winter](https://www.zdnet.com/article/crypto-coach-how-to-stay-warm-during-a-crypto-winter/)
* [How to set up a cold storage wallet](https://www.zdnet.com/article/crypto-coach-how-to-set-up-a-cold-storage-wallet/)
* [How to purchase crypto coins using Robinhood](https://www.zdnet.com/article/crypto-coach-how-to-purchase-crypto-coins-using-robinhood/)

The scheme finds two patterns that point to users: one is the presence of recurring bits of code, and one is duplicate addresses for certain transactions. 

As the authors write,

> _Two of these techniques exploit how the bitcoin mining software generated apparently-meaningless strings, which were used as part of bitcoin's cryptographic protections against forgery. In fact, there are extensive correlations between the apparently-meaningless strings associated with a single user. The other two techniques exploit insecure user behaviors, such as the use of multiple addresses to pay for a single transaction, that make it possible to link addresses based on transaction activity._ 

The consequence of that, they write, is that it is possible to "follow the money" to expose any identity by following a chain of relatedness in a graph of addresses, starting from a known identity:

> _These network properties have unintended privacy consequences, because they make the network much more vulnerable to deanonymization using a "follow-the-money" approach. In this approach, the identity of a target bitcoin address can be ascertained by identifying a short transaction path linking it to an address whose identity is known, and then using off-chain data sources (ranging from public data to subpoenas) to walk along the path, determining who-paid-whom to de-identify addresses until the target address is identified._

Further, they hypothesize that "many cryptocurrencies may be susceptible to follow-the-money attacks."

Blackburn told _The New York Times_'s Siobhan Roberts, "When you are encrypting private data and making it public, you cannot assume that it'll be private forever." 

As the team concludes in the report, "Drip-by-drip, information leakage erodes the once-impenetrable blocks, carving out a new landscape of socioeconomic data." 

#### More Crypto

[How do I buy Bitcoin? Here's how it works](https://www.zdnet.com/article/how-do-i-buy-bitcoin-the-crypto-coach-shows-you-how/ "How do I buy Bitcoin? Here's how it works")

[The best crypto credit cards](https://www.zdnet.com/article/best-crypto-credit-card/ "The best crypto credit cards")

[Top crypto exchanges: The ones you need to know](https://www.zdnet.com/article/best-crypto-exchange/ "Top crypto exchanges: The ones you need to know")

[Must-have cryptocurrency hardware wallets: Keep your cryptocurrency safe](https://www.zdnet.com/article/best-crypto-wallet/ "Must-have cryptocurrency hardware wallets: Keep your cryptocurrency safe")

* [How do I buy Bitcoin? Here's how it works](https://www.zdnet.com/article/how-do-i-buy-bitcoin-the-crypto-coach-shows-you-how/ "How do I buy Bitcoin? Here's how it works")
* [The best crypto credit cards](https://www.zdnet.com/article/best-crypto-credit-card/ "The best crypto credit cards")
* [Top crypto exchanges: The ones you need to know](https://www.zdnet.com/article/best-crypto-exchange/ "Top crypto exchanges: The ones you need to know")
* [Must-have cryptocurrency hardware wallets: Keep your cryptocurrency safe](https://www.zdnet.com/article/best-crypto-wallet/ "Must-have cryptocurrency hardware wallets: Keep your cryptocurrency safe")

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/new-a-primer-on-using-azures-voice-to-text-service-for-2024/"><u>[New] A Primer on Using Azure's Voice-to-Text Service for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-android-users-the-top-6-video-downloaders-for-easy-access-for-2024/"><u>[New] Android Users The Top 6 Video Downloaders for Easy Access for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-current-lighting-infrastructure/"><u>[Updated] Current Lighting Infrastructure</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-launched-visuals-review-synopsis-for-2024/"><u>[Updated] Launched Visuals Review Synopsis for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-xplits-rival-software-for-effortless-splits/"><u>2024 Approved Xplit's Rival Software for Effortless Splits</u></a></li>
<li><a href="https://fox-glue.techidaily.com/crafting-a-hit-solo-podcast-trendsetting-tips-for-2024/"><u>Crafting a Hit Solo Podcast Trendsetting Tips for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/detailed-budget-insight-the-podcast-beginning-prices/"><u>Detailed Budget Insight The Podcast Beginning Prices</u></a></li>
<li><a href="https://app-tips.techidaily.com/discover-the-top-20-most-popular-bluetooth-enabled-multiplayer-games-on-phones-and-tablets/"><u>Discover the Top 20 Most Popular Bluetooth-Enabled Multiplayer Games on Phones & Tablets</u></a></li>
<li><a href="https://app-tips.techidaily.com/discover-the-top-8-ultimate-free-fax-applications-for-your-android-device/"><u>Discover the Top 8 Ultimate Free Fax Applications for Your Android Device</u></a></li>
<li><a href="https://app-tips.techidaily.com/discover-the-ultimate-6-imovie-substitutes-for-your-android-smartphones-video-edits/"><u>Discover the Ultimate 6 iMovie Substitutes for Your Android Smartphone's Video Edits</u></a></li>
<li><a href="https://app-tips.techidaily.com/discover-the-ultimate-list-of-free-user-friendly-android-notes-applications-the-best-picks-you-need/"><u>Discover the Ultimate List of FREE, User-Friendly Android Notes Applications: The Best Picks You Need</u></a></li>
<li><a href="https://app-tips.techidaily.com/download-the-ultimate-free-audiobook-library-now-compatible-with-ios-and-android-devices/"><u>Download the Ultimate Free Audiobook Library Now - Compatible with iOS & Android Devices</u></a></li>
<li><a href="https://app-tips.techidaily.com/get-started-with-tango-step-by-step-instructions-for-downloading-video-chatting-app/"><u>Get Started With Tango - Step-by-Step Instructions For Downloading Video Chatting App</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-wondering-the-best-alternative-to-hola-on-realme-12-proplus-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>In 2024, Wondering the Best Alternative to Hola On Realme 12 Pro+ 5G? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/ranking-the-xbox-one-elite-series-2-controller-a-legacy-in-electronic-sports-equipment/"><u>Ranking the Xbox One Elite Series 2 Controller: A Legacy in Electronic Sports Equipment</u></a></li>
<li><a href="https://app-tips.techidaily.com/solving-idevice-software-challenges-tips-for-successful-ios-upgrades/"><u>Solving iDevice Software Challenges: Tips for Successful iOS Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-high-memory-consumption-in-edges-webview2/"><u>Tackling High Memory Consumption in Edge's WebView2</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-10-best-free-morning-motivators-unique-alarm-apps-for-an-easy-start/"><u>Top 10 Best FREE Morning Motivators: Unique Alarm Apps for an Easy Start</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-6-essential-iphone-apps-for-restoring-lost-contact-information/"><u>Top 6 Essential iPhone Apps for Restoring Lost Contact Information</u></a></li>
</ul></div>


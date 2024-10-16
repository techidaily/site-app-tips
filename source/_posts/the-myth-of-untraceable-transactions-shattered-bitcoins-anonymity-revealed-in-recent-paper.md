---
title: "The Myth of Untraceable Transactions Shattered: Bitcoin's Anonymity Revealed in Recent Paper"
date: 2024-10-13T20:20:16.649Z
updated: 2024-10-18T08:12:24.837Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1885932/19272" target="_top" id="1885932">
  <img src="//a.impactradius-go.com/display-ad/19272-1885932" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885932/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://on-screen-recording.techidaily.com/new-expert-tips-for-capturing-your-gaming-skills-in-obs-for-2024/"><u>[New] Expert Tips for Capturing Your Gaming Skills in OBS for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-smartest-top-10-free-image-platforms-for-endless-memories/"><u>[New] Smartest Top 10 Free Image Platforms for Endless Memories</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-from-raw-footage-to-youtube-perfection-premiere-pro-techniques/"><u>[Updated] In 2024, From Raw Footage to YouTube Perfection - Premiere Pro Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-keep-your-viewers-hooked-6-compelling-video-types/"><u>2024 Approved Keep Your Viewers Hooked 6 Compelling Video Types</u></a></li>
<li><a href="https://app-tips.techidaily.com/essential-software-picks-for-your-computer-the-ultimate-guide-to-windowsmac-tools-recommended-by-zdnet/"><u>Essential Software Picks for Your Computer: The Ultimate Guide to Windows/Mac Tools Recommended by ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/expanding-horizons-arista-introduces-advanced-cognitive-networking-in-the-middle-market-segment-insights-from-zdnet/"><u>Expanding Horizons: Arista Introduces Advanced Cognitive Networking in the Middle Market Segment - Insights From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/exploring-the-increased-demand-for-openstack-and-kata-containers-in-modern-tech-ecosystems/"><u>Exploring the Increased Demand for OpenStack and Kata Containers in Modern Tech Ecosystems</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-samsung-galaxy-a24-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Samsung Galaxy A24 FRP</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exclusive-round-up-premium-vr-tools/"><u>In 2024, Exclusive Round-Up Premium VR Tools</u></a></li>
<li><a href="https://app-tips.techidaily.com/inside-look-at-nvidias-open-sourced-gpu-drivers-demystifying-what-powers-your-graphics-performance/"><u>Inside Look at Nvidia's Open Sourced GPU Drivers – Demystifying What Powers Your Graphics Performance</u></a></li>
<li><a href="https://some-approaches.techidaily.com/is-image-stabilization-a-feature-worth-your-time-for-2024/"><u>Is Image Stabilization a Feature Worth Your Time for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/shadowed-display-tech-conundrum/"><u>Shadowed Display: Tech Conundrum</u></a></li>
<li><a href="https://app-tips.techidaily.com/streamlining-it-management-with-artificial-intelligence-red-hats-approach-to-simplifying-admin-duties/"><u>Streamlining IT Management with Artificial Intelligence: Red Hat's Approach to Simplifying Admin Duties</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-rising-popularity-how-openstack-and-kata-containers-are-gaining-traction-in-tech-circles-zdnet/"><u>The Rising Popularity: How OpenStack & Kata Containers Are Gaining Traction in Tech Circles | ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/unveiling-the-latest-features-of-macos-sonoma-your-ultimate-guide-all-tips-and-insights-from-zdnet/"><u>Unveiling the Latest Features of macOS Sonoma: Your Ultimate Guide - All Tips and Insights From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/vulnerability-detected-in-curl-utility-for-linux-systems-prompt-mitigation-measures-implemented-tech-news-blog/"><u>Vulnerability Detected in Curl Utility for Linux Systems: Prompt Mitigation Measures Implemented | Tech News Blog</u></a></li>
</ul></div>


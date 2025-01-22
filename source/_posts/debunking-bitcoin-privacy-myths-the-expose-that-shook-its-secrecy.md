---
title: "Debunking Bitcoin Privacy Myths: The Exposé That Shook Its Secrecy"
date: 2025-01-15T01:09:41.743Z
updated: 2025-01-21T22:28:21.961Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://thmb.techidaily.com/25348c47fef7e0c5d4c880e473042e01e47d5973d7a411956a452edb781f4e13.jpg
---

## Debunking Bitcoin Privacy Myths: The Exposé That Shook Its Secrecy

![crypto-mining.jpg](https://www.zdnet.com/a/img/resize/9f8b9119a90c2a50fa28a57c841d1010cb02395e/2021/10/18/020be019-67fa-40c2-acb0-0a825ec1c582/crypto-mining.jpg?auto=webp&width=1280)

By Jiap -- Shutterstock

It has been a totem of the cryptocurrency community that the numeric addresses of Bitcoin and other wallets will protect the identity of those using them to buy and sell. 

A new paper, released this week by researchers at Baylor College of Medicine and Rice University, has shattered that presumed anonymity. Titled "Cooperation among an anonymous group, protected Bitcoin during failures of decentralization," the paper is now posted on the [researchers' server](https://aidenlab.org/bitcoin.pdf). 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-techniques-for-engaging-google-meet-audiences-with-laptop-based-ppt/"><u>[New] In 2024, Techniques for Engaging Google Meet Audiences with Laptop-Based PPT</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-navigating-the-maze-of-igtv-video-downloads/"><u>[New] Navigating the Maze of IGTV Video Downloads</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-fishing-footage-frontier-top-action-cameras-for-the-sea-for-2024/"><u>[Updated] Fishing Footage Frontier Top Action Cameras for the Sea for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-optimal-windows-video-calls-4-1-picks/"><u>[Updated] In 2024, Optimal Windows Video Calls #4-#1 Picks</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-twitter-jokes-made-accessible-with-3-simple-steps-pc/"><u>[Updated] In 2024, Twitter Jokes Made Accessible with 3 Simple Steps (PC)</u></a></li>
<li><a href="https://app-tips.techidaily.com/1password-secures-massive-620m-investment-recent-financing-news-covered-by-tech-industry-leaders/"><u>1Password Secures Massive $620M Investment - Recent Financing News Covered by Tech Industry Leaders</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-reddit-threads-ever-the-10-greatest-hits/"><u>2024 Approved Top Reddit Threads Ever The 10 Greatest Hits</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-vivo-v30-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/a-beginners-guide-to-using-dashlane-unraveling-its-pricing-structure-and-features-as-explained-by-zdnet/"><u>A Beginner's Guide to Using Dashlane: Unraveling Its Pricing Structure and Features as Explained by ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/cybercriminals-exploit-fears-over-new-omicron-variant-to-target-american-academic-institutions-insights-from-zdnet/"><u>Cybercriminals Exploit Fears Over New Omicron Variant to Target American Academic Institutions - Insights From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/enhancing-password-manager-security-expert-tips-and-techniques-zdnet/"><u>Enhancing Password Manager Security: Expert Tips & Techniques [ZDNet]</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-newest-epson-wf-2540-driver-optimized-for-windows-7-to-10-users/"><u>Get the Newest Epson WF 2540 Driver: Optimized for Windows 7 to 10 Users</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-vivo-y02t-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/overcoming-user-memory-lapses-with-biometric-authentication-insights-from-zdnet/"><u>Overcoming User Memory Lapses with Biometric Authentication - Insights From ZDNet</u></a></li>
<li><a href="https://buynow-info.techidaily.com/performance-analysis-of-the-tp-link-av1300-wireless-range-enhancer-beyond-expectations/"><u>Performance Analysis of the TP-Link AV1300 Wireless Range Enhancer: Beyond Expectations?</u></a></li>
<li><a href="https://app-tips.techidaily.com/protect-your-data-avoid-these-common-mistakes-in-cloud-security-that-attract-cyber-thieves-zdnet/"><u>Protect Your Data: Avoid These Common Mistakes in Cloud Security That Attract Cyber Thieves | ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/secure-your-sensitive-information-under-20month-using-robust-encryption-techniques-insights-from-zdnet/"><u>Secure Your Sensitive Information Under $20/Month Using Robust Encryption Techniques – Insights From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-myth-of-untraceable-transactions-shattered-bitcoins-anonymity-revealed-in-recent-paper/"><u>The Myth of Untraceable Transactions Shattered: Bitcoin's Anonymity Revealed in Recent Paper</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-rated-password-security-tools-comprehensive-reviews-and-comparisons-cnet/"><u>Top Rated Password Security Tools : Comprehensive Reviews and Comparisons - CNET</u></a></li>
</ul></div>


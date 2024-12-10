---
title: Exploring the Truth Behind Crypto Anonymity – A Deep Dive Into a Groundbreaking Study
date: 2024-12-07T17:58:53.568Z
updated: 2024-12-10T03:01:40.325Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/password-manager/    https://www.zdnet.com/a/img/resize/71f609c78931c855f971472635de5478b206f083/2021/10/18/020be019-67fa-40c2-acb0-0a825ec1c582/crypto-mining.jpg?width=170&height=128&fit=crop&auto=webp
---

## Exploring the Truth Behind Crypto Anonymity – A Deep Dive Into a Groundbreaking Study

![crypto-mining.jpg](https://www.zdnet.com/a/img/resize/9f8b9119a90c2a50fa28a57c841d1010cb02395e/2021/10/18/020be019-67fa-40c2-acb0-0a825ec1c582/crypto-mining.jpg?auto=webp&width=1280)

By Jiap -- Shutterstock

It has been a totem of the cryptocurrency community that the numeric addresses of Bitcoin and other wallets will protect the identity of those using them to buy and sell. 

A new paper, released this week by researchers at Baylor College of Medicine and Rice University, has shattered that presumed anonymity. Titled "Cooperation among an anonymous group, protected Bitcoin during failures of decentralization," the paper is now posted on the [researchers' server](https://aidenlab.org/bitcoin.pdf). 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-kickstart-cinematic-craft-install-xp-movie-maker/"><u>[New] Kickstart Cinematic Craft Install XP Movie Maker</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-the-comprehensive-guide-to-9gag-for-meme-enthusiasts/"><u>[Updated] 2024 Approved The Comprehensive Guide to 9GAG for Meme Enthusiasts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-efficient-roblox-gaming-save-techniques-on-macs/"><u>2024 Approved Efficient Roblox Gaming Save Techniques on Macs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-guiding-the-gaze-leading-line-techniques-for-iphones/"><u>2024 Approved Guiding the Gaze Leading Line Techniques for iPhones</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-realme-11-pro-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Realme 11 Pro without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/capture-perfect-shots-mastering-the-art-of-zipping-inout-on-iphoneipad/"><u>Capture Perfect Shots: Mastering the Art of Zipping In/Out on iPhone/iPad</u></a></li>
<li><a href="https://app-tips.techidaily.com/comprehensive-analysis-and-critique-of-the-vizmato-application/"><u>Comprehensive Analysis & Critique of the Vizmato Application</u></a></li>
<li><a href="https://app-tips.techidaily.com/discover-the-ultimate-selection-of-free-android-chat-applications-ranked-from-1-to-10/"><u>Discover the Ultimate Selection of Free Android Chat Applications: Ranked From #1 to #10</u></a></li>
<li><a href="https://app-tips.techidaily.com/effortless-ways-to-master-boomerang-feature-across-ios-android-and-web-platforms/"><u>Effortless Ways to Master Boomerang Feature Across iOS, Android & Web Platforms</u></a></li>
<li><a href="https://app-tips.techidaily.com/enhance-road-safety-with-the-11-most-effective-apps-for-handsfree-sms-access/"><u>Enhance Road Safety with the 11 Most Effective Apps for Handsfree SMS Access</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-successfully-boot-armored-core-vi-fires-of-rubicon-without-errors/"><u>How to Successfully Boot Armored Core VI: Fires of Rubicon Without Errors?</u></a></li>
<li><a href="https://win-reviews.techidaily.com/overcoming-installation-issues-expert-tips-from-yl-computing-for-your-hardware-woes/"><u>Overcoming Installation Issues: Expert Tips From YL Computing for Your Hardware Woes</u></a></li>
<li><a href="https://extra-information.techidaily.com/shoot-the-worlds-hustle-and-bustle-iphone-tips-for-shutter-speed-blurs/"><u>Shoot the World's Hustle and Bustle IPhone Tips for Shutter Speed Blurs</u></a></li>
<li><a href="https://app-tips.techidaily.com/simple-guide-5-methods-to-securely-backup-your-iphone-applications/"><u>Simple Guide: 5 Methods to Securely Backup Your iPhone Applications</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-marketers-best-friend-20-words-that-work-wonders-for-2024/"><u>The Marketer's Best Friend - 20 Words That Work Wonders for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-ultimate-list-of-11-superior-sound-integration-tools-for-adding-music-and-voice-to-videos-across-android-ios-mac-and-pc-platforms/"><u>The Ultimate List of 11 Superior Sound Integration Tools for Adding Music & Voice to Videos Across Android, iOS, Mac & PC Platforms</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-10-biometric-lock-screen-applications-for-your-android-device/"><u>Top 10 Biometric Lock Screen Applications for Your Android Device</u></a></li>
<li><a href="https://app-tips.techidaily.com/ultimate-list-of-free-tools-create-and-share-laugh-out-loud-memes-anywhere-anytime/"><u>Ultimate List of Free Tools: Create and Share Laugh-Out-Loud Memes Anywhere, Anytime</u></a></li>
<li><a href="https://app-tips.techidaily.com/ultimate-selection-of-10-leading-music-organizers-for-all-your-platform-needs-windows-mac-iphone-and-android/"><u>Ultimate Selection of 10 Leading Music Organizers for All Your Platform Needs: Windows, Mac, iPhone & Android</u></a></li>
</ul></div>


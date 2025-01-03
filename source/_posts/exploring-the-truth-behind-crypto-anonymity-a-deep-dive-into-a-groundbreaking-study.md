---
title: Exploring the Truth Behind Crypto Anonymity – A Deep Dive Into a Groundbreaking Study
date: 2024-12-28T20:36:28.718Z
updated: 2025-01-02T19:09:49.139Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-resources.techidaily.com/new-bidding-adieu-with-elegance-sample-choices/"><u>[New] Bidding Adieu with Elegance Sample Choices</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-mastery-of-mobile-and-desktop-calendar-integration-with-zoom-for-2024/"><u>[New] Mastery of Mobile and Desktop Calendar Integration with Zoom for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-designing-effective-video-previews-for-channels/"><u>[Updated] Designing Effective Video Previews for Channels</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-selecting-superior-hdr-cameras-a-buyers-guide-for-2024/"><u>[Updated] Selecting Superior HDR Cameras A Buyer's Guide for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-revolutionizing-image-post-processing-advanced-use-of-3d-luts-in-ps/"><u>2024 Approved Revolutionizing Image Post-Processing Advanced Use of 3D LUTs in PS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-sifting-through-centuries-online-unlicensed-treasures/"><u>2024 Approved Sifting Through Centuries Online Unlicensed Treasures</u></a></li>
<li><a href="https://app-tips.techidaily.com/avoid-music-chaos-a-detailed-walkthrough-on-updatingreinstalling-itunes-while-preserving-your-library/"><u>Avoid Music Chaos: A Detailed Walkthrough on Updating/Reinstalling iTunes While Preserving Your Library</u></a></li>
<li><a href="https://app-tips.techidaily.com/complete-tutorial-on-moving-your-itunes-media-library-onto-an-external-storage-device-for-mac-and-pc-users/"><u>Complete Tutorial on Moving Your iTunes Media Library Onto an External Storage Device for Mac and PC Users</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/deciphering-the-disappearance-of-recommended-video-content-in-your-newsfeed/"><u>Deciphering the Disappearance of Recommended Video Content in Your Newsfeed</u></a></li>
<li><a href="https://app-tips.techidaily.com/1723620278966-discover-the-ideal-12-substitutes-for-itunes-navigate-windows-and-mac-alternatives-ahead-of-2024/"><u>Discover the Ideal 12 Substitutes for iTunes: Navigate Windows & Mac Alternatives Ahead of 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/download-anytime-anythnough-how-to-get-past-or-latest-itunes-versions-for-pcs-and-apple-devices-without-paying-a-dime/"><u>Download Anytime, Anythnough: How to Get Past or Latest iTunes Versions for PCs and Apple Devices Without Paying a Dime</u></a></li>
<li><a href="https://app-tips.techidaily.com/easy-steps-removing-redundant-songs-from-your-itunes-library/"><u>Easy Steps: Removing Redundant Songs From Your iTunes Library</u></a></li>
<li><a href="https://app-tips.techidaily.com/get-your-favorite-songs-and-movies-for-free-directly-from-itunes-no-cost-at-all/"><u>Get Your Favorite Songs and Movies for Free Directly From iTunes – No Cost at All</u></a></li>
<li><a href="https://some-approaches.techidaily.com/global-idc-analysis-of-leading-intelligent-document-processing-solutions-2023-2024-comprehensive-vendor-evaluation/"><u>Global IDC Analysis of Leading Intelligent Document Processing Solutions (2023-2024): Comprehensive Vendor Evaluation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-install-battleye-anti-cheat-tips-and-tricks/"><u>How To Successfully Install BattlEye Anti-Cheat: Tips & Tricks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/making-a-big-impact-with-small-size-the-cherry-kw-9200-mini-keyboard-reviewed/"><u>Making a Big Impact with Small Size: The Cherry KW 9200 Mini Keyboard Reviewed</u></a></li>
<li><a href="https://app-tips.techidaily.com/revive-your-ipad-top-3-strategies-to-restore-connectivity-with-itunes/"><u>Revive Your iPad: Top 3 Strategies to Restore Connectivity with iTunes</u></a></li>
<li><a href="https://app-tips.techidaily.com/troubleshooting-guide-effective-tips-for-when-itunes-refuses-to-start-up/"><u>Troubleshooting Guide: Effective Tips for When iTunes Refuses to Start Up</u></a></li>
<li><a href="https://app-tips.techidaily.com/troubleshooting-how-to-fix-apple-music-not-syncing-to-your-iphone-ipad-or-ipod/"><u>Troubleshooting: How to Fix Apple Music Not Syncing to Your iPhone, iPad or iPod</u></a></li>
</ul></div>


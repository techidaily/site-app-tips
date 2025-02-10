---
title: Exploring the Truth Behind Crypto Anonymity – A Deep Dive Into a Groundbreaking Study
date: 2025-02-06T16:55:36.948Z
updated: 2025-02-10T00:23:08.110Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://app-tips.techidaily.com/company-names-revolutionary-ai-for-sustainable-smart-appliances-spotlight-on-zdnet-review/"><u>[Company Name]'s Revolutionary AI for Sustainable Smart Appliances: Spotlight on ZDNET Review</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-easy-to-implement-strategies-to-stand-out-with-sound-in-pubg/"><u>[New] Easy-to-Implement Strategies to Stand Out with Sound in PUBG</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/1716491022533-new-triller-vs-tiktok-similarities-and-differences-a-complete-guide-for-2024/"><u>[New] Triller Vs. TikTok - Similarities & Differences - a Complete Guide for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-navigating-social-media-preferences-tiktok-versus-youtube-shorts/"><u>[Updated] 2024 Approved Navigating Social Media Preferences TikTok Versus YouTube Shorts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-convert-your-webcam-to-vlc-clip-for-2024/"><u>[Updated] Convert Your Webcam to VLC Clip for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-monetizing-your-content-deciphering-the-minimum-views-needed/"><u>[Updated] In 2024, Monetizing Your Content Deciphering the Minimum Views Needed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-strategies-for-effective-whiteboard-interaction-during-online-engagement-across-multiple-systems/"><u>[Updated] In 2024, Strategies for Effective Whiteboard Interaction During Online Engagement Across Multiple Systems</u></a></li>
<li><a href="https://app-tips.techidaily.com/1-manager-training-essential-before-introducing-artificial-intelligence-in-business-insights-from-zdnet/"><u>1. Manager Training Essential Before Introducing Artificial Intelligence in Business: Insights From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/ai-integration-one-third-of-marketing-crews-embrace-advanced-tech-zdnet-insights/"><u>AI Integration: One-Third of Marketing Crews Embrace Advanced Tech | ZDNet Insights</u></a></li>
<li><a href="https://win-blog.techidaily.com/banishing-the-blues-in-sea-of-thieves-no-more-crashes/"><u>Banishing the Blues in Sea of Thieves: No More Crashes</u></a></li>
<li><a href="https://app-tips.techidaily.com/beyond-ais-horizon-discover-the-accelerating-wave-of-emerging-technologies/"><u>Beyond AI's Horizon: Discover the Accelerating Wave of Emerging Technologies</u></a></li>
<li><a href="https://app-tips.techidaily.com/debunking-common-errors-in-understanding-how-to-earn-from-big-data-a-deep-dive-nextgen-business-trends/"><u>Debunking Common Errors in Understanding How to Earn From Big Data: A Deep Dive | NextGen Business Trends</u></a></li>
<li><a href="https://app-tips.techidaily.com/effective-strategies-for-technology-team-management-dive-into-your-business-foundations-expert-advice-from-zdnet/"><u>Effective Strategies for Technology Team Management: Dive Into Your Business Foundations | Expert Advice From ZDNet</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-vivo-v30-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/how-to-prove-the-value-of-generative-ai-overcoming-roi-hurdles-explained-expert-analysis-by-zdnet/"><u>How to Prove the Value of Generative AI - Overcoming ROI Hurdles Explained | Expert Analysis by ZDNET</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-xiaomi-13t-pro-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Xiaomi 13T Pro Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-patches-understanding-the-shutdown-of-windows-7-and-81-support/"><u>No More Patches: Understanding the Shutdown of Windows 7 & 8.1 Support</u></a></li>
<li><a href="https://app-tips.techidaily.com/overcoming-ai-hurdles-unlocking-significant-commercial-gains-insights-from-zdnet/"><u>Overcoming AI Hurdles: Unlocking Significant Commercial Gains - Insights From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/zdnet-exclusive-singapore-advocates-for-financial-backing-of-ai-integration-and-carbon-neutral-goals/"><u>ZDNet Exclusive: Singapore Advocates for Financial Backing of AI Integration and Carbon-Neutral Goals</u></a></li>
</ul></div>


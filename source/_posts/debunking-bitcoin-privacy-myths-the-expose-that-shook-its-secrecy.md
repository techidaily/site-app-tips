---
title: "Debunking Bitcoin Privacy Myths: The Exposé That Shook Its Secrecy"
date: 2024-10-30T16:02:49.820Z
updated: 2024-11-04T16:51:17.309Z
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
<a href="https://united.elfm.net/c/5597632/2139558/4704" target="_top" id="2139558">
  <img src="//a.impactradius-go.com/display-ad/4704-2139558" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139558/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1918679/19272" target="_top" id="1918679">
  <img src="//a.impactradius-go.com/display-ad/19272-1918679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918679/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/updated-androids-role-in-virtual-reality-content-consumption-for-2024/"><u>[Updated] Android's Role in Virtual Reality Content Consumption for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-filmora-for-windows-10-and-other-top-video-editors-recommendation/"><u>[Updated] Filmora for Windows 10 and Other Top Video Editors Recommendation</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-screenprime-pro-for-advanced-users-for-2024/"><u>[Updated] ScreenPrime Pro for Advanced Users for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-multi-screen-recording-setup/"><u>2024 Approved Multi-Screen Recording Setup</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-dynamics-of-gopros-burst-capture-capabilities/"><u>2024 Approved The Dynamics of GoPro's Burst Capture Capabilities</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ring-youtube-icons-browser-extension-command-line-and-software-trio/"><u>Capturing Youtube Icons Browser Extension, Command Line & Software Trio</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/effortless-film-and-disc-transformation-the-expertise-of-digiarty-software/"><u>Effortless Film & Disc Transformation: The Expertise of Digiarty Software</u></a></li>
<li><a href="https://app-tips.techidaily.com/emerging-trends-how-edge-computing-boosts-job-opportunities-and-growth-insights-by-zdnet/"><u>Emerging Trends: How Edge Computing Boosts Job Opportunities & Growth - Insights by ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/exploring-the-role-of-a-chief-ai-officer-pathways-to-achieve-this-executive-position/"><u>Exploring the Role of a Chief AI Officer – Pathways to Achieve This Executive Position</u></a></li>
<li><a href="https://app-tips.techidaily.com/how-enhanced-rules-accelerate-the-2-trill-cuartos-de-dolares-in-aseans-digital-economy-by-2030-analysis-on-zdnet/"><u>How Enhanced Rules Accelerate the $2 Trill Cuartos De Dólares in ASEAN's Digital Economy By 2030, Analysis on ZDNET</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-motorola-razr-40-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Motorola Razr 40 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-sensational-screens-the-top-10-tech-for-live-recordings/"><u>In 2024, Sensational Screens The Top 10 Tech for Live Recordings</u></a></li>
<li><a href="https://app-tips.techidaily.com/it-hand-held-tight-exploring-how-minimal-coding-tools-are-changing-software-development-landscapes-zdnet/"><u>IT Hand-Held Tight?: Exploring How Minimal-Coding Tools Are Changing Software Development Landscapes | ZDNET</u></a></li>
<li><a href="https://app-tips.techidaily.com/navigating-your-path-to-becoming-an-influential-c-level-executive-in-artificial-intelligence/"><u>Navigating Your Path to Becoming an Influential C-Level Executive in Artificial Intelligence.</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/select-alternative-save-area-for-mac-pics/"><u>Select Alternative Save Area for Mac Pics</u></a></li>
<li><a href="https://app-tips.techidaily.com/study-reveals-challenges-at-the-intersection-of-ai-innovation-and-agile-methodologies-insights-from-zdnet/"><u>Study Reveals Challenges at the Intersection of AI Innovation and Agile Methodologies: Insights From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/surpassing-artificial-intelligence-the-rapid-rise-of-the-next-tech-trend/"><u>Surpassing Artificial Intelligence: The Rapid Rise of the Next Tech Trend</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-future-is-cashless-how-non-monetary-transactions-are-set-to-soar-past-16t-driven-by-asian-markets-zdnet-insights/"><u>The Future Is Cashless: How Non-Monetary Transactions Are Set to Soar Past $1.6T, Driven by Asian Markets | ZDNET Insights</u></a></li>
<li><a href="https://app-tips.techidaily.com/zdnet-explores-singapores-push-towards-eco-friendly-tech-funding-artificeal-intelligence-to-combat-climate-change/"><u>ZDNet Explores Singapore’s Push Towards Eco-Friendly Tech: Funding Artificeal Intelligence to Combat Climate Change</u></a></li>
</ul></div>


---
title: "Unmasking Crypto Illusions: A Revealing Paper Challenges Bitcoin's Anonymity Claims"
date: 2024-10-16T22:46:35.489Z
updated: 2024-10-17T23:49:10.256Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4a0e802a162a5a423f94ca329819be0d261aa988bda1b4b5ab8aef4726e226b5.jpg
---

## Unmasking Crypto Illusions: A Revealing Paper Challenges Bitcoin's Anonymity Claims

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
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-elevating-engagement-strategic-use-of-youtube-titles/"><u>[Updated] 2024 Approved Elevating Engagement Strategic Use of Youtube Titles</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-your-guide-to-selecting-a-superior-virtual-reality-headset-mobility-focused-or-connection-centric/"><u>[Updated] 2024 Approved Your Guide to Selecting a Superior Virtual Reality Headset Mobility-Focused or Connection-Centric?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-foremost-apps-to-upgrade-your-gopro-creations-on-smartphones/"><u>[Updated] Foremost Apps to Upgrade Your GoPro Creations on Smartphones</u></a></li>
<li><a href="https://app-tips.techidaily.com/banking-innovation-at-risk-cio-warns-against-reliance-on-easy-prompt-tech-in-favour-of-creative-geniuses/"><u>Banking Innovation at Risk: CIO Warns Against Reliance on Easy-Prompt Tech in Favour of Creative Geniuses</u></a></li>
<li><a href="https://app-tips.techidaily.com/elevate-your-professional-edge-without-solely-focusing-on-ai-insights-for-todays-workforce/"><u>Elevate Your Professional Edge Without Solely Focusing on AI | Insights for Today's Workforce</u></a></li>
<li><a href="https://app-tips.techidaily.com/enhancing-synergy-how-ai-empowers-developers-and-business-teams-insights-from-zdnet/"><u>Enhancing Synergy: How AI Empowers Developers & Business Teams - Insights From ZDNet</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-vivo-y100i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/guida-passo-passo-al-ripristino-del-sistema-in-windows-11-come-farlo-con-facilita/"><u>Guida Passo-Passo Al Ripristino Del Sistema in Windows 11: Come Farlo Con Facilità</u></a></li>
<li><a href="https://app-tips.techidaily.com/how-emerging-companies-can-leverage-ai-models-to-capture-market-share-insights-from-zdnet/"><u>How Emerging Companies Can Leverage AI Models to Capture Market Share: Insights From ZDNet</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-why-the-lenovo-thinkpad-x12-is-a-top-choice-for-2-in-1s-and-typewriter-enthusiasts-alike/"><u>In-Depth Analysis: Why the Lenovo ThinkPad X12 Is a Top Choice for 2-In-1s and Typewriter Enthusiasts Alike</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-canon-pixma-mx922-driver-software-for-windows-pcs/"><u>Latest Canon PIXMA MX922 Driver Software for Windows PCs</u></a></li>
<li><a href="https://app-tips.techidaily.com/navigating-the-complexities-of-integrating-artificasternotext-ai-and-agile-methodologies-zdnet-reported-findings/"><u>Navigating the Complexities of Integrating Artificasternotext AI and Agile Methodologies - ZDNET Reported Findings</u></a></li>
<li><a href="https://app-tips.techidaily.com/navigating-the-rise-of-agent-ecosystems-in-artificial-intelligence-future-service-domination/"><u>Navigating the Rise of Agent Ecosystems in Artificial Intelligence: Future Service Domination</u></a></li>
<li><a href="https://app-tips.techidaily.com/prioritize-manager-training-before-ai-deployment-insights-from-zdnet/"><u>Prioritize Manager Training Before AI Deployment: Insights From ZDNet</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/profiling-success-a-step-by-step-guide-for-2024/"><u>Profiling Success A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/revolutionizing-work-how-ai-agents-forge-a-new-era-in-employment-insights-from-zdnet/"><u>Revolutionizing Work: How AI Agents Forge a New Era in Employment - Insights From ZDNet</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-successfully-address-the-error-0x8024401c-during-windows-updates-on-win10win11/"><u>Step-by-Step Solution to Successfully Address the Error 0X8024401C During Windows Updates on Win10/Win11</u></a></li>
</ul></div>


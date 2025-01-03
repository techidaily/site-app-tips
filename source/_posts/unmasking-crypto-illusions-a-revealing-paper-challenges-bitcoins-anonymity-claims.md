---
title: "Unmasking Crypto Illusions: A Revealing Paper Challenges Bitcoin's Anonymity Claims"
date: 2025-01-01T03:44:21.705Z
updated: 2025-01-03T06:07:17.942Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-from-ordinary-to-extraordinary-your-pathway-with-tiktok-templates/"><u>[New] 2024 Approved From Ordinary to Extraordinary Your Pathway with TikTok Templates</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-top-9-cross-platform-communication-apps-iphone-vs-android-comparison-for-2024/"><u>[New] Top 9 Cross-Platform Communication Apps IPhone vs Android Comparison for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-ideal-action-cameras-for-stabilized-shots/"><u>2024 Approved Ideal Action Cameras for Stabilized Shots</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unboxing-the-market-strategic-essentials/"><u>2024 Approved Unboxing the Market Strategic Essentials</u></a></li>
<li><a href="https://app-tips.techidaily.com/advanced-ai-load-management-in-new-kubernetes-version-unveiled-technews/"><u>Advanced AI Load Management in New Kubernetes Version Unveiled | TechNews</u></a></li>
<li><a href="https://app-tips.techidaily.com/how-artificeinvents-faster-software-development-cycles-and-the-complexities-behind-assessing-its-pace-as-reported-by-zdnet/"><u>How Artificeinvents Faster Software Development Cycles & The Complexities Behind Assessing Its Pace, as Reported by ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/implications-of-embracing-decentralization-and-web3-technologies-for-businesses-an-in-depth-analysis-by-zdnet/"><u>Implications of Embracing Decentralization & Web3 Technologies for Businesses - An In-Depth Analysis by ZDNET</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-gmail-password-on-samsung-galaxy-m14-5g-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Samsung Galaxy M14 5G Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-make-your-images-pop-with-backdrop-removal-techniques-in-canva/"><u>In 2024, Make Your Images Pop with Backdrop Removal Techniques in Canva</u></a></li>
<li><a href="https://app-tips.techidaily.com/increased-patent-safeguards-for-linux-systems-oin-exclusivity-intensifies-skirts-ai-coverage-zdnet/"><u>INCREASED PATENT SAFEGUARDS FOR LINUX SYSTEMS: OIN EXCLUSIVITY INTENSIFIES, SKIRTS AI COVERAGE - ZDNET</u></a></li>
<li><a href="https://technical-tips.techidaily.com/master-the-right-way-to-use-iphone-and-airpods-expert-advice-from-zdnets-latest-article/"><u>Master the Right Way to Use iPhone and AirPods: Expert Advice From ZDNet's Latest Article!</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/optimal-stabilization-tech-iphoneandroiddslr-focused-for-2024/"><u>Optimal Stabilization Tech IPhone/Android/DSLR Focused for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/organizing-chaos-a-comprehensive-guide-to-taming-linux-and-open-source-docs/"><u>Organizing Chaos: A Comprehensive Guide to Taming Linux & Open Source Docs</u></a></li>
<li><a href="https://app-tips.techidaily.com/organizing-chaos-streamlining-linux-and-open-source-docs-with-proven-solutions/"><u>Organizing Chaos: Streamlining Linux & Open Source Docs with Proven Solutions</u></a></li>
<li><a href="https://win-solutions.techidaily.com/quick-fix-overcome-discord-setup-errors-effortlessly/"><u>Quick Fix: Overcome Discord Setup Errors Effortlessly</u></a></li>
<li><a href="https://app-tips.techidaily.com/step-by-step-guide-uploading-images-from-iphone-to-windows-pc/"><u>Step-by-Step Guide: Uploading Images From iPhone to Windows PC</u></a></li>
</ul></div>


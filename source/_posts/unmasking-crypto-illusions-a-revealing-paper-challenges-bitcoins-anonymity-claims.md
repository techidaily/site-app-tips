---
title: "Unmasking Crypto Illusions: A Revealing Paper Challenges Bitcoin's Anonymity Claims"
date: 2024-12-04T20:52:33.494Z
updated: 2024-12-10T00:00:07.554Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-devising-a-personalized-tiktok-alphanumeric-marker/"><u>[Updated] 2024 Approved Devising a Personalized TikTok Alphanumeric Marker</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-from-basics-to-advanced-crafting-powerful-instagram-hashtags-for-2024/"><u>[Updated] From Basics to Advanced Crafting Powerful Instagram Hashtags for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-unlocking-the-secrets-of-snapchat-boomerang-tricks-for-2024/"><u>[Updated] Unlocking the Secrets of Snapchat Boomerang Tricks for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/1password-analysis-is-this-top-tier-password-solution-a-smart-investment-insights-from-tech-experts/"><u>1Password Analysis: Is This Top-Tier Password Solution a Smart Investment? - Insights From Tech Experts</u></a></li>
<li><a href="https://app-tips.techidaily.com/bypassing-master-passwords-with-ease-discover-how-dashlane-enables-seamless-sign-ins-according-to-zdnet-analysis/"><u>Bypassing Master Passwords with Ease: Discover How Dashlane Enables Seamless Sign-Ins, According to ZDNet Analysis</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-usage-balancing-progress-and-security/"><u>ChatGPT Usage: Balancing Progress and Security</u></a></li>
<li><a href="https://app-tips.techidaily.com/ditching-lastpass-master-managing-passwords-with-icloud-on-windows-a-complete-guide-by-zdnet/"><u>Ditching LastPass? Master Managing Passwords with iCloud on Windows - A Complete Guide by ZDNet</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-address-and-prevent-edge-browser-failures-on-windows-10/"><u>How to Address and Prevent Edge Browser Failures on Windows 10</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-on-iphone-15-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account On iPhone 15?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-6-ways-to-transfer-text-messages-from-itel-a70-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 6 Ways to Transfer Text Messages from Itel A70 to Other Android Devices | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/introducing-protons-latest-feature-a-secure-password-vault-with-advanced-end-to-end-encryption-comprehensive-review-on-zdnet/"><u>Introducing Proton's Latest Feature: A Secure Password Vault with Advanced End-to-End Encryption - Comprehensive Review on ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/mastering-security-my-experience-with-top-passwordless-password-manager-tools-the-clear-winner/"><u>Mastering Security: My Experience with Top Passwordless Password Manager Tools – The Clear Winner!</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-top-picks-the-most-advanced-mp3-tags-organizers-for-mac-users/"><u>New In 2024, Top Picks The Most Advanced MP3 Tags Organizers for Mac Users</u></a></li>
<li><a href="https://app-tips.techidaily.com/oregon-healthcare-provider-alerts-over-half-a-million-clients-about-major-security-incident-tech-news/"><u>Oregon Healthcare Provider Alerts Over Half a Million Clients About Major Security Incident - Tech News</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-sound-problems-during-your-powerpoint-show/"><u>Solving Sound Problems During Your PowerPoint Show</u></a></li>
<li><a href="https://app-tips.techidaily.com/west-virginia-hospital-data-compromised-following-phishing-scheme-insights-by-zdnet/"><u>West Virginia Hospital Data Compromised Following Phishing Scheme - Insights by ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/zerofoxs-strategic-acquisition-of-idx-and-merger-with-landf-forms-a-mega-14b-cybersecurity-giant-insights-from-zdnet/"><u>ZeroFox's Strategic Acquisition of IDX and Merger with L&F Forms a Mega $1.4B Cybersecurity Giant - Insights From ZDNet</u></a></li>
</ul></div>


---
title: ZDNet Investigates the Recent Cybersecurity Breach Exposing 30K+ Healthcare Workers' Confidential Details in Florida Database
date: 2025-02-04T01:04:40.105Z
updated: 2025-02-09T18:13:06.263Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/password-manager/    https://www.zdnet.com/a/img/resize/9682a2d409521ab988e5431f7a83b43e7f231c8f/2021/12/06/da0b5bd5-0564-4192-8a5e-e7c83e8df42e/healthcare-data-breach.jpg?width=170&height=128&fit=crop&auto=webp
---

## ZDNet Investigates the Recent Cybersecurity Breach Exposing 30K+ Healthcare Workers' Confidential Details in Florida Database

More than 30,000 US healthcare workers' personal information was recently exposed due to a non-password protected database, according to [security researcher Jeremiah Fowler](https://www.websiteplanet.com/author/jeremiah-fowler/) and a team of ethical hackers with Website Planet. 

Fowler [discovered](https://www.websiteplanet.com/blog/galeapp-leak-report/) a database run by Gale Healthcare Solutions with 170,239 exposed records that included names, emails, home addresses, photos and in some cases, Social Security Numbers as well as tax documents. 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best security key While robust passwords help you secure your valuable online accounts, hardware-based two-factor authentication takes that security to the next level.  Read now](https://www.zdnet.com/article/best-security-key/)

Gale Healthcare Solutions is a Tampa, Florida tech company that connects healthcare workers with healthcare organizations looking to hire people for certain shifts. 

Fowler said the information also included forms about certain incidents, disciplines and terminations. 

"We only reviewed a limited sampling of documents and did not review each and every file. The files were hosted on an AWS cloud server, and many of the registration documents were open and publicly accessible," Fowler told _ZDNet_. 

"The images I saw were usually of the healthcare worker's face or ID badge, but the URL contained their full name, SSN and a number consistent with an SSN. Here is an example of how the link appeared: .com/gale-registration-documents/documents/last\_name\_first\_name-LPN/-SSN-\*\*\*\*\*\*\*\*\*.jpeg. I called several individuals and validated only that these were real people and their information matched that in the files." 

Fowler explained that he didn't feel it was appropriate to ask victims for their SSN or ask them to validate the information due to the highly sensitive nature of SSNs. 

"These people have a hard enough job without a random stranger calling them and reading out their SSN to them. If the names, phone numbers, and locations of these individuals matched those who I called and validated, it is logical to assume that the number indicated as SSN would most likely be real," he added. 

"I can only speculate that someone at Gale likely assumed this would make content management easier if the link had all needed information and could be easily indexed in a readable format and not a more secure unidentifiable internal code ID structure. They also overlooked that these URL paths and file names were not secure or private. Even if the images did not contain pictures of SSN cards, an exposure in the numerical text of the image name is just as much of a privacy risk and identity threat."

Gale Healthcare Solutions initially did not respond to requests for comment, but after this story was published, it sent in a statement disputing some of what Fowler and Website Planet found. 

The company said the database was a "temporary environment created for an internal system test." 

"When the researcher notified us of a potential vulnerability in September, the environment had already been deactivated and secured. There is no evidence there was any further unauthorized access beyond the researcher or that any personal data has been, or will be, misused," the company said in a statement to _ZDNet_. 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best ethical hacking certifications Becoming a certified ethical hacker can lead to a rewarding career. Here are our recommendations for the top certifications.  Read now](https://www.zdnet.com/article/best-ethical-hacking-certification/)

"Contrary to the report findings, Social Security Numbers were not used in the file names, nor disclosed. Rather, file names featured auto-generated sequential ten-digit Unix timestamps that were used in the testing environment. Dates of birth were also not disclosed, and to our knowledge, the accounts did not contain active links to images of tax documents or other credentials."

Fowler and other ethical hackers with Website Planet search for serious data leaks by investigating open, unprotected databases that it finds randomly, never targeting specific companies.

The 170,239 records covered medical workers, nurses, and caregivers. In a report, Fowler explained that internal email addresses, usernames, and administrative passwords were stored in plain text.

Fowler and his team contacted Gale, and public access to the databases was closed the same day. The company never responded to their questions. 

During his investigation of the database, Fowler found that multiple administrative accounts used weak passwords, noting that in a sampling of 10,000 records, "Password" appeared 2,921 times.

"We could also see multiple internal Admin accounts that used very similar and easy passwords. This is the first time I have ever seen full names and a number called 'SSN' in the actual file name. In theory, the file wouldn't have to be opened to expose sensitive data because the file name alone contained what appeared to be PII (personally identifiable information)," Fowler added. 

"The Covid 19 pandemic has hit healthcare workers hard with long hours, and many are physically and emotionally exhausted. Hospitals all over the United States are suffering from a shortage of healthcare workers. Any service that allows hospitals to fill their shifts is extremely important and valuable to sick patients. Unfortunately, this incident may have exposed the data of frontline workers during an already difficult time. Healthcare workers' private information publicly available also poses a risk of unwanted harassment, intimidation, or cyberstalking." 

Fowler said it was unclear how long the database had been exposed and who else may have accessed it. Gale did not respond to requests for comment about whether they have notified any healthcare workers who may have had their sensitive information exposed. He said the company is required to notify victims as part of the Florida Information Protection Act of 2014\. 

#### Security

[The best VPN services of 2024: Expert tested](https://www.zdnet.com/article/best-vpn/ "The best VPN services of 2024: Expert tested")

[How to turn on Private DNS Mode on Android (and why you should)](https://www.zdnet.com/article/how-to-turn-on-private-dns-mode-on-android-and-why-you-should/ "How to turn on Private DNS Mode on Android (and why you should)")

[The best antivirus software and apps you can buy](https://www.zdnet.com/article/best-antivirus/ "The best antivirus software and apps you can buy")

[The best VPN routers you can buy](https://www.zdnet.com/article/best-vpn-router/ "The best VPN routers you can buy")

[How to find and remove spyware from your phone](https://www.zdnet.com/article/how-to-find-and-remove-spyware-from-your-phone/ "How to find and remove spyware from your phone")

* [The best VPN services of 2024: Expert tested](https://www.zdnet.com/article/best-vpn/ "The best VPN services of 2024: Expert tested")
* [How to turn on Private DNS Mode on Android (and why you should)](https://www.zdnet.com/article/how-to-turn-on-private-dns-mode-on-android-and-why-you-should/ "How to turn on Private DNS Mode on Android (and why you should)")
* [The best antivirus software and apps you can buy](https://www.zdnet.com/article/best-antivirus/ "The best antivirus software and apps you can buy")
* [The best VPN routers you can buy](https://www.zdnet.com/article/best-vpn-router/ "The best VPN routers you can buy")
* [How to find and remove spyware from your phone](https://www.zdnet.com/article/how-to-find-and-remove-spyware-from-your-phone/ "How to find and remove spyware from your phone")

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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevate-your-digital-footprint-crafting-compelling-shorts-thumbnails/"><u>[New] In 2024, Elevate Your Digital Footprint Crafting Compelling Shorts Thumbnails</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-kickstart-creative-video-editing-with-xp-edition/"><u>[New] In 2024, Kickstart Creative Video Editing with Xp Edition</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-advanced-techniques-for-perfecting-your-voice-with-morphvox/"><u>[Updated] Advanced Techniques for Perfecting Your Voice with MorphVOX</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-inside-the-magic-box-how-does-vr-function/"><u>[Updated] Inside the Magic Box How Does VR Function?</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/audio-offloading-for-windows-10-videos-a-budget-friendly-method/"><u>Audio Offloading for Windows 10 Videos A Budget-Friendly Method</u></a></li>
<li><a href="https://app-tips.techidaily.com/discover-the-best-alternative-messaging-apps-to-whatsapp-10-amazing-choices/"><u>Discover the Best Alternative Messaging Apps to WhatsApp – 10 Amazing Choices</u></a></li>
<li><a href="https://app-tips.techidaily.com/1723620192671-discover-the-ideal-free-pdf-modification-apps-and-online-utilities-ranked-for-you/"><u>Discover the Ideal Free PDF Modification Apps & Online Utilities – Ranked for You</u></a></li>
<li><a href="https://app-tips.techidaily.com/discover-the-ideal-free-pdf-modification-apps-and-online-utilities-ranked-for-you/"><u>Discover the Ideal Free PDF Modification Apps & Online Utilities – Ranked for You!</u></a></li>
<li><a href="https://app-tips.techidaily.com/1723620188306-download-top-20-best-free-android-games-play-the-complete-versions-with-no-cost/"><u>Download Top 20 Best Free Android Games: Play the Complete Versions with No Cost!</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/expert-review-the-power-saving-benefits-of-dual-displays-in-the-new-mobvoi-ticwatch-pro-3-with-precise-gps/"><u>Expert Review: The Power-Saving Benefits of Dual Displays in the New Mobvoi TicWatch Pro 3 with Precise GPS</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-i-fixed-persistent-microsoft-edge-issues-on-my-windows-10-system/"><u>How I Fixed Persistent Microsoft Edge Issues on My Windows 10 System</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-motorola-razr-40-ultra-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Motorola Razr 40 Ultra</u></a></li>
<li><a href="https://app-tips.techidaily.com/optimize-task-management-with-these-5-outstanding-zapier-replacements/"><u>Optimize Task Management with These 5 Outstanding Zapier Replacements</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-ultimate-list-of-top-ranking-lock-screen-enhancers-for-android-devices/"><u>The Ultimate List of Top-Ranking Lock Screen Enhancers for Android Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/1723620192928-top-5-trusted-ipad-video-player-apps-of-2024-install-now/"><u>Top 5 Trusted iPad Video Player Apps of 2024 - Install Now!</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-recommended-apps-for-seamless-mobile-hotspot-access/"><u>Top Recommended Apps for Seamless Mobile Hotspot Access</u></a></li>
</ul></div>


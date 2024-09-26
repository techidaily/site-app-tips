---
title: ZDNet Investigates the Recent Cybersecurity Breach Exposing 30K+ Healthcare Workers' Confidential Details in Florida Database
date: 2024-09-19T23:04:15.372Z
updated: 2024-09-25T23:39:36.976Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/password-manager/    https://www.zdnet.com/a/img/resize/9682a2d409521ab988e5431f7a83b43e7f231c8f/2021/12/06/da0b5bd5-0564-4192-8a5e-e7c83e8df42e/healthcare-data-breach.jpg?width=170&height=128&fit=crop&auto=webp
---

## ZDNet Investigates the Recent Cybersecurity Breach Exposing 30K+ Healthcare Workers' Confidential Details in Florida Database

More than 30,000 US healthcare workers' personal information was recently exposed due to a non-password protected database, according to [security researcher Jeremiah Fowler](https://www.websiteplanet.com/author/jeremiah-fowler/) and a team of ethical hackers with Website Planet. 

Fowler [discovered](https://www.websiteplanet.com/blog/galeapp-leak-report/) a database run by Gale Healthcare Solutions with 170,239 exposed records that included names, emails, home addresses, photos and in some cases, Social Security Numbers as well as tax documents. 

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
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-seekingnextgencamerasolutions/"><u>[New] SeekingNextGenCameraSolutions</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-a-filmmakers-must-visit-list-free-visual-effect-and-editing-websites-reviewed/"><u>[Updated] In 2024, A Filmmaker's Must-Visit List Free Visual Effect & Editing Websites Reviewed</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-overwatch-recording-made-simple-with-us-for-2024/"><u>[Updated] Overwatch Recording Made Simple with Us for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/comprehensive-eva-formerly-ex-journey-ai-chatbot-overview-essential-insights/"><u>Comprehensive EVA (Formerly Ex Journey) AI Chatbot Overview - Essential Insights</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-review-of-netgear-nighthawk-rax80-unleashing-the-power-of-wi-fi-6/"><u>Comprehensive Review of Netgear Nighthawk RAX80: Unleashing the Power of Wi-Fi 6</u></a></li>
<li><a href="https://app-tips.techidaily.com/decoding-eva-ai-a-deep-dive-into-the-transformed-ex-journey-conversational-agent/"><u>Decoding EVA AI - A Deep Dive Into the Transformed Ex Journey Conversational Agent</u></a></li>
<li><a href="https://app-tips.techidaily.com/elevenlabs-ai-voice-generation-review-with-a-look-at-other-options/"><u>ElevenLabs AI: Voice Generation Review with a Look at Other Options</u></a></li>
<li><a href="https://app-tips.techidaily.com/exploring-bing-chat-how-to-converse-using-cutting-edge-gpt-language-models-by-microsoft/"><u>Exploring Bing Chat: How to Converse Using Cutting-Edge GPT Language Models by Microsoft</u></a></li>
<li><a href="https://win-solutions.techidaily.com/get-back-on-track-with-forza-horizon-4-expert-troubleshooting-guide-for-a-smooth-launch/"><u>Get Back on Track with Forza Horizon 4: Expert Troubleshooting Guide for a Smooth Launch</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-htc-u23-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on HTC U23 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Lava Agni 2 5G? | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/navigating-through-the-best-of-ai-conversational-agents-in-depth-review-of-chatgpt/"><u>Navigating Through The Best of AI Conversational Agents: In-Depth Review Of ChatGPT</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-zte-blade-a73-5g-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on ZTE Blade A73 5G and Browser | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-download-hp-stream-driver-software-fast-and-easy-installation/"><u>Quick Download: HP Stream Driver Software - Fast & Easy Installation</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-ultimate-guide-to-advanced-chatbot-innovations-combining-gpt-tech-with-astrological-insights/"><u>The Ultimate Guide to Advanced Chatbot Innovations Combining GPT Tech with Astrological Insights</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-ultimate-walkthrough-expert-assessment-and-key-features-of-the-revolutionary-ai-chatbot-chatsoner/"><u>The Ultimate Walkthrough: Expert Assessment and Key Features of the Revolutionary AI Chatbot, Chatsoner</u></a></li>
<li><a href="https://app-tips.techidaily.com/ultimate-guide-to-choosing-a-leading-ai-companion-spotlight-on-chatgpts-excellence/"><u>Ultimate Guide to Choosing a Leading AI Companion: Spotlight on ChatGPT's Excellence</u></a></li>
<li><a href="https://app-tips.techidaily.com/unveiling-the-power-of-eva-the-ultimate-guide-to-the-former-ex-journey-ai-bot/"><u>Unveiling the Power of EVA: The Ultimate Guide to the Former Ex Journey AI Bot</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-zero-watermark-total-freedom-best-free-online-video-editors-for-2024/"><u>Updated Zero Watermark, Total Freedom Best Free Online Video Editors for 2024</u></a></li>
</ul></div>


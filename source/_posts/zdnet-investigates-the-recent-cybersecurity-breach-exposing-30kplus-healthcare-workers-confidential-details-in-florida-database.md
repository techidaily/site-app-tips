---
title: ZDNet Investigates the Recent Cybersecurity Breach Exposing 30K+ Healthcare Workers' Confidential Details in Florida Database
date: 2024-10-05T22:21:29.173Z
updated: 2024-10-11T21:50:34.658Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1896505/19272" target="_top" id="1896505">
  <img src="//a.impactradius-go.com/display-ad/19272-1896505" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896505/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-helps.techidaily.com/new-top-mac-mkv-players-compilation-for-2024/"><u>[New] Top Mac MKV Players Compilation for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-huawei-nova-y71-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Huawei Nova Y71 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/a-leap-towards-no-code-revolution-the-impactful-role-of-generative-artificial-intelligence-in-evolving-coding-paradigms-zdnet-insights/"><u>A Leap Towards 'No Code' Revolution: The Impactful Role of Generative Artificial Intelligence in Evolving Coding Paradigms | ZDNET Insights</u></a></li>
<li><a href="https://app-tips.techidaily.com/access-control-systems/"><u>Access Control Systems</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/discover-language-growth-in-international-film/"><u>Discover Language Growth in International Film</u></a></li>
<li><a href="https://win-solutions.techidaily.com/enhancing-your-gameplay-a-guide-to-addressing-the-frame-rate-slump-in-dying-light/"><u>Enhancing Your Gameplay: A Guide to Addressing the Frame Rate Slump in Dying Light</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/essential-bandicam-know-how-a-complete-review/"><u>Essential Bandicam Know-How - A Complete Review</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-innovative-techniques-unlocking-your-steam-decks-potential/"><u>Exploring Innovative Techniques: Unlocking Your Steam Deck's Potential</u></a></li>
<li><a href="https://app-tips.techidaily.com/exploring-the-fresh-updates-in-macos-sonoma-comprehensive-overview-for-tech-enthusiasts-by-zdnet/"><u>Exploring the Fresh Updates in macOS Sonoma: Comprehensive Overview for Tech Enthusiasts by ZDNet</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-vivo-y100a-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Vivo Y100A to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/integrating-task-management-adding-to-do-lists-to-your-slack-workspace-zdnet-insights/"><u>Integrating Task Management: Adding To-Do Lists to Your Slack Workspace | ZDNet Insights</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/master-the-art-of-social-media-video-capture-with-5-leaders-for-2024/"><u>Master the Art of Social Media Video Capture with 5 Leaders for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/mastering-the-transition-seamless-update-strategies-for-ubuntu-linux-users-moving-to-version-2404/"><u>Mastering the Transition: Seamless Update Strategies for Ubuntu Linux Users Moving to Version 24.04</u></a></li>
<li><a href="https://app-tips.techidaily.com/side-and-back-lobes-are-usually-undesirable-as-they-represent-radiation-in-directions-that-do-not-contribute-to-effective-communication-and-can-cause-interf86/"><u>Side and Back Lobes Are Usually Undesirable as They Represent Radiation in Directions that Do Not Contribute to Effective Communication and Can Cause Interference.</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-battle-for-dominance-in-the-web-browsing-realm-who-leads/"><u>The Battle for Dominance in the Web Browsing Realm: Who Leads?</u></a></li>
<li><a href="https://win-dash.techidaily.com/top-ranked-driver-downloads-compatible-bluetooth-drivers-for-windows-systems/"><u>Top-Ranked Driver Downloads: Compatible Bluetooth Drivers for Windows Systems</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-ranking-mac-software-a-comprehensive-guide-by-zdnet/"><u>Top-Ranking Mac Software : A Comprehensive Guide by ZDNet</u></a></li>
</ul></div>


---
title: "Database Leak Reveals Personal Data of Over 30,000 Medical Staff in Florida: An In-Depth Look by ZDNet"
date: 2024-10-01T19:00:56.270Z
updated: 2024-10-06T18:46:41.779Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6ef60ecb7cca2401b9fc5fadf824084078b845e24ce4184a0282eba3264f61a8.jpg
---

## Database Leak Reveals Personal Data of Over 30,000 Medical Staff in Florida: An In-Depth Look by ZDNet

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
<a href="https://appsumo.8odi.net/c/5597632/2151890/7443" target="_top" id="2151890">
  <img src="//a.impactradius-go.com/display-ad/7443-2151890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151890/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-professionals-choice-of-best-windows-edits-tools/"><u>[New] 2024 Approved Professionals' Choice of Best Windows Edits Tools</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-10-best-webcams-you-should-know-for-2024/"><u>[Updated] 10 Best Webcams You Should Know for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-enhancing-video-content-top-formats-on-youtube-for-2024/"><u>[Updated] Enhancing Video Content Top Formats on YouTube for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/debunking-common-errors-in-understanding-how-to-earn-from-big-data-a-deep-dive-nextgen-business-trends/"><u>Debunking Common Errors in Understanding How to Earn From Big Data: A Deep Dive | NextGen Business Trends</u></a></li>
<li><a href="https://app-tips.techidaily.com/effective-strategies-for-technology-team-management-dive-into-your-business-foundations-expert-advice-from-zdnet/"><u>Effective Strategies for Technology Team Management: Dive Into Your Business Foundations | Expert Advice From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/how-to-prove-the-value-of-generative-ai-overcoming-roi-hurdles-explained-expert-analysis-by-zdnet/"><u>How to Prove the Value of Generative AI - Overcoming ROI Hurdles Explained | Expert Analysis by ZDNET</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-mini-to-other-iphone-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 mini To Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-google-pixel-fold-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Google Pixel Fold to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-dominance-in-video-landscape-mirrorless-vs-dslr-cameras/"><u>In 2024, Dominance in Video Landscape Mirrorless vs DSLR Cameras</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-motorola-moto-g23-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Motorola Moto G23 Phone Hassle-Free</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ring-youtube-tvs-features-a-beginners-guide/"><u>Mastering YouTube TV's Features A Beginner's Guide</u></a></li>
<li><a href="https://app-tips.techidaily.com/overcoming-ai-hurdles-unlocking-significant-commercial-gains-insights-from-zdnet/"><u>Overcoming AI Hurdles: Unlocking Significant Commercial Gains - Insights From ZDNet</u></a></li>
</ul></div>


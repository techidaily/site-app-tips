---
title: "Database Leak Reveals Personal Data of Over 30,000 Medical Staff in Florida: An In-Depth Look by ZDNet"
date: 2025-01-02T07:06:51.810Z
updated: 2025-01-03T08:38:47.128Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6ef60ecb7cca2401b9fc5fadf824084078b845e24ce4184a0282eba3264f61a8.jpg
---

## Database Leak Reveals Personal Data of Over 30,000 Medical Staff in Florida: An In-Depth Look by ZDNet

More than 30,000 US healthcare workers' personal information was recently exposed due to a non-password protected database, according to [security researcher Jeremiah Fowler](https://www.websiteplanet.com/author/jeremiah-fowler/) and a team of ethical hackers with Website Planet. 

Fowler [discovered](https://www.websiteplanet.com/blog/galeapp-leak-report/) a database run by Gale Healthcare Solutions with 170,239 exposed records that included names, emails, home addresses, photos and in some cases, Social Security Numbers as well as tax documents. 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-solved-obs-full-screen-anomaly-for-2024/"><u>[New] Solved OBS Full Screen Anomaly for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-clever-circumventions-for-edgenuity-video-course-skipping/"><u>[Updated] Clever Circumventions for Edgenuity Video Course Skipping</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-how-to-combine-videos-on-iphone/"><u>2024 Approved How to Combine Videos on iPhone</u></a></li>
<li><a href="https://app-tips.techidaily.com/advancing-coding-skills-with-patience-and-productivity-unveiling-github-copilots-impact-on-software-development-zdnet/"><u>Advancing Coding Skills with Patience & Productivity: Unveiling GitHub Copilot's Impact on Software Development - ZDNet</u></a></li>
<li><a href="https://games-able.techidaily.com/controller-components-revealed-xbox-s-edition/"><u>Controller Components Revealed: Xbox S Edition</u></a></li>
<li><a href="https://app-tips.techidaily.com/discover-the-perfect-accounting-system-in-2-a-comprehensive-guide-techradar/"><u>Discover the Perfect Accounting System in 2# #: A Comprehensive Guide | TechRadar</u></a></li>
<li><a href="https://tech-hub.techidaily.com/expanding-bluetooth-coverage-on-windows-11-a-step-by-step-guide/"><u>Expanding Bluetooth Coverage on Windows 11 – A Step-by-Step Guide</u></a></li>
<li><a href="https://app-tips.techidaily.com/facing-the-sunset-of-windows-11-5-essential-steps-to-take-as-microsoft-ends-support/"><u>Facing the Sunset of Windows 11: 5 Essential Steps to Take as Microsoft Ends Support</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-mac-for-iphone-xs-max-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock on Mac For iPhone XS Max?</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-poco-x6-pro-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Poco X6 Pro</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-big-wave-of-enterprise-5g-celonas-landmark-60-million-series-c-investment-explained-by-zdnet/"><u>The 'Big Wave' Of Enterprise 5G: Celona's Landmark $60 Million Series C Investment Explained by ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-journey-towards-integrated-tech-and-enterprise-strategies-realizing-the-long-awaited-synergy-zdnet/"><u>The Journey Towards Integrated Tech and Enterprise Strategies: Realizing the Long-Awaited Synergy | ZDNET</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-5-in-demand-coding-languages-of-today-comprehensive-learning-resources/"><u>Top 5 In-Demand Coding Languages of Today: Comprehensive Learning Resources</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-tutorial-on-leveraging-googles-gemini-feature/"><u>Ultimate Tutorial on Leveraging Google's Gemini Feature</u></a></li>
<li><a href="https://app-tips.techidaily.com/why-companies-find-it-hard-to-utilize-generative-ai-unveiling-survey-results-by-deloitte-as-featured-on-zdnet/"><u>Why Companies Find It Hard to Utilize Generative AI - Unveiling Survey Results by Deloitte as Featured on ZDNet</u></a></li>
</ul></div>


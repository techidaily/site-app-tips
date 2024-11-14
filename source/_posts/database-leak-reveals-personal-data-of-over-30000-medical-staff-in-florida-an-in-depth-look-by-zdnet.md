---
title: "Database Leak Reveals Personal Data of Over 30,000 Medical Staff in Florida: An In-Depth Look by ZDNet"
date: 2024-11-09T17:06:32.443Z
updated: 2024-11-13T18:21:57.557Z
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
<a href="https://appsumo.8odi.net/c/5597632/2094476/7443" target="_top" id="2094476">
  <img src="//a.impactradius-go.com/display-ad/7443-2094476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094476/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-clips.techidaily.com/new-adding-visual-time-indicators-to-your-youtube-links/"><u>[New] Adding Visual Time Indicators to Your YouTube Links</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-7-crucial-gadgets-for-successful-metaverse-journey-for-2024/"><u>[Updated] 7 Crucial Gadgets for Successful Metaverse Journey for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/adaptive-antenna-arrays-dynamically-alter-their-radiation-patterns-in-response-to-environmental-changes-optimizing-communication-links-with-moving-targets-o76/"><u>Adaptive Antenna Arrays Dynamically Alter Their Radiation Patterns in Response to Environmental Changes, Optimizing Communication Links with Moving Targets or Fluctuating Interference Conditions.</u></a></li>
<li><a href="https://app-tips.techidaily.com/enterprise-security-at-risk-with-generative-ai-crowdstrike-cto-alerts-in-latest-analysis-for-zdnet/"><u>Enterprise Security at Risk with Generative AI, CrowdStrike CTO Alerts in Latest Analysis for ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/essential-linux-69-kernel-improvements-a-ranking-digitalreviewer/"><u>Essential Linux 6.9 Kernel Improvements: A Ranking - DigitalReviewer</u></a></li>
<li><a href="https://youtube-help.techidaily.com/harnessing-hdr-in-post-top-4-youtube-guides-with-complimentary-green-screen-effects-for-2024/"><u>Harnessing HDR in Post Top 4 YouTube Guides with Complimentary Green Screen Effects for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/install-validity-biometric-sensor-drivers-swiftly-a-user-friendly-guide-to-get-started/"><u>Install Validity Biometric Sensor Drivers Swiftly: A User-Friendly Guide to Get Started!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-chatgpt-capable-of-adapting-from-real-time-conversations/"><u>Is ChatGPT Capable of Adapting From Real-Time Conversations?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/optimizacion-del-rendimiento-visual-a-traves-de-intelligent-frame-interpolation-aumento-fps-y-transiciones-sin-esfuerzo/"><u>Optimización Del Rendimiento Visual a Través De Intelligent Frame Interpolation - Aumento FPS Y Transiciones Sin Esfuerzo</u></a></li>
<li><a href="https://video-capture.techidaily.com/step-by-step-tutorial-effortless-av1-transcoding-of-dvds-on-windows-pc/"><u>Step-by-Step Tutorial: Effortless AV1 Transcoding of DVDs on Windows PC</u></a></li>
<li><a href="https://facebook.techidaily.com/the-ups-and-downs-of-life-with-facebook/"><u>The Ups and Downs of Life with Facebook</u></a></li>
<li><a href="https://app-tips.techidaily.com/unveiling-nvidias-secret-sauce-a-deep-dive-into-gpu-driver-source-release/"><u>Unveiling Nvidia’s Secret Sauce: A Deep Dive Into GPU Driver Source Release</u></a></li>
</ul></div>


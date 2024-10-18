---
title: "Database Leak Reveals Personal Data of Over 30,000 Medical Staff in Florida: An In-Depth Look by ZDNet"
date: 2024-10-17T11:01:31.694Z
updated: 2024-10-18T05:26:27.582Z
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
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/new-cross-platform-hulu-playback-mastery-a-how-to-guide/"><u>[New] Cross-Platform Hulu Playback Mastery - A How-To Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-tips-for-overcoming-obs-screen-blackout/"><u>[New] Tips for Overcoming OBS Screen Blackout</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-boost-interaction-with-crafted-ig-story-queries/"><u>[Updated] In 2024, Boost Interaction with Crafted IG Story Queries</u></a></li>
<li><a href="https://app-tips.techidaily.com/amplifying-the-role-of-it-professionals-in-shaping-customer-satisfaction-expert-analysis-by-zdnet/"><u>Amplifying the Role of IT Professionals in Shaping Customer Satisfaction | Expert Analysis by ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/empowering-tech-departments-elevating-your-brand-through-enhanced-customer-experiences-insights-from-zdnet/"><u>Empowering Tech Departments: Elevating Your Brand Through Enhanced Customer Experiences - Insights From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/expanding-security-juniper-networks-integrates-cloud-firewall-into-sase-solutions-zdnet-insight/"><u>Expanding Security: Juniper Networks Integrates Cloud Firewall Into SASE Solutions - ZDNet Insight</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-8-solutions-to-fix-find-my-friends-location-not-available-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, 8 Solutions to Fix Find My Friends Location Not Available On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-samsung-galaxy-a14-5g-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Samsung Galaxy A14 5G</u></a></li>
<li><a href="https://app-tips.techidaily.com/nvidia-leads-with-blackwell-jensen-huang-reveals-revolutionary-chip-series-during-gtc-keynote-insights-for-tech-enthusiasts-zdnet/"><u>Nvidia Leads with Blackwell: Jensen Huang Reveals Revolutionary Chip Series During GTC Keynote - Insights for Tech Enthusiasts | ZDNet</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ps5-reviewed-unveiling-4-compelling-factors-to-purchase-sonys-latest-console/"><u>PS5 Reviewed: Unveiling 4 Compelling Factors to Purchase Sony's Latest Console</u></a></li>
<li><a href="https://app-tips.techidaily.com/revolutionizing-ux-with-xr-digital-twins-and-spatial-tech-a-comprehensive-industry-handbook-zdnet-insights/"><u>Revolutionizing UX with XR, Digital Twins & Spatial Tech: A Comprehensive Industry Handbook | ZDNet Insights</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-lasting-linguistic-legacy-of-the-english-playwright/"><u>The Lasting Linguistic Legacy of the English Playwright</u></a></li>
<li><a href="https://app-tips.techidaily.com/transforming-the-cloud-industry-key-forecasts-by-renowned-tech-cto-on-evolving-business-strategies-wired/"><u>Transforming the Cloud Industry: Key Forecasts by Renowned Tech CTO on Evolving Business Strategies - Wired</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-ai-potential-for-enhanced-windows-applications/"><u>Unveiling AI Potential for Enhanced Windows Applications</u></a></li>
<li><a href="https://app-tips.techidaily.com/unveiling-linux-65-revolutionary-updates-and-improvements-detailed-digital-trends/"><u>Unveiling Linux 6.5: Revolutionary Updates and Improvements Detailed | Digital Trends</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-get-the-right-tone-5-free-online-generators-for-any-occasion/"><u>Updated 2024 Approved Get the Right Tone 5 Free Online Generators for Any Occasion</u></a></li>
</ul></div>


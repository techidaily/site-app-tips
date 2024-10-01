---
title: "Database Leak Reveals Personal Data of Over 30,000 Medical Staff in Florida: An In-Depth Look by ZDNet"
date: 2024-09-24T19:09:04.907Z
updated: 2024-10-01T11:37:03.963Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-pinnacle-music-organizer-for-android-users/"><u>[New] 2024 Approved Pinnacle Music Organizer for Android Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-time-saving-ways-to-log-vimeo-media/"><u>[Updated] 2024 Approved Time-Saving Ways to Log Vimeo Media</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-spotlight-on-professionals-the-cutting-edge-soundtracked-photovideo-artists/"><u>[Updated] Spotlight on Professionals The Cutting-Edge, Soundtracked Photo/Video Artists</u></a></li>
<li><a href="https://app-tips.techidaily.com/1-embracing-the-edge-how-surge-in-edge-computing-devices-shapes-future-careers-techworld/"><u>1. Embracing the Edge: How Surge in Edge Computing Devices Shapes Future Careers | TechWorld</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-asus-rog-phone-7-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Asus ROG Phone 7 to iPhone | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-examination-of-the-stunningly-modern-dell-alienware-aurora-r9-gaming-machine/"><u>Comprehensive Examination of the Stunningly Modern Dell Alienware Aurora R9 Gaming Machine</u></a></li>
<li><a href="https://fox-links.techidaily.com/epic-review-and-substitute-guidance/"><u>Epic Review & Substitute Guidance</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/explore-best-speech-recognition-software-on-your-mac-for-2024/"><u>Explore Best Speech Recognition Software on Your Mac for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/how-disparities-shape-our-progress-in-real-time-technology-breakthroughs-zdnet/"><u>How Disparities Shape Our Progress in Real-Time Technology Breakthroughs | ZDNet</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-get-the-newest-sas-drivers-for-your-pc-running-on-win10-win8-or-win7/"><u>How to Get the Newest SAS Drivers for Your PC Running on Win10, Win8, or Win7</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-vivo-x-flip-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/tackling-the-accountability-gap-in-artificial-intelligence-development/"><u>Tackling the Accountability Gap in Artificial Intelligence Development</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-definitive-guide-to-ai-watermarking-solutions-revealed-on-zdnet/"><u>The Definitive Guide to AI Watermarking Solutions - Revealed on ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-future-of-work-how-ai-agents-define-the-new-era-and-transform-employment-landscape-permanently-insights-from-zdnet/"><u>The Future of Work: How AI Agents Define the New Era and Transform Employment Landscape Permanently - Insights From ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-unseen-challenge-in-conversational-ai-stanford-highlights-english-centric-flaws-in-modern-chatbots-zdnet/"><u>The Unseen Challenge in Conversational AI: Stanford Highlights English-Centric Flaws in Modern Chatbots | ZDNET</u></a></li>
<li><a href="https://app-tips.techidaily.com/transforming-work-how-ai-agents-mark-a-new-era-of-innovation-and-permanent-shifts-in-employment-landscape/"><u>Transforming Work: How AI Agents Mark a New Era of Innovation and Permanent Shifts in Employment Landscape</u></a></li>
<li><a href="https://app-tips.techidaily.com/unpacking-the-irony-of-automation-when-artificnial-intelligence-spurs-more-work-not-less-zdnet-insights/"><u>Unpacking the Irony of Automation: When Artificnial Intelligence Spurs More Work, Not Less | ZDNET Insights</u></a></li>
</ul></div>


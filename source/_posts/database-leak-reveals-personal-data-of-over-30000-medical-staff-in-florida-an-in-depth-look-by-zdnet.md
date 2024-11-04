---
title: "Database Leak Reveals Personal Data of Over 30,000 Medical Staff in Florida: An In-Depth Look by ZDNet"
date: 2024-11-02T16:57:49.656Z
updated: 2024-11-04T16:06:50.541Z
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
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-untapped-realities-of-instagram-story-watchers/"><u>[New] In 2024, Untapped Realities of Instagram Story Watchers</u></a></li>
<li><a href="https://win-answers.techidaily.com/beat-the-lag-in-black-ops-cold-war-solve-your-shader-compiling-glitches-now/"><u>Beat the Lag in Black Ops Cold War - Solve Your Shader Compiling Glitches Now</u></a></li>
<li><a href="https://vp-tips.techidaily.com/fast-track-turning-zip-into-professional-quality-srt-files/"><u>Fast Track Turning ZIP Into Professional-Quality Srt Files</u></a></li>
<li><a href="https://app-tips.techidaily.com/five-alternative-paths-for-your-still-running-windows-10-system-as-microsofts-official-support-nears-its-end/"><u>Five Alternative Paths for Your Still-Running Windows 10 System as Microsoft's Official Support Nears Its End</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-deactivate-windows-defense-features-in-windows-11-using-these-three-simple-strategies/"><u>How to Deactivate Windows Defense Features in Windows 11 Using These Three Simple Strategies</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/in-depth-assessment-of-matterports-virtual-tour-tool-insights-from-pcmag-review/"><u>In-Depth Assessment of Matterport's Virtual Tour Tool - Insights From PCMag Review</u></a></li>
<li><a href="https://app-tips.techidaily.com/mastering-windows-11-vms-expert-tips-for-optimal-configuration-wisdom-directly-from-zdnets-pros/"><u>Mastering Windows 11 VMs: Expert Tips for Optimal Configuration - Wisdom Directly From ZDNet's Pros</u></a></li>
<li><a href="https://app-tips.techidaily.com/new-microsoft-software-refresh-risks-boosting-office-stress-levels-says-zdnet-analysis/"><u>New Microsoft Software Refresh Risks Boosting Office Stress Levels, Says ZDNet Analysis</u></a></li>
<li><a href="https://app-tips.techidaily.com/overcoming-obstacles-in-ai-precision-and-reliability-for-todays-developers-expert-analysis-at-zdnet/"><u>Overcoming Obstacles in AI Precision & Reliability for Today's Developers | Expert Analysis at ZDNet</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-nokia-c12-plus-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Nokia C12 Plus? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/sdk-upgrade-alert-enhancing-facebook-video-downloader-apps-for-android/"><u>SDK Upgrade Alert Enhancing Facebook Video Downloader Apps for Android</u></a></li>
<li><a href="https://youtube-web.techidaily.com/your-roll-thriving-in-the-world-of-sluggish-youtube-content-52-chars-for-2024/"><u>Slow Your Roll Thriving in the World of Sluggish YouTube Content (52 Chars) for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-critical-need-for-clarity-in-artificer-interests-exploring-the-transparency-gap-in-ai-evolution-zdnet/"><u>The Critical Need for Clarity in Artificer Interests: Exploring the Transparency Gap in AI Evolution | ZDNET</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-purpose-of-an-artificial-earth-plane-in-antenna-systems-can-be-similar-to-that-of-natural-ground-when-it-comes-to-reflecting-radio-waves-and-improving-s78/"><u>The Purpose of an Artificial Earth Plane in Antenna Systems Can Be Similar to that of Natural Ground when It Comes to Reflecting Radio Waves and Improving Signal Quality.</u></a></li>
<li><a href="https://app-tips.techidaily.com/unlocking-the-power-of-ai-servicenows-essential-four-core-tenets-explained-boost-your-enterprise-success/"><u>Unlocking the Power of AI: ServiceNow's Essential Four Core Tenets Explained - Boost Your Enterprise Success!</u></a></li>
<li><a href="https://app-tips.techidaily.com/urgent-challenge-microsofts-window-of-opportunity-shrinks-as-they-race-against-time-on-windows-11-tech-analysis/"><u>Urgent Challenge: Microsoft's Window of Opportunity Shrinks as They Race Against Time on Windows 11 | Tech Analysis</u></a></li>
<li><a href="https://extra-resources.techidaily.com/web-based-viewer-ratio-optimization/"><u>Web-Based Viewer Ratio Optimization</u></a></li>
</ul></div>


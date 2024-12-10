---
title: ZDNet Investigates the Recent Cybersecurity Breach Exposing 30K+ Healthcare Workers' Confidential Details in Florida Database
date: 2024-12-05T02:14:43.985Z
updated: 2024-12-09T20:37:22.628Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevate-your-online-presence-audios-for-your-channel/"><u>[New] In 2024, Elevate Your Online Presence Audios for Your Channel</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-deciphering-tiktoks-pfp-code-a-thorough-analysis/"><u>[Updated] 2024 Approved Deciphering TikTok's PFP Code - A Thorough Analysis</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-mastering-photo-background-removal-techniques-for-2024/"><u>[Updated] Mastering Photo Background Removal Techniques for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-mastering-handheld-shots-no-tripod-necessary/"><u>2024 Approved Mastering Handheld Shots No Tripod Necessary</u></a></li>
<li><a href="https://some-guidance.techidaily.com/5lit5lia5lq65aor6ycj55so55qe5pya5l2z5ywn6ls555s15a2q5b2x5yop57yw6l6r5zmo77ym5oplusq6auy6keg6akr5ase55cg5pwi546h/"><u>专业人士选用的最佳免费电子影像编辑器，提高视频处理效率</u></a></li>
<li><a href="https://app-tips.techidaily.com/guide-to-eliminating-the-icloud-security-code-without-using-your-apple-id/"><u>Guide to Eliminating the iCloud Security Code Without Using Your Apple ID</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Samsung Galaxy A24? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-add-filters-and-music-on-windows-11-photos-app/"><u>In 2024, How to Add Filters and Music on Windows 11 Photos App</u></a></li>
<li><a href="https://app-tips.techidaily.com/1723620263951-locked-out-of-your-icloud-account-try-our-top-6-secrets-for-regaining-access/"><u>Locked Out of Your iCloud Account? Try Our Top ✨6 Secrets✨ for Regaining Access!</u></a></li>
<li><a href="https://app-tips.techidaily.com/navigating-ios-photography-tips-on-managing-camera-roll-photo-library-and-pictures/"><u>Navigating iOS Photography: Tips on Managing Camera Roll, Photo Library, and Pictures</u></a></li>
<li><a href="https://vp-tips.techidaily.com/paso-a-paso-para-usar-winx-dvd-ripper-platinum-un-tutorial-completo-sobre-como-copiar-y-extraer-videos-de-dvd-protegidos/"><u>Paso a Paso Para Usar WinX DVD Ripper Platinum – Un Tutorial Completo Sobre Cómo Copiar Y Extraer Vídeos De DVD Protegidos</u></a></li>
<li><a href="https://app-tips.techidaily.com/retrieve-deleted-items-from-your-icloud-a-comprehensive-guide-to-icloud-file-restoration/"><u>Retrieve Deleted Items From Your iCloud: A Comprehensive Guide to iCloud File Restoration</u></a></li>
<li><a href="https://app-tips.techidaily.com/reviving-your-ipad-from-an-icloud-backup-complete-instructions-including-non-reset-options/"><u>Reviving Your iPad From an iCloud Backup: Complete Instructions Including Non-Reset Options</u></a></li>
<li><a href="https://app-tips.techidaily.com/seamless-iphone-photo-syncing-strategies-with-icloud-discover-these-4-effective-techniques/"><u>Seamless iPhone Photo Syncing Strategies with iCloud - Discover These 4 Effective Techniques</u></a></li>
<li><a href="https://app-tips.techidaily.com/step-by-step-guide-removing-your-pics-photos-and-images-from-icloud-securely/"><u>Step-by-Step Guide: Removing Your Pics, Photos & Images From iCloud Securely</u></a></li>
<li><a href="https://app-tips.techidaily.com/step-by-step-tutorial-viewing-icloud-saved-passwords-on-ios-devices-and-computers/"><u>Step-by-Step Tutorial: Viewing iCloud Saved Passwords on iOS Devices & Computers</u></a></li>
<li><a href="https://printer-issues.techidaily.com/step-by-step-incorporating-hp-printer-in-pc-network/"><u>Step-by-Step: Incorporating HP Printer in PC Network</u></a></li>
</ul></div>


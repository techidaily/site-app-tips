---
title: Urgent Security Flaw Exposed in Linux's Essential Curl Utility, with Immediate Patch Available | Report by ZDNET
date: 2024-09-29T17:27:33.637Z
updated: 2024-10-06T17:44:08.569Z
tags:
  - enterprise-software
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/2066f4ff42cc6e40848df9ef9bd42bfd06aced18/2023/10/11/778ec254-7053-4e22-960b-4837bc5200f7/gettyimages-1474277379.jpg?width=278&height=156&fit=crop&auto=webp
---

## Urgent: Microsoft Faces Critical Challenge with Windows 11 - Just One Year Left![ZDNet Exclusive]

![windows 10 on a laptop](https://www.zdnet.com/a/img/resize/5b619d0e1ad976d7312257869ef26bc7a57772ce/2024/09/04/2fb7bd5c-1bbb-4042-8e53-ae01a38c8443/gettyimages-491551172.jpg?auto=webp&width=1280)

John Taggart/Bloomberg via Getty Images

Windows 10 is about to expire.

In just over one year, Microsoft's most successful operating system release ever will reach its end-of-support date. Like [Monty Python's Norwegian Blue](https://genius.com/Monty-python-dead-parrot-sketch-annotated), it will be pushing up the daisies. It will have shuffled off its mortal coil, run down the curtain, and joined the bleedin' choir invisible!

**Also: [How to upgrade your 'incompatible' Windows 10 PC to Windows 11](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/)**

How is this even possible? It feels like only yesterday, but in fact, Windows 10 was officially released to the public more than nine years ago, in July 2015\. Following on the heels of the ill-fated Windows 8, it became an unqualified success among consumers and business customers alike.

That's good news, right? Well, not exactly.

Microsoft has a big challenge on its hands in the runup to that end-of-support date: convincing its enormous installed base to leave their beloved Windows 10 behind and make the move to its successor operating system, Windows 11.

I wrote the original version of this post in July 2023\. Now, as that end date draws uncomfortably closer, I decided to revisit the topic and answer some burning questions.

## When does Windows 10 support end, and what does that mean for Windows 10 users?

Like every version of Windows in the modern era, Windows 10 adheres to a 10-year support lifecycle. That means that most Windows 10 editions -- Home, Pro, Pro Workstation, Enterprise, and Education -- reach their end-of support date on October 14, 2025\. (For the nerdy details on how that date is calculated, see ["When will Microsoft end support for your version of Windows or Office?"](https://www.zdnet.com/article/when-will-microsoft-pull-the-plug-on-your-version-of-windows-or-office/))

So, what happens when that day arrives? Nothing. Seriously, absolutely nothing happens on that date. PCs running Windows 10 continue to work just as they always have, and they will do so indefinitely. 

**Also: [Still have a Windows 10 PC? You have 5 options before support ends next year](https://www.zdnet.com/article/still-have-a-windows-10-pc-you-have-5-options-before-support-ends-next-year/)**

From that date forward, however, those PCs will no longer receive security fixes through Windows Update unless their owners [pay Microsoft for an Extended Security Updates (ESU) subscription](https://www.zdnet.com/article/want-to-keep-getting-windows-10-updates-next-year-heres-what-it-will-cost/). On Windows 10 PCs without an ESU subscription, however, any security flaws found from that day forward will remain unpatched, making those PCs increasingly vulnerable to online attacks.

There is at least one exception to this cutoff date, which applies to PCs running Windows 10 Enterprise Long Term Servicing editions. In all, Microsoft has released four of these editions. The 2015 Long Term Servicing Branch (LTSB) ends support on October 14, 2025, along with the editions described earlier. The 2016 LTSB release ends support a year later, on October 13, 2026\. Beginning in 2019, the name changed to Long Term Servicing Channel (LTSC). For Windows 10 Enterprise LTSC 2019, the end date is January 9, 2029\. 

Confusingly, Windows 10 Enterprise LTSC 2021 has only a five-year support lifecycle, which means it ends support on January 12, 2027.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How many PCs are running Windows 10 today?

If anyone tells you they know the answer to this one, maybe stop listening to them?

Microsoft can probably make a solid estimate based on its telemetry, but the rest of us are forced to guess based on fragmentary third-party metrics.

**Also: [How to install Windows 11 the way you want (and sneak by Microsoft's restrictions)](https://www.zdnet.com/article/how-to-install-windows-11-the-way-you-want-and-sneak-by-microsofts-restrictions/)**

One of the sources I have relied on over the years is the United States Government's [Digital Analytics Program (DAP)](https://analytics.usa.gov/), which has a well-organized repository of information about traffic to official websites run by agencies like the Postal Service, the National Institutes of Health, the National Weather Service, the IRS, and NASA.

When I visited DAP last week, I retrieved data for the 30 days ending August 31, 2024, summarizing more than 1.6 billion visits to those websites from people using computers and mobile devices from all around the world. Here's what the data told me about the visits from PCs and Macs:

Windows 11 is still having trouble overtaking Windows 10\. Microsoft's compatibility requirements aren't helping. 

DAP/ZDNET

That's an improvement over the numbers I found last year, which were unable to distinguish between visits from Windows 10 and Windows 11\. One bit of good news is that other versions of Windows represent a trivial share of visits, being outnumbered by every alternative desktop platform, including [ChromeOS](https://www.zdnet.com/article/5-things-chrome-os-needs-to-rival-macos/).

But if you extrapolate those numbers to the worldwide population of Windows PCs, you can see the problem. According to those numbers, roughly 60% of Windows PCs are still running Windows 10, which adds up to more than 700 million PCs that will be running an outdated, unsupported operating system a year from now. Yikes.

**Also: [Why 'debloating' Windows is a bad idea (and what to do instead)](https://www.zdnet.com/article/why-debloating-windows-is-a-bad-idea-and-what-to-do-instead/)**

For people who are concerned about the security of the internet at large, that thought is ... well, let's call it _unnerving_.

Another widely used measure of web traffic, StatCounter, offers its own estimates of traffic from PCs running Microsoft Windows. Here's its graph of [web traffic from Windows PCs](https://gs.statcounter.com/os-version-market-share/windows/desktop/worldwide) in their network over the past year.

The top line is Windows 10\. The slowly climbing line far below it is Windows 11.

Stat Counter/ZDNET

That purple line at the top of the chart is Windows 10, and the blue line far below it is Windows 11\. Now, I have my issues with StatCounter's metrics, a topic [I have not been shy about discussing](https://www.zdnet.com/article/net-market-share-vs-statcounter-whose-online-measurements-can-you-trust/) over the years. But I think the broad strokes of this data are probably accurate. 

The current installed base of Windows PCs consists of about twice as many PCs running Windows 10 compared to its successor. (That's an improvement over last year's number, at least, where the ratio was more than three to one.)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123511/26400" target="_top" id="2123511">
  <img src="//a.impactradius-go.com/display-ad/26400-2123511" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123511/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How many PCs will still be running Windows 10 at the end of 2025?

That's the real question, isn't it?

Despite predictions of the imminent demise of the PC market, OEMs continue to sell more than 200 million new Windows computers each year. The most optimistic scenario is that every one of those new PCs sold in the next year replaces a Windows 10 device that is then retired, with another 100 million or so older PCs replaced by Chromebooks, iPads, and Macs. Maybe some old PCs are simply put out to pasture and not replaced at all, as consumers decide to use their phones or tablets instead.

**Also:** [**The best computers: Comparing laptops, Macs, PCs and more**](https://www.zdnet.com/article/best-computer/)

That best-case scenario still leaves hundreds of millions of people running Windows 10 when the October 2025 end-of-support date rolls around. Who owns those PCs?

* **Those who don't qualify for an automatic upgrade.** Some people own older hardware that doesn't meet the minimum hardware compatibility standards for Windows 11\. Basically, that means any PC that was designed in 2018 or earlier. Note that this category includes many budget PCs that used older designs and unsupported CPUs but were sold as new in 2019 and 2020.
* **Corporate PCs that are standardized on Windows 10.** A nontrivial number of enterprise IT managers have just finished their Windows 10 migrations in the last year or two and probably aren't anxious to do it again.
* **Windows 10 diehards.** From my time spent reading support forums, I know there's a large population of longtime Windows users who are unhappy about the changes in Windows 11\. Some of them will reluctantly upgrade, but others won't.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Will Microsoft extend the support deadline for Windows 10?

That's certainly a possibility, and there's precedent for it in the experience of Windows XP, which ended support in April 2014, more than 12 years after it was first released. Windows XP users even received emergency security updates well after that official end date, to address the [WannaCry vulnerability](https://www.zdnet.com/article/why-wannacry-ransomware-is-still-a-threat-to-your-pc/) in 2017 and a similar flaw in 2019\. Likewise, Microsoft [issued emergency security updates for Windows 7 in 2021](https://www.zdnet.com/article/install-immediately-microsoft-delivers-emergency-patch-for-printnightmare-security-bug/) after its support had officially ended.

**Also: [For Windows 11 setup, which user account type should you choose? How to decide](https://www.zdnet.com/article/for-windows-11-setup-which-user-account-type-should-you-choose-how-to-decide/)**

But it's more likely that Microsoft will tell Windows 10 holdouts to pay for Extended Security Updates rather than giving them away for free.

Of course, in both cases, the customers running the soon-to-be-obsolete Windows version had the option to upgrade to a new version. Indeed, that's the recommendation from Microsoft's [official Product End of Support page](https://learn.microsoft.com/en-us/lifecycle/overview/product-end-of-support-overview):

> Once a product reaches the end of support, or a service retires, there will be no new security updates, non-security updates, or assisted support. Customers are encouraged to migrate to the latest version of the product or service.

For Windows 10, though, that alternative might not be available. Devices that don't meet the hardware compatibility requirements will have no Microsoft-supported migration path to a newer version. As I pointed out [the last time I looked at this issue](https://www.zdnet.com/article/still-have-a-windows-10-pc-you-have-5-options-before-support-ends-next-year/), the owners of those perfectly functional PCs, some only five or six years old, will instead have the following options:

* **Install a non-Microsoft operating system.** Maybe 2026 will be the year when desktop [Linux finally takes hold](https://www.zdnet.com/article/5-reasons-why-linux-will-eventually-overtake-windows-and-macos-on-the-desktop/), although that's unlikely. [ChromeOS Flex](https://www.zdnet.com/article/installing-chromeos-flex-5-things-you-need-to-do-first-to-avoid-headaches/) might be another option, but it has its own [hardware compatibility requirements](https://support.google.com/chromeosflex/answer/11513094?sjid=1307842147959197296-NA#zippy=,apple,microsoft) that probably make it unsuitable for older hardware.
* **Ignore Microsoft's warnings and upgrade to Windows 11 anyway.** There are options to [install Windows 11 on "incompatible" hardware](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/), but they require a fair amount of technical experience. People who are clinging to old PCs because they can't afford a new one likely don't have those specialized skills and may not even realize that the option is available. I doubt that many businesses would be willing to risk the support issues that come with that approach.
* **Keep running Windows 10 and hope for the best.** History suggests that this is the most likely option.

Microsoft and its OEM partners would prefer that the owners of those devices dump them in a landfill and buy a new PC running Windows 11\. However, my experience with PC owners, especially older people on a fixed income, is that they will use those devices until they stop working. Those PCs will be sitting ducks for a cyberattack like [WannaCry](https://www.zdnet.com/article/wannacry-ransomware-crisis-one-year-on-are-we-ready-for-the-next-global-cyber-attack/), which was brutally effective against the large population of Windows 7 PCs that were still in use three years after its support ended.

**Also: [This secret Windows 11 setting lets you kill unresponsive apps much faster](https://www.zdnet.com/article/this-secret-windows-11-setting-lets-you-kill-unresponsive-apps-much-faster/)**

That incident was a PR nightmare for Microsoft, and a repeat would be even more devastating to the company's reputation. That's why Microsoft has offered paid options to extend support for Windows 10 by three years. Customers in enterprise and education deployments are likely to take advantage of those options.

Consumers, though, will apparently be on their own.

_This article was originally published in July 2023\. The most recent update was in September 2024._

#### Windows

[How to install Windows 11 the way you want (and sneak by Microsoft's restrictions)](https://www.zdnet.com/article/how-to-install-windows-11-the-way-you-want-and-bypass-microsofts-restrictions/ "How to install Windows 11 the way you want (and sneak by Microsoft's restrictions)")

[When Windows 10 support runs out, you have 5 options but only 2 are worth considering](https://www.zdnet.com/article/still-have-a-windows-10-pc-you-have-5-options-before-support-ends-in-2025/ "When Windows 10 support runs out, you have 5 options but only 2 are worth considering")

[9 settings I changed on my Windows 11 PC to maximize the battery life](https://www.zdnet.com/article/9-settings-i-changed-on-my-windows-11-pc-to-maximize-the-battery-life/ "9 settings I changed on my Windows 11 PC to maximize the battery life")

[How to recover deleted files in Windows 10 or 11](https://www.zdnet.com/article/how-to-recover-deleted-files-in-windows-10-or-11/ "How to recover deleted files in Windows 10 or 11")

[Windows 11 setup: Which user account type should you choose?](https://www.zdnet.com/article/for-windows-11-setup-which-user-account-type-should-you-choose-how-to-decide/ "Windows 11 setup: Which user account type should you choose?")

[5 reasons why Linux will overtake Windows and MacOS on the desktop - eventually](https://www.zdnet.com/article/5-reasons-why-linux-will-eventually-overtake-windows-and-macos-on-the-desktop/ "5 reasons why Linux will overtake Windows and MacOS on the desktop - eventually")

[Microsoft is changing how it delivers Windows updates: 4 things you need to know](https://www.zdnet.com/article/microsoft-is-changing-how-it-delivers-windows-updates-4-things-you-need-to-know/ "Microsoft is changing how it delivers Windows updates: 4 things you need to know")

* [How to install Windows 11 the way you want (and sneak by Microsoft's restrictions)](https://www.zdnet.com/article/how-to-install-windows-11-the-way-you-want-and-bypass-microsofts-restrictions/ "How to install Windows 11 the way you want (and sneak by Microsoft's restrictions)")
* [When Windows 10 support runs out, you have 5 options but only 2 are worth considering](https://www.zdnet.com/article/still-have-a-windows-10-pc-you-have-5-options-before-support-ends-in-2025/ "When Windows 10 support runs out, you have 5 options but only 2 are worth considering")
* [9 settings I changed on my Windows 11 PC to maximize the battery life](https://www.zdnet.com/article/9-settings-i-changed-on-my-windows-11-pc-to-maximize-the-battery-life/ "9 settings I changed on my Windows 11 PC to maximize the battery life")
* [How to recover deleted files in Windows 10 or 11](https://www.zdnet.com/article/how-to-recover-deleted-files-in-windows-10-or-11/ "How to recover deleted files in Windows 10 or 11")
* [Windows 11 setup: Which user account type should you choose?](https://www.zdnet.com/article/for-windows-11-setup-which-user-account-type-should-you-choose-how-to-decide/ "Windows 11 setup: Which user account type should you choose?")
* [5 reasons why Linux will overtake Windows and MacOS on the desktop - eventually](https://www.zdnet.com/article/5-reasons-why-linux-will-eventually-overtake-windows-and-macos-on-the-desktop/ "5 reasons why Linux will overtake Windows and MacOS on the desktop - eventually")
* [Microsoft is changing how it delivers Windows updates: 4 things you need to know](https://www.zdnet.com/article/microsoft-is-changing-how-it-delivers-windows-updates-4-things-you-need-to-know/ "Microsoft is changing how it delivers Windows updates: 4 things you need to know")

###

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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-the-complete-how-to-for-mac-obs-plus-streamlabs-integration/"><u>[New] 2024 Approved The Complete How-To for Mac OBS + Streamlabs Integration</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-snappy-solutions-maintaining-a-vigorous-snapstreak/"><u>[Updated] Snappy Solutions Maintaining a Vigorous Snapstreak</u></a></li>
<li><a href="https://app-tips.techidaily.com/an-insightful-guide-to-choosing-between-elevenlabs-genvoice-ai-and-competitor-products/"><u>An Insightful Guide to Choosing Between ElevenLabs' GenVoice AI and Competitor Products</u></a></li>
<li><a href="https://app-tips.techidaily.com/comprehensive-analysis-elevenlabs-generative-voice-ai-and-comparable-options/"><u>Comprehensive Analysis: ElevenLabs' Generative Voice AI & Comparable Options</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-oneplus-nord-n30-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My OnePlus Nord N30 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-tecno-pop-7-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Tecno Pop 7 Pro Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-iphone-6s-activation-lock-by-drfone-ios/"><u>In 2024, How to Remove iPhone 6s Activation Lock</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, Read This Guide to Find a Reliable Alternative to Fake GPS On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lte-advanced-category-13-with-up-to-600-mbits-download-speeds-using-band-41-2x20-mhz-channel-arrangement-and-up-to-75-mbitn-upload-speeds-also-supports-dl-r99/"><u>LTE Advanced – Category 13 with up to 600 Mbit/S Download Speeds Using Band 41 (2X20 MHz) Channel Arrangement and up to 75 Mbit/N Upload Speeds. Also Supports DL-RevA Protocol Aggregation, but only with Other TANGO Radios on the Network</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/mastering-the-art-of-online-meeting-recordings-with-google-for-2024/"><u>Mastering the Art of Online Meeting Recordings with Google for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/unlocking-the-secrets-of-ex-journeys-eva-ai-an-authoritative-chatbot-overview-you-need-to-read/"><u>Unlocking the Secrets of Ex Journey's EVA AI: An Authoritative Chatbot Overview You Need to Read</u></a></li>
<li><a href="https://app-tips.techidaily.com/unveiling-the-pros-and-cons-a-deep-dive-into-elevenlabs-ai-innovation/"><u>Unveiling the Pros and Cons: A Deep Dive Into ElevenLabs' AI Innovation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/your-ai-companion-just-got-better-top-9-pluses-of-chatgptplus/"><u>Your AI Companion Just Got Better – Top 9 Pluses of ChatGPT+</u></a></li>
</ul></div>


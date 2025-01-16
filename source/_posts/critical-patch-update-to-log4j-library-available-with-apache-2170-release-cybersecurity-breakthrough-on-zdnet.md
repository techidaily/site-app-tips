---
title: Critical Patch Update to Log4j Library Available with Apache 2.17.0 Release | Cybersecurity Breakthrough on ZDNET
date: 2025-01-13T18:07:29.408Z
updated: 2025-01-15T23:29:09.048Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/password-manager/    https://www.zdnet.com/a/img/resize/e3bbd669dd97fe9909e7182c999f89be71428d24/2019/04/03/9b318728-bf96-4c85-9130-0655cc6a31f9/apache-web-server-logo.png?width=170&height=128&fit=crop&format=pjpg&auto=webp
---

## Critical Patch Update to Log4j Library Available with Apache 2.17.0 Release | Cybersecurity Breakthrough on ZDNET

![](https://www.zdnet.com/a/img/resize/635b68ab579c07867b881a368f252860f4e43a93/2021/12/15/2387d6fb-c15a-4555-9e7b-efe8155ed89b/20211214-danny-beth-log4.jpg?auto=webp&fit=cover&height=482&width=856)

Log4j: It's bad and it's only going to get worse

Log4j: It's bad and it's only going to get worse

Video Player is loading.

Play Video

PlaySkip BackwardSkip ForwardNext playlist item

Mute

Current Time 0:00

/

Duration 7:08

Loaded: 1.37%

0:00

Stream Type LIVE

Seek to live, currently behind liveLIVE

Remaining Time \-7:08

1x

Playback Rate

Chapters

* Chapters

Descriptions

* descriptions off, selected

Captions

* captions settings, opens captions settings dialog
* captions off, selected
* Eng US

Share

Audio Track

* en (Main), selected

Fullscreen

This is a modal window.

Beginning of dialog window. Escape will cancel and close the window.

TextColorWhiteBlackRedGreenBlueYellowMagentaCyanOpacityOpaqueSemi-Transparent

Text BackgroundColorBlackWhiteRedGreenBlueYellowMagentaCyanOpacityOpaqueSemi-TransparentTransparent

Caption Area BackgroundColorBlackWhiteRedGreenBlueYellowMagentaCyanOpacityTransparentSemi-TransparentOpaque

Font Size50%75%100%125%150%175%200%300%400%

Text Edge StyleNoneRaisedDepressedUniformDrop shadow

Font FamilyProportional Sans-SerifMonospace Sans-SerifProportional SerifMonospace SerifCasualScriptSmall Caps

ResetDone

Close Modal Dialog

End of dialog window.

Close Modal Dialog

This is a modal window. This modal can be closed by pressing the Escape key or activating the close button.

This is a modal window. This modal can be closed by pressing the Escape key or activating the close button.

Share: 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 

[Facebook](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fwww.zdnet.com%2Fvideo%2Flog4j-its-bad-and-its-only-going-to-get-worse%2F&title= "Facebook") [Twitter](https://twitter.com/intent/tweet?original%5Freferer=https%3A%2F%2Fabout.twitter.com%2Fresources%2Fbuttons&text=&tw%5Fp=tweetbutton&url=https%3A%2F%2Fwww.zdnet.com%2Fvideo%2Flog4j-its-bad-and-its-only-going-to-get-worse%2F "Twitter") 

Direct LinkEmbed Code

Close Modal Dialog

Apache [has released version 2.17.0](https://logging.apache.org/log4j/2.x/security.html) of the patch for Log4j after discovering issues with their previous release, which [came out on Tuesday](https://www.zdnet.com/article/second-log4j-vulnerability-found-apache-log4j-2-16-0-released/). 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### more Log4j

* [Log4j zero-day: How to protect yourself](https://www.zdnet.com/article/log4j-zero-day-flaw-what-you-need-to-know-and-how-to-protect-yourself/)
* [Apache releases new 2.17.0 patch](https://www.zdnet.com/article/apache-releases-new-2-17-0-patch-for-log4j-to-solve-denial-of-service-vulnerability/)
* [Security firm discovers new attack vector](https://www.zdnet.com/article/security-firm-blumira-discovers-major-new-log4j-attack-vector/)
* [10 questions you need to be asking](https://www.zdnet.com/article/log4j-flaw-10-questions-you-should-be-asking/)
* [Governments release Log4j advisory](https://www.zdnet.com/article/cisa-cybersecurity-centers-from-australia-nz-uk-and-canada-release-log4j-advisory/)
* [So far, nearly half of corporate networks have been attacked](https://www.zdnet.com/article/log4j-flaw-nearly-half-of-corporate-networks-have-been-targeted-by-attackers-trying-to-use-this-vulnerability/)
* [US: Hundreds of millions of devices at risk](https://www.zdnet.com/article/log4j-flaw-puts-hundreds-of-millions-of-devices-at-risk-says-us-cybersecurity-agency/)

Apache said version 2.16 "does not always protect from infinite recursion in lookup evaluation" and explained that it is vulnerable to [CVE-2021-45105](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-45105), a denial of service vulnerability. They said the severity is "high" and gave it a CVSS score of 7.5\. 

"Apache Log4j2 versions 2.0-alpha1 through 2.16.0 did not protect from uncontrolled recursion from self-referential lookups. When the logging configuration uses a non-default Pattern Layout with a Context Lookup (for example, ${ctx:loginId}), attackers with control over Thread Context Map (MDC) input data can craft malicious input data that contains a recursive lookup, resulting in a StackOverflowError that will terminate the process. This is also known as a DOS (Denial of Service) attack," Apache explained. 

They added that the latest issue was discovered by Akamai Technologies' Hideki Okamoto and an anonymous vulnerability researcher. 

Mitigations include applying the 2.17.0 patch and replacing Context Lookups like ${ctx:loginId} or ${ctx:loginId} with Thread Context Map patterns (%X, %mdc, or %MDC) in PatternLayout in the logging configuration. Apache also suggested removing references to Context Lookups in the the configuration like ${ctx:loginId} or ${ctx:loginId} where they originate from sources external to the application such as HTTP headers or user input. 

They noted that only the Log4j-core JAR file is impacted by CVE-2021-45105\. 

On Friday, security researchers online began [tweeting about potential issues](https://twitter.com/vxunderground/status/1471943986705281029?ref%5Fsrc=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1471943986705281029%7Ctwgr%5E%7Ctwcon%5Es1%5F&ref%5Furl=https%3A%2F%2Fwww.bleepingcomputer.com%2Fnews%2Fsecurity%2Fupgraded-to-log4j-216-surprise-theres-a-217-fixing-dos%2F) with 2.16.0, with some [identifying the denial of service vulnerability](https://issues.apache.org/jira/browse/LOG4J2-3230). 

Discussion about Log4j has dominated conversation all week. CISA [released multiple advisories](https://www.zdnet.com/article/cisa-orders-federal-agencies-to-mitigate-log4j-vulnerabilities-in-emergency-directive/) mandating federal civilian agencies in the US [apply patches before Christmas](https://www.zdnet.com/article/cisa-orders-federal-civilian-agencies-to-patch-log4j-vulnerability-by-december-24/) while [several major tech companies](https://www.zdnet.com/article/vmware-patches-critical-non-log4j-flaw-as-ibm-cisco-release-log4j-fixes/) like IBM, Cisco and VMware have raced to address Log4j vulnerabilities in their products. 

Security company Blumira claims to have found a [new Log4j attack vector](https://www.blumira.com/analysis-log4shell-local-trigger/) that can be exploited through the path of a listening server on a machine or local network, potentially putting an end to the assumption that the problem was limited to exposed vulnerable servers. 

Other cybersecurity firms have found that [major ransomware groups like Conti](https://www.zdnet.com/article/conti-ransomware-attacking-vmware-vcenter-servers-through-log4j-vulnerability/) are exploring ways to take advantage of the vulnerability. 

Google [released a security report](https://security.googleblog.com/2021/12/understanding-impact-of-apache-log4j.html) on Friday where Open Source Insights Team members James Wetter and Nicky Ringland said they found that 35,863 of the available Java artifacts from Maven Central depend on the affected Log4j code. This means that more than 8% of all packages on Maven Central have at least one version that is impacted by this vulnerability, the two explained. 

"The average ecosystem impact of advisories affecting Maven Central is 2%, with the median less than 0.1%," Wetter and Ringland said. 

So far, nearly 5,000 artifacts have been patched, leaving more than 30,000 more. But the two noted that it will be difficult to address the issue because of how deep Log4j is embedded in some products. 

Google

"Most artifacts that depend on log4j do so indirectly. The deeper the vulnerability is in a dependency chain, the more steps are required for it to be fixed. For greater than 80% of the packages, the vulnerability is more than one level deep, with a majority affected five levels down (and some as many as nine levels down)," Wetter and Ringland wrote. 

**"**These packages will require fixes throughout all parts of the tree, starting from the deepest dependencies first." 

The two went on to say that after looking at all publicly disclosed critical advisories affecting Maven packages, they found less than half (48%) of the artifacts affected by a vulnerability have been fixed, meaning it may take years for the Log4j issue to be solved. 

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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-expert-insights-switching-from-webp-to-jpg-format/"><u>[New] In 2024, Expert Insights Switching From WebP to JPG Format</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-seamless-sharing-twitch-links-on-your-fb-page-for-2024/"><u>[New] Seamless Sharing Twitch Links on Your FB Page for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-threefold-way-to-extract-and-save-youtubes-subtitles-srt/"><u>[New] The Threefold Way to Extract and Save YouTube's Subtitles (SRT)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-does-apples-m1-compare-to-traditional-editing-workstations/"><u>[Updated] How Does Apple’s M1 Compare to Traditional Editing Workstations?</u></a></li>
<li><a href="https://solve-helper.techidaily.com/1-best-live-streaming-apps-discover-manycam-and-other-top-virtual-camera-solutions/"><u>1. Best Live Streaming Apps: Discover ManyCam and Other Top Virtual Camera Solutions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-elevate-your-episodes-a-comprehensive-guide-to-sound-design-and-editing/"><u>2024 Approved Elevate Your Episodes A Comprehensive Guide to Sound Design and Editing</u></a></li>
<li><a href="https://app-tips.techidaily.com/adobe-full-voice-booster-evaluation-techniques-for-superior-sound-quality/"><u>Adobe Full Voice Booster Evaluation: Techniques for Superior Sound Quality</u></a></li>
<li><a href="https://win-dash.techidaily.com/best-practices-for-downloading-asus-chipset-drivers-on-windows-pcs/"><u>Best Practices for Downloading ASUS Chipset Drivers on Windows PCs</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722961604346-effortless-installation-keeping-your-scansnap-up-to-date-on-pc/"><u>Effortless Installation: Keeping Your ScanSnap Up-to-Date on PC!</u></a></li>
<li><a href="https://app-tips.techidaily.com/explore-the-leading-substitutes-for-voicemyai-your-guide-to-innovative-ai-voice-solutions/"><u>Explore the Leading Substitutes for voicemy.ai: Your Guide to Innovative AI Voice Solutions</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-itel-p55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Itel P55 | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/in-depth-analysis-of-leading-artificeintelligence-video-makers-for-image-based-production/"><u>In-Depth Analysis of Leading ArtificeIntelligence Video Makers for Image-Based Production</u></a></li>
<li><a href="https://app-tips.techidaily.com/in-depth-insight-on-avclabs-video-improvement-software-features-benefits-and-drawbacks/"><u>In-Depth Insight on AVCLabs Video Improvement Software: Features, Benefits & Drawbacks</u></a></li>
<li><a href="https://app-tips.techidaily.com/leading-5-ai-technologies-for-transforming-grayscale-videos-into-full-color-masterpieces/"><u>Leading 5 AI Technologies for Transforming Grayscale Videos Into Full Color Masterpieces</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-3-video-to-text-conversion-software-a-comprehensive-guide/"><u>Top 3 Video-to-Text Conversion Software: A Comprehensive Guide</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-5-substitutes-for-elevenlabs-explored-detailed-comparison-and-key-characteristics/"><u>Top 5 Substitutes for ElevenLabs Explored: Detailed Comparison and Key Characteristics</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-5-superior-substitutes-to-zapier-enhance-your-workflow-automation/"><u>Top 5 Superior Substitutes to Zapier: Enhance Your Workflow Automation</u></a></li>
<li><a href="https://app-tips.techidaily.com/unveiling-exceptional-no-limit-character-ai-solutions-for-dynamic-experiences/"><u>Unveiling Exceptional No-Limit Character AI Solutions for Dynamic Experiences</u></a></li>
</ul></div>


---
title: Apache Introduces Security Fix in Version 2.17.0 for Log4j's DoS Issue | Tech News by ZDNet
date: 2024-11-29T11:33:27.210Z
updated: 2024-12-02T08:58:48.975Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/password-manager/    https://www.zdnet.com/a/img/resize/e3bbd669dd97fe9909e7182c999f89be71428d24/2019/04/03/9b318728-bf96-4c85-9130-0655cc6a31f9/apache-web-server-logo.png?width=170&height=128&fit=crop&format=pjpg&auto=webp
---

## Apache Introduces Security Fix in Version 2.17.0 for Log4j's DoS Issue | Tech News by ZDNet

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 

[Facebook](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fwww.zdnet.com%2Fvideo%2Flog4j-its-bad-and-its-only-going-to-get-worse%2F&title= "Facebook") [Twitter](https://twitter.com/intent/tweet?original%5Freferer=https%3A%2F%2Fabout.twitter.com%2Fresources%2Fbuttons&text=&tw%5Fp=tweetbutton&url=https%3A%2F%2Fwww.zdnet.com%2Fvideo%2Flog4j-its-bad-and-its-only-going-to-get-worse%2F "Twitter") 

Direct LinkEmbed Code

Close Modal Dialog

Apache [has released version 2.17.0](https://logging.apache.org/log4j/2.x/security.html) of the patch for Log4j after discovering issues with their previous release, which [came out on Tuesday](https://www.zdnet.com/article/second-log4j-vulnerability-found-apache-log4j-2-16-0-released/). 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-tips.techidaily.com/new-in-2024-all-encompassing-look-at-the-ricoh-theta-s-design/"><u>[New] In 2024, All-Encompassing Look at the Ricoh Theta S Design</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-innovative-ways-to-infuse-voiceovers-into-your-media/"><u>[New] Innovative Ways to Infuse Voiceovers Into Your Media</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-the-ultimate-editors-guide-best-for-youtube-content/"><u>[Updated] 2024 Approved The Ultimate Editor's Guide Best for YouTube Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-harnessing-monetization-potential-with-youtube-ad-strategies-for-2024/"><u>[Updated] Harnessing Monetization Potential with YouTube Ad Strategies for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/advanced-array-designs-employ-strategies-like-amplitude-tapering-and-null-steering-algorithms-to-control-side-lobes-for-improved-directivity-and-reduced-int87/"><u>Advanced Array Designs Employ Strategies Like Amplitude Tapering and Null-Steering Algorithms to Control Side Lobes for Improved Directivity and Reduced Interference Potential.</u></a></li>
<li><a href="https://app-tips.techidaily.com/ai-initiatives-surge-by-10x-in-recent-year-insights-from-latest-research-zdnet/"><u>AI Initiatives Surge by 10X in Recent Year - Insights From Latest Research | ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/collaboration-ensures-continued-life-for-linux-414-long-term-support-version-zdnet-tech-news/"><u>Collaboration Ensures Continued Life for Linux 4.14 Long-Term Support Version | ZDNET Tech News</u></a></li>
<li><a href="https://app-tips.techidaily.com/conquering-chaos-in-linuxopen-source-guidebooks-explore-our-streamlined-remedy-zdnet/"><u>Conquering Chaos in Linux/Open-Source Guidebooks: Explore Our Streamlined Remedy | ZDNet</u></a></li>
<li><a href="https://app-tips.techidaily.com/could-microsofts-new-offering-soothe-or-annoy-you-expert-analysis-by-zdnet-revealed/"><u>Could Microsoft's New Offering Soothe or Annoy You? Expert Analysis by ZDNet Revealed</u></a></li>
<li><a href="https://app-tips.techidaily.com/exploring-the-barriers-how-firms-find-it-challenging-to-leverage-generative-ai-according-to-deloittes-latest-insights/"><u>Exploring the Barriers: How Firms Find It Challenging to Leverage Generative AI According to Deloitte's Latest Insights</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-a14-4gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy A14 4Gwith/without a PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hp-laserjet-printer-support-find-and-install-the-correct-windows-p1102w-driver-software-now/"><u>HP LaserJet Printer Support: Find and Install the Correct Windows P1102w Driver Software Now!</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-simplified-srt-transformation-from-ttml-xml-and-ssa/"><u>In 2024, Simplified SRT Transformation From TTML, XML & SSA</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidiaintel-card-syncing-a-win11-update-success-story/"><u>Nvidia/Intel Card Syncing, A Win11 Update Success Story</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/proven-strategies-for-effective-phone-note-taking-for-2024/"><u>Proven Strategies for Effective Phone Note-Taking for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/surprising-upsides-for-it-professionals-facing-burnout-insights-from-zdnets-latest-article/"><u>Surprising Upsides for IT Professionals Facing Burnout: Insights From ZDNet's Latest Article</u></a></li>
<li><a href="https://app-tips.techidaily.com/understanding-the-link-between-kernel-vulnerabilities-and-linux-system-security-proactive-measures-for-protection/"><u>Understanding the Link Between Kernel Vulnerabilities and Linux System Security: Proactive Measures for Protection</u></a></li>
<li><a href="https://app-tips.techidaily.com/unleash-efficiency-on-the-linux-platform-explore-ubuntu-2204-as-your-workhorse-insights-by-zdnet/"><u>Unleash Efficiency on the Linux Platform - Explore Ubuntu 22.04 as Your Workhorse | Insights by ZDNET</u></a></li>
</ul></div>


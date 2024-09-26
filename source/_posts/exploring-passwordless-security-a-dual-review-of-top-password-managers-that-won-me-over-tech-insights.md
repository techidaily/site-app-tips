---
title: "Exploring Passwordless Security: A Dual Review of Top Password Managers That Won Me Over | Tech Insights"
date: 2024-09-17T08:32:09.705Z
updated: 2024-09-19T20:12:05.610Z
tags:
  - password-manager
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e696268502b283ed640a05098ec06b8044deb546bbd2035bab816a7494c0bab9.jpg
---

## Exploring Passwordless Security: A Dual Review of Top Password Managers That Won Me Over | Tech Insights

![Fingerprint for biometrics](https://www.zdnet.com/a/img/resize/c9ef286bb7a06c77114866ca22c1ce4c369e5693/2023/12/28/bb6fb116-a4b4-41d7-b195-2fb97d72da7a/gettyimages-1286541364.jpg?auto=webp&width=1280)

Andriy Onufriyenko/Getty Images

[Password management apps](https://www.zdnet.com/article/best-password-manager/) have been around for decades. These days, there are dozens of legitimate candidates for the job of wrangling your online credentials, and they all start with the same basic architecture: Your usernames, passwords, and other secrets are stored in a database (often called a _vault_) that's protected with strong encryption. To unlock that vault, you enter a master password.

In fact, that model is so pervasive that it's inspired the names of some leading products in the category. There's [1Password](https://www.anrdoezrs.net/click-9041660-14308408-1615917146000?sid=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp), for example, which promises that you'll only need to remember one password instead of dozens or hundreds. [LastPass](https://lastpass.wo8g.net/c/159047/506709/8692?&sharedId=zdnet&u=https%3A%2F%2Fwww.lastpass.com%2F&subId1=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp) claims that your master password will be "the last password you'll ever need."

**Also: [Why you can still trust (other) password managers, even after that LastPass mess](https://www.zdnet.com/article/why-you-can-still-trust-other-password-managers-even-after-that-lastpass-mess/)**

The best products in the category offer [passwordless options](https://www.zdnet.com/article/passkeys-what-are-they-and-how-to-get-started/) as an alternative to typing that master password to unlock your password vault. Typically that means using biometrics (face recognition or fingerprint ID) or a hardware key on a trusted device. But in all those cases, the master password is still available as a backup decryption method.

And that's where some people get nervous about entrusting all those secrets to a password manager. If someone can steal your master password, they can take over your entire online existence. You can make an attacker's job considerably more difficult with [multi-factor authentication](https://www.zdnet.com/article/multi-factor-authentication-how-to-enable-2fa-and-boost-your-security/), but it's still a weak point, architecturally.

But what if you could get rid of the master password completely, using only a trusted device to prove your identity? That option's available today for anyone [creating a new account with Dashlane](https://www.zdnet.com/article/dashlane-launches-passwordless-login-for-new-users-only-so-far/), and rival [1Password is offering a public beta](https://www.zdnet.com/article/1password-now-lets-you-ditch-master-password-in-favor-of-a-passkey/) to allow its customers to test a similar feature. (Both companies say customers with existing personal accounts and anyone who wants to set up a business account will have to wait till sometime in 2024 to make their accounts completely passwordless.)

**Also: [How long should a password be in 2023? You're asking the wrong question](https://www.zdnet.com/article/how-long-is-the-perfect-password-youre-asking-the-wrong-question/)**

Should you ditch your master password completely? I took the plunge with both [Dashlane](https://www.dpbolvw.net/click-9041660-15672274-1699990289000?sid=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp) and [1Password](https://www.anrdoezrs.net/click-9041660-14308408-1615917146000?sid=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp), setting up free test accounts to see what the experience is like. 

My conclusion: There's a passwordless password manager in your future, but only technically sophisticated customers should plunge in today.

## Setting up a passwordless account

Both products follow a similar workflow to enable passwordless accounts. For Dashlane, you start by installing the Dashlane app on a mobile device (iOS or Android) and then setting up a new personal account using the passwordless option with an email address that becomes your username. (It doesn't have to be a primary email address, but you do need to confirm the address before completing setup.)

Dashlane was the first developer to ship a completely passwordless password manager

Screenshot by Ed Bott/ZDNET

1Password requires you to join the public beta by using its [mobile](https://1password.com/sign-up/passkey-preview) or [desktop](https://start.1password.com/sign-up?c=NOPASSWORD) links; after creating a new individual account, you can follow the prompts to create a passkey. (If you're on an iPhone, make sure you've set up iCloud Keychain as a place to store passkeys. If you have an Android device, keep reading.)

1Password uses passkeys to enable passwordless accounts, which causes some problems

Screenshot by Ed Bott/ZDNET

With those tasks out of the way, you can import your existing passwords and add new ones. More importantly, you now have a device that you can use to set up access to the password vault on other devices, with no master password required.

## Setting up additional devices

Most modern password managers store the encrypted password database in the cloud so that you can sync and share credentials across devices. Dashlane and 1Password take very different approaches to the task of configuring additional devices.

After setting up my passwordless Dashlane account on an Android device, I found it easy to set up other devices, including an iPhone and iPad, a MacBook Air, and multiple PCs running Windows 10 and Windows 11\. Here's how it works.

**Also: [The best VPN services: Expert tested and reviewed](https://www.zdnet.com/article/best-vpn/)**

On a mobile device, install the Dashlane app; on a PC or Mac, install the Dashlane browser extension. Then start the sign-in process by entering the email address you use for the account. On the device that's already signed in, go to **Settings** \> **Add New Device** in the Dashlane app and confirm that yes, it's you trying to sign in. 

On the new device, Dashlane displays a security challenge consisting of five random words, taken from the [Electronic Frontier Foundation's Large Wordlist for Passphrases](https://www.eff.org/document/passphrase-wordlists); that same list appears on the device where you're already signed in, with one box empty. Fill in the missing word, tap Confirm, and your new device is set up.

Dashlane requires you to pass this challenge by typing the missing word displayed on the other device 

Screenshot by Ed Bott/ZDNET

I wish I could say the process was equally simple using 1Password's beta, but it most emphatically is not, at least not in my cross-platform world. 1Password uses passkeys to enable passwordless logins, which means you need a way to share passkeys among devices. 

If you have Apple's iCloud Keychain enabled, it's pretty easy to do that on Macs, iPhones, and iPads, but Windows PCs and Android devices present a problem. [1Password's documentation](https://support.1password.com/passkeys/), in fact, notes that you need Windows 11 22H2 or later (sorry, Windows 10), and that "\[e\]ven on supported versions of Android, some devices may not support saving a passkey for a 1Password account."

**Also: [Windows security: How to protect your home and small business PCs](https://www.zdnet.com/article/windows-security-how-to-protect-your-home-and-small-business-pcs/)**

I had no problem using a QR code to set up my iPhone, but when I tried to set up the 1Password extension on Microsoft Edge for the Mac, it took me easily a half-dozen tries to get things working. First I had to explain to 1Password that there was no passkey on my Samsung phone, after which it popped up a QR code I scanned with my iPhone to enable a passkey prompt from the Keychain. Then I had to approve a pop-up confirming it really was me. 1Password then showed me a code that I was supposed to enter in a dialog box on a browser window that was hidden behind some other windows.

But setting up a passwordless account on Windows or Android added a whole new level of frustration. This was the default error message when I tried to sign in on a Windows 11 PC.

Windows doesn't offer a way to share passkeys, making 1Password harder to set up

Screenshot by Ed Bott/ZDNET

I might have been able to use the Google Chrome Password Manager to share my passkey, but does it really make sense to use someone else's password manager to enable a 1Password feature? 

It turned out that the best way to activate my passwordless account was to save a passkey in 1Password using my current account on the Samsung device I started with, then attach that account to 1Password on the new device using its master password and secret key, and (finally!) add the new account there. Because 1Password supports attaching multiple accounts to a single device, this works, but it's extremely kludgey, and it helps explain why this app isn't close to being release-worthy yet.

**Also: [Beyond passwords: 4 key security steps you're probably forgetting](https://www.zdnet.com/article/beyond-passwords-4-key-security-steps-youre-probably-forgetting/)**

The dealbreaker for me, though, came when I tried to export my passwords from the new passwordless account. 1Password's beta app insists that you type a master password (which doesn't exist for this account, of course) before it will begin an export. A tech support rep confirmed that this feature is missing in the current beta.

Given those beta headaches, I decided to delete my passwordless 1Password account and try again in a few months. But Dashlane was impressive enough to make me seriously consider switching.

## What's the risk?

When you have a passwordless account, the only way to access your passwords is to establish your identity with the help of a trusted device where you've already confirmed your credentials with the password management servers.

So, what happens if you can't access any of those trusted devices? You're locked out, probably for good. The whole point of zero-knowledge credential managers is that you _and only you_ can unlock that vault. Without a master password, you don't have a fallback method to restore access to your encrypted vault.

**Also: [Stop using weak passwords for streaming services - it's riskier than you think](https://www.zdnet.com/article/stop-using-weak-passwords-for-streaming-services-its-riskier-than-you-think/)**

Both Dashlane and 1Password offer an alternative in the form of a recovery key. That's a randomly generated alphanumeric code (Dashlane's key is 28 characters long; 1Password uses a 56- character recovery key) that you print out and store in a safe place. If you're ever in a situation where you don't have a PC or mobile device that's signed in to your account, you can break the glass and use that recovery key as a last resort. But you'll never need to type it under normal circumstances, meaning it's resistant to phishing, keyloggers, and other hacking tools.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Should you switch to a passwordless account?

There's no question that passwordless accounts represent the future, but not the present. At this point, only one company, Dashlane, is offering the feature on a shipping product, and then only for new personal accounts. If you're happy with your current password manager, it's not time to think about switching yet.

I was impressed enough by [Dashlane](https://www.tkqlhce.com/click-9041660-15578685-1689361269000?sid=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp) that I'm going to use my new passwordless account for a few months and see if it's a worthy replacement for 1Password. I'll keep you posted.

#### Featured

[The fastest VPNs: Expert tested and reviewed](https://www.zdnet.com/article/fastest-vpn/ "The fastest VPNs: Expert tested and reviewed")

[Google Pixel 9 Pro XL vs. Samsung Galaxy S24 Ultra: I tested both and here are the key differences](https://www.zdnet.com/article/google-pixel-9-pro-xl-vs-samsung-galaxy-s24-ultra/ "Google Pixel 9 Pro XL vs. Samsung Galaxy S24 Ultra: I tested both and here are the key differences")

[How to upgrade your 'incompatible' Windows 10 PC to Windows 11](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/ "How to upgrade your 'incompatible' Windows 10 PC to Windows 11")

[Your Android phone is getting an anti-theft upgrade, thanks to AI. How it works](https://www.zdnet.com/article/your-android-phone-is-getting-an-anti-theft-upgrade-thanks-to-ai-how-it-works/ "Your Android phone is getting an anti-theft upgrade, thanks to AI. How it works")

* [The fastest VPNs: Expert tested and reviewed](https://www.zdnet.com/article/fastest-vpn/ "The fastest VPNs: Expert tested and reviewed")
* [Google Pixel 9 Pro XL vs. Samsung Galaxy S24 Ultra: I tested both and here are the key differences](https://www.zdnet.com/article/google-pixel-9-pro-xl-vs-samsung-galaxy-s24-ultra/ "Google Pixel 9 Pro XL vs. Samsung Galaxy S24 Ultra: I tested both and here are the key differences")
* [How to upgrade your 'incompatible' Windows 10 PC to Windows 11](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/ "How to upgrade your 'incompatible' Windows 10 PC to Windows 11")
* [Your Android phone is getting an anti-theft upgrade, thanks to AI. How it works](https://www.zdnet.com/article/your-android-phone-is-getting-an-anti-theft-upgrade-thanks-to-ai-how-it-works/ "Your Android phone is getting an anti-theft upgrade, thanks to AI. How it works")

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




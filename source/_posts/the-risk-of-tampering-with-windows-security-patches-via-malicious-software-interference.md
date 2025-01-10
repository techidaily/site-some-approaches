---
title: The Risk of Tampering with Windows Security Patches via Malicious Software Interference
date: 2025-01-08T20:15:29.167Z
updated: 2025-01-09T22:33:19.399Z
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/laptop-with-windows-10-on-the-left-and-laptop-with-windows-11-on-the-right-with-an-update-icon-in-the-center.jpg
---

## The Risk of Tampering with Windows Security Patches via Malicious Software Interference

Security researcher Alon Leviev has discovered a vulnerability in Windows Update that allows attackers to disable security patches without detection. This downgrade attack can potentially compromise fully updated Windows systems, and expose them to old threats which Microsoft has already patched.

 According to Leviev, he wanted to test the protection Windows offers against downgrade attacks. To his surprise, Windows barely has any fail safes to prevent unauthorized OS rollbacks. The researcher found serious security flaws in Windows Update that he exploited to gain elevated system privileges and breeze past Windows security. Using a custom tool called Windows Downdate, he managed to downgrade system files, [drivers](https://hardware-tips.techidaily.com/increase-your-savings-with-a-huge-80-off-the-elegoo-neptune-plus-ideal-for-big-prints/), and the Windows kernel (the core program which has full control over the operating system) on Windows 10 and 11.

 The downgrades he made remained undetectable and persistent, meaning they were invisible to Windows Update and [system recovery](https://tech-hub.techidaily.com/innovative-training-crafting-custom-exercise-routines-using-chatgpt-for-trainers/) tools. They're also irreversible. The attack would trick the victim into thinking their machine is up-to-date (as Windows Update would confirm). But the core components would have been quietly replaced with older versions, exposing them to thousands of already-fixed vulnerabilities.

 Leviev also discovered critical flaws in the Windows virtualization security, including [Hyper V](https://fox-glue.techidaily.com/the-ultimate-guide-to-using-telegram-web-effectively-for-2024/). Exploiting those flaws, he managed to downgrade and bypass virtualization security features. The researcher warns that Windows might not be the only operating system vulnerable to downgrade attacks.

 There have been no attacks in the wild using this attack vector, which is good news. But Leviev demoed it at Black Hat USA 2024 and DEF CON 32 2024\. He also reached out to Microsoft in February, when he first identified these threats.

 Microsoft has since been working on an update to patch them, but six months later, it’s still not available. “We are actively developing mitigations to protect against these risks while following an extensive process involving a thorough investigation, update development across all affected versions, and compatibility testing, to ensure maximized customer protection with minimized operational disruption,” Microsoft stated in an official response.

 Source: Alon Leviev via [Safebreach](https://www.safebreach.com/blog/downgrade-attacks-using-windows-updates/)

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
<li><a href="https://visual-screen-recording.techidaily.com/new-essential-call-customization-applications-ranked-for-2024/"><u>[New] Essential Call Customization Applications Ranked for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-perfect-screen-capture-on-mac-the-top-5-recommended-approaches/"><u>[New] In 2024, Perfect Screen Capture on Mac The Top 5 Recommended Approaches</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-editing-game-changer-fcps-best-10-plugins/"><u>[New] The Editing Game Changer FCP's Best 10 Plugins</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ranscribing-online-master-the-art-of-free-youtube-conversion/"><u>[New] Transcribing Online Master the Art of Free YouTube Conversion</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unlock-iphone-editing-magic-shorter-smaller-videos/"><u>[New] Unlock iPhone Editing Magic Shorter, Smaller Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-unveiling-the-top-4-fullscreen-recorder-for-pc-and-mac-users/"><u>[New] Unveiling the Top 4 Fullscreen Recorder for PC & Mac Users</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-effortless-video-streams-youtube-loops-for-television-viewers/"><u>[Updated] 2024 Approved Effortless Video Streams YouTube Loops for Television Viewers</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-elevate-design-top-tier-tips-from-canva-experts/"><u>[Updated] Elevate Design Top-Tier Tips From Canva Experts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-refining-online-discussions-in-google-meet-for-2024/"><u>[Updated] Refining Online Discussions in Google Meet for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-tapping-into-traditional-hymns-downloads-and-editing-guide/"><u>[Updated] Tapping Into Traditional Hymns Downloads & Editing Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-insiders-guide-to-creating-viral-memes-on-9gag/"><u>[Updated] The Insider's Guide to Creating Viral Memes on 9GAG</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-how-to-manual-for-creating-an-inclusive-and-productive-skype-chat-room-accessible-by-both-windows-and-mac-users/"><u>2024 Approved How-To Manual for Creating an Inclusive and Productive Skype Chat Room Accessible by Both Windows & Mac Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-ideal-accessories-for-optimal-gopro-photography/"><u>2024 Approved Ideal Accessories for Optimal GoPro Photography</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-list-of-text-tools-and-plugins/"><u>2024 Approved Ultimate List of Text Tools & Plugins</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlock-optimal-performance-with-these-key-tricks/"><u>2024 Approved Unlock Optimal Performance with These Key Tricks</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-samsung-galaxy-f54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-essence-of-uavs-understanding-their-mechanics-and-use-for-2024/"><u>The Essence of UAVs Understanding Their Mechanics & Use for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlock-the-power-of-time-lapse-with-gopro-hero5-for-2024/"><u>Unlock the Power of Time-Lapse with GoPro Hero5 for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-windows-high-dynamic-range-potential-for-2024/"><u>Unlocking Windows' High Dynamic Range Potential for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->


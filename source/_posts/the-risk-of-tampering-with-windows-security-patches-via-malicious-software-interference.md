---
title: The Risk of Tampering with Windows Security Patches via Malicious Software Interference
date: 2024-08-30T21:22:40.381Z
updated: 2024-08-31T21:22:40.381Z
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



<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
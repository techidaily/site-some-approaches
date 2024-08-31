---
title: Permanently Deactivate Microsoft's Built-In Security App on Your Windows 11 PC - A Comprehensive Tutorial
date: 2024-08-30T21:22:27.076Z
updated: 2024-08-31T21:22:27.076Z
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/windows-desktop.jpg
---

## Permanently Deactivate Microsoft's Built-In Security App on Your Windows 11 PC - A Comprehensive Tutorial

### Quick Links

* [When Should You Permanently Disable Microsoft Defender Antivirus](https://article-knowledge.techidaily.com/2024-approved-ultimate-guide-newest-lg-bp550-specs/)
* [Turn Off Real-Time Protection and Tamper Protection in the Windows Security App](https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-tecno-spark-20c-drfone-by-drfone-virtual-android/)
* [Disable Microsoft Defender Using the Registry Editor](https://screen-sharing-recording.techidaily.com/new-remote-recording-mastery-a-comprehensive-approach/)
* [Disable Microsoft Defender Using the Local Group Policy Editor](https://fox-access.techidaily.com/a-compreenas-guide-to-producing-slow-motion-content-with-photos-and-internet-for-2024/)
* [How to Check the State of Microsoft Defender on Windows 11](https://screen-mirroring-recording.techidaily.com/new-broadcast-software-beyond-standard-obs/)

### Key Takeaways

* If you want to permanently disable Microsoft Defender on Windows 11, you’ll first need to disable Real-time protection and Tamper protection in the Windows Security app.
* Windows Home users can use the Registry Editor to turn off Microsoft Defender. Windows Pro users have the option to do it through either the Registry Editor or the Local Group Policy Editor.
* You can determine whether Microsoft Defender is currently disabled by running the "Get-MpComputerStatus | select AMRunningMode" command in Windows PowerShell.

 Windows built-in security app, Microsoft Defender, protects your computer from malicious agents and viruses. However, there may be situations when you want to disable it, such as when testing a third-party security app. We'll show you how to permanently disable Microsoft Defender on Windows 11.

##  When Should You Permanently Disable Microsoft Defender Antivirus 

 Microsoft Defender Antivirus provides various protection features, including real-time protection, cloud-delivered protection, network protection, and more. When you disable Microsoft Defender, you lose access to all these protections, leaving your computer at risk.

 Generally, you should avoid disabling Microsoft Defender Antivirus. However, if the need arises—for example, when you need to install an application that Defender is blocking—you can [temporarily turn it off](https://tech-renaissance.techidaily.com/what-is-the-difference-between-an-ipad-and-a-tablet/). To do so, [turn off Real-time protection](https://desktop-recording.techidaily.com/new-record-gameplay-in-samsung-galaxy-phones-for-2024/) in the Windows Security app, install the application, and then re-enable Real-time protection.

![Real-time Protection toggle disabled in the Windows Security app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/real-time-protection-toggle-disabled-in-the-windows-security-app.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Additionally, if you intend to permanently disable Defender Antivirus to install a third-party security application, you must reconsider your choice. This is because when you install a compatible [non-Microsoft antivirus program](https://video-capture.techidaily.com/2024-approved-nvidia-game-capturer-simple-gaming-sessions/), Microsoft Defender antivirus will automatically disable itself. Compatible non-Microsoft antivirus programs are those that do not cause any issues when installed alongside Windows Defender.

 Luckily, there are numerous [antivirus programs](https://facebook-video-recording.techidaily.com/in-2024-access-high-res-fb-media-files/) that are compatible with Microsoft. To verify compatibility, you should check the antivirus program’s user manual or inquire with the seller.

 However, if you wish to install a security program that is not compatible with Microsoft, you will need to disable Microsoft Defender Antivirus permanently.

 Now that you know when you should and should not permanently disable Microsoft Defender, let’s check out how you can permanently disable Microsoft Defender on Windows 11.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
##  Turn Off Real-Time Protection and Tamper Protection in the Windows Security App

 Unlike temporarily disabling Microsoft Defender Antivirus, permanently disabling it isn’t straightforward. First, you’ll need to disable Real-time and Tamper Protection in the Windows Security app.

 Disabling Real-time protection ensures that Microsoft Defender won’t scan any files on your computer. And disabling [Tamper Protection](https://some-techniques.techidaily.com/in-2024-harnessing-funimates-downloading-prowess-quickly/) allows you to make changes to the Microsoft Defender antivirus settings on your computer, which otherwise wouldn’t be possible. To turn off these settings, open the Start menu, type **Windows Security** in the search bar, and hit Enter.

![Typing Windows Security in the Start Menu search bar.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/typing-windows-defender-in-the-start-menu-search-bar.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
 Choose "Virus & Threat Protection" from the left sidebar, then click "Manage Settings" on the right.

![Virus & Threat Protection option in the Windows Security App.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/virus-threat-protection-option-in-the-windows-security-app.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Turn off the “Real-Time Protection” toggle. If UAC pops up, click “Yes” to confirm your decision.

![Real-time Protection toggle in the Windows Security app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/real-time-protection-toggle-in-the-windows-security-app.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Next, disable the “Tamper Protection” toggle. Click “Yes” when the UAC prompt appears.

![Tamper Protection toggle in the Windows Security app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/tamper-protection-toggle-in-the-windows-security-app.jpg) 

 Once you’ve adjusted these settings in the Windows Security app, you’re all set to disable Microsoft Defender Antivirus on Windows 11 permanently.

##  Disable Microsoft Defender Using the Registry Editor

 If you have Windows 11 Home installed on your computer, you can use the Registry Editor to disable Microsoft Defender permanently.

 Editing the registry is risky, as one wrong move can make your system unstable. As a precautionary measure, be sure to [back up the registry](https://screen-recording.techidaily.com/quick-start-guide-dells-simple-screen-recording-methods-for-2024/) and [create a restore point](https://instagram-video-files.techidaily.com/updated-in-2024-multiplying-joy-sharing-a-pile-of-photos-and-videos-with-instagram/). This way, you can [restore your computer](https://article-posts.techidaily.com/in-2024-proven-methods-to-infuse-engaging-dialogue-in-videos/) to a working state in case something goes wrong.

 Open the Start menu, type **Registry Editor** in the search bar, and hit Enter. Then, in the Registry Editor, navigate to the following path:

        `Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
    
 Right-click the “Windows Defender” key in the left sidebar, hover over “New,” and choose “DWORD (32-bit) Value”.

![Windows Defender Key in the Registry Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/windows-defender-key-in-the-registry-editor.jpg) 

 Name the value “DisableAntiSpyware.” Then, double-click the “DisableAntiSpyware” value, type **1** in the “Value Data” field, and click “OK.”

![Value Data field in the Registry Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/value-data-field-in-the-registry-editor.jpg) 

 After that, [restart your computer](https://instagram-clips.techidaily.com/2024-approved-15-must-use-hashtags-for-popularity-on-instagram-feed/) for the changes to take effect. Upon restart, you’ll see that Microsoft Defender has been permanently disabled on your computer.

 To reenable Microsoft Defender Antivirus, type **0** in the “Value Data” field of the “DisableAntiSpyware” value and click “OK.” Afterward, you’ll need to enable “Real-time Protection” and “Tamper Protection” in the Windows Security app, too. 

![Enabling Windows Defender through Registry Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/enabling-windows-defender-through-registry-editor.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
##  Disable Microsoft Defender Using the Local Group Policy Editor

 If you are a Windows 11 Pro user, you have an additional option to permanently disable Microsoft Defender. While you can use the Registry Editor for this process, as a Pro user, you also have the option to use Local Group Policy Editor.

 Press Win+R to open the Run tool. Then, type **gpedit.msc** in the search field and click “OK.”

![Gpedit.msc command in the Run tool.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/gpedit-msc-command-in-the-run-tool.jpg) 

 In the Local Group Policy Editor window, navigate to the following location:

        `Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Antivirus`
    
 Double-click the “Turn Off Microsoft Defender Antivirus” policy.

![Turn Off Microsoft Defender Antivirus policy in the Local Group Policy Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/turn-off-microsoft-defender-antivirus-policy-in-the-local-group-policy-editor.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In the Edit window, choose “Enabled.” Then, click “Apply” and “OK” to save the changes.

![Enabled option in the Local Group Policy Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/enabled-option-in-the-local-group-policy-editor.jpg) 

 That’s it! Restart your computer, and you’ll see that Microsoft Defender is disabled.

 If you want to enable Microsoft Defender in the future, set the “Turn Off Microsoft Defender Antivirus” policy to “Disable.” After that, turn on the “Real-time Protection” and “Tamper Protection” toggles in the Windows Security app."

![Disabled option in the Local Group Policy Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/disabled-option-in-the-local-group-policy-editor.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Check the State of Microsoft Defender on Windows 11

 Once you’ve disabled Microsoft Defender using the above method, you must check its state to confirm if it has actually been disabled. To do this, open the Start menu, type **PowerShell** in the search bar, and press Enter. Then, in the PowerShell window, type the following command and hit Enter:

        `Get-MpComputerStatus | select AMRunningMode`
    
 If you get “Not Running” as the result, then it confirms that you have disabled Microsoft Defender.

![PowerShell window showing Not Running in result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/powershell-window-showing-not-running-in-result.jpg) 

 However, if you get “Normal” as the result, it means Microsoft Defender is still running on your computer. In this case, double-check that you followed the steps correctly.

![PowerShell window showing Normal in result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/powershell-window-showing-normal-in-result.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
---

 Microsoft opted for the longer process to permanently disable Microsoft Defender instead of providing a one-click button to ensure computer safety. Even though it might be tempting, you really should disable it unless you absolutely need to.

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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2023s-social-media-shopping-top-tiktok-and-amazon-picks-for-2024/"><u>[New] 2023’S Social Media Shopping  Top TikTok and Amazon Picks for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-secrets-to-joining-friends-tiktok-live-events-for-2024/"><u>[Updated] Secrets to Joining Friends' TikTok Live Events for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-ultimate-guide-to-free-online-youtube-mp3-converters/"><u>[Updated] The Ultimate Guide to Free Online YouTube-MP3 Converters</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1-macx-dvd-ripper-pro-macx-video-converter-pro/"><u>1. 格安特典: 公式オフィシャル・サイトからMacX DVD Ripper Pro, MacX Video Converter Proを最安価で購入！</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-perfect-picture-spotlights-how-to-zoom-in-and-out-on-insta-stories/"><u>2024 Approved  Perfect Picture Spotlights  How to Zoom in & Out on Insta Stories</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top6/"><u>無料で動画サイズ変更！速度が速く、品質も低下しないフリー圧縮ソフトTop6のヒント</u></a></li>
<li><a href="https://some-approaches.techidaily.com/access-terrifying-telugu-and-lgbtqplus-short-films-for-free-via-youtube-downloads/"><u>Access Terrifying Telugu & LGBTQ+ Short Films for Free via YouTube Downloads</u></a></li>
<li><a href="https://extra-resources.techidaily.com/affordable-high-quality-asmr-recording-devices-revealed/"><u>Affordable, High-Quality ASMR Recording Devices Revealed</u></a></li>
<li><a href="https://some-approaches.techidaily.com/all-you-need-to-know-about-enjoying-content-on-apple-tv/"><u>All-You-Need-to-Know About Enjoying Content on Apple TV</u></a></li>
<li><a href="https://some-approaches.techidaily.com/best-5-top-rated-video-converters-for-ipad-ensuring-highest-quality-playback-on-your-device/"><u>Best 5 Top-Rated Video Converters for iPad: Ensuring Highest Quality Playback on Your Device</u></a></li>
<li><a href="https://some-approaches.techidaily.com/comment-acceder-au-contenu-video-dvd-en-mode-lecture-sur-ordinateurs-mac-guideline-complet/"><u>Comment Accéder Au Contenu Vidéo DVD en Mode Lecture Sur Ordinateurs Mac: Guideline Complet</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/demystifying-the-502-gateway-problem-tips-for-quick-recovery/"><u>Demystifying the 502 Gateway Problem: Tips for Quick Recovery</u></a></li>
<li><a href="https://some-approaches.techidaily.com/digiarty-software-insights-explore-sales-strategies-license-agreements-update-options-partnerships-technical-assistance-and-product-catalogs/"><u>Digiarty Software Insights: Explore Sales Strategies, License Agreements, Update Options, Partnerships, Technical Assistance, and Product Catalogs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/dvd-copy-and-convert-software-for-macos-best-alternatives-to-dvdfab/"><u>DVD Copy and Convert Software for macOS: Best Alternatives to DVDFab</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/edit-like-a-pro-gopro-video-editing-on-mac-for-beginners-for-2024/"><u>Edit Like a Pro GoPro Video Editing on Mac for Beginners for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/efficient-methods-to-clear-multiple-photos-at-once-on-an-iphone-plus/"><u>Efficient Methods to Clear Multiple Photos at Once on an iPhone (Plus)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/efficient-vob-to-avi-transformation-ultimate-guide-for-seamless-video-format-conversion/"><u>Efficient VOB to AVI Transformation: Ultimate Guide for Seamless Video Format Conversion</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-access-the-best-and-most-iconic-disney-bollywood-movies-original-songs-listed/"><u>Free Access: The Best & Most Iconic Disney-Bollywood Movies' Original Songs Listed!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-macx-software-convert-your-dvds-into-mp3-and-mp4-files-effortlessly/"><u>Free MacX Software: Convert Your DVDs Into MP3 and MP4 Files Effortlessly</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-macx-video-converter-ultimate-guide-to-convert-mkv-files-on-mac-with-ease/"><u>Free MacX Video Converter: Ultimate Guide to Convert MKV Files on Mac with Ease</u></a></li>
<li><a href="https://some-approaches.techidaily.com/how-to-correct-audio-discrepancies-when-burning-dvds-updated-techniques-explained/"><u>How to Correct Audio Discrepancies When Burning DVDs: Updated Techniques Explained</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-honor-x8b-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Honor X8b to Apple TV | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Google Pixel 8? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/join-our-10th-anniversary-tribute-to-iphone-participate-in-the-macxdvd-survey-for-an-exclusive-chance-at-winning-a-gift-card-from-itunes/"><u>Join Our 10Th Anniversary Tribute to iPhone – Participate in the MacXDVD Survey for an Exclusive Chance at Winning a Gift Card From iTunes!</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/learn-urdu-online-in-just-10-minutes-a-day/"><u>Learn Urdu Online in Just 10 Minutes a Day</u></a></li>
<li><a href="https://some-approaches.techidaily.com/simplify-your-workflow-with-the-leading-vr-video-conversion-tools-on-the-market-today/"><u>Simplify Your Workflow with the Leading VR Video Conversion Tools on the Market Today</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-curser-pause-on-windows-10-black/"><u>Solving Curser Pause on Windows 10 Black</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-gecastete-filme-fur-den-sommer-2016-und-deren-erfolg-am-kinokasse-best-practices-zum-herunterladen/"><u>Top Gecastete Filme Für Den Sommer 2016 Und Deren Erfolg Am Kinokasse: Best Practices Zum Herunterladen</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-ranked-photo-organization-tools-compatible-with-mac-and-windows-systems/"><u>Top-Ranked Photo Organization Tools Compatible with Mac and Windows Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transform-your-dvds-into-digital-format-using-these-5-free-methods/"><u>Transform Your DVDs Into Digital Format Using These 5 Free Methods</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/transform-your-video-how-to-flip-a-clip-in-final-cut-pro-for-2024/"><u>Transform Your Video How to Flip a Clip in Final Cut Pro for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/ultimate-guide-to-high-quality-mac-frames-max-156-chars-for-2024/"><u>Ultimate Guide to High-Quality Mac Frames (Max 156 Chars) for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/ultimate-low-cost-gaming-setups-keyboard-picks/"><u>Ultimate Low-Cost Gaming Setups  Keyboard Picks</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-how-to-restore-audio-in-avidemux-a-comprehensive-solution-for-2024/"><u>Updated How to Restore Audio in Avidemux A Comprehensive Solution for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/x-dvdandhd-macx-dvd/"><u>マックX DVDリッパープロ&HDビデオコンバータープロ: MacX DVD最大割引セールで最安値購入方法</u></a></li>
</ul></div>

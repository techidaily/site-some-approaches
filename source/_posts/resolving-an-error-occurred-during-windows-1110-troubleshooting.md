---
title: Resolving 'An Error Occurred' During Windows 11/10 Troubleshooting
date: 2024-08-30T21:20:32.090Z
updated: 2024-08-31T21:20:32.090Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/52781763425_7caa012745_o.jpg
---

## Resolving 'An Error Occurred' During Windows 11/10 Troubleshooting

### Key Takeaways

* Try launching the troubleshooter from the Settings app on your Windows 11 or 10 PC.
* Restart the "Background Intelligent Transfer Service" and "Cryptographic Services" services.
* If the issue persists, fix Windows' damaged system files with DSM and SFC, try to use the troubleshooter in safe mode, or reset your Windows PC.

 If you’ve encountered an “An error occurred while troubleshooting” error while launching a troubleshooter, worry not, as fixing this issue is easy in most cases. Here’s how to do that on your Windows 11 or Windows 10 PC.

 After applying each fix, launch your troubleshooter to check if it’s working.

##  Run the Troubleshooter From Settings

 While Windows allows you to [launch the built-in troubleshooters](https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-honor-play-40c-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) from the Run dialog box, we recommend opening those tools from Settings, as this is where the tools are hosted.

 To do that, [open the Settings app](https://facebook-video-footage.techidaily.com/updated-2024-approved-5-easy-ways-to-multiply-your-youtube-follower-base/) by pressing Windows+i. On Windows 11, head into System > Troubleshoot > Other Troubleshooters. On Windows 10, go to Update & Security > Troubleshoot > Additional Troubleshooters.

 Find the troubleshooting tool to launch. On Windows 11, next to the troubleshooter, select "Run."

!['Run' highlighted for multiple troubleshooters in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-troubleshooter-windows-11-settings-1.jpg) 

 On Windows 10, click the troubleshooter and choose "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for a troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-troubleshooter-windows-10-settings.jpg) 

 The tool will launch.

##  Restart the Required Windows Services

 The built-in troubleshooters rely on various Windows services to function. These services might not be working correctly, causing an error. Give these services a reboot to fix the problem.

 Open the Run dialog box by pressing Windows+R, then type the following in the box and press Enter:

services.msc

 Find the service named "Background Intelligent Transfer Service." Right-click it and select "Restart."

!['Restart' highlighted for the 'Background Intelligent Transfer Service' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-restart-bits-service.jpg) 

 Similarly, right-click the "Cryptographic Services" service and select "Restart."

!['Restart' highlighted for the 'Cryptographic Services' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-restart-cryptographic-services-service.jpg) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Close the Services window.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Fix Broken Troubleshooters

 It’s possible Windows’ system files are corrupted, causing the troubleshooters to malfunction. In this case, you must [repair the damaged core files](https://some-guidance.techidaily.com/twirl-forge-instruments-for-2024/) using the built-in System File Checker (SFC) tool.

 To do that, open the Start Menu, search for **Command Prompt**, and select "Run as Administrator."

!['Run as Administrator' highlighted for Command Prompt in Windows Search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-open-cmd-as-admin.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 In the User Account Control"(UAC) prompt, select "Yes."

 In Command Prompt, type the following command and press Enter. This command will download the files required to fix the broken system files.

DISM.exe /Online /Cleanup-image /Restorehealth

![The DISM command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-run-dism-command-in-cmd.jpg) 

 Next up, run the following command to begin finding and repairing the damaged system files:

sfc /scannow

[Restart your Windows 11](https://screen-video-capture.techidaily.com/updated-in-2024-addressing-mute-problems-in-obs-live-recording/) or [Windows 10](https://article-posts.techidaily.com/comparing-the-creme-de-la-creme-gopro-hero5-black-to-hero4-silver-for-2024/) PC once it finishes.

##  Launch the Troubleshooter in Safe Mode

[Safe mode on Windows](https://video-capture.techidaily.com/new-essential-scripting-instant-stopwatch-integration-in-obs-for-2024/) lets you check if third-party apps are preventing you from performing your tasks. In safe mode, Windows only loads the essential files to boot the system, letting you check for interference from any third-party programs or drivers.

 To [start your Windows 11 PC in safe mode](https://buynow-marvelous.techidaily.com/unveiling-the-strong-battery-feature-in-moto-g-power-a-tech-review-insight/), go to Settings > System > Recovery. Next to "Advanced Startup," click "Restart Now."

!['Restart Now' highlighted for 'Advanced Startup' in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-advanced-restart-windows-11.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
 To [boot your Windows 10 PC in safe mode](https://screen-recording.techidaily.com/updated-leveraging-obs-establishing-an-efficient-countdown-clock/), head into Settings > Update & Security > Recovery. In the "Advanced Startup" section, click "Get Started."

!['Get Started' highlighted for 'Advanced Startup' in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-advanced-restart-windows-10.jpg) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When your PC reboots, navigate to Troubleshoot > Advanced Options > Startup Settings and select "Restart." Then, choose the number for safe mode to boot into that mode. When your PC enters safe mode, launch the troubleshooter you wanted to use.

 If the tool works, a third-party app is likely the culprit. Review the list of your installed apps and remove any suspicious ones. It’s quick and easy to [uninstall apps on Windows 11](https://youtube-docs.techidaily.com/ed-in-2024-strategies-for-using-youtube-to-boost-classroom-engagement/) and [Windows 10](https://tech-recovery.techidaily.com/top-savings-on-apple-watches-in-april/).

##  Reset Windows

 If nothing else works, you can reset your Windows 11 or Windows 10 PC to the factory defaults. Resetting the system will fix any issues related to settings or corrupted files, but it should only be used as an last resort.

 You’ll lose your installed apps when you reset your PC. You’ll have the option to keep your personal files, though.

 To [reset a Windows 11 PC](https://facebook-video-footage.techidaily.com/new-blueprints-for-breaking-ground-in-edu-video-production-on-youtube-channels-for-2024/), navigate to Settings > System > Recovery. Next to "Reset This PC," click "Reset PC."

!['Reset PC' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-reset-windows-11-pc.jpg) 

 To [reset a Windows 10 PC](https://instagram-videos.techidaily.com/fast-and-free-strategies-for-authenticity-in-insta-circles-for-2024/), go to Settings > Update & Security > Recovery. In the "Reset This PC" section, click "Get Started."

!['Get Started' highlighted in the 'Reset This PC' section of Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-restart-windows-10-pc.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
 On the open window, select "Keep My Files" so Windows doesn’t delete your personal files. Then, follow the on-screen instructions to finish resetting your computer.

 Your troubleshooting tool should work once your machine is back to the default settings.

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-craft-engaging-visual-narratives-with-soundtrack-integration/"><u>[New] 2024 Approved  Craft Engaging Visual Narratives with Soundtrack Integration</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-innovative-tips-producing-instagram-ready-loop-videos/"><u>[New] 2024 Approved  Innovative Tips  Producing Instagram-Ready Loop Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-bypassing-identification-to-explore-instagram-stories-desktop-android-ios-for-2024/"><u>[New] Bypassing Identification to Explore Instagram Stories [Desktop, Android, iOS] for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-elevate-your-video-presence-with-swiftly-created-captions-and-text-on-fb/"><u>[New] In 2024, Elevate Your Video Presence with Swiftly Created Captions and Text on FB</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-get-your-favorite-podcasts-and-videos-anytime-on-the-go-with-these-tools-for-2024/"><u>[Updated] Get Your Favorite Podcasts & Videos Anytime, On-the-Go, With These Tools for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-unwinding-film-narratives-the-art-of-reversing-on-instagram/"><u>[Updated] In 2024, Unwinding Film Narratives  The Art of Reversing on Instagram</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-sky-high-success-on-social-media-mastering-dji-drone-streams-for-2024/"><u>[Updated] Sky-High Success on Social Media  Mastering DJI Drone Streams for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-the-ultimate-compilation-top-6-downloader-apps-for-facebooks-lite-version-for-2024/"><u>[Updated] The Ultimate Compilation  Top 6 Downloader Apps for Facebook's Lite Version for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-the-ultimate-guide-to-replacing-bandicam-on-mac-systems/"><u>[Updated] The Ultimate Guide to Replacing Bandicam on Mac Systems</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-gopro-studio-steps-for-time-lapse-magic/"><u>[Updated] Ultimate GoPro Studio Steps for Time Lapse Magic</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mp3-mac-mp3/"><u>「オマ Mp3 Mac音声変換ソフト | ムービーファイルをmp3に無料で変換」</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1724766318826-dvd/"><u>「マッキーでDVDコピー：初めて触れる人への手順と振り返りガイド付き詳細解説」</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1-how-to-erase-icloud-backup-data-from-your-iphone-or-ipad-a-comprehensive-guide/"><u>1. How to Erase iCloud Backup Data From Your iPhone or iPad: A Comprehensive Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1-why-cant-i-add-movies-to-my-itunes-library-best-troubleshooting-tips-and-fixes/"><u>1. Why Can't I Add Movies to My iTunes Library? Best Troubleshooting Tips & Fixes</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-oppo-a18-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-hues-in-harmony-applying-color-principles/"><u>2024 Approved  Hues in Harmony  Applying Color Principles</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024mp3/"><u>2024最新MP3変換ツール：無料で使いやすく、高速かつ機能も充実したフリーソフトをご紹介！</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1724766172510-itunes/"><u>最強手段でイヤフォンとiTunesを完璧同期するコツ - 悲鳴無しのパーフェクトマッチ</u></a></li>
<li><a href="https://some-approaches.techidaily.com/dvd-2024-mac/"><u>最新DVDコピーソフトが完全無料! 2024 Mac対応モデルを特集 - おすすめの人気ソフトで満載!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1724766658071-anydvd/"><u>AnyDVDアプリケーションガイド: ダウンロードから初期設定、暗号化回避、クラッキングについて</u></a></li>
<li><a href="https://some-approaches.techidaily.com/download-uefa-euro-2er-2021-complete-roster-and-matches-for-free-in-ultra-clear-4khd-from-youtube-streaming/"><u>Download UEFA Euro 2Er 2021 Complete Roster and Matches for Free in Ultra-Clear 4K/HD From YouTube Streaming</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-hd-8k-downloads-of-rio-de-janeiro-2016-olympic-games-footage/"><u>Free HD 8K Downloads of Rio De Janeiro 2016 Olympic Games Footage</u></a></li>
<li><a href="https://some-approaches.techidaily.com/hd-and-sd-mpeg-macx-mac/"><u>HD & SD ビデオを容易にMPEG形式へ - MacX: Mac上で最適化されたフリーダウンロードソフト</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-do-i-sim-unlock-my-apple-iphone-14-pro-max-by-drfone-ios/"><u>How Do I SIM Unlock My Apple iPhone 14 Pro Max?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/how-to-use-handbrake-for-dvd-conversion-to-m4v-files-different-from-standard-mp4-output/"><u>How to Use Handbrake for DVD Conversion to M4V Files, Different From Standard MP4 Output</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-asus-rog-phone-8-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Asus ROG Phone 8 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-oppo-f23-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Oppo F23 5G Devices | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/intel-thunderbolt-interface-drivers-smooth-and-easy-setup-for-free/"><u>Intel Thunderbolt Interface Drivers - Smooth & Easy Setup for Free!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/is-fake-gps-location-spoofer-a-good-choice-on-realme-c51-drfone-by-drfone-virtual-android/"><u>Is Fake GPS Location Spoofer a Good Choice On Realme C51? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/join-our-social-media-giveaway-for-macxdvd-aficionados-and-save-big-get-entire-software-at-no-cost/"><u>Join Our Social Media Giveaway for MacXDVD Aficionados and Save Big – Get Entire Software at No Cost!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macx-dvd-macx-hdwindowsd/"><u>MacX DVD最大割引: MacX HD動画変換プロフェッショナルWindows版セールスペリオDがこちら</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macxdvd-software-licensing-agreement-key-points-explained-for-consumers/"><u>MacXDVD Software Licensing Agreement: Key Points Explained for Consumers</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-this-article-points-out-the-key-differences-between-after-effects-and-premiere-to-get-a-clearer-understanding-of-what-is-best-for-2024/"><u>New This Article Points Out the Key Differences Between After Effects and Premiere to Get a Clearer Understanding of What Is Best for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/portable-frozen-fun-how-to-legally-acquire-stream-and-watch-disneys-ice-queen-adventure-on-the-move/"><u>Portable Frozen Fun: How to Legally Acquire, Stream, and Watch Disney’s Ice Queen Adventure On-the-Move</u></a></li>
<li><a href="https://some-approaches.techidaily.com/preserving-clarity-in-editing-guide-to-non-interlaced-video-processing/"><u>Preserving Clarity in Editing: Guide to Non-Interlaced Video Processing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/profi-aufnahmetipps-top-programme-zur-herstellung-von-screenshots-auf-dem-macos/"><u>Profi-Aufnahmetipps: Top-Programme Zur Herstellung Von Screenshots Auf Dem macOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/qualitatsbewahrend-dvd-zu-mkv-konvertierung-auf-einem-mac-schritt-fur-schritt-anleitung/"><u>Qualitätsbewahrend DVD-Zu-MKV Konvertierung Auf Einem Mac - Schritt-Für-Schritt-Anleitung</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-vivo-x100-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-guide-cropping-your-screen-capture-images-in-macos/"><u>Step-by-Step Guide: Cropping Your Screen Capture Images in macOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-greatest-world-cup-goals-in-history-a-comprehensive-guide-to-the-top-five-scoring-masterpieces/"><u>The Greatest World Cup Goals in History: A Comprehensive Guide to the Top Five Scoring Masterpieces</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-11-free-music-downloader-applications-for-ios-android-and-ipad-a-comprehensive-guide/"><u>Top 11 FREE Music Downloader Applications for iOS, Android & iPad: A Comprehensive Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-free-macmp4-players-ultimate-guide-to-the-best-mp4-viewer-apps/"><u>Top Free MacMP4 Players: Ultimate Guide to the Best MP4 Viewer Apps</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transform-dvds-to-digital-on-macos-with-macx-download-free-dvd-ripper-software-and-stream-seamlessly-to-youtube-flvmp4mp3/"><u>Transform DVDs to Digital on macOS with MacX - Download FREE DVD Ripper Software and Stream Seamlessly to YouTube, FLV/MP4/MP3</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-guide-to-high-efficiency-video-minimizers-cutting-down-footage-size-by-90-while-preserving-excellent-visuals/"><u>Ultimate Guide to High-Efficiency Video Minimizers: Cutting Down Footage Size by 90%% While Preserving Excellent Visuals</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-guide-discover-the-top-11-free-dvd-crackers-for-safe-extraction-of-secure-movies/"><u>Ultimate Guide: Discover the Top 11 Free DVD Crackers for Safe Extraction of Secure Movies</u></a></li>
<li><a href="https://win-dash.techidaily.com/upgrade-your-headphones-now-instant-nahimic-driver-enhancement/"><u>Upgrade Your Headphones Now - Instant Nahimic Driver Enhancement!</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-realme-gt-5-pro-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Realme GT 5 Pro Offline? Troubleshooting Guide | Dr.fone</u></a></li>
</ul></div>

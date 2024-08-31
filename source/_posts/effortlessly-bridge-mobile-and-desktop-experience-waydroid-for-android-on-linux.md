---
title: "Effortlessly Bridge Mobile and Desktop: Experience WayDroid for Android on Linux"
date: 2024-08-30T21:19:58.580Z
updated: 2024-08-31T21:19:58.580Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d01c44a9ae23f7efe9fb5e1960e68d56b4d2035c87f626ffb448d9a10326cec7.png
---

## Effortlessly Bridge Mobile and Desktop: Experience WayDroid for Android on Linux

### Key Takeaways

* WayDroid lets you launch a complete Android system on Linux with Google Play Services so you can install your favorite apps.
* You can install it on most major Linux distros, but be sure to choose the "GAPPS" Android type during WayDroid's setup. You'll also need to get your device certified by visiting Google's website.
* Once you're certified, launch WayDroid and open the Play Store to start installing apps.

 Looking to run Android apps on your Linux desktop? Learn how to use WayDroid to turn your Linux desktop or laptop into an Android app powerhouse.

##  What Is WayDroid?

 WayDroid is a container-based tool that allows for launching a complete Android system within the Linux desktop. It does this with Linux namespaces, effectively utilizing the Linux kernel. In simple terms, namespaces are a feature that helps isolate and separate parts of a computer so that it is possible to run each part independently as if it is the only one on the computer.

 If you're trying to run Android apps on Linux, WayDroid is the way to do it, and former "Android on Linux" tools [like Anbox](https://iphone-location.techidaily.com/a-full-review-for-itools-virtual-location-and-top-5-alternatives-for-apple-iphone-8ipad-drfone-by-drfone-virtual-ios/) recommend it. WayDroid is compatible with a wide variety of Linux distributions and CPU architectures. Additionally, it harnesses Android's Mesa technology to enable efficient GPU pass-through from the container to the host system, which enhances the performance of graphical applications, ensuring a smooth user experience.

##  Setting Up WayDroid in No Time

 To get started with WayDroid on your Linux desktop or laptop, open a terminal window. You can do this by pressing Ctrl+Alt+T on your keyboard or searching for "Terminal" in your Linux app menu. Follow the steps below to install WayDroid:

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Ubuntu or Debian Installation

 For users on Ubuntu, Debian, or derivatives, begin by installing the "curl" tool, which is necessary for running WayDroid's official installation script. First, Install curl:

sudo apt install curl

 After setting up curl, run the official WayDroid installation script with curl:

curl -s https://repo.waydro.id/ | sudo bash

 After the script is completed, install the WayDroid package:

sudo apt install waydroid

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
###  WayDroid on Other Linux Distributions

 WayDroid enjoys broad support across various Linux platforms. While the installation script primarily targets Ubuntu and Debian-based systems, other distributions can run WayDroid. If you're looking to install WayDroid on your Linux device, search for WayDroid packages on [Pkgs.org](https://pkgs.org/search/?q=waydroid) to find compatible installation options.

 If you're unable to find a package to install WayDroid on your system at Pkgs.org, consider checking out the [official WayDroid documentation](https://docs.waydro.id/) for information on how you can get it working on your Linux workstation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
##  The WayDroid Experience

 WayDroid stands out as a great tool for Linux, especially as it helps get the best out of your device by enabling the integration of Android applications into the Linux environment. Unlike many alternatives that offer Android compatibility, WayDroid excels in ease of use and system integration.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Installing Android Apps with WayDroid on Linux

 To enjoy Android apps on Linux through WayDroid, first open WayDroid from the Linux application menu. The "Initialize Waydroid" window will appear on the first launch. When the "Initialize WayDroid" window is open, navigate to the "Android Type" option and choose "GAPPS" to integrate [Google Play Services](https://tech-recovery.techidaily.com/top-11-free-movie-downloading-websites-you-should-know-about/). Hit the "Download" button to begin downloading and installing your Android container. This might take a while, so patience is key.

![The WayDroid initialization wizard on Ubuntu, showing the download options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/waydroid-init.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 After installation, click "Done" in the "Initialize WayDroid" window to start WayDroid Android. Upon the first startup, a notification may indicate that the device isn’t certified to run Google Play apps. You now need to certify your Android device. Certification is required, as without it, you cannot install Android applications on WayDroid via the Google Play Store.

 Open a terminal and enter **sudo waydroid shell**. Execute the command to display your device's Android ID:

ANDROID_RUNTIME_ROOT=/apex/com.android.runtime ANDROID_DATA=/data ANDROID_TZDATA_ROOT=/apex/com.android.tzdata ANDROID_I18N_ROOT=/apex/com.android.i18n sqlite3 /data/data/com.google.android.gsf/databases/gservices.db "select * from main where name = 'android_id';"

 After you've found your ID, you need to submit it to Google for device verification purposes. To do this, visit the [Google "Uncertified" page](https://www.google.com/android/uncertified) and enter the code shown in your terminal. With your Android device registered with Google, restart WayDroid using the terminal commands **waydroid session stop** and then **waydroid session start** following that.

 You can now install Android apps. To start, open the Play Store app within WayDroid, sign in with your Google account.

![The WayDroid Android launcher showing the Google Play Store icon, with an arrow pointing to the user instructing them to open it.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/waydroid-select-play-store.png) 

 Once you've logged in, you can search the Google Play Store for your favorite apps.

![The Google Play Store search box in WayDroid. The user is searching for the Audible app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/waydroid-search-for-audible.png) 

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Just select "Install," to download it directly to your Linux system.

![The Google Play Store in WayDroid. The user is searching for Audible, and Google Play is showing it as the top search result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/waydroid-google-play-store-2.jpg) 

---

 WayDroid is an excellent tool to run Android apps on Linux, and most apps run quite well on the platform. Give WayDroid a try and install your favorite apps with it. Once you do, you'll find that WayDroid is a worthy addition to the Linux desktop.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-exclusive-access-to-free-switch-clones-for-2024/"><u>[New] Exclusive Access to Free Switch Clones for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-tiny-tranquil-houses-japanese-style/"><u>[New] In 2024, Tiny Tranquil Houses  Japanese Style</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-look-best-iphone-camera-aids/"><u>[New] In-Depth Look  Best iPhone Camera Aids</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-latest-trends-in-360-cameras-a-shoppers-companion/"><u>[New] Latest Trends in 360 Cameras – A Shopper's Companion</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-chorus-chronicles-a-guide-to-audio-selection-for-ig/"><u>[Updated] Chorus Chronicles  A Guide to Audio Selection for IG</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-humor-harmony-optimal-websites-for-fun-ringtones/"><u>[Updated] Humor Harmony  Optimal Websites for Fun Ringtones</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-signal-of-a-block-missed-snaps-and-none-left/"><u>[Updated] In 2024, Signal of a Block  Missed Snaps and None Left</u></a></li>
<li><a href="https://some-approaches.techidaily.com/dvd-decrypterand/"><u>「無料日本語版DVD Decrypterダウンロード&使用ガイド」</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mp3-mac-mp3/"><u>「オマ Mp3 Mac音声変換ソフト | ムービーファイルをmp3に無料で変換」</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-benq-sw320-review-a-gateway-to-true-high-definition/"><u>2024 Approved  BenQ SW320 Review  A Gateway to True High Definition</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-kickstart-profits-earnings-blueprint-for-periscope-novices/"><u>2024 Approved  Kickstart Profits  Earnings Blueprint for Periscope Novices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1724766658071-anydvd/"><u>AnyDVDアプリケーションガイド: ダウンロードから初期設定、暗号化回避、クラッキングについて</u></a></li>
<li><a href="https://windows11.techidaily.com/balance-usage-and-energy-efficiency-with-automatic-rest-mode/"><u>Balance Usage & Energy Efficiency with Automatic Rest Mode</u></a></li>
<li><a href="https://some-approaches.techidaily.com/best-mp4-to-mp3-convertors-on-a-mac-free-vs-premium-options-top-9/"><u>Best MP4 to MP3 Convertors on a Mac: Free Vs. Premium Options (TOP 9)</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-paths-blocked-by-shared-printers/"><u>Clearing Paths Blocked by Shared Printers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/come-creare-file-iso-da-dvd-su-un-mac-inclusi-sistemi-con-big-sur/"><u>Come Creare File ISO Da DVD Su Un Mac, Inclusi Sistemi Con Big Sur</u></a></li>
<li><a href="https://tech-hub.techidaily.com/comparing-chatgpt-and-huggingchat-determining-the-superior-conversation-ai/"><u>Comparing ChatGPT and HuggingChat: Determining the Superior Conversation AI</u></a></li>
<li><a href="https://some-approaches.techidaily.com/compress-and-convert-dvd-movies-on-macos-with-dvd-shrink/"><u>Compress and Convert DVD Movies on macOS with DVD Shrink</u></a></li>
<li><a href="https://some-approaches.techidaily.com/convert-dvds-and-videos-to-compatible-formats-mp4-h264-mp3-on-mac-for-ipad-viewing/"><u>Convert DVDs and Videos to Compatible Formats (MP4, H.264, MP3) on Mac for iPad Viewing</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cutting-edge-20-public-domain-pubg-slideshows/"><u>Cutting-Edge 20 Public Domain PUBG Slideshows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-whos-behind-microsofts-chatgpt-technology/"><u>Discover Who's Behind Microsoft's ChatGPT Technology</u></a></li>
<li><a href="https://some-approaches.techidaily.com/download-uefa-euro-2er-2021-complete-roster-and-matches-for-free-in-ultra-clear-4khd-from-youtube-streaming/"><u>Download UEFA Euro 2Er 2021 Complete Roster and Matches for Free in Ultra-Clear 4K/HD From YouTube Streaming</u></a></li>
<li><a href="https://some-approaches.techidaily.com/download-unrestricted-mac-dvd-ripping-software-free-clean-outputs-and-easy-to-use-interface/"><u>Download Unrestricted Mac DVD Ripping Software: Free, Clean Outputs & Easy-to-Use Interface</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1724766368369-dvd/"><u>DVDの最大限圧縮：安全でストリーミングが利用可能な無料解決法！高画質保持方法を学ぶ</u></a></li>
<li><a href="https://some-approaches.techidaily.com/enhancing-4k-video-encoding-speed-using-hardware-assisted-hevc-technology/"><u>Enhancing 4K Video Encoding Speed Using Hardware-Assisted HEVC Technology</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-mac-x-mkv-transcoder-hassle-free-high-definition-video-conversion-for-macos-users/"><u>Free Mac X MKV Transcoder: Hassle-Free High Definition Video Conversion for macOS Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/free-mobile-image-editing-tools-top-10-overlay-app-list/"><u>Free Mobile Image Editing Tools - Top 10 Overlay App List</u></a></li>
<li><a href="https://some-approaches.techidaily.com/guide-watching-itunes-m4v-content-on-your-chromecast-device/"><u>Guide: Watching iTunes M4V Content on Your Chromecast Device</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-achieve-crystal-clear-sounds-on-windows-11-mastering-the-equalizer-technique/"><u>How to Achieve Crystal Clear Sounds on Windows 11 - Mastering the Equalizer Technique</u></a></li>
<li><a href="https://some-approaches.techidaily.com/how-to-guides-for-dvd-movie-enjoyment-a-step-by-step-tutorial/"><u>How-To Guides for DVD Movie Enjoyment: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-twitters-quick-fix-for-downloading-funny-images-on-pc/"><u>In 2024, Twitter's Quick-Fix for Downloading Funny Images on PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ios-macx-mediatrans-mac/"><u>IOSデータ管理・バックアップのプロフェッショナル ソリューション：MacX MediaTrans 推奨 Macユーザー向け</u></a></li>
<li><a href="https://some-approaches.techidaily.com/iphone-10s-milestone-moment-join-macxdvds-limited-time-sweepstakes-and-win-exclusive-rewards/"><u>IPhone 10'S Milestone Moment - Join MacXDVD’s Limited-Time Sweepstakes & Win Exclusive Rewards!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/is-it-time-to-switch-a-comparison-of-macos-ventura-and-monterey/"><u>Is It Time to Switch? A Comparison of macOS Ventura and Monterey</u></a></li>
<li><a href="https://some-approaches.techidaily.com/keine-powerdvd-version-fur-mac-entdecken-sie-hier-andere-videoabspielsoftware/"><u>Keine PowerDVD-Version Für Mac? Entdecken Sie Hier Andere Videoabspielsoftware!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/kostenloser-download-von-ultrahochauflosenden-3d-filmen-in-voller-1080p4k-uhd-qualitat-fur-moderne-3d-fernseher/"><u>Kostenloser Download Von Ultrahochauflösenden 3D Filmen - In Voller 1080P/4K-UHD-Qualität Für Moderne 3D-Fernseher.</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mac-and-windows-dvddvd/"><u>Mac & Windowsに最適: DVDストレッチエラーを解決し、読み込み・コピー不可能なDVDの修正方法</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macx-dvd-ripper-pro-windows70/"><u>MacX DVD Ripper Pro 特別価格: 「官方」でWindows版70%%オフクーポンが手に入る！</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macx-mediatrans-takes-the-lead-with-groundbreaking-features-for-managing-itunes-downloads-and-deleting-photos-from-your-devices-memory/"><u>MacX MediaTrans Takes the Lead with Groundbreaking Features for Managing iTunes Downloads and Deleting Photos From Your Device's Memory</u></a></li>
<li><a href="https://screen-capture.techidaily.com/premium-choices-for-unparalleled-video-communication/"><u>Premium Choices for Unparalleled Video Communication</u></a></li>
<li><a href="https://some-approaches.techidaily.com/quick-and-efficient-mac-video-conversion-with-intel-quick-sync-video/"><u>Quick and Efficient Mac Video Conversion with Intel Quick Sync Video</u></a></li>
<li><a href="https://some-approaches.techidaily.com/seamlessly-transform-torrent-downloads-into-mp4-format-for-all-devices-without-cost-windows-android-and-mac-compatible/"><u>Seamlessly Transform Torrent Downloads Into MP4 Format for All Devices without Cost – Windows, Android, and Mac Compatible</u></a></li>
<li><a href="https://some-approaches.techidaily.com/simple-steps-to-save-youtubess-subtitles-for-mac-users-without-worry/"><u>Simple Steps to Save YouTubes's Subtitles for Mac Users Without Worry</u></a></li>
<li><a href="https://extra-support.techidaily.com/standard-rgb-versus-srgb-standards-for-2024/"><u>Standard Rgb Versus Srgb Standards for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-tutorial-on-seamless-movie-transfers-between-ipad-and-mac-devices/"><u>Step-by-Step Tutorial on Seamless Movie Transfers Between iPad and Mac Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-11-free-music-downloader-applications-for-ios-android-and-ipad-a-comprehensive-guide/"><u>Top 11 FREE Music Downloader Applications for iOS, Android & iPad: A Comprehensive Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-macs-for-seamless-video-editing-simplify-your-workflow-today/"><u>Top Macs for Seamless Video Editing: Simplify Your Workflow Today</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-ranking-tools-for-transforming-videos-into-perfect-format-for-instagram-shares/"><u>Top-Ranking Tools for Transforming Videos Into Perfect Format for Instagram Shares</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transfer-iron-man-3-movie-from-dvd-with-drm-onto-mobile-devices-like-iphone-ipad-and-android-on-the-go-viewing-guide/"><u>Transfer Iron Man 3 Movie From DVD with DRM Onto Mobile Devices Like iPhone, iPad & Android - On-The-Go Viewing Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/troubleshooting-guide-resolving-ios-17-stagnation-during-iphone-software-update/"><u>Troubleshooting Guide: Resolving iOS 17 Stagnation During iPhone Software Update</u></a></li>
<li><a href="https://some-approaches.techidaily.com/troubleshooting-itunes-unknown-error-0xe80n0065-when-attempting-iphone-connection/"><u>Troubleshooting iTunes Unknown Error (0xE80n0065) When Attempting iPhone Connection</u></a></li>
<li><a href="https://some-approaches.techidaily.com/troubleshooting-the-transfer-to-ios-feature-complete-solution-tutorial/"><u>Troubleshooting the 'Transfer to iOS' Feature - Complete Solution Tutorial</u></a></li>
<li><a href="https://some-approaches.techidaily.com/tutorial/"><u>Tutorial</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/twitch-and-youtube-a-comprehensive-streamers-guide/"><u>Twitch and YouTube  A Comprehensive Streamer's Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-guide-to-bypassing-dvd-regional-lockouts-on-your-player/"><u>Ultimate Guide to Bypassing DVD Regional Lockouts on Your Player</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-guide-to-high-efficiency-video-minimizers-cutting-down-footage-size-by-90-while-preserving-excellent-visuals/"><u>Ultimate Guide to High-Efficiency Video Minimizers: Cutting Down Footage Size by 90%% While Preserving Excellent Visuals</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-guide-to-resolving-grounded-pc-crashes-in-2n-d-ensuring-seamless-gameplay/"><u>Ultimate Guide to Resolving Grounded PC Crashes in 2N-D, Ensuring Seamless Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-minimizing-dwms-impact-on-gpu-performance-in-windows-10-and-11/"><u>Ultimate Guide: Minimizing DWM's Impact on GPU Performance in Windows 10 and 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/understanding-the-distinctions-a-comprehensive-guide-to-mp3-vs-mp4-formats/"><u>Understanding the Distinctions: A Comprehensive Guide to MP3 vs MP4 Formats</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/which-ones-right-for-you-obs-or-twitch-studio-reviewed-for-2024/"><u>Which One's Right for You? - OBS or Twitch Studio Reviewed for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/dvd-macx-dvd-ripper-proshow/"><u>マックでDVDをリッパして変更する - MacX DVD Ripper Pro：ダウンロードから始めまSHOW！</u></a></li>
</ul></div>

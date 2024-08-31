---
title: How to Enable Missing Minimize/Maximize Icons for a Windows-Like Experience in Fedora OS
date: 2024-08-30T21:19:05.954Z
updated: 2024-08-31T21:19:05.954Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/hero-3.png
---

## How to Enable Missing Minimize/Maximize Icons for a Windows-Like Experience in Fedora OS

### Quick Links

* [Where Are the Standard Buttons?](https://facebook-clips.techidaily.com/the-like-factor-techniques-for-traffic-driving-facebook-content-for-2024/)
* [Restoring the Buttons Using GNOME Tweaks](https://facebook-record-videos.techidaily.com/updated-decoding-youtubes-user-comment-selection-criteria-for-2024/)
* [Restoring the Buttons Using the Command Line](https://youtube-sure.techidaily.com/24-fifas-best-players-trendy-videos-on-youtube/)
* [You’ve Always Got a Choice With Fedora](https://vp-tips.techidaily.com/updated-in-2024-breezy-blogging-quick-video-concept-ideas/)

### Key Takeaways

* Fedora's GNOME desktop lacks minimize and maximize buttons, making it confusing for newcomers.
* You can restore them with this command in a terminal window "gsettings set org.gnome.desktop.wm.preferences button-layout 'appmenu:minimize,maximize,close'." You can also use GNOME Tweaks to restore the missing buttons.
* Tweaking desktop settings in Linux is optional, but it offers the freedom to customize your Linux experience and to work around annoyances.

 Fedora’s GNOME desktop windows neither have minimize nor maximize buttons. It’s counterproductive because it makes the Linux desktop even more alien to newcomers. Here are two different ways to get them back.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
##  Where Are the Standard Buttons?

 Let’s clear this up, right out of the gate. It isn’t Fedora's fault. Other distributions such as Ubuntu have minimize and maximize buttons on GNOME, but Fedora didn’t remove the buttons. [The GNOME developers removed them](https://mail.gnome.org/archives/gnome-shell-list/2011-February/msg00192.html), a long time ago.

 Fedora Linux gives you GNOME in its untouched fresh-from-the-box state. The buttons are only present on the GNOME desktops of other distributions because those distributions have tweaked the version of GNOME they ship.

 I like [the GNOME desktop](https://some-guidance.techidaily.com/new-the-complete-vivacut-overview-editors-deep-dive/). It’s the desktop environment I recommend Linux newcomers cut their teeth with, and [Fedora is a great distribution for newbies](https://unlock-android.techidaily.com/full-guide-to-unlock-your-tecno-spark-20-pro-by-drfone-android/), so they go hand in hand. But those missing buttons confuse people. We’re so used to seeing them, that their absence is akin to a culture shock.

 There are other ways to remove a window from the desktop and return to it, effectively replacing the missing minimize and maximize functionality, but they’re not immediately apparent.

 Double-clicking a title bar will expand a window to fill the entire desktop. That’s great, but sometimes it’s easier said than done. On a browser with a lot of open tabs, for example, you can struggle to find a tiny gap between the tabs that you can double-click on. Dragging a window upwards so that it bounces against the top edge of the desktop will also maximize it.

 In GNOME, you don’t minimize windows. There’s nothing for a window to minimize _to_. There’s no taskbar like you have on Windows.

 If you’re running a dock, you can configure it to have an indicator beneath the launcher for that application, so that you know there’s a running instance of that application. Some docks support clicking the launcher icon to restore or hide an application. That only works when the dock is in view, though. If your dock is auto-hiding, you need to make the dock visible first, which makes it a two-step process.

 You can right-click the title bar of the application window and select "Hide" (or a similarly worded option) from the drop-down menu, but that’s a two-step process too.

 The official GNOME stance is you should be using workspaces to organize your windows, and the activities overview to switch between applications. GNOME also supports using Alt+Tab or Super+Tab to cycle through your running applications.

 All of these options are workable, but they’re not immediately apparent, and they’re not particularly discoverable. The good news is that if Canonical can tweak their GNOME to restore the minimize and maximize buttons, so can we. And there are two simple ways to do it.

##  Restoring the Buttons Using GNOME Tweaks

 The GNOME Tweaks tool lets you adjust a lot of desktop settings, not just the buttons in the title bar of a window. To install it on Fedora, type:

sudo dnf install gnome-tweaks

 To launch Tweaks, press the Super key and start to type “tweaks.” You’ll see the Tweaks icon.

![Launching GNOME Tweaks](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-6.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 Click the icon to start the program. The main screen of the application will appear. In the sidebar, click the "Windows" option.

![The main GNOME Tweaks window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-12.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You’ll see two sliders in the "Titlebar Buttons" section labeled "Maximize" and "Minimize."

![The Windows pane of the GNOME Tweaks tool](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-12.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
 To restore each of the missing buttons, activate the sliders by clicking on them. The buttons appear or disappear as soon as the sliders are moved.

![The GNOME Tweaks tool with the maximize and minimize buttons restored to the toolbar](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-9.png) 

 There’s also a toggle button labeled "Placement." You can use it to position the buttons at the left or right end of the window title bar.

##  Restoring the Buttons Using the Command Line

 We can use the gsettings command in a terminal window to turn on and off our maximize and minimize buttons.

 The command is quite long, but it’s actually very simple.

gsettings set org.gnome.desktop.wm.preferences button-layout 'appmenu:minimize,maximize,close'

 From left to right, we’re using the gsettings command with the set option to adjust some GNOME desktop preferences, specifically the button-layout options. We’re asking for the minimize, maximize, and close buttons to be present. As soon as you hit the Enter key, the buttons appear on the title bar of the terminal window.

![The minimize and maximize buttons restored and displayed in the titlebar of a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-10.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
 You can select any permutation of buttons, just include the name of the buttons you want and omit the ones you don’t want.

 Another trick you can do with this command is to set the buttons to appear on the left or right end of the window title bar. To have the buttons appear on the left, move the names of the buttons so that they are _before_ the “appmenu” list entry.

gsettings set org.gnome.desktop.wm.preferences button-layout 'minimize,maximize,close:appmenu'

![Using the gsettings command to position the minimize and maximize buttons to the left hand end of the titlebar](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-9.png) 

 As soon as you hit the Enter key on the command, the buttons move to the other side of the window title bar.

 The buttons are on the left, but they look a little odd. The close button is the innermost button, but it's usually the outermost one. Let’s fix that. The order of the buttons in the command dictates the order they appear on the title bar. We’ll move the close button to be first in the list of buttons.

gsettings set org.gnome.desktop.wm.preferences button-layout 'close,minimize,maximize:appmenu'

 That gives the window a more natural look.

![A terminal window with the close button outermost on the left hand end of the titlebar](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/11-2.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  You’ve Always Got a Choice With Fedora

 It’s rare that a Linux distribution or desktop environment exactly matches your personal preferences. There's usually some compromise somewhere along the line. Tweaking lets you adjust, work around, or remove little annoyances.

 Tweaking is optional. You don’t need to do it to use Linux, but it’s there if you want it. Some people tweak one or two little things that they don’t like, while others take tweaking to another level and completely customize their Linux experience. That’s why, when people ask me “What’s the best thing about Linux?”, I always tell them it’s freedom of choice.

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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-express-screen-snag-aural-elements/"><u>[New] 2024 Approved  Express Screen Snag  Aural Elements</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-quickening-instagram-video-streams-on-mobile-devices/"><u>[New] In 2024, Quickening Instagram Video Streams on Mobile Devices</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-solutions-for-missing-shorts-thumbnails-on-youtube/"><u>[New] Solutions for Missing Shorts Thumbnails on YouTube</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-getting-started-with-azures-speech-to-text-feature/"><u>[Updated] 2024 Approved  Getting Started with Azure's Speech-to-Text Feature</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-effortless-background-watching-of-youtube-on-mobile-for-2024/"><u>[Updated] Effortless Background Watching of YouTube on Mobile for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-enhancing-workflow-meeting-management-on-zoom-for-2024/"><u>[Updated] Enhancing Workflow  Meeting Management on Zoom for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-youtubers-overture-orchestrating-video-triumphs/"><u>[Updated] The YouTuber’s Overture  Orchestrating Video Triumphs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-unified-insight-the-easeus-perspective/"><u>2024 Approved  Unified Insight  The EaseUS Perspective</u></a></li>
<li><a href="https://driver-download.techidaily.com/bcm2045a0-driver-troubles-resolve-them-fast-and-smooth/"><u>BCM2045A0 Driver Troubles? Resolve Them Fast and Smooth!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/best-free-techniques-for-changing-wmv-videos-to-mp4-on-macos-devices/"><u>Best Free Techniques for Changing WMV Videos to MP4 on macOS Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/capture-crisp-4k-footage-60-fps-with-iphone-and-enjoy-effortless-playback-quality/"><u>Capture Crisp 4K Footage @ 60 FPS with iPhone & Enjoy Effortless Playback Quality</u></a></li>
<li><a href="https://some-approaches.techidaily.com/comparing-the-macbook-pro-and-air-retina-advantages-and-disadvantages-revealed/"><u>Comparing the MacBook Pro and Air Retina: Advantages and Disadvantages Revealed</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/complete-iphone-backup-solution-for-mac-securely-retrieve-erased-media-files-and-contacts/"><u>Complete iPhone Backup Solution for Mac: Securely Retrieve Erased Media Files and Contacts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/convert-videos-seamlessly-with-macx-pro-the-leading-solution-for-high-definition-hd4k-file-format-changes-on-macos/"><u>Convert Videos Seamlessly with MacX Pro: The Leading Solution for High-Definition (HD/4K) File Format Changes on macOS</u></a></li>
<li><a href="https://techtrends.techidaily.com/create-your-ideal-summer-day-with-these-7-edc-staples/"><u>Create Your Ideal Summer Day with These 7 EDC Staples</u></a></li>
<li><a href="https://some-approaches.techidaily.com/discover-superior-alternatives-for-converting-and-saving-youtube-videos-offline/"><u>Discover Superior Alternatives for Converting and Saving YouTube Videos Offline</u></a></li>
<li><a href="https://some-approaches.techidaily.com/download-and-stream-videos-anytime-top-alternatives-to-keepvid-for-pc-and-mac-users/"><u>Download and Stream Videos Anytime: Top Alternatives to KeepVid for PC & Mac Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/download-macx-top-rated-mac-dvd-to-mpeg-and-mp3-format-converter-freeware/"><u>Download MacX: Top-Rated Mac DVD to MPEG & MP3 Format Converter (Freeware)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/effortless-conversion-guide-changing-mkv-files-into-mov-to-play-on-apple-products-and-itunes-easily/"><u>Effortless Conversion Guide: Changing MKV Files Into MOV to Play on Apple Products & iTunes Easily</u></a></li>
<li><a href="https://some-approaches.techidaily.com/essential-insights-on-upgrading-from-jpeg-to-advanced-heifheic-format/"><u>Essential Insights on Upgrading From JPEG to Advanced HEIF/HEIC Format</u></a></li>
<li><a href="https://some-approaches.techidaily.com/explore-the-macx-collection-easy-online-shopping-at-the-official-macx-digital-outlet/"><u>Explore the MacX Collection: Easy Online Shopping at the Official MacX Digital Outlet</u></a></li>
<li><a href="https://facebook.techidaily.com/facebooks-journey-2004-present-adaptations-and-growth/"><u>Facebook's Journey: 2004-Present Adaptations and Growth</u></a></li>
<li><a href="https://some-approaches.techidaily.com/fehlerbehebung-fur-nicht-abspielbare-dvds-auf-dem-xbox-one-schnelllosungsguide/"><u>Fehlerbehebung Für Nicht Abspielbare DVDs Auf Dem Xbox One - Schnelllösungsguide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-effortless-mac-x-flv-video-transcoding-tool-no-cost-solution-for-flv-format-on-macos/"><u>FREE: Effortless Mac X FLV Video Transcoding Tool - No Cost Solution for FLV Format on macOS</u></a></li>
<li><a href="https://techtrends.techidaily.com/get-ahead-of-the-curve-with-details-on-the-upcoming-apple-watch-ultra-ebe-pricing-predictions-and-release-dates/"><u>Get Ahead of the Curve with Details on the Upcoming Apple Watch Ultra Ebe: Pricing Predictions and Release Dates!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/get-your-macx-mediatrans-now-at-a-low-price-purchase-securely-online/"><u>Get Your MacX MediaTrans Now at a Low Price - Purchase Securely Online!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/huge-savings-alert-snag-your-macx-mediatrans-with-a-staggering-63-discount/"><u>HUGE Savings Alert: Snag Your MacX MediaTrans with a Staggering 63%% DISCOUNT!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-gmail-password-on-honor-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Honor Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/iphone-drm/"><u>IPhone DRM解除アプリ一斉紹介：すべてのユーザーが楽しめる簡単操作</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mac-compatible-vob-file-transcoder-easily-convert-your-vob-videos-into-common-formats-like-mp4-avi-wmv-and-mov/"><u>Mac-Compatible VOB File Transcoder: Easily Convert Your VOB Videos Into Common Formats Like MP4, AVI, WMV & MOV</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macx-dvd-ripper-pro-lite/"><u>MacX DVD Ripper Pro Lite フォーウィンズで購入したら、リッピングソフトの使用を始めるためのライセンスコード登録ガイド</u></a></li>
<li><a href="https://some-approaches.techidaily.com/master-the-art-of-watching-webm-files-on-ios-devices/"><u>Master the Art of Watching WebM Files on iOS Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/master-video-format-conversion-effortlessly-make-your-videos-ready-for-iphone-ipad-apple-tv-and-itunes-playback/"><u>Master Video Format Conversion: Effortlessly Make Your Videos Ready for iPhone, iPad, Apple TV & iTunes Playback</u></a></li>
<li><a href="https://some-approaches.techidaily.com/master-your-device-the-best-app-for-seamlessly-handling-iphone-pictures-tunes-and-movies/"><u>Master Your Device: The Best App for Seamlessly Handling iPhone Pictures, Tunes & Movies</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mastering-the-art-of-capturing-youtube-videos-with-sound-a-comprehensive-guide-for-mac-users/"><u>Mastering the Art of Capturing YouTube Videos With Sound: A Comprehensive Guide for Mac Users</u></a></li>
<li><a href="https://discord-videos.techidaily.com/optimal-mobile-tech-for-discord-recording-for-2024/"><u>Optimal Mobile Tech for Discord Recording for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/paving-your-way-to-cost-savvy-cloud-choices/"><u>Paving Your Way to Cost-Savvy Cloud Choices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/revolutionize-playtime-unveiling-win11s-latest-titles/"><u>Revolutionize Playtime  Unveiling Win11's Latest Titles</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-tutorial-on-removing-dvd-region-restrictions-for-global-playback/"><u>Step-by-Step Tutorial on Removing DVD Region Restrictions for Global Playback</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-free-no-install-video-editing-tools-you-can-use-immediately/"><u>Top Free No-Install Video Editing Tools You Can Use Immediately</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-video-editing-software-for-macos-the-best-alternatives-to-imovie/"><u>Top Video Editing Software for macOS: The Best Alternatives to iMovie</u></a></li>
<li><a href="https://some-approaches.techidaily.com/trouble-watching-hd-mkv-files-on-your-ipad-discover-effortless-solutions-for-superior-playback/"><u>Trouble Watching HD MKV Files on Your iPad? Discover Effortless Solutions for Superior Playback!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/troubleshooting-freemake-video-downloader-issues-solutions-for-mac-and-pc/"><u>Troubleshooting Freemake Video Downloader Issues: Solutions for Mac and PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/tutorial-facile-comment-sapproprier-les-films-sur-ton-ordinateur-avec-un-decrypteur-de-dvd-gratuit/"><u>Tutorial Facile: Comment S'Approprier Les Films Sur Ton Ordinateur Avec Un Decrypteur De DVD Gratuit</u></a></li>
<li><a href="https://facebook.techidaily.com/us-users-ready-for-verified-recognition-at-meta/"><u>U.S. Users Ready for Verified Recognition at Meta</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-mac-video-converter-transform-videos-into-compatible-formats-for-iphone-ipad-apple-tv-and-more/"><u>Ultimate Mac Video Converter: Transform Videos Into Compatible Formats for iPhone, iPad, Apple TV & More</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-techniques-for-casting-ripping-and-watching-dvds-from-your-computer-onto-chromecast/"><u>Ultimate Techniques for Casting, Ripping & Watching DVDs From Your Computer Onto Chromecast</u></a></li>
<li><a href="https://extra-information.techidaily.com/voice-change-leaders-the-magic-call-alternatives/"><u>Voice-Change Leaders  The Magic Call Alternatives</u></a></li>
</ul></div>

---
title: Quick Guide to Conducting Fast Network Speed Tests Across PC, Mac, and Linux Systems
date: 2024-08-30T21:22:30.039Z
updated: 2024-08-31T21:22:30.039Z
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/illustration-of-a-rocket-launching-and-a-connection-speed-bar.jpg
---

## Quick Guide to Conducting Fast Network Speed Tests Across PC, Mac, and Linux Systems

### Quick Links

* [Run a Speed Test on Mac via Terminal](https://instagram-videos.techidaily.com/new-capture-and-replay-screen-recording-for-instagram-stories-for-2024/)
* [Run a Speed Test on Windows via Command Prompt](https://fake-location.techidaily.com/ispoofer-is-not-working-on-xiaomi-redmi-note-12-proplus-5g-fixed-drfone-by-drfone-virtual-android/)
* [Run a Speed Test on Linux via Terminal](https://games-able.techidaily.com/bring-back-those-good-old-days-why-your-game-needs-pi/)

 Internet speed test websites are often bogged down with ads, slowing down your system. Fortunately, Ookla offers a lightweight Command Line Interface (CLI) version of its speed test so you can test your internet speed without the overhead of a web browser. Here's how to use it on macOS, Windows, and Linux.

##  Run a Speed Test on Mac via Terminal

 To accomplish this on Mac, we will be using [Homebrew](https://visual-screen-recording.techidaily.com/new-breaking-ground-video-capture-breakdown-for-2024/), a [popular macOS package manager](https://screen-activity-recording.techidaily.com/updated-in-2024-virtualvista-viewers-verdict/). If you haven't installed Homebrew yet or if you are unsure, open Terminal (you'll find it under Applications > Utilities) and enter the following command:

        `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    
 This command will download and install Homebrew. Once installed, you can easily install the speed test CLI by entering:

        `brew install speedtest-cli`
    
 After the installation is complete, you can run the speed test by simply typing:

        `speedtest-cli  
`
    
![Running speedtest cli in macOS Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-macos-terminal.png) 

 This command will initiate a quick analysis of your internet connection speed, all from within the Terminal. This method not only saves system resources but also eliminates the need for navigating through ad-heavy websites.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Run a Speed Test on Windows via Command Prompt

 Installing the speed test CLI on a Windows PC is straightforward. Start by visiting the [Speedtest CLI download page](https://www.speedtest.net/apps/cli). Scroll down to find the download option for Windows. It's important to note that the CLI tool is only available for 64-bit versions of Windows.

![Downloading Speedtest CLI on Windows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/downloading-speedtest-cli-for-windows-2.png) 

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After downloading the installer, unzip the file to find "speedtest.exe." It's a good idea to place this file in a directory like C:\\Program Files\\speedtest.exe as this location is both easy to remember and accessible by all user accounts on your system. For added convenience, consider creating a desktop shortcut or pinning the executable to your taskbar.

 To run the speed test in Command Prompt (hit Start, type "command" and click "Command Prompt" when it appears), all you need to do is type the full path to the executable, encased in quotation marks to prevent conflicts arising from spaces, and hit enter:

        `"C:\Program Files\speedtest.exe"`
    
 To run in [PowerShell (Terminal)](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/), the syntax is slightly modified. You must prepend an ampersand to run the executable at the given file path, like so:

        `& "C:\Program Files\speedtest.exe"`
    
![Running Speedtest CLI in PowerShell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-powershell.png) 

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 These commands will run the application via the command line, providing you with a quick readout of your current internet speed and related parameters.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Run a Speed Test on Linux via Terminal

 Linux users have a slightly different setup process, as the steps can vary depending on the distribution. Here, we'll cover the installation process for one of the [most widely used distributions](https://win11.techidaily.com/the-art-of-merging-your-guide-to-windows-efficiency/): Debian/Ubuntu.

 First, open a Terminal window. Before installing the speed test CLI, you may need to install curl, a command-line tool for transferring data with URLs. If you're unsure whether curl is installed, you can install it by running:

        `sudo apt-get install curl`
    
 Next, add the Ookla repository to your list of package sources. This ensures that you get the latest version of the speed test CLI. Use the following command to do this:

        `curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash`
    
 Once the repository is added, you can install the speed test CLI with:

        `sudo apt-get install speedtest`
    
![Running Speedtest CLI on Ubuntu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-on-ubuntu-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
 After installation, you can test your internet speed by typing "speedtest" in the Terminal and pressing enter. This command will run the test and display the results directly in the window.

---

 Using Ookla's CLI speed test is an efficient way to measure your internet connection speed without the distractions and slowdowns caused by browser-based tools. No matter which OS you're using, this lightweight tool provides accurate and quick results. It's particularly useful when you want to avoid ads or need to integrate speed tests into automated systems or scripts.

 With just a few commands or a shortcut workflow, you can have a reliable tool at your disposal for monitoring and diagnosing your network performance, empowering you to run a network test at the drop of a hat or a hotkey.

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-elevate-your-videography-with-top-seo-gadgets/"><u>[New] 2024 Approved  Elevate Your Videography with Top SEO Gadgets</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-from-social-media-savant-to-money-maker-on-instagram/"><u>[New] 2024 Approved  From Social Media Savant to Money Maker on Instagram</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-enhancing-youtube-popularity-editing-and-optimizing-content-metadata-for-2024/"><u>[New] Enhancing YouTube Popularity  Editing & Optimizing Content Metadata for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-select-selections-ideal-pages-for-acquiring-snapalert-tunes/"><u>[New] Select Selections  Ideal Pages for Acquiring SnapAlert Tunes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-elevate-your-social-media-presence-insta-videography/"><u>[Updated] In 2024, Elevate Your Social Media Presence  Insta-Videography</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-speedy-tips-for-unearthing-lost-reddit-memes/"><u>[Updated] Speedy Tips for Unearthing Lost Reddit Memes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/celebrate-thanksgiving-top-family-friendly-movies-for-a-festive-holiday/"><u>Celebrate Thanksgiving: Top Family-Friendly Movies for a Festive Holiday</u></a></li>
<li><a href="https://some-approaches.techidaily.com/choosing-between-vimeo-and-youtube-for-your-video-needs-which-platform-reigns-supreme/"><u>Choosing Between Vimeo and YouTube for Your Video Needs: Which Platform Reigns Supreme?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/combining-youtube-and-imovie-for-professional-results/"><u>Combining YouTube and iMovie for Professional Results</u></a></li>
<li><a href="https://hardware-help.techidaily.com/comprehensive-setup-for-corsair-mouse-free-download-and-instructions-inside/"><u>Comprehensive Setup for Corsair Mouse - Free Download and Instructions Inside</u></a></li>
<li><a href="https://some-approaches.techidaily.com/download-macx-the-ultimate-free-video-to-audio-converter-for-avi-wmv-and-more-on-macos/"><u>Download MacX: The Ultimate Free Video-to-Audio Converter for AVI, WMV & More on MacOS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/easily-install-the-latest-asus-drivers-on-your-pc-with-windows-10-or-7/"><u>Easily Install the Latest ASUS Drivers on Your PC with Windows 10 or 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-guide-downloading-and-installing-logitech-c525-webcam-drivers-on-windows/"><u>Easy Guide: Downloading & Installing Logitech C525 Webcam Drivers on Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/easy-methods-for-transforming-your-dvdmedia-into-mp4-video-format-using-your-mac-computer/"><u>Easy Methods for Transforming Your DVDMedia Into MP4 Video Format Using Your Mac Computer</u></a></li>
<li><a href="https://some-approaches.techidaily.com/exclusive-macxdvd-sale-save-up-to-65-on-mac-software-bundle-and-amazing-discounts/"><u>Exclusive MacXDVD Sale: Save Up to 65%% on Mac Software Bundle & Amazing Discounts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/get-macx-dvd-ripper-pro-today-rip-any-disc-to-mp4flvmov-without-cost-perfect-for-ios-devices/"><u>Get MacX DVD Ripper Pro Today: Rip Any Disc to MP4/FLV/MOV without Cost – Perfect for iOS Devices!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/how-to-access-and-download-html5-movies-without-charge-a-guide-for-windows-and-macos/"><u>How to Access and Download HTML5 Movies without Charge – A Guide for Windows and macOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/how-to-enable-all-capabilities-in-macx-dvd-ripper-pro-windows-version-discover-solutions-here/"><u>How to Enable All Capabilities in MacX DVD Ripper Pro (Windows Version) - Discover Solutions Here!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/imovie-dvd/"><u>IMovie DVD マスタリング: シンプルな手順で自宅での無料ビデオ変換</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-audio-recording-101-from-youtube-playback-to-files/"><u>In 2024, Audio Recording 101  From YouTube Playback To Files</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-11-pro-passcode-without-computer-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 11 Pro Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-note-12-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi Note 12 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-ispring-review-a-deep-dive-into-screen-capture/"><u>In 2024, ISpring Review  A Deep Dive Into Screen Capture</u></a></li>
<li><a href="https://some-approaches.techidaily.com/leading-ios-apps-comparable-to-iexplorer-for-seamless-mobile-file-handling-and-data-exchange/"><u>Leading iOS Apps Comparable to iExplorer for Seamless Mobile File Handling and Data Exchange</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/mac-friendly-software-to-recover-your-iphones-erased-content-photos-videos-and-phone-numbers-revisited/"><u>Mac-Friendly Software to Recover Your iPhone's Erased Content: Photos, Videos, and Phone Numbers Revisited</u></a></li>
<li><a href="https://games-able.techidaily.com/master-game-privacy-hiding-steam-titles/"><u>Master Game Privacy: Hiding Steam Titles</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/maximizing-productivity-top-10-ways-to-utilize-chatgpt-in-vs-code/"><u>Maximizing Productivity: Top 10 Ways to Utilize ChatGPT in VS Code</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/king-masterpieces-crafting-successful-parodies/"><u>Mimicking Masterpieces  Crafting Successful Parodies</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-severe-cold-and-heat-do-electric-vehicles-deliver-reliable-performance/"><u>Navigating Severe Cold and Heat – Do Electric Vehicles Deliver Reliable Performance?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/professionelle-videokompression-von-mp4-bis-mkv-die-fuhrenden-kompressorlosungen/"><u>Professionelle Videokompression Von MP4 Bis MKV - Die Führenden Kompressorlösungen</u></a></li>
<li><a href="https://some-approaches.techidaily.com/professionnel-macx-transforme-votre-video-en-mp4mkvaviwmv-pour-ios-et-android/"><u>Professionnel MacX : Transforme Votre Vidéo en MP4/MKV/AVI/WMV Pour iOS Et Android</u></a></li>
<li><a href="https://some-approaches.techidaily.com/quick-guide-how-to-securely-obtain-the-pokemon-go-apk-for-android-users/"><u>Quick Guide: How to Securely Obtain the Pokémon GO APK for Android Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/reviving-the-past-essential-vhs-visuals-in-todays-edits-for-2024/"><u>Reviving the Past  Essential VHS Visuals in Today's Edits for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/safety-and-legality-of-using-handbrake-for-dvd-ripping-and-video-conversion/"><u>Safety & Legality of Using HandBrake for DVD Ripping & Video Conversion</u></a></li>
<li><a href="https://some-approaches.techidaily.com/smart-tv-showdown-the-benefits-of-apple-tv-roku-and-chromecast-unveiled/"><u>Smart TV Showdown: The Benefits of Apple TV, Roku, and Chromecast Unveiled</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-guide-seamlessly-move-your-iphone-apps-and-data-to-mac-illustrated-with-images/"><u>Step-by-Step Guide: Seamlessly Move Your iPhone Apps and Data to Mac, Illustrated with Images</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-tutorial-for-seamless-mp4-to-mpg-upgrades-across-macos-and-windows-systems/"><u>Step-by-Step Tutorial for Seamless MP4 to MPG Upgrades Across macOS & Windows Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/strategies-efficaces-pour-gerer-lechec-de-lecture-sur-un-disque-dur-mac-defectueux/"><u>Stratégies Efficaces Pour Gérer L'Échec De Lecture Sur Un Disque Dur Mac Défectueux</u></a></li>
<li><a href="https://article-tips.techidaily.com/the-best-storytelling-youtube-channels-to-follow-this-year-for-2024/"><u>The Best Storytelling YouTube Channels to Follow This Year for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-iphone-data-management-and-transfer-apps-the-best-alternatives-to-itunes/"><u>Top iPhone Data Management & Transfer Apps: The Best Alternatives to iTunes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-rated-nas-devices-ideal-for-mac-users-perfect-solutions-for-your-home-or-business/"><u>Top-Rated NAS Devices Ideal for Mac Users: Perfect Solutions for Your Home or Business</u></a></li>
<li><a href="https://some-approaches.techidaily.com/troubleshooting-guide-solving-the-4k-video-downloaders-failed-video-extraction-problem/"><u>Troubleshooting Guide: Solving the 4K Video Downloader's Failed Video Extraction Problem</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-kid-friendly-holiday-movie-guide-classic-and-modern-picks-for-the-festive-season/"><u>Ultimate Kid-Friendly Holiday Movie Guide: Classic and Modern Picks for the Festive Season</u></a></li>
<li><a href="https://win-answers.techidaily.com/understanding-and-fixing-the-root-causes-of-arise-game-crashes/"><u>Understanding and Fixing the Root Causes of Arise Game Crashes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unique-vlogging-conversation-pieces-for-2024/"><u>Unique Vlogging Conversation Pieces for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unrivaled-efficiency-macx-dvd-ripper-pro-v55-dominates-global-market-master-of-all-disc-formats/"><u>Unrivaled Efficiency - MacX DVD Ripper Pro V5.5 Dominates Global Market, Master of All Disc Formats</u></a></li>
<li><a href="https://some-approaches.techidaily.com/why-waiting-to-convert-your-files-a-must-read-guide-before-using-any-internet-m4v-to-mov-translator/"><u>Why Waiting to Convert Your Files: A Must-Read Guide Before Using Any Internet M4V to MOV Translator</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1724766286977-mp3-mac-and-windowsmp3/"><u>おすすめ MP3 圧縮ツール: Mac & Windows両用で高音質フリーソフトウェア！オンラインで無料配信を、パワフルなMP3サイズ小振り化【有料版も】</u></a></li>
</ul></div>

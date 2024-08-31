---
title: Resolving the 'Sudo Command Not Found' Error in Linux with This Quick Trick
date: 2024-08-30T21:19:17.609Z
updated: 2024-08-31T21:19:17.609Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/example-of-a-terminal-with-the-error-sudo-command-not-found-and-a-notebook-with-the-linux-mascot-on-the-screen.jpg
---

## Resolving the 'Sudo Command Not Found' Error in Linux with This Quick Trick

### Quick Links

* [What Is the sudo Command?](https://facebook-video-content.techidaily.com/new-2024-approved-explore-our-1-ranked-facebook-video-downloading-apps-for-ios/)
* [Why Are You Getting This Error?](https://youtube-videos.techidaily.com/mute-auto-generated-youtube-content-trails/)
* [Here's How to Fix the "sudo: command not found" Error](https://data-wizards.techidaily.com/how-to-handle-advanced-video-technology-failure/)
* [Try Adding sudo to the PATH Variable](https://win-dash.techidaily.com/get-your-ultimate-gaming-experience-free-download-steelseries-engine-on-windows-10/)

### Key Takeaways

* Become root (using "su -") and install sudo using the "apt install sudo" command on Debian and Ubuntu.
* Add your user to the sudo group using the "usermod -aG sudo username" (Debian/Ubuntu) or "usermod -aG wheel username" (other distros) commands as a root user.
* If sudo is installed but not working, add its directory to the PATH variable by editing the "/etc/profile" file as a root user.

 Tried using your first Linux command as a superuser and getting the "sudo: command not found" error? This is one of the most common problems new Linux users face after a fresh installation. Here's how you can solve this issue and start using the sudo command again.

 For this tutorial, I'll be demonstrating everything on Debian 12\. However, you'll find the necessary commands to fix the "sudo: command not found" error on other Linux distros as well.

##  What Is the sudo Command?

 The sudo command on Linux, a contraction of the phrase "superuser do", is a powerful utility that allows users to execute commands with the privileges of another user, typically root. With sudo, authorized users can perform administrative tasks without needing to log in as the root user.

 The way to use sudo is to begin another command with the word "sudo". This allows you to run the command with elevated privileges. So the sudo command lets you have the required permissions of a different user and run a sensitive command. You can learn more about the sudo command from its [manual page](https://man7.org/linux/man-pages/man8/sudo.8.html).

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Why Are You Getting This Error?

 There are usually two possible reasons for the "sudo: command not found" error on Linux. It's either because sudo is not installed or the sudo directory is not present in your system's PATH variable.

 Some Linux distributions may not have the sudo package installed by default. This is true for Arch and Gentoo Linux. On Debian, if you set a root password during installation, then you'll face the same problem.

![An example of the error sudo command not found on Debian Linux being displayed on the terminal](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/1-4.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
 The second reason is that sudo is installed, but its directory is not included in the PATH variable. PATH is an environment variable the Linux system uses to locate a command without specifying its full path.

 When you type a command in the terminal, the system searches through the directories listed in the PATH variable and tries to find the correct executable file. If the sudo command is not in that PATH variable, the system will not find it and won't be able to use it.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
##  Here's How to Fix the "sudo: command not found" Error

 If you don't have sudo installed, installing it and adding your user to the sudo/wheel group should be enough to fix the problem. To ensure whether you have sudo installed, run:

sudo -V

![An example of checking the version of sudo installed on Debian using the sudo -V command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/0.png) 

 If you don't have sudo installed, you should see a similar output, in which case proceed to the following method.

###  Install sudo on Linux

 To install the sudo package, you need to become [root](https://digital-screen-recording.techidaily.com/updated-2024-approved-entrance-video-analysis-review/) first. To become a root user, open your terminal and run:

su -

 Type in the root password and press Enter. If successful, you should see the shell prompt become white and the word "root" written at the beginning of the prompt.

![An example of becoming root user on Debian Linux using the su - command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/2-4.png) 

 As a root user, you can install any software package, including sudo. To install sudo, run this command on Debian-based distros:

apt install sudo

![The Linux terminal showing the process of installing the sudo command as a root use](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/3-2.png) 

 For RHEL-based systems, use this command:

yum install sudo

 On Arch Linux, run:

pacman -S sudo

 If you're using Gentoo, then use this command:

emerge --ask app-admin/sudo

###  Add Your User to the sudo Group

 Once you've installed the sudo command, you need to [add your non-root user to the sudo group](https://instagram-clips.techidaily.com/new-2024-approved-social-media-momentum-linking-igtv-and-fb/). This is because you want to give that user superuser privileges. Then your non-root user can use the sudo command to gain elevated privileges.

 To add a user to the sudo group, run this command on a Debian-based distro:

usermod -aG sudo username

 Make sure to replace "username" in the command with the correct username.

![The Linux terminal displaying the command to add a user to the sudoer group on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/4-1.png) 

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you're using Arch Linux, Fedora, or other RHEL-based distros, then use the following command:

usermod -aG wheel username

 Finally, switch back to the non-root user with:

su username

![The Linux terminal demonstrating the process of switching between users on Debian using commands](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/5-2.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
 Now you can try a command beginning with sudo to test whether it's working. For example, let's try to update the packages on the system. To do that, use:

sudo apt update

![An example of updating the packages on Debian Linux using the sudo apt update command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/6-1.png) 

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
 It works as expected.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Try Adding sudo to the PATH Variable

 If you already have sudo installed, but it's still not working, then you need to add sudo to the PATH variable. Let's first determine the location of the sudo command.

which sudo

![An example of using the which command on Linux to display the location of a certain command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/7-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
 As you can see, it's in the "/usr/bin/" directory. Now let's check if the directory is in the PATH variable or not. Run this command:

echo $PATH

![The Linux terminal displaying the PATH variable content on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/8-1.png) 

 In my case, the location of the sudo command is present in the PATH variable. In case it's not, you can add it with this command:

export PATH=$PATH:/usr/bin

 However, this will only add the sudo command's directory temporarily. After you end the terminal session, things will go back to what they were.

 To permanently add the directory, open the "/etc/profile" file in a text editor. To open it in the [nano text editor](https://sound-issues.techidaily.com/fixing-the-problem-of-a-non-functional-corsair-hs70-microphone-a-step-by-step-guide/), first become root by entering **su -** and use this command:

nano /etc/profile

 Edit the line that declares the PATH variable. Add a colon (:) and then append the path to sudo ("/usr/bin" in this case.)

![The /etc/profile file opened in the Nano text editor with its content displayed on the Linux terminal](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/9-1.png) 

 Save the file using Ctrl+O and then exit from the editor using Ctrl+X. Now try to use the sudo command to see if it's working.

---

 That should solve your problem and let you use the sudo command without any errors. Remember that, only the users added to the sudo group will be able to use it. If you want to grant sudo privileges to more users, check out our guide on [controlling sudo access on Linux](https://snapchat-videos.techidaily.com/new-in-2024-advanced-techniques-to-save-snapchat-stories-on-devices/).

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
<li><a href="https://extra-information.techidaily.com/new-building-a-following-with-captivating-instagram-reels/"><u>[New] Building a Following with Captivating Instagram Reels</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-all-encompassing-outline-googles-podcast-app-at-a-glance/"><u>[Updated] All-Encompassing Outline  Google's Podcast App at a Glance</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1-effortless-tactics-syncing-your-ipods-library-with-a-mac/"><u>1. Effortless Tactics: Syncing Your iPod's Library with a Mac</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1-insider-secrets-unveiling-the-best-movie-and-television-show-picks/"><u>1. Insider Secrets: Unveiling the Best Movie & Television Show Picks</u></a></li>
<li><a href="https://some-approaches.techidaily.com/analyzing-web-media-file-types-the-detailed-contrast-of-webm-and-mp4/"><u>Analyzing Web Media File Types: The Detailed Contrast of WebM and MP4</u></a></li>
<li><a href="https://some-approaches.techidaily.com/best-video-downloader-apps-for-macos-top-11-free-and-premium-options/"><u>Best Video Downloader Apps for macOS: Top 11 Free and Premium Options</u></a></li>
<li><a href="https://fox-http.techidaily.com/comprehensive-exploration-of-vsco-image-processing/"><u>Comprehensive Exploration of VSCO Image Processing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/digiarty-software-insights-explore-sales-strategies-license-agreements-update-options-partnerships-technical-assistance-and-product-catalogs/"><u>Digiarty Software Insights: Explore Sales Strategies, License Agreements, Update Options, Partnerships, Technical Assistance, and Product Catalogs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/direkter-vergleich-zwischen-ios-10-und-ios-9-erkenne-die-verbesserungen-und-nachteile/"><u>Direkter Vergleich Zwischen iOS 10 Und iOS 9 - Erkenne Die Verbesserungen Und Nachteile</u></a></li>
<li><a href="https://some-approaches.techidaily.com/efficient-methods-to-clear-multiple-photos-at-once-on-an-iphone-plus/"><u>Efficient Methods to Clear Multiple Photos at Once on an iPhone (Plus)</u></a></li>
<li><a href="https://sound-issues.techidaily.com/enhance-your-sea-of-thieves-adventure-essential-tips-to-repair-micspeakers-on-windows-computers/"><u>Enhance Your Sea of Thieves Adventure - Essential Tips to Repair Mic/Speakers on Windows Computers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/exclusive-black-friday-offer-on-macxdvd-gaming-shopping-and-prize-contests-await-you/"><u>Exclusive Black Friday Offer on MacXDVD: Gaming, Shopping & Prize Contests Await You!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/faq-for-macxdvd-your-essential-guide-to-digiarty-softwares-dvd-creation-tool-faq-for-macxdvd-your-essential-guide-to-creating-dvds-with-digiarty-software/"><u>FAQ for MacXDVD: Your Essential Guide to Digiarty Software's DVD Creation Tool (FAQ for MacXDVD - Your Essential Guide to Creating DVDs with Digiarty Software)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-macx-video-converter-ultimate-guide-to-convert-mkv-files-on-mac-with-ease/"><u>Free MacX Video Converter: Ultimate Guide to Convert MKV Files on Mac with Ease</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-up-space-essential-strategies-for-clearing-your-macs-boot-volume/"><u>Free Up Space: Essential Strategies for Clearing Your Mac's Boot Volume</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-oneplus-nord-3-5g-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked OnePlus Nord 3 5G Phone | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/guide-bypassing-drm-how-to-watch-the-avengers-dvd-on-ios-devices/"><u>Guide: Bypassing DRM - How to Watch 'The Avengers' DVD on iOS Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/hd-video-downloader-converter-and-editor-for-macos-free-dvdvideosoft-studio/"><u>HD Video Downloader, Converter & Editor for MacOS - Free DVDVideoSoft Studio</u></a></li>
<li><a href="https://some-approaches.techidaily.com/how-to-legally-replicate-your-netflix-rental-into-a-digital-format/"><u>How to Legally Replicate Your Netflix Rental Into a Digital Format</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-life360-from-tracking-you-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Life360 from Tracking You On Realme GT 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-mastering-multiplatform-meeting-logistics-on-zoom/"><u>In 2024, Mastering Multiplatform Meeting Logistics on Zoom</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-the-world-of-high-tech-tools-at-toms-hardware-hub/"><u>Navigating the World of High-Tech Tools at Tom's Hardware Hub</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1724765999789-onlinevideoconverter/"><u>OnlineVideoConverterの使用ガイド：問題発生時における修正・詳報 - 利用者のレビュー集</u></a></li>
<li><a href="https://some-approaches.techidaily.com/revolutionizing-mediamove-ultra-quick-transfer-for-gbs-of-iphone-memories/"><u>Revolutionizing MediaMove: Ultra-Quick Transfer for GBs of iPhone Memories!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/speedy-video-editors-top-tools-to-overcome-laggy-video-editing-pace/"><u>Speedy Video Editors: Top Tools To Overcome Laggy Video Editing Pace</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-troubleshooting-resolve-failing-ntfs-filesystem-error-in-windows-11-bsods/"><u>Step-by-Step Troubleshooting: Resolve Failing NTFS Filesystem Error in Windows 11 BSODs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transform-your-dvds-into-digital-format-using-these-5-free-methods/"><u>Transform Your DVDs Into Digital Format Using These 5 Free Methods</u></a></li>
<li><a href="https://some-approaches.techidaily.com/troubleshooting-macs-youtube-problems-for-smooth-downloads-and-streaming-fix-your-errors-now/"><u>Troubleshooting Mac's YouTube Problems for Smooth Downloads and Streaming | Fix Your Errors Now!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-guide-to-premium-audio-services-and-secrets-of-free-legit-mp3-track-acquisition/"><u>Ultimate Guide to Premium Audio Services & Secrets of Free Legit MP3 Track Acquisition</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-selection-the-top-10-greatest-rom-coms-ever-made/"><u>Ultimate Selection: The Top 10 Greatest Rom-Coms Ever Made</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unleash-the-potential-of-youtube-videos-through-strategic-chapters-and-segments-for-2024/"><u>Unleash the Potential of YouTube Videos Through Strategic Chapters and Segments for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-macx-mediatrans-from-macxdvd-a-milestone-advancement-in-managing-your-ios-devices/"><u>Unveiling MacX MediaTrans From MacXDVD - A Milestone Advancement in Managing Your iOS Devices</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-premier-7-voice-silencers-seamless-clip-editing-online-and-offline/"><u>Updated In 2024, Premier 7 Voice Silencers Seamless Clip Editing Online & Offline</u></a></li>
</ul></div>

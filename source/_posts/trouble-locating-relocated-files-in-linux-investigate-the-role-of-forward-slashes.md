---
title: Trouble Locating Relocated Files in Linux? Investigate the Role of Forward Slashes
date: 2024-08-30T21:21:13.256Z
updated: 2024-08-31T21:21:13.256Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/a-magnifying-glass-pointed-at-the-linux-mascot-next-to-a-file-folder.jpg
---

## Trouble Locating Relocated Files in Linux? Investigate the Role of Forward Slashes

### Quick Links

* [How This Particular Problem Foxes People](https://vimeo-videos.techidaily.com/2024-approved-discovering-vimeo-home-for-high-quality-films/)
* [The Part Slash Plays in the mv Command](https://youtube-help.techidaily.com/in-2024-optimized-video-engagement-with-peak-post-times/)
* [It’s Not Exactly Slash’s Fault](https://mondly-stories.techidaily.com/film-and-television-as-educational-resources/)

 Typically, mv is one of the first Linux commands you learn. But one little slip, and things can get surprisingly confusing for the user. Sometimes it looks like moved files have simply vanished.

##  How This Particular Problem Foxes People

 Moving a file on the [command line is pretty simple](https://buynow-help.techidaily.com/misinterpretation-of-gram-staining-results-can-lead-to-incorrect-identification-affecting-treatment-decisions-in-clinical-settings/). You specify the file you want to move, and where you want to move it to. But still, it’s easy for a new user to find themselves exasperated and frustrated over mv.

 They try to move a file into a directory, and it seems to work. They don’t get a confirmation message, but neither do they get an error message. Linux often takes the no news is good news approach. If you don’t get an error message, it must have worked.

 Or did it? When they cd into the target directory, the file isn’t there. And of course, because mv moves the file from the original directory, it’s not there either. It’s starting to look like the file has been lost in the ether. This is usually the point where the frustrated user reaches out for help.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  The Part Slash Plays in the mv Command

 Let’s say you’re moving a file to a different directory. You’re going to keep the same filename. In theory, this makes things easy because you don’t need to specify a target filename on the command line. By default, mv uses the original filename.

 We’ve got a file in the \~/Downloads/src directory. We move it to the \~/Documents/backup directory. As expected, it’s now in the backup directory, and it has been removed from the src directory.

        `ls ~/Downloads/src  
mv ~/Downloads/src/important-file.dat ~/Documents/backup   
ls ~/Documents/backup/  
ls ~/Downloads/src  
`
    
![Moving a file with the mv command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/1-4.png) 

 That’s nice and simple, and everything works as expected. If we look into our target directory, we find the moved file, and we get on with the rest of our work.

![A moved file in its new directory.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/2-4.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
 But let's say our Linux newcomer isn’t using [tab completion](https://desktop-recording.techidaily.com/new-2024-approved-an-impartial-appraisal-the-power-of-recordcast/). They're typing the directory paths by hand. If they misspell the name of the final directory, we get a very different behavior.

mv ~/Downloads/src/important-file.dat ~/Documents/backpu

![Trying to use the mv command with a typo in the final directory name.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/3-3.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
 They’ve made a typo with the target directory name, but mv exits silently back to the command prompt. On the face of it, it looks like the file move worked.

 Let’s check.

        `ls ~/Downloads/src  
ls ~/Documents/backup/  
`
    
![Using ls to look for the file in the original and new directories.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/4-2.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 The original and target directories are both empty. Where did the file go?

 Bash tries to find a directory called backpu, but can't find one. It concludes you want to rename your moved file to backpu. You’ll find a file called backpu one directory level higher than your target directory.

ls -l ~/Documents

![The location of the missing and misspelled file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/5-2.png) 

 To fix this, you can move your file to where it should have gone, and specify its proper name on the command line.

        `mv ~/Documents/backpu ~/Documents/backup/important-file.dat   
ls ~/Documents/backup  
`
    
![Moving and renaming the misspelled file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/6-2.png) 

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
 The confusion and the hunt for the missing, badly-named file could have been avoided by adding a trailing slash to the target directory on the command line. That way, if you make a typo, Bash reports an error.

mv ~/Downloads/src/important-file.dat ~/Documents/backpu/

![The trailing slash on the mv command line flags errors with the final directory name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/7-2.png) 

 The trailing slash explicitly tells Bash that this is a directory name, not a filename. Because Bash can’t find the misspelled directory, it reports the error to you and doesn’t move anything.

 This is a better outcome for failures. You’re alerted to the error, and the original file remains touched.

 Using the Bash tab completion feature not only speeds up the entry of directory paths, it gives a few extra bonuses. All the directory names are automatically spelled correctly, and a trailing slash is added to the final directory.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
##  It’s Not Exactly Slash’s Fault

 Slash didn’t make the typo, after all. But if slash is present and on duty, you're told about the error before mv does anything questionable with your file.

 As is often the case, a good diagnostic first step is to check the [command history](https://article-posts.techidaily.com/2024-approved-precision-techniques-shifting-bulk-video-data-from-iphone-to-mac/) and see what command was actually issued, not what you think you typed. If you spot a typo, look for a file with that misspelled name, one directory level higher than where you expect it to be.

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-tailoring-talent-to-treasure-the-proactive-pursuit-of-video-profitability/"><u>[New] 2024 Approved  Tailoring Talent to Treasure  The Proactive Pursuit of Video Profitability</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-comprehensive-tips-for-constructing-podcast-rss-feeds-for-2024/"><u>[New] Comprehensive Tips for Constructing Podcast RSS Feeds for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-gaining-exposure-cost-effective-promotion-hacks-for-youtubers-for-2024/"><u>[New] Gaining Exposure  Cost-Effective Promotion Hacks for YouTubers for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-a-palette-of-pleasantness-five-winter-backgrounds-ideas/"><u>[New] In 2024, A Palette of Pleasantness  Five Winter Backgrounds Ideas</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-unusual-upsets-top-10-unexpected-gaming-sensations-on-tiktok/"><u>[New] Unusual Upsets  Top 10 Unexpected Gaming Sensations on TikTok</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-navigating-frame-rate-control-for-optimal-viewing-on-snapchat/"><u>[Updated] In 2024, Navigating Frame Rate Control for Optimal Viewing on Snapchat</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-methods-to-flip-video-content-in-android/"><u>[Updated] Methods to Flip Video Content in Android</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-easy-ways-to-factory-reset-a-locked-apple-iphone-12-pro-max-without-itunes-drfone-by-drfone-ios/"><u>3 Easy Ways to Factory Reset a Locked Apple iPhone 12 Pro Max Without iTunes | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/best-free-techniques-for-changing-wmv-videos-to-mp4-on-macos-devices/"><u>Best Free Techniques for Changing WMV Videos to MP4 on macOS Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/capture-crisp-4k-footage-60-fps-with-iphone-and-enjoy-effortless-playback-quality/"><u>Capture Crisp 4K Footage @ 60 FPS with iPhone & Enjoy Effortless Playback Quality</u></a></li>
<li><a href="https://some-approaches.techidaily.com/comparing-the-macbook-pro-and-air-retina-advantages-and-disadvantages-revealed/"><u>Comparing the MacBook Pro and Air Retina: Advantages and Disadvantages Revealed</u></a></li>
<li><a href="https://some-approaches.techidaily.com/convert-videos-seamlessly-with-macx-pro-the-leading-solution-for-high-definition-hd4k-file-format-changes-on-macos/"><u>Convert Videos Seamlessly with MacX Pro: The Leading Solution for High-Definition (HD/4K) File Format Changes on macOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/discover-superior-alternatives-for-converting-and-saving-youtube-videos-offline/"><u>Discover Superior Alternatives for Converting and Saving YouTube Videos Offline</u></a></li>
<li><a href="https://some-approaches.techidaily.com/download-and-stream-videos-anytime-top-alternatives-to-keepvid-for-pc-and-mac-users/"><u>Download and Stream Videos Anytime: Top Alternatives to KeepVid for PC & Mac Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/download-macx-top-rated-mac-dvd-to-mpeg-and-mp3-format-converter-freeware/"><u>Download MacX: Top-Rated Mac DVD to MPEG & MP3 Format Converter (Freeware)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/effortless-conversion-guide-changing-mkv-files-into-mov-to-play-on-apple-products-and-itunes-easily/"><u>Effortless Conversion Guide: Changing MKV Files Into MOV to Play on Apple Products & iTunes Easily</u></a></li>
<li><a href="https://some-approaches.techidaily.com/essential-insights-on-upgrading-from-jpeg-to-advanced-heifheic-format/"><u>Essential Insights on Upgrading From JPEG to Advanced HEIF/HEIC Format</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/experience-tech-at-its-finest-with-the-amazfit-bip-a-comprehensive-review-for-beginners/"><u>Experience Tech at Its Finest with the Amazfit BIP: A Comprehensive Review for Beginners</u></a></li>
<li><a href="https://some-approaches.techidaily.com/explore-the-macx-collection-easy-online-shopping-at-the-official-macx-digital-outlet/"><u>Explore the MacX Collection: Easy Online Shopping at the Official MacX Digital Outlet</u></a></li>
<li><a href="https://some-approaches.techidaily.com/fehlerbehebung-fur-nicht-abspielbare-dvds-auf-dem-xbox-one-schnelllosungsguide/"><u>Fehlerbehebung Für Nicht Abspielbare DVDs Auf Dem Xbox One - Schnelllösungsguide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/free-effortless-mac-x-flv-video-transcoding-tool-no-cost-solution-for-flv-format-on-macos/"><u>FREE: Effortless Mac X FLV Video Transcoding Tool - No Cost Solution for FLV Format on macOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/get-your-macx-mediatrans-now-at-a-low-price-purchase-securely-online/"><u>Get Your MacX MediaTrans Now at a Low Price - Purchase Securely Online!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/huge-savings-alert-snag-your-macx-mediatrans-with-a-staggering-63-discount/"><u>HUGE Savings Alert: Snag Your MacX MediaTrans with a Staggering 63%% DISCOUNT!</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-rewind-android-movies-successfully/"><u>In 2024, How to Rewind Android Movies Successfully</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-reel-revolution-top-tech-for-brightening-videos/"><u>In 2024, Reel Revolution  Top Tech for Brightening Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unrestricted-media-playback-free-on-windows-and-macos/"><u>In 2024, Unrestricted Media Playback  FREE on Windows & MacOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/iphone-drm/"><u>IPhone DRM解除アプリ一斉紹介：すべてのユーザーが楽しめる簡単操作</u></a></li>
<li><a href="https://win-solutions.techidaily.com/lost-ark-resolved-frame-rate-drops-and-enhanced-gameplay-stability/"><u>Lost Ark: Resolved Frame Rate Drops and Enhanced Gameplay Stability</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mac-compatible-vob-file-transcoder-easily-convert-your-vob-videos-into-common-formats-like-mp4-avi-wmv-and-mov/"><u>Mac-Compatible VOB File Transcoder: Easily Convert Your VOB Videos Into Common Formats Like MP4, AVI, WMV & MOV</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macx-dvd-ripper-pro-lite/"><u>MacX DVD Ripper Pro Lite フォーウィンズで購入したら、リッピングソフトの使用を始めるためのライセンスコード登録ガイド</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1724766349171-macx-dvd-ripper-pro/"><u>MacX DVD Ripper Pro製品手引き: 正しいインストールと操作方法解説</u></a></li>
<li><a href="https://some-approaches.techidaily.com/master-the-art-of-watching-webm-files-on-ios-devices/"><u>Master the Art of Watching WebM Files on iOS Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/master-video-format-conversion-effortlessly-make-your-videos-ready-for-iphone-ipad-apple-tv-and-itunes-playback/"><u>Master Video Format Conversion: Effortlessly Make Your Videos Ready for iPhone, iPad, Apple TV & iTunes Playback</u></a></li>
<li><a href="https://some-approaches.techidaily.com/master-your-device-the-best-app-for-seamlessly-handling-iphone-pictures-tunes-and-movies/"><u>Master Your Device: The Best App for Seamlessly Handling iPhone Pictures, Tunes & Movies</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mastering-the-art-of-capturing-youtube-videos-with-sound-a-comprehensive-guide-for-mac-users/"><u>Mastering the Art of Capturing YouTube Videos With Sound: A Comprehensive Guide for Mac Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/navigating-through-wows-issue-519/"><u>Navigating Through WoW's Issue #519</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-cooldown-chart-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-tutorial-on-removing-dvd-region-restrictions-for-global-playback/"><u>Step-by-Step Tutorial on Removing DVD Region Restrictions for Global Playback</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-5-best-tools-to-convert-videos-directly-to-twitter/"><u>The 5 Best Tools to Convert Videos Directly to Twitter</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-free-no-install-video-editing-tools-you-can-use-immediately/"><u>Top Free No-Install Video Editing Tools You Can Use Immediately</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-video-editing-software-for-macos-the-best-alternatives-to-imovie/"><u>Top Video Editing Software for macOS: The Best Alternatives to iMovie</u></a></li>
<li><a href="https://some-approaches.techidaily.com/trouble-watching-hd-mkv-files-on-your-ipad-discover-effortless-solutions-for-superior-playback/"><u>Trouble Watching HD MKV Files on Your iPad? Discover Effortless Solutions for Superior Playback!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/troubleshooting-freemake-video-downloader-issues-solutions-for-mac-and-pc/"><u>Troubleshooting Freemake Video Downloader Issues: Solutions for Mac and PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/tutorial-facile-comment-sapproprier-les-films-sur-ton-ordinateur-avec-un-decrypteur-de-dvd-gratuit/"><u>Tutorial Facile: Comment S'Approprier Les Films Sur Ton Ordinateur Avec Un Decrypteur De DVD Gratuit</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-techniques-for-casting-ripping-and-watching-dvds-from-your-computer-onto-chromecast/"><u>Ultimate Techniques for Casting, Ripping & Watching DVDs From Your Computer Onto Chromecast</u></a></li>
</ul></div>

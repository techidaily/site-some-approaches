---
title: "Mastering the Basics: Step-by-Step Guide to Finding Mean Values Using Microsoft Excel"
date: 2024-08-30T21:21:27.439Z
updated: 2024-08-31T21:21:27.439Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/7d0feaf90637aa15b789896b9b4144f8ee9d0a1514b5ec2518db335a12809dc5.jpg
---

## Mastering the Basics: Step-by-Step Guide to Finding Mean Values Using Microsoft Excel

### Quick Links

* [How Many Average Functions Are There in Excel?](https://instagram-video-files.techidaily.com/updated-in-2024-rapid-route-learning-the-ins-and-outs-of-insta-talks/)
* [How to Use AVERAGE in Excel](https://data-safeguard.techidaily.com/photoshop-cs8-installation-tutorial-for-windows-users-start-editing/)
* [How to Use AVERAGEA in Excel](https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-huawei-p60-drfone-by-drfone-virtual-android/)
* [How to Use AVERAGEIF in Excel](https://program-issues.techidaily.com/solving-the-mystery-a-step-by-step-guide-to-resolve-dev-error-6034-on-pc-and-xbox/)
* [How to Use AVERAGEIFS in Excel](https://extra-hints.techidaily.com/slowly-quieting-tracks-with-fl-studio/)

 Excel has hundreds of functions that can help you to quickly and accurately perform calculations, among which are the AVERAGE functions. You might want to calculate the average sales figures, get the average of a group of data that contains numbers and text, or work out the average of all student scores over a certain number.

##  How Many Average Functions Are There in Excel?

 There are four AVERAGE functions and each has different uses:

* **AVERAGE**: This produces the arithmetic mean (the sum of all numbers divided by the number of values) of a set of data, ignoring anything that isn't a number.
* **AVERAGEA**: This returns the mean of a set of numbers, text, and logical arguments.
* **AVERAGEIF**: This calculates the arithmetic mean of a set of numerical data that fulfill a single criterion.
* **AVERAGEIFS**: This tells you the arithmetic mean of a set of numerical data that fulfill several criteria.

 Let's explore these in more detail.

##  How to Use AVERAGE in Excel

 To calculate the average in Excel, use the following syntax:

=AVERAGE(A,B)

 where A is the first number, cell reference, or range, and B is up to a maximum of 255 additional numbers, cell references, or ranges to include in the average calculation.

 In this example, we have a set of seven students and want to calculate their average exam score.

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is an 'average' cell, where their average scores will be calculated using the AVERAGE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/average-uncalculated.png) 

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As you can see, Student C scored 0 and Student F has yet to take the exam. As a result, we want Excel to work out the scores of those who have taken the exam (all students except for Student F).

 To do this, we would type the following formula into cell D2:

=AVERAGE(B2:B8)

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is an 'average' cell, where their average scores has been calculated using the AVERAGE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/average-calculated-1.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
 The AVERAGE function includes 0 within its calculations, but ignores all empty cells, text, and logical values (TRUE or FALSE). So, we can be confident that this calculation will include Student C's score, but ignore Student F's score.

 If any of the values being used in the AVERAGE calculation were to contain [one of Excel's formula errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/), the calculation would not work.

 To save time, you can instead calculate the average through a few simple clicks. First, select your data to average, click the "Home" tab on the ribbon, and in the "Editing" group, click on the drop-down arrow next to the sigma (Σ) symbol. From there, click "Average". The result will appear at the end of your data.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
##  How to Use AVERAGEA in Excel

 AVERAGEA works in a very similar way to AVERAGE, but includes more than just numbers within the calculation. Here's the syntax for this function:

=AVERAGE(A,B)

 where A is the first value (including numbers, logical values such as TRUE or FALSE, and text), and B is up to a maximum of 255 additional values to include in the average calculation.

 The AVERAGEA function is useful if you have a mixed set of data containing numbers, logical values, and text, and you want to include them all within your calculation.

 Taking the same set of data that we used in the example above, we now want to work out the average using AVERAGEA.

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is the average of the scores, calculated using AVERAGE, and a space where their average scores will be calculated using the AVERAGEA function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averagea-uncalculated.png) 

 In cell D5, we would type the following formula:

=AVERAGEA(B2:B8)

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is the average of the scores, calculated using AVERAGE, and their average scores, calculated using the AVERAGEA function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averagea-calculated.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Unlike the AVERAGE function, which ignores logical values, the AVERAGEA calculation includes FALSE within the calculation as 0\. If this were instead TRUE, this would be counted as 1\. As a result, in our example, Student C's score of 0 is included, and Student F is also calculated as having scored 0\. This is why the result is lower for this calculation than the previous one.

 AVERAGEA counts any other text as 0 (for example, if you type FOUR, this is still represented as 0, and not 4), and ignores empty cells.

 As with AVERAGE, if any of the values being used in the AVERAGEA calculation were to contain [one of Excel's formula errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/), the calculation would return an error.

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
##  How to Use AVERAGEIF in Excel

 AVERAGEIF effectively performs two calculations in one go, first identifying data that meet a certain criterion before then finding the average of these data. AVERAGEIF uses the following syntax:

=AVERAGEIF(A,B,C)

 where A is the range of values or cells to include in the average, B is the criterion, and C (optional) is the actual set of cells to average. Confusing? Let's look at this example.

 We want to work out two things from this table. First, we want to find the average score of all students who scored more than 10 in the exam, and second, we want to work out the average scores of all students over 12 years of age.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table are cells where the AVERAGEIF functions will be tested.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-uncalculated.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
 To work out the average score of all students who scored more than 10, we would use the following formula:

=AVERAGEIF(B2:B8,">10")

 Notice two things in this formula. First, the criteria must always be enclosed in double quotes. Second, we've only included two arguments within the parentheses, as there's no need to refer to any other data elsewhere within our calculation.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, the first AVERAGEIF calculation has been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-1.png) 

 This has correctly picked up the scores of Students A, B, D, and E, as these are all more than 10.

 To work out the average scores of all students over 12 years of age, we would use the following formula:

=AVERAGEIF(C2:C8,">12",B2:B8)

 Notice the difference between the two formulas. Where the previous calculation contained two arguments, this one contains three, as we are assessing two sets of data.

 The "C2:C8" part of the formula tells Excel to look in that range (the students' ages) for the criteria, the ">12" part tells Excel to identify any values over 12 in the C2:C8 range (the students' ages), and "B2:B8" (the students' scores) is the part being averaged.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, both AVERAGEIF calculations have been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-2-1.png) 

 This has correctly picked up the scores of Students A, B, D, and E, as they are all over 12 years of age. The calculation also ignores logical values, which is why it hasn't considered Student F, even though they are over 12 years old.

 The criteria used in AVERAGEIF can use one of Excel's six logical operators—these are > (greater than), < (less than), = (equal to), <= (less than or equal to), >= (greater than or equal to), or <> (not equal to)—and wildcards (\* and ?). If you want to include an actual question mark or asterisk, add a tilde (\~) before the character.

##  How to Use AVERAGEIFS in Excel

 The AVERAGEIFs function allows you to include several criteria to assess before calculating the average. It works using the following syntax:

=AVERAGEIFS(A,B,C)

 where A identifies the cells to average, B is the cells used to identify the criteria, and C is the criteria. There can be up to 127 criteria, so multiple pairs of cells (B) and criteria (C) can be used.

 Take this example, where we want to work out the exam scores of students in Green House over the age of 10.

![Excel sheet showing a table with four columns: column A contains student names, column B contains their exam scores, column C contains their house, and column D contains their age. Next to this table is a cell where AVERAGEIFS will be performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageifs-uncalculated.png) 

 To do this, we would use the following formula:

=AVERAGEIFS(B2:B8,C2:C8,"Green",D2:D8,">10")

 "B2:B8" contains the data to be averaged (the students' scores), "C2:C8" is the first range to be tested with the criterion of "Green" (the student's house), and "D2:D18" is the second range to be tested with the criterion of ">10" (the student's age).

![Excel sheet showing a table with four columns: column A contains student names, column B contains their exam scores, column C contains their house, and column D contains their age. Next to this table is a cell where an AVERAGEIFS calculation has been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageifs-calculated-1.png) 

 This has correctly averaged the scores of Students D and G, as they are both in Green House and are over 10 years old.

 Other things to note about AVERAGEIFS:

* TRUE is counted as 1, and FALSE is counted as 0.
* In the criteria, you can use a question mark (?) as a wildcard to match any single character, or an asterisk (\*) as a wildcard to match any sequence of characters. Use a tilde (\~) before the character if you're looking to identify an actual question mark or asterisk.

---

 As well as using AVERAGEIF and AVERAGEIFS, you can [sort and filter data in Excel](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/) to only show certain figures within your tables.

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-fix-there-is-no-sound-on-twitter-videos/"><u>[New] 2024 Approved  Fix There Is No Sound on Twitter Videos</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-echoes-in-the-room-mac-sound-studio-for-2024/"><u>[New] Echoes in the Room  Mac Sound Studio for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-advanced-image-manipulation-with-pixlr-tips/"><u>[Updated] Advanced Image Manipulation with Pixlr Tips</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-boost-visibility-with-customized-channel-names-for-2024/"><u>[Updated] Boost Visibility with Customized Channel Names for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-streamlining-your-watch-time-on-instagram-mobiledesktop/"><u>[Updated] Streamlining Your Watch Time on Instagram (Mobile/Desktop)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1-unleash-video-magic-mastering-spectacular-effects-and-filters/"><u>1. Unleash Video Magic: Mastering Spectacular Effects & Filters</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1-ultimate-mac-video-converter-leading-the-pack-with-native-intel-qsv-acceleration-support/"><u>1) Ultimate Mac Video Converter: Leading the Pack with Native Intel QSV Acceleration Support</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-ultimate-chuckles-and-pixels-suite/"><u>2024 Approved  Ultimate Chuckles and Pixels Suite</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macx/"><u>移動式 MacX ビデオコンバータ - 世界で最も優れた無料モバイル動画変換ツール</u></a></li>
<li><a href="https://some-approaches.techidaily.com/anytime-anywhere-access-with-a-digital-backup-how-to-transfer-and-play-venom-from-dvd-to-digital-device/"><u>Anytime, Anywhere Access with a Digital Backup: How to Transfer and Play 'Venom' From DVD to Digital Device</u></a></li>
<li><a href="https://extra-resources.techidaily.com/connect-and-captivate-youtube-twitter-and-facebook-using-zoom-for-2024/"><u>Connect and Captivate  YouTube, Twitter & Facebook Using Zoom for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/conversione-rapida-e-senza-perdite-di-qualita-trasforma-i-tuoi-file-mkv-in-mp4-sul-tuo-mac/"><u>Conversione Rapida E Senza Perdite Di Qualità: Trasforma I Tuoi File MKV in MP4 Sul Tuo Mac</u></a></li>
<li><a href="https://some-approaches.techidaily.com/download-your-first-8k-ultra-hd-4320p-60fps-videos-for-free-directly-from-youtube/"><u>Download Your First 8K Ultra HD (4320P, 60Fps) Videos for Free - Directly From YouTube!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/easy-guide-for-rotating-footage-by-quarter-half-and-three-quarters-turns/"><u>Easy Guide for Rotating Footage by Quarter, Half and Three-Quarters Turns</u></a></li>
<li><a href="https://some-approaches.techidaily.com/effortless-guide-convert-your-dvds-into-avi-format-on-mac/"><u>Effortless Guide: Convert Your DVDs Into AVI Format on Mac</u></a></li>
<li><a href="https://some-approaches.techidaily.com/effortless-ios-mac-device-syncing-with-copytrans-for-mac/"><u>Effortless iOS-Mac Device Syncing with CopyTrans for Mac</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-advice-on-computer-components-from-toms-hardware-team/"><u>Expert Advice on Computer Components From Tom's Hardware Team</u></a></li>
<li><a href="https://some-approaches.techidaily.com/expert-in-digitizing-content-digiartys-innovative-solutions-for-dvd-and-video-format-conversion/"><u>Expert in Digitizing Content: Digiarty's Innovative Solutions for DVD & Video Format Conversion</u></a></li>
<li><a href="https://some-approaches.techidaily.com/hot-topics-in-technology-expert-tips-for-apple-devices-ios-enhancements-and-entertaining-ways-to-stay-updated/"><u>Hot Topics in Technology: Expert Tips for Apple Devices, iOS Enhancements, and Entertaining Ways to Stay Updated</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-poco-x5-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/how-to-solve-your-iphones-bluetooth-issues-following-the-latest-ios-17-update/"><u>How to Solve Your iPhone's Bluetooth Issues Following the Latest iOS 17 Update</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-ispoofer-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Tecno Phantom V Flip? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-samsungs-rival-the-leading-cameras-to-match-your-gear-360-needs/"><u>In 2024, Samsung’s Rival  The Leading Cameras to Match Your Gear 360 Needs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1724765904134-macx-dvd/"><u>MacX DVDコレクションでお得な情報が見つかる! プロモ節度大解放</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mastering-the-art-of-prores-recording-on-iphone-13-a-comprehensive-tutorial/"><u>Mastering the Art of ProRes Recording on iPhone 13 - A Comprehensive Tutorial</u></a></li>
<li><a href="https://some-approaches.techidaily.com/optimize-your-collection-with-quality-80s-movie-downloads-and-copies/"><u>Optimize Your Collection with Quality 80'S Movie Downloads & Copies</u></a></li>
<li><a href="https://some-approaches.techidaily.com/slash-h2t64-encoded-file-sizes-up-to-50-for-optimized-storage-and-streaming/"><u>Slash H.2t64 Encoded File Sizes Up to 50%% for Optimized Storage and Streaming</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-guide-reverting-from-macos-ventura-back-to-monterey-or-previous-versions/"><u>Step-by-Step Guide: Reverting From macOS Ventura Back to Monterey or Previous Versions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-4-no-cost-dvd-sound-extraction-tools-for-harvesting-audio-from-discs/"><u>Top 4 No-Cost DVD Sound Extraction Tools for Harvesting Audio From Discs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-rated-macx-avi-converter-transform-your-media-into-any-video-type-without-payment/"><u>Top Rated MacX Avi Converter - Transform Your Media Into Any Video Type without Payment!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-rated-virtual-reality-vr-video-players-compatible-with-pc-mac-android-and-iphone-2018-edition/"><u>Top-Rated Virtual Reality (VR) Video Players Compatible with PC, Mac, Android & iPhone - 2018 Edition</u></a></li>
<li><a href="https://android-transfer.techidaily.com/two-ways-to-sync-contacts-from-nokia-c300-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Two Ways to Sync Contacts from Nokia C300 to Gmail | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unveiling-visuals-top-10-instagram-editing-applications-for-professionals/"><u>Unveiling Visuals  Top 10 Instagram Editing Applications for Professionals</u></a></li>
</ul></div>

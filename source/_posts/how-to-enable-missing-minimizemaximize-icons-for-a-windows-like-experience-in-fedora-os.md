---
title: How to Enable Missing Minimize/Maximize Icons for a Windows-Like Experience in Fedora OS
date: 2025-01-06T20:52:36.782Z
updated: 2025-01-10T01:31:59.089Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Fedora's GNOME desktop lacks minimize and maximize buttons, making it confusing for newcomers.
* You can restore them with this command in a terminal window "gsettings set org.gnome.desktop.wm.preferences button-layout 'appmenu:minimize,maximize,close'." You can also use GNOME Tweaks to restore the missing buttons.
* Tweaking desktop settings in Linux is optional, but it offers the freedom to customize your Linux experience and to work around annoyances.

 Fedora’s GNOME desktop windows neither have minimize nor maximize buttons. It’s counterproductive because it makes the Linux desktop even more alien to newcomers. Here are two different ways to get them back.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Restoring the Buttons Using GNOME Tweaks

 The GNOME Tweaks tool lets you adjust a lot of desktop settings, not just the buttons in the title bar of a window. To install it on Fedora, type:

sudo dnf install gnome-tweaks

 To launch Tweaks, press the Super key and start to type “tweaks.” You’ll see the Tweaks icon.

![Launching GNOME Tweaks](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-6.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click the icon to start the program. The main screen of the application will appear. In the sidebar, click the "Windows" option.

![The main GNOME Tweaks window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-12.png) 

 You’ll see two sliders in the "Titlebar Buttons" section labeled "Maximize" and "Minimize."

![The Windows pane of the GNOME Tweaks tool](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-12.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-recording.techidaily.com/new-reimagining-streaming-experience-beyond-manycam-for-2024/"><u>[New] Reimagining Streaming Experience Beyond ManyCam for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-streaming-spectrum-digital-vs-physical-frontiers/"><u>[New] The Streaming Spectrum Digital vs Physical Frontiers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-6-virtual-reality-vr-gloves-to-check-out/"><u>[New] Top 6 Virtual Reality (VR) Gloves to Check Out</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-master-your-screen-time-top-10-in-depth-guide-to-excellent-offline-ios-gaming/"><u>[Updated] Master Your Screen Time - Top 10 In-Depth Guide to Excellent Offline iOS Gaming</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-premier-choice-the-best-10-recorders-for-tech-talks/"><u>[Updated] Premier Choice The Best 10 Recorders for Tech Talks</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-dji-phantom-3s-expert-features/"><u>[Updated] Unveiling DJI Phantom 3'S Expert Features</u></a></li>
<li><a href="https://vp-tips.techidaily.com/guide-securing-smooth-playback-on-any-device-windows-mac-android-and-iphone/"><u>Guide: Securing Smooth Playback on Any Device - Windows, Mac, Android & iPhone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-xr-without-passcode-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone XR Without Passcode? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-lenovo-thinkphone-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Lenovo ThinkPhone Without PUK Codes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-essential-iphone-handbook-for-gif-enthusiasts/"><u>In 2024, The Essential iPhone Handbook for GIF Enthusiasts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-clicker-article-titles-maker/"><u>In 2024, Top Clicker Article Titles Maker</u></a></li>
<li><a href="https://sound-issues.techidaily.com/no-audio-post-windows-11-upgrade-quick-fixes-inside/"><u>No Audio Post-Windows 11 Upgrade? Quick Fixes Inside!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-art-of-narrative-on-film-for-2024/"><u>The Art of Narrative on Film for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-vision-tech-top-5-for-slow-motion-for-2024/"><u>Ultimate Vision Tech Top 5 for Slow Motion for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-samsung-galaxy-s23-tactical-edition-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Samsung Galaxy S23 Tactical Edition Phone Password Without Factory Reset Full Guide Here</u></a></li>
</ul></div>


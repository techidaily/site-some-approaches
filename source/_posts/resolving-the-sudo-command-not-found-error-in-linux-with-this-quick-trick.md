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



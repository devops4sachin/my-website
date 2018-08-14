+++
title =  "Article"
date = 2018-08-08T14:47:38+05:30
tags = []
featured_image = ""
description = ""
+++

+++
title =  "Article"
date = 2018-08-08T11:54:52+05:30
tags = []
featured_image = ""
description = ""
+++

### How to Install Sublime Text 3 on Ubuntu and Other Linux Distributions ###

Last updated May 26, 2018 By Abhishek Prakash 11 Comments

Brief: This tutorial shows several ways to install Sublime Text 3 on Ubuntu and other Linux distribution for free. Both GUI and command line ways have been discussed. 

Sublime Text is a cross-platform proprietary text editor that is available for Linux, Windows and macOS used for “code, markup and prose”. It has often been termed as the best code editor for a long time.

Sublime Text has been facing the tough competition due to new modern code editors like Atom and Visual Studio Code. Despite that, Sublime Text on Linux still has a good user base.
Install Sublime Text on Ubuntu [Graphically]

Installing Sublime Text on Ubuntu is way easier thanks to Snap support in Ubuntu Software Center. All you need to do is to search for Sublime Text in the software center and install it from there in a couple of clicks.
Install sublime text on Ubuntu Linux
Sublime Text is available in Ubuntu Software Center

Alternatively, you can also use Snap command to install Sublime Text 3:

sudo snap install sublime-text

Install Sublime Text on Ubuntu and other Linux [Command Line]

If you do not like Snap packages, don’t worry. Packages and package repositories have been provided for major Linux distros. Users of Debian, Ubuntu and other Ubuntu-based Linux distribution such as Linux Mint, elementary OS etc, can follow the commands below to install Sublime Text 3:

wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
sudo apt-get update
sudo apt-get install sublime-text

For Arch, CentOS, Fedora and openSUSE, please follow the installation instructions on the page below:

Install Sublime Text 3 on Linux 
Suggested read
How To Install Visual Studio Code On Ubuntu
New Features in Sublime Text 3.0

After several years in beta, Sublime Text 3.0 was finally released last year. The stable version of Sublime Text 3 sees major changes seen in almost every aspect of version 2.0. According to the release statement, “virtually every aspect of the editor has been improved in some way, and even a list of the major changes would be too long.”

The major changes to be seen in Sublime Text 3.0 are the Goto Definition, the new UI, syntax highlighting engine and an expanded API. Spell-check and word wrapping work better now.

The release specifies that Sublime Text 3.0 has more performance when compared to Sublime Text 2 even though it is larger in size than 2. It now has a faster startup, scrolling is more efficient and files open faster.

General UI

    The most prominent change here is the settings which now opens in a new window. The user and default settings stand side-by-side.
    Image preview is added when opening images
    A preview tab is created when previewing files from the sidebar
    The status bar now displays encoding and line endings
    Panel Switcher has been added to the status bar
    When pressing ctrl+w, a tweaked window closing behavior is seen

OS Integration for Linux

    Starting Sublime Text from the command line will daemonize the process by default
    Sudo save has been added
    Menu hiding now possible
    Other fixes like the incorrect handling of double clicks in the Find panel and underscore display in some of the menus

Editor Control

    An “Open URL” will show when you right-click on a URL
    Word wrap behavior improved
    Word navigation has been improved
    Paste from History added
    Autocomplete works as expected in macros
    Spell checking word selection behavior has improved

You can check out all the Sublime Text 2.0 to 3.0 changes here.

Sublime Text may be downloaded and evaluated for free for unlimited time, however, a license must be purchased for continued use.

Sublime Text 3.0 already accepts license key for those who purchased it in February 2013. For those who have a license key for Sublime Text 1 or 2, they can purchase an upgrade.
In the end

I hope this tutorial helped you to install Sublime Text 3 on Linux. If you have any questions or suggestions, do let me know in the comment section below.

Filed Under: Apps, News Tagged With: Release, Sublime Text, Sublime Text 3.0
About Abhishek Prakash

I am a professional software developer, and founder of It's FOSS. I am an avid Linux lover and Open Source enthusiast. I use Ubuntu and believe in sharing knowledge. Apart from Linux, I love classic detective mysteries. I'm a huge fan of Agatha Christie's work.
Join Our Vibrant Linux Community
132.2k Follows

    Twitter
    4.2k Followers
    YouTube
    8.4k Followers
    Instagram
    9k Followers
    Facebook
    110.5k Followers

Subscribe to Weekly Newsletter
Sign up for FREE weekly newsletter
Join an exclusive community of over 75,000 other Linux learners to become a better Linux user.
I agree to receive emails from It's FOSS.
New to Ubuntu? Start Here!
Getting started with Ubuntu
About Pages

    About It's FOSS
    Meet the team
    We Donate to FOSS Projects

Contact Pages

    Contact Us
    Get Featured on It's FOSS
    Request a tutorial

Stay in Touch with It's FOSS

    Follow us on Facebook
    Follow us on Google Plus
    Follow us on Instagram
    Follow us on Pinterest
    Follow us on Twitter
    Subscribe to Newsletter
    Subscribe to YouTube Channel

Communities

    Exclusive Telegram Channel
    Join LinkedIn Community
    Linux Users Group on Facebook
    Linux Users Group on Google Plus
    Linux Users Group on Reddit

Policies

    Affiliate Policy
    Privacy Policy

Copyright © 2018 It's F.O.S.S · Built on Genesis Framework
Powered by OptinMonster
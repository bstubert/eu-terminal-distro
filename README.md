# Qt Embedded Linux System for Operator Terminal

This is the companion repository for the blog post:
  - [Setting Up Yocto Projects with kas](https://embeddeduse.com/2021/09/18/setting-up-yocto-projects-with-kas/). How to install kas and how to build an embedded Linux system with kas for the Toradex Verdin iMX8M Mini.

You have installed kas as described in the post [Setting Up Yocto Projects with kas](https://embeddeduse.com/2021/09/18/setting-up-yocto-projects-with-kas/). The post also explains some fixes to common errors.

You build the embedded Linux system for the Toradex Verdin iMX8M Mini with kas as follows.

    $ cd /public/Projects
    $ git clone https://github.com/bstubert/eu-terminal-distro.git
    $ cd eu-terminal-distro
    $ kas-container build ./eu-terminal-distro.yml

Instead of `/public/Projects`, you can use any other directory, to which you have read and write access as a normal user.

Laptop
======

Laptop is a script to set up a Mac OS X or Linux laptop for Rails development.

Requirements
------------

1) Get XCode + Command Line Tools

You can get Xcode from the Mac App Store. You’ll need at least version 4.4 of Xcode for it to work with OS X Mountain Lion. After the installation, open up Xcode in your /Applications folder. 
You’d want to go to Xcode -> Preferences -> Downloads tab then install the “Command Line Tools.” After you’re done, quit Xcode and fire up Terminal.

2) Set zsh as your default shell and install Oh-My-ZShell

Run `curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh`

3) Install XQuartz, a version of the X.Org X Window System that runs on OS X

http://xquartz.macosforge.org/landing/

Install
-------

Run our script:

`zsh <(curl -s https://raw.github.com/zenjoy/laptop/master/bootstrap)`

What it sets up
---------------

* Bundler gem for managing Ruby libraries
* Foreman gem for serving Rails apps locally
* Hub gem for interacting with the GitHub API
* Homebrew for managing operating system libraries (OS X only)
* ImageMagick for cropping and resizing images
* Qt for headless JavaScript testing via Capybara Webkit
* Rails gem for writing web applications
* Rbenv for managing versions of the Ruby programming language
* Redis for storing key-value data
* Ruby Build for installing Rubies
* Ruby stable for writing general-purpose code
* SSH public key for authenticating with Github and Heroku

It should take less than 15 minutes to install (depends on your machine).

Credits
-------

This script is heavily inpired by Laptop by [thoughtbot, inc](http://thoughtbot.com/community). They're awesome!
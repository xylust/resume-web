<p align="center">
  <img src="https://i.imgur.com/KJzR1Ve.png"/>
</p>

# Introduction

This website has been built using [jekyll](https://jekyllrb.com/). It is currently being deployed live on [Netlify](https://www.netlify.com/) using this repository. You can find the project live [here](https://www.lukasn.com/).

# Running

## Windows

I recommend using [Ubuntu on Windows](https://tutorials.ubuntu.com/tutorial/tutorial-ubuntu-on-windows), it is what I use personally to work on this website. I have this repository cloned on my Windows drive which I can access via Ubuntu on Windows by navigating to `mnt`, e.g. `mnt/c/Users/Me/Desktop/resume-web`.

1. Clone this repository to somewhere on your Windows machine
2. Installl [Ubuntu on Windows](https://tutorials.ubuntu.com/tutorial/tutorial-ubuntu-on-windows)
3. Install [jekyll](https://jekyllrb.com/docs/windows/#installation-via-bash-on-windows-10)
3. Run `sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev`, `nokogiri` will not work otherwise.
3. Navigate to `mnt/windows_drive/location/to/this/repo` using Ubuntu on Windows
3. Run `bundle install`
3. Run `bundle exec jekyll serve` to begin a localhost session of the website
3. Navigate to `localhost:4000`

## Linux

Assuming jekyll is installed:

1. Clone this repository
2. Run `bundle install`
3. Run `bundle exec jekyll serve` to begin a localhost session of the website
3. Navigate to `localhost:4000`

# Credits

This project was initially forked from [jglovier](https://github.com/jglovier/resume-template). If you are looking to start your own I highly recommend beginning from his/her template instead!

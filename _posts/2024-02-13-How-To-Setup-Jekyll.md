---
layout: post
title:  "How To Setup A Website with Jekyll"
author: Adam
categories: [ Jekyll, Adam ]
featured: true
image: assets/images/13.jpg
---
This Page will walk you though the steps of setting up and publishing a website, though github pages using the jekyll framework, in this guide we will laos be using the Mediumish theme for jekyll

## Step 1 Ruby<br>
Jekyll is made with the Ruby Language. Follow the link below and install Ruby for your machine.<br>
(https://jekyllrb.com/docs/installation/)

Make sure to follow ALL steps for installing Ruby, and make sure you confirm the instillation 
<br><br>

## Step 2 Ruby Gems
Jekyll also used the Gems Package Management system as before follow the link below and install gems complataly for your system.<br>
(https://rubygems.org/pages/download)<br><br>

## Step 3 Make and gCC<br>
Most Link Distros should have Make and gcc already installed, if not, or you are not on linux, make sure they are installed and work<br>
gcc  : https://gcc.gnu.org/install/
make : https://www.gnu.org/software/make/

# Step 5 Install jekyll
Now you can actually install jekyll. todo this cop and past the following commands into a terminal<br>
`gem install jekyll bundler`<br>

with jekyll now installed you have 2 options:<br>
1. Make a new Jekyll site and have a good day<br>
2. Use a Theme for you site<br><br>

IF you are making a new site with no theme : <br>`jekyll new ~NAME_OF_SITE~`<br>
`cd ~NAME_OF_SITE~`<br>

IF You want to use a theme Download or clone the repo locally and use that directory(we will be using mediumish in the next step)
<br>
At this point you have to open the "Gemfile" located in the root folder and add the following lines<br>
```
gem "jekyll", "~> 3.9"
gem "webrick", "~> 1.7"
gem "kramdown-parser-gfm"
```
Now go back to the terminal and type the fallowing<br>
`bundle add webrick`<br>
`bundle exec jekyll serve --livereload` <br><br>
And you should now have a localy running jekyll website!

# Step 6 Theme
You might want to USe a Theme  for your jekyll website, for this guide we will be using Mediumish<br>
(https://github.com/wowthemesnet/mediumish-theme-jekyll/) <br>




---
layout: post
title:  "How to install jekyll"
date:   2017-04-26 14:51:06 -0300
categories: jekyll update
---





<h1> How to install jekyll</h1>
<br>
#### 1: Install Chocolatey using `cmd` as shown here 
<br>
`@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1 && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"`
<br>
<br>
#### 2: Close`cmd` and reopen it to have Chocolatey available
<br>
<br>
<h4> <strong> Install dependencies and Jekyll </strong> </h4>
<br>
<h4> 3. Install <a href="https://chocolatey.org/packages/ruby">Ruby</a></h4>
`choco install ruby -y`
#### 4. Close and reopen `cmd`
#### 5. Install gem bundler `gem install bundler`
#### 6. Install jekyll `gem install jekyll`
<br>
<h4><samp> Now you can use jekyll commands to create a new site...</samp></h4>
<br>
`jekyll new my blog`
<br>
`cd myblog`
<br>
`jekyll serve`
<style>
body{
	background-color: #008080;
}
</style>
<img src="http://www.reactiongifs.com/wp-content/uploads/2013/10/tim-and-eric-mind-blown.gif" alt="mind blowned">
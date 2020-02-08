---
layout:     post
title:      Simple recursive python scrapper
subtitle:   w/ BeautifulSoup and selenium
date:       2020-02-07
author:     Wniu
header-img: img/tag-bg-o.jpg
catalog: true
tags:
    - python
    - scrap
    - beautifulSoup
    - selenium
    - chrome
---

## Overview

A lot of supervised and semi-supervised machine learning  algorithms need hugh amount of data through training validation and testing. A lot of popular image and video hosing/social media uses dynamic site and recaptcha to prevent being scraped. Sometimes using selenium and chromedriver with a viable cockle is the only way to scrap them.

This is basically another web scraper for me to practice my oop and prepare a ultimate task of scrapping online video for neural net training.

The entire system consists of using selenium with chromedriver to control chrome get page source then parse the page with BeautifulSoup. Finally put the useful content in a file of some type. The system uses a highly recursive object as main focus, that in itself introduced some problem.

Anyway, I am still a beginner. If you got any kind of problem and/or suggestion leave it in the comment section down below. And please be constructive.

### About asic world

asic-world.com is a wonderful tutorial site that summarize all thing asic. Since I majored in ic design. Having a singular place to learn everything from verilog HDL to synthesize to verification. I am kind of tired of going to website everytime and no quick global searching. So I want to scrap the site tutorial into pdf file.

*** 
**Disclaimer**

I want to be upfront and say this. I respect robot.txt copyright and online scraping policy. All my working in this post is aimed at research and training purposes. Any commercial use is not authorized. I am not responsible for illegal use of this work.
***
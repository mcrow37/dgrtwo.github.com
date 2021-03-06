---
layout: post
title: "Slides, videos, and tweets from the 2017 New York R Conference"
description: "Some notes from the 2017 New York R Conference, and slides and video from my talk."
date: 2017-05-22 11:30:00 -0400
category: r
tags: [r, statistics]
comments: true
---



In April I attended the [2017 New York R conference](http://www.work-bench.com/blog/2017/05/16/highlights-from-the-2017-r-conference/), hosted by [Lander Analytics](https://www.landeranalytics.com/) and [Work-Bench](https://www.work-bench.com/about). It was both the third time the conference was held and the third time I've attended, and it gets more fun each year, especially because this year eight of us attended from Stack Overflow (including all five of us on the Data Team).

Now that the [videos from the conference are all posted](http://www.rstats.nyc/2017), I'm sharing some thoughts on the conference, and the slides and video from my talk, below. [As is my habit](http://varianceexplained.org/r/user-jsm-conferences/), I'm also sharing some of my favorite tweets from the conference.

## We R What We Ask

I've [been at Stack Overflow](http://varianceexplained.org/r/year_data_scientist/) for almost two years now, which has granted me access to a lot of interesting data about how people code, including in my favorite programming language R. I got the chance to share these insights with the R community in my talk **We R What We Ask: The Landscape of R Users on Stack Overflow**.

* [Video](https://www.youtube.com/watch?v=WEwFckGPRzU)
* [Slides (Keynote)](https://www.dropbox.com/s/kimx2mm75r6aj6b/WeRWhatWeAsk-DavidRobinson.key?dl=1)
* [Slides (PDF)](https://www.dropbox.com/s/g3evox3uxrww50b/WeRWhatWeAsk-DavidRobinson.pdf?dl=1)

(I'm going to give a similar talk at the useR 2017 conference this summer, so if you're attending you can also see it then!)

I started by showing that Stack Overflow data can track the rise and decline of programming languages and technologies, by charting the growth of R questions in the last decade, along with several other technologies used in the expanding data science field. 

![](https://www.dropbox.com/s/6hz03phk89nov0x/growth-languages.png?dl=1)

(You can make your own plots of technologies using our new [Stack Overflow Trends tool](https://insights.stackoverflow.com/trends)).

I also examined the growth and decline of particular R packages, by parsing the code from questions and answers.

![](https://www.dropbox.com/s/3t1r9q7qv92a2u9/r-packages.png?dl=1)

One of my favorite results is a "bird's eye view" of the R package ecosystem, built from correlations of packages that tended to appear in answers to the same questions. You can see how it breaks the packages out into particular problem domains.

![](https://www.dropbox.com/s/nu3xn6ai54phj0v/ecosystem.png?dl=1)

Since I'm into live tweeting conferences, host Jared Lander surprised me by asking me to give a second, four-minute talk ([video](https://www.youtube.com/watch?v=pxwGIZlPKT0)) to share my advice about live-tweeting. That was fun!

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/drob">@drob</a> giving tips on live-tweeting a conference <a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> ✔️✔️✔️ <a href="https://t.co/VUx7aJy2D4">pic.twitter.com/VUx7aJy2D4</a></p>&mdash; Emily Zabor (@zabormetrics) <a href="https://twitter.com/zabormetrics/status/855518845779496961">April 21, 2017</a></blockquote>

## Talks

Ricardo Bion started the conference ([video](https://www.youtube.com/watch?v=70luTZU-D3E)) by talking about how Airbnb built an internal R ecosystem, including packages, classes, custom themes and even stickers. I was a great fan of his [blog post](https://medium.com/airbnb-engineering/using-r-packages-and-education-to-scale-data-science-at-airbnb-906faa58e12d) on the topic and I am always interested in hearing more about this philosophy.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Great kick-off to <a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> by <a href="https://twitter.com/ricardobion">@ricardobion</a>. Airbnb looks like an awesome place to become a strong r programmer and data scientist! <a href="https://t.co/DqpWCjY1MT">pic.twitter.com/DqpWCjY1MT</a></p>&mdash; Emily Robinson (@robinson_es) <a href="https://twitter.com/robinson_es/status/855415998538711042">April 21, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Serge Belongie gave a fascinating talk ([video](https://www.youtube.com/watch?v=mD5cuMza6Rc&feature=youtu.be)) on some of the newest challenges in image recognition, including developing a training set from users even when the training data isn't common knowledge (e.g. telling the difference between a sparrow and a robin).

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/SergeBelongie">@SergeBelongie</a>: w/deep learning, seeing if a bird is in a pic is now easy- what&#39;s hard is identifying type of bird<br><br>🐦🐔🐧🐤🦆🦅🦉<a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> <a href="https://t.co/Om2pwnSBqU">pic.twitter.com/Om2pwnSBqU</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/855418188015824900">April 21, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Sandy Griffith](http://www.sandradgriffith.com/) gave a brilliant talk on how her team went from a research question to a completed manuscript in just two days. I enjoy hackathons (like [this recent one](http://varianceexplained.org/programming/tagger-news/)) so I've often dreamed of being part of an effort like that.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">How did <a href="https://twitter.com/sgrifter">@sgrifter</a> and colleagues write a publication in 2 day? Feeling ownership, shutting off distractions, and strict timeline <a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> <a href="https://t.co/sQ0wb5he9Y">pic.twitter.com/sQ0wb5he9Y</a></p>&mdash; Emily Robinson (@robinson_es) <a href="https://twitter.com/robinson_es/status/855789522671611905">April 22, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

I also really enjoyed Friederike Schuur's talk ([video](https://www.youtube.com/watch?v=xcLjjeKzU-c&feature=youtu.be)) on the history and philosophy of data science, and how it compares to the history of software engineering.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/FSchueuer">@FSchueuer</a>: skeptics think data science will disappear w/ better tools- but people said exact same thing about programmers <a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> <a href="https://t.co/1DxCGyg4ro">pic.twitter.com/1DxCGyg4ro</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/855792035554627586">April 22, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

JD Long gave a popular talk ([video](https://www.youtube.com/watch?v=P7VnKgVMLvY)) about the role of empathy- with colleagues, with users, or with the subjects of data- in a technical career.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Empathy as cross validation of your models <a href="https://twitter.com/CMastication">@CMastication</a> <a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> <a href="https://t.co/WvIP2V1mFI">pic.twitter.com/WvIP2V1mFI</a></p>&mdash; sandy griffith (@sgrifter) <a href="https://twitter.com/sgrifter/status/855499687041937408">April 21, 2017</a></blockquote>

I'd been looking forward to Ramnath Vaidyanathan's talk ([video](https://www.youtube.com/watch?v=gf6KrnXLs9I)) on HTML widgets, and he didn't disappoint, showing us the details of creating a widget in real time.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Just watched <a href="https://twitter.com/ramnath_vaidya">@ramnath_vaidya</a> build a new htmlwidget from scratch in front of us in about 5 minutes 😮<a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> <a href="https://t.co/Ttw1wbvBfv">pic.twitter.com/Ttw1wbvBfv</a></p>&mdash; Julia Silge (@juliasilge) <a href="https://twitter.com/juliasilge/status/855799239200387073">April 22, 2017</a></blockquote>

There were many other excellent speakers: make sure you check out [the full list of videos](http://www.rstats.nyc/2017)!

## Stack Overflow Data Team

I was excited to see Julia Silge (only the third time we've met in person!) and data team members Nick Larsen and Jason Punyon, who normally work remotely but came to New York for the week.

Julia gave a terrific talk ([video](https://www.youtube.com/watch?v=0poJP8WQxew)) on the [tidytext package](https://github.com/juliasilge/tidytext), as well as our upcoming book [Text Mining with R](http://tidytextmining.com/)).

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">tidytext + dplyr can get to cool graphs like this in just a few lines of code b/c <a href="https://twitter.com/drob">@drob</a> &amp; <a href="https://twitter.com/juliasilge">@juliasilge</a> used tidy data principles <a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> <a href="https://t.co/wMA3hscSjE">pic.twitter.com/wMA3hscSjE</a></p>&mdash; Emily Robinson (@robinson_es) <a href="https://twitter.com/robinson_es/status/855880453194121216">April 22, 2017</a></blockquote>

Jason got a data-related souvenir from the trip.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">My favorite shirt I won at <a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> this week. <a href="https://t.co/xuXWDaHINw">pic.twitter.com/xuXWDaHINw</a></p>&mdash; ERSATZ DEVLOPER (@JasonPunyon) <a href="https://twitter.com/JasonPunyon/status/856214823830507520">April 23, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

And all around, our live-tweeting game was **on point**.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Three of the seven actual people on this board are <a href="https://twitter.com/StackOverflow">@StackOverflow</a> employees. <a href="https://twitter.com/hashtag/rstatsnyc?src=hash">#rstatsnyc</a> <a href="https://t.co/1OSxORvLiV">pic.twitter.com/1OSxORvLiV</a></p>&mdash; Kevin Montrose (@kevinmontrose) <a href="https://twitter.com/kevinmontrose/status/855828929013313538">April 22, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

I'll be going to a few other R and statistics conferences this year (including useR and JSM), but I'm particularly glad I got to share this one with my team.

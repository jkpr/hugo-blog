+++
draft = false
date = "2017-11-28T09:26:02-05:00"
tags = ["2017", "bash"]
description = ""
title = "Start using Bash"
highlight = true
css = []
scripts = []
+++

![GNU Bash logo](/img/gnu-bash-logo.png)

One of the reasons I switched to Mac when Windows 8 came out was Mac's UNIX-y background. I liked being able to open a terminal and do all the things I had been learning about in my computer science classes. Mac's default shell is Bash, or the Bourne Again SHell.
Sure, I could `cd` around, `ls` directories, and `cp` or `mv` things.
But, I knew I was not even close to tapping the power of the shell.
Unforunately, learning how to use Bash on the internet is difficult.
Many tutorials are old, have examples of usage heralding back to the beginning of UNIX, and have subtle errors and inconsistent style.
I was stuck in my progression.

# How to learn Bash

I recently stumbled upon this [bash hackers tutorial list](http://wiki.bash-hackers.org/scripting/tutoriallist) which reviews many of the Bash tutorials/guides/articles out on the web.
I am glad someone with more knowledge and experience was able to look at these tutorials/guides/articles with a critical eye to be able to show a novice where to go.

The following are the five highest-rated Bash readings from the Bash hackers wiki:

* [Bash guide on Greg's wiki](http://guide.bash.academy/)
* [Steve Parker's shell scripting guide](http://steve-parker.org/sh/intro.shtml)
* [Bash Guide for Beginners](http://tldp.org/LDP/Bash-Beginners-Guide/html/)
* [Bash by example series by IBM](https://www.ibm.com/developerworks/linux/library/l-bash/index.html)
* [Advancing in the Bash shell](http://samrowe.com/wordpress/advancing-in-the-bash-shell/)

I have now read the first three and they are all quite good. Bash syntax used to be a fog in my head, but after reading the first three guides, I am much more comfortable.
The Bash guide of Greg's wiki, now at [http://guide.bash.academy/](http://guide.bash.academy), is a very strong introduction.
That should be the first reading for most people, in my opinion.

# On second thought, don't use Bash

In my readings about Bash, I came across the [shell scripting guide from Google](https://google.github.io/styleguide/shell.xml). Basically, they recommend not to use Bash if it can be avoided, but it is OK in simple cases. Because scripts tend to be not so simple, Google recommends using Python instead.

> If you are writing a script that is more than 100 lines long, you should probably be writing it in Python instead. Bear in mind that scripts grow. Rewrite your script in another language early to avoid a time-consuming rewrite at a later date.


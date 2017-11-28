+++
title = "Beginning VIM"
description = ""
tags = ["vim","programming", "2017"]
date = "2017-02-28T10:52:57-05:00"
scripts = []
css = []
highlight = true

+++

How does one begin to use VIM? This is a question that has been asked many
times around the internets. The only answer I can give is to dive in and start
using.

![VIM logo](/img/vim.png)

Along the way I have found a few resources to be helpful. Definitely start
with the `vimtutor`. It takes 30 minutes to read and play around with. Once
finished, you should feel comfortable writing in `INSERT` mode and moving
around in `NORMAL` mode.

At the very bottom of `vimtutor` is a section on further reading. I am
currently working through `:help user-manual`. Since the help files are
read-only, I copy things from into a second window to try stuff out.

![Original keyboard VI creator used](/img/vim-keyboard.jpg)

Finally, here are some other tips and tricks I have picked up along the way.

* **Change the escape key to the caps lock key.** It is obvious that the
escape key is important in VIM. On older keyboards, the escape key was
approximately where the tab key is. Ask yourself, when was the last time you
used caps lock that wasn't for Internet raging? If you are like me, the
answer is nigh on never. Give it some love and bind the caps lock key to
`<ESCAPE>`. I use [Seil](https://pqrs.org/osx/karabiner/seil.html.en).
* **Use `INSERT` mode as little as possible**. With VIM, you need to be aware
of what mode you are in. `NORMAL` mode is called "normal" because it is meant
to be the "normal" mode. You should be there normally. Be a ninja: make your
edits and get out of there.
* **Try to minimize keystrokes.** As you are learning VIM, be aware that there
is probably a better way to do things than what you are doing now. Set a goal
never to use the arrow keys. Set a goal never to "press-and-hold" a key. For
example, instead of holding down `j` to scroll, try `}` to jump paragraphs. As
you seek out new and better ways to do things, your VIM vocabulary will
increase and you will be more effective.


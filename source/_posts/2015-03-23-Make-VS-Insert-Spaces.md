---
layout: post
title: Make Visual Studio Use Spaces for Newline Indents
published: true
---
It's really annoying when Visual Studio shows you this:

![_config.yml]({{ site.baseurl }}/images/vs1.png)

But github or vim shows you the same file like this:

![_config.yml]({{ site.baseurl }}/images/vim1.png)


If you use the "show whitespace" Visual Studio chord `(CTRL-R, CTRL-W)`, 
you'll see that visual studio inserts tabs instead of spaces by
default for newline indent:


![_config.yml]({{ site.baseurl }}/images/ws.png)


Visual Studio displays tabs as having the same 
width as four spaces.  But if you're collaborating with someone working 
in another text editor like vim, your automatically-inserted tabs will
appear larger than four spaces.

Here's how to make visual studio insert spaces instead of tabs on newline indents:
go to `Tools->Options->Text Editor->All Languages->Tabs`:

![_config.yml]({{ site.baseurl }}/images/spaces.png)


That's better:

![_config.yml]({{ site.baseurl }}/images/ws2.png)

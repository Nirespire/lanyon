---
layout: post
title: Poor Windows 9
---

Recently, Microsoft announced and [demoed](http://youtu.be/84NI5fjTfpQ?t=1m34s) their latest Windows OS: Windows 10. At
first glance it looks very similar aesthetically to windows 8 and 8.1, with a stronger emphasis on catering to the desktop
user rather than the tablet crowd.

As exciting as this news might be, I wanted to address a simple question that I and many others had about the newly
announced OS: **Why not Windows 9?**

There are a few theories surrounding the seemingly enigmatic decision to simply skip the number 9. The simplest reason
relates to how Microsoft hasn't exactly stuck to a consistent naming convention in the past. Rarely did the retail name
 of the OS actually coincide with
the [version number of the software](http://en.wikipedia.org/wiki/List_of_Microsoft_Windows_versions#Client_versions). For
example, windows 8 is actually windows NT version 6.2 and
Windows 8.1
follows closely at version 6.3. Actually, Windows hasn't shared its name with its version since 1996 and the release of
Windows NT 4.0.

Regardless, the reasoning behind what happened between then and now might be a more interesting topic to be revisited at a
later time. We return to the issue at hand and what I personally think is the most intriguing (possible, **not** confirmed)
reason why 9 was skipped. 

The following [link](https://searchcode.com/?q=if%28version%2Cstartswith%28%22windows+9%22%29) I found on
[/r/programming](http://reddit.com/r/programming)
not too long after windows 10 was announced presents the theorized issue.

Developers wanted their software to identify if they were running on Windows 95 and or 98. They accomplished this by
simply checking if the name of the OS running their program included the character 9. No other windows OS names contained
this character '9', so they thought it was a safe bet. I'm no expert on writing cross compatible windows applications (or
any windows applications for that matter), but I assume as soon as one person implemented this method, everyone did. It
follows the typical developer's process:

* Find issue that needs solving
* Check online or ask other developers if they have encountered this problem and have a solution
* Find a solution that solves the problem
* Implement said solution without further thought becuase if it was used before, it must be rock solid

Honestly, I don't blame the devs. This is a perfectly good method <del>90%</del> <del>70%</del> 50% of the
time...maybe. However, if the speculation is true, this workaround is so common, it forced Microsoft to literally skip
windows 9 lest a wide scope of applications suffer from compatibility issues if left unpatched.

This theory could very well be completely false and the marketing department at Microsoft simply sought to establish a new
naming scheme (analogous to OS X *insert large cat here*). Yet noticing correlation of this programming practice to its 
larger implications makes for something interesting to think about as a developer.
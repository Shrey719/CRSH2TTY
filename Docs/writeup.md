# Writeup 
I had an extra Chromebook that my friend wanted. However, it was keyrolled and on v128. So how do I unenroll it? I didn't know either, so I messed around in the OOBE for a while before putting it in my closet again. A while later, Hazel had the idea for a new exploit group. So I dug it out of my closet, and... it was unenrolled? I hoped this wasn't a one-off thing. I re-enrolled it and kept testing. After trial and error, I realized you needed to restart once before turning it off, and...
![unenrolled](/Docs/Images/unenrolled.png) 
I knew this meant something, so I tracked the time it took. 15 hours. This ended up being the minimum amount of time required after a few days of testing, but just to make sure I tested it with 15 again, and...
![unenrolled](/Docs/Images/unenrolled2.jpg) 
I needed a name. But what sounded good? CRSH2TTY is a funny name. It's pronounced "sea-are-shh-tootie". Plus, I could talk about it publicly and no one would think it's real! But why would I name it after a bad exploit? Well...

CRSH1TTY itself was *not* a good exploit at all. It required a near infinite amount of time due how it works:

3 codes get processed > Wait 10 secs > Roll code > Back to start

This means that, since it's always rolling, there's a non-zero chance you can hit a past code multiple times. CRSH1TTY is very slow.

Now, let's move on to CRSH2TTY. It's also slow, taking at least 15 hours, which isn't *that* bad considering you can do it on a weekend or in your last period at school, but it's nowhere near as fast as other exploits, however, it's also a *universal*, *USB-less* exploit that works on *all* versions, *and* supports re-enrollment.

"Universal" in this sense means that it works on *every* Chromebook *ever made*.

"USB-less" in this sense means that it does not require a USB drive to use. This is a big deal because a lot of Chromebooks have their recovery keys rolled, so they can't boot shims.

But how does unenrollment occur? We don't know. There are 3 leading theories:

-Flash Memory Decay
-Server-Side Bug
-Corrupted Data

If you want to read about these, go to [Theories](CRSH2TTY/Docs/theories)
 
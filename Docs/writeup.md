# Writeup 
I had an extra Chromebook that my friend wanted. However, it was keyrolled and on v124. So how do I unenroll it? I didn't know either, so I messed around in the OOBE for a while before putting it in my closet again. A while later, Hazel had the idea for a new exploit group. So I dug it out of my closet, and... it was unenrolled? I hoped this wasn't a one-off thing. I re-enrolled it and kept testing. After trial and error, I realized you needed to restart once before turning it off, and...\
![unenrolled1](Media/v124nissa.png) 
I knew this meant something, so I tracked the time it took. 15 hours. This ended up being the minimum amount of time required after a few days of testing, but just to make sure I tested it with 15 again, and...\
![unenrolled2](Media/v124nissa2.jpg) 
Then I decided to update from v124 to v127 (the current latest) to see if it worked, and tested it again. But was there a maximum amount of time? What if you were out for the day and didn't get a chance to check it?\
So I left it out for 26 hours, and...\
![unenrolled3](Media/v127nissa.png)
Okay, so it works on the latest version, but what about older versions?\
![unenrolled4](Media/v76peppy.png)
Yep!! :3\
It works on older versions (and older Chromebooks) too!\
(even though on most of these you could just unenroll with unroll, but whatever)\
So is this truly universal?\
...Probably. We'll never know until-\
![unenrolled5](Media/v31peppy.png)
It works on v31!!! :3 (You can tell it's unenrolled because of the "browse as Guest" button)
So this is officially universal! >w<\
\
But why name it CRSH2TTY?\
Let's start with CRSH1TTY. CRSH1TTY itself was *not* a good exploit at all. It required a near infinite amount of time due how it works:\
3 codes get processed > Wait 10 secs > Roll code\
This process repeats forever which means that since it's always rolling, there's a non-zero chance you can hit a past code multiple times. It's *very* slow.\
\
Because of this, CRSH2TTY is a funny name. I could talk about it publicly and no one would think it's real!\
And I feel like the name just *works*, due to both of them taking time to unenroll you. 15 hours itself isn't *that* bad considering you can do it on a weekend, but even though it's nowhere near as fast as other exploits, it's still a universal USB-less exploit.\
\
But how does unenrollment occur? We don't know. There are a few theories:\
\- Flash memory decay\
\- Server-side bug\
\- Enrollment data corruption
If you want to read about these, go to [Theories](CRSH2TTY/Docs/theories)\

<h2 align="center">!!! this page will be removed once we figure out what's going on !!!</h2>

1. Flash memory decay\
Flash memory can decay under certain conditions - but none that the Chromebook will ever be in, so let's not even bother *thinking* about this one.

2. Server-side bug\
chromeOS is kinda held together by birch wood & rusty nails. It's safe to assume that the server-side components were made the same way. There's a chance that the server has a "fallback mode" where if the Chromebook doesn't communicate with it for 15 hours, it'll just unenroll you, but why even have a fallback mode in the first place? \
This theory still doesn't explain the 2-second wait.

4. Enrollment data corruption\
You *must* wait 2 seconds each time, or it won't work. This might mean that it tries to get some data, but mismatches two sets of data effectively making it corrupted. Then, when it tries to enroll, it sees this bad data already here, and just... decides gives up. This explains the 2-second wait, but not how you have to leave it for at least 15 hours.\

The below image, ([v127nissa.png](/Docs/Media/v127nissa.png)) shows a background with a blue hue. The default ChromeOS v127 palatte colors are supposed to have a orange hue, not blue. The blue background is the default color that my district uses for it's login screen, which supports this theory. \
<p align="center"><img src="/Docs/Media/v127nissa.png" width="400" alt="v127nissa.png"/></p>

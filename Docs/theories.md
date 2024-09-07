!!! this page will be removed once we figure out what's going on !!!

1. Flash Memory Decay
Flash memory can decay under certain conditions - but none that the Chromebook will ever be in, so let's not even bother considering this one

2. Server-Side Bug
chromeOS is kinda held together by old wood & rusty nails. It's safe to assume that the server-side components were made the same way. There's a chance that the server has a "fallback mode" where if the Chromebook doesn't communicate with it for 15 hours, it'll just unenroll you, which would explain why it's time-based, but it doesn't explain why the fallback mode exists.

3. Corrupted data
From what I've seen, you *need* to wait 2 seconds each time it enrolls you before doing anything else, or it won't work. This might mean that it tries to get some data, but mismatches two sets of data effectively making it corrupted. Then, when it tries to enroll, it sees this data already here, and just... gives up. However, this doesn't really explain why it's time based. 
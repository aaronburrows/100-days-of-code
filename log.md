# 100 Days Of Code - Log

### Day 1: January 3, Tuesday

**Today's Progress:** Worked on touching up some CSS on my personal site.

**Thoughts:** I really need to spend more time on this site. A lot of it is a design process, but part of good design is good code. I'll have more to show for it in the coming days.

**Link(s) to work:**
1. [My personal site](https://aaronburrows.com)


### Day 2: January 4, Wednesday

**Today's Progress:** More CSS and refactoring some HTML on the personal site.

**Thoughts:** I know it's boring right now. I realize that I don't have a good working environment for myself (While my workflow at my full time job is fine, I want to get myself in a better position for personal projects, and I want something that's portable.)

**Link(s) to work:**
1. [My personal site (but there's nothing new yet)](https://aaronburrows.com)


### Day 3: January 7, Saturday

**Today's Progress:** You'll notice I skipped a couple days. I just want to be honest about putting in 100 total days. Today I worked on setting up Nginx on my local dev machine and read about using it as a reverse proxy for Node.js apps.

**Thoughts:** I really want to get good at the webserver stack (I'm pretty familiar with the standard LAMP setup, but there's so much more cool stuff now.) From what I see I really like Nginx. It seems far lighter and simpler to configure than Apache, which is a monster. Not a bad thing, just huge. I'm mostly serving static sites, and will experiment with some apps. Want to replace my CMS with something nice and modern too. I like WordPress, but there's a ton of stuff about it I hate. Current site is static HTML/PHP files, and I feel like I can do better than that, but without so much overhead. So right now establishing a good workflow and setting myself up with proper tools is the priority.

**Link(s) to work:**
1. Nothing to show for it (I promise this will change)


### Day 4: January 10, Tuesday

**Today's Progress:** JavaScript30 Example #1 - Drump kit.

**Thoughts:** Pretty cool I realize JavScript does some things natively that I've been relying on jQuery for or writing more complicated stuff for. This is exciting.

**Link(s) to work:**
1. [JavaScript30](https://javascript30.com/)
2. [Day 4](work/day04/)

### Day 5: January 12, Thursday

**Today's Progress:** JavaScript30 Example #2 - Clock Face.

**Thoughts:** This one is interesting. I'm not sure if there's a more practical way to sync Javascript with a clock, other than querying the time constantly. I did find that 1000ms sometimes caused it to skip a second if there was any latency. Changing the interval to 500ms solves this, though I'm not sure of the performance implications.

I thought it was funny that the author of this exercise went through the trouble of finding the angle of the clock face as a decimal value when a clock is already perfectly suited to measuring in degrees. Seems like an obvious mistake the author didn't think through.

I want to work out how to get the clock hands at different sizes in CSS. But changing the width throws off their positioning. I might revisit this one later to see what I can do.

I added a digital clock display too, though it's not styled. And I borrowed the more precise minute and hour hand position idea from @adamabernathy. It's a nice touch that makes the clock more realistic. (Though I like my math better, since I'm not going to a decimal and back again.)

**Link(s) to work:**
1. [Day 5](work/day05)


### Day 6: January 17, Tuesday

**Today's Progress:** Modified the clock CSS. Changed the hands to be vertically oriented to eliminate the need to compensate by adding 90 degrees to the hand rotation. Also changed the width and length of each hand and adjusted the offset on each hand individually, no longer needing the translateY on the clock face.

Managed to get the second hand to not rewind around the clock face when resetting to 0 degrees, but it's not smooth for that one second. I thought I could remove the transition, rotate, and then restore the transition in one swift move, but I can't due to the way the browser reflows content after Javascript executes. *[http://stackoverflow.com/questions/11131875/what-is-the-cleanest-way-to-disable-css-transition-effects-temporarily]*

**Thoughts:** Been skipping a lot of days this week. Pretty busy week. There were a couple extra days off work and the kids were home, and surprisingly it's even harder to get side work done under those circumstances sometimes. Besides that, I had a fantastic time with the kids over the weekend. I regret nothing. Though I will commit to putting more time to this, or else my 100 days will take over a year. That will not be acceptible. Also I didn't commit changes so it's one big nasty commit for several days worth of work. I'll get my act together, I promise. Also, I might soon from @adamabernathy again, and flip the order of my log to put the most recent entry at the top. I like that, except when I want to read an entire project log, then I'd rather it just be chronological.

**Link(s) to work:**
1. [Still in Day 5](work/day05)


### Day 7: January 18, Wednesday

**Today's Progress:** Fun with Array functions in ES6

**Thoughts:** This is a skill I need to work on deepening. Programming fundamentals like this are made more enjoyable in modern Javascript but they still seem pretty abstract. I'm happy with this though. These are fun.

**Link(s) to work:**
1. [Day 7](work/day07)


### Day 8: January 19, Thursday

**Today's Progress:** Spending more time on Array methods in ES6

**Thoughts:** Still working on honing these skills. Getting really solid here will be better for my career and my enjoyment of this work.

**Link(s) to work:**
1. [Day 8](work/day08)

<!-- ### Day 7: January 18, Wednesday

**Today's Progress:**

**Thoughts:**

**Link(s) to work:**  -->

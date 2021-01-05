# 100 Days Of Code - Log

### Day 0: December 20, 2020


**Today's Progress:** Preparing environment:
* updated Windows to latest feature update
* installed ~~WSL2~~ WSL (apparently WSL2 doesn't work with my Comodo Firewall though a patch is on it's way I'll just start with WSL which also works pretty well)
* installed OpenSuse (I already use Ubuntu at work so it's time for a change)
* installed rbenv, Ruby, git, etc ...

**Thoughts:** Wanted to start early but my body said no so I've been sleeping half of the day thanks to a headache. TIL that there's an ed25519 algorithm to generate SSH keys.

**Link to work:**  Some usefull links I used
* [Installing Ruby](https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-with-rbenv-on-ubuntu-18-04)
* [The WSL2 bug](https://forums.comodo.com/bug-reports-cis/ethernet-adapter-vethernet-wsl-cant-create-with-installed-comodo-t125940.0.html)
* [Build-essentials on OpenSuse](https://forums.opensuse.org/showthread.php/413553-Build-Essential)
* [Install WSL2](https://www.windowscentral.com/how-install-wsl2-windows-10)
* [Using SSH keys](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

### Day 1: Monday December 21, 2020

**Today's Progress:** Spend about 1,5h on it. Wrote very little Ruby code because my VSCode setup was still very basic and needed some tweaking. On the plus-side, I already wrote one unit test and I can run all my Ruby code with just a simple CTRL+ALT+N command in VSCode.

**Thoughts:** I still feel the headache from yesterday and my fingers are freezing off because I have the window open for some fresh air. I'm glad I have a silly project to work on and I hope to learn a lot from it. I've decided to dedicate myself to a no-zero days style instead of the very strict 1h rule.

**Link to work:**  [Todays commit](https://github.com/PW999/5e-dice-roller/commit/b7c398960be6fd8e16cede079e0db5b5f2ac287c) and a second one since I was in the mood to do some more work [click](https://github.com/PW999/5e-dice-roller/commit/7f436204bb3eaa20804e8460617919419e18e196)

### Day 2: Tuesday December 22, 2020

**Today's Progress:** Worked on a system to roll multiple dice, with advantage or disadvantage. Seems to work as it should. I kind of cheated with the mocks in my unit tests by exposing a method to inject these mocks (but it's not production code anyway). I didn't want to start using RSpec or Minitest yet, I first want to "master" the basics of unit tests in Ruby.

**Thoughts:** First day I'm doing this _after_ a working day. It already was a long day with lots of issues to investigate so I was kind of not in the mood but I didn't want to fail on my second day so I fired up my laptop anyway. It felt like I had already forgotten everything and I'm constantly using Java syntax in my Ruby code, but luckily the Linter warns me in time. Unit tests also save me a lot of time (though I wrote my code first and then my tests, which is kind of bad).

**Link to work:**  [Todays commit](https://github.com/PW999/5e-dice-roller/commit/b7c398960be6fd8e16cede079e0db5b5f2ac287c) and a second one since I was in the mood to do some more work [click](https://github.com/PW999/5e-dice-roller/commit/7f436204bb3eaa20804e8460617919419e18e196)

### Day 3: Wednesday December 23, 2020

**Today's Progress:** Skipped today. Wednesday is family day, my mom is the only person I get to see during this pandemic so I'm not going to sacrifice it for some Ruby code. Will probably skip more Wednesdays.

### Day 4: Thursday December 24, 2020

**Today's Progress:** Spent some time on making my code cleaner. Started on working on a parser for the user input but progress is slow as I still need to figure out how to parse it.

**Thoughts:** I start to get how Ruby can be used to write as little code as possible (which does not mean the most readable code). With every line of Ruby I write I have the feeling that I loose a bit of feeling with Java. TDD is nice but, especially for little projects like these.

### Day 5: Friday December 25, 2020

**Today's Progress:** The dice roller now works. Next step is to extend is so that we can define which damage is rolled. Since there's not much to do on a lock-down Christmas I decided to spend some more time getting an old project back-up and running: J-ExifTool.

**Thoughts:** I get the feeling that Ruby isn't always the most consistent language but that might just be me. I do get to like it more though and I'm also starting to get the hang of Visual Studio Code.

Java Integration kind of works but it'll probably never be as good as IntelliJ or Eclipse (though it's so much faster than Eclipse in any aspect :) ). I feel more comfy hacking on an old Java project than using Ruby (but that's probably because I lack the Ruby experience).

**Link to work:** [Revival branch](https://bitbucket.org/P_W999/j-exiftool/branches/compare/feature/21..)

### Day 6: Saturday December 26, 2020
**Today's Progress:** Back to Ruby. I started the Advent of Code 2020 challenge (the day _after_ Christmas ...) and they are great little challenges to learn Ruby. I finished the 4 challenges of the first 2 days without any error (in the result, not the code :) )

**Thoughts:**: Not sure if I spent an hour on coding but I had a great time and that's what counts I guess.

**Link to work:** [AoC 2020 Repo](https://github.com/PW999/AoC2020/)

### Day 7: Sunday December 27, 2020
**Today's Progress:** More Ruby today but I'm working on my dice roller. I've added parsing of the advantage/disadvantage modifier and improved the general code quality a bit using Rubocop.

**Thoughts:**: A bit a longer thought today, looking back at the previous week.

There are a couple of reasons I started this challenge:
1. There's not much to do during this global pandemic so I have a lot of spare time that I want to spend on something I like
2. I started a new job in March and they (we) use Ruby a lot in our CI/CD pipelines so I want to learn Ruby
3. I want to improve my general coding skils
4. I want to see if Visual Studio code is actually *that* good.

As for the number 1, having at least an hour a day that I can spend on coding is a good use of my extra spare time. I have to be honest that in the past 1,5 I have had my doubts about my job as a coder (due to loads of stress) so spending some stress-free time on coding only made me realize I still like it, I just don't like the stressy environments (hence the reason I quit consultancy).

For the second item on the list, I can already tell you that I learned a lot and there's so much that I've learned that I want to take with me in my day2day job. Ruby is a bit a quirky language if you come from Java, but that's why I love it, it's nothing like Java. Being only at the 14th place in the list of popular technologies of the (2020 Stackoverflow Survey)[https://insights.stackoverflow.com/survey/2020#technology-programming-scripting-and-markup-languages-all-respondents] it certainly isn't the most popular technology to working in, but I don't mind that.

It's only been a week but I'm starting to get the hang of Ruby so I *think* my Ruby skills are already improving. I'm also starting to appreciate Linters a lot more, they are a PITA and slow you down at first but they do give the immediate feedback you need (and will never get from a code review).

For the last part ... well it's not *bad*. It's versatile and works with a lot of languages and it's actually pretty stable and fast. I'm still not a fan of the Java integration, IntelliJ (Ultimate) and Eclipse just do it better. For small projects like J-ExifTool it should be sufficient I guess but I can't image developing our Spring Boot micro-service in VSCode.

One side-note I want to add, I'm still a bit of a cheater since I didn't participate in the online community thing of the #100DaysOfCode challenge (didn't tweet a lot about it either), but the most important thing is that I'm still doing it. Second, I'm also going to skip every Wednesday but count them as actual days of the challenge so instead it'll probably be a #115DaysOfCOde for me 🙂

**Link to work:** [Ruby Dice Roller](https://github.com/PW999/5e-dice-roller)

### Day 8: Monday December 28, 2020
**Today's Progress:** Worked on Advent of Code 2020 Day 4 today.

**Thoughts:**: I wasn't as motived as usual, I don't know why but it took me a while before I finally wanted to start. Yesterday I also completed day 3 in AoC and today day 4 and both days were a lot of trial-and-error (okay, not really but got a few wrong answers).

Maybe it's the perfectionist in me that doesn't like me getting wrong answers. I'm probably even more offset because I just read that some people spent 12 min on day 4, just jabbing some code in a JS console and I'm here working my ass off for an hour just to get wrong answers. But that's just my personallity, hopefully I'm still motivated tomorrow after another day of work.

### Day 9: Tuesday December 29, 2020
**Today's Progress:** Today I've spent some time on further upgrading J-Exiftool to 2020 (and now I realize that's stupid because 2020 is about to end 😅)

**Thoughts:**: Somehow I have the feeling that updating J-Exiftool is a bit cheating. Java is my main language and updating some dependencies and doing small code improvements isn't exactly a big challenge right. Still, after a long day of working (and hardly getting the chance to write some code) I'm still happy to be coding without any strings attached.

### Day 10: Wednesdays December 30, 2020
**Today's Progress:** No progress, it's my habitual skip day

### Day 11: Thursday December 31, 2020
**Today's Progress:** Started a new Ruby project. Not much progress after an hour because there's still the overhead of setting it up and getting everything right. I can run through directories already, next step will be to process all files and store the results in SQLLite.

**Thoughts:** I'm still struggling with the basics of Ruby but practice makes progress.

**Link to work:** [photo-graph](https://github.com/PW999/photo-graph)

### Day 12: Friday January 01, 2021 🎉🎊
**Today's Progress:** Continued on the photo-graph application. It can now store the data to a SQLite database so almost all pieces are finished, just need to integrate with the Pixela API and then stitch it all toghether.

**Thoughts:** The more I use Ruby to more I grow fond of it, it's great for simple and small scripts, in a couple of hours you get something functioning. The same is probably true for Python but we're not using that at work.

Yesterday I realised that a year ago I would have never done this with my work in mind. Leaving the consultancy world in favour for an internal position was such a life saver for me and I still do not regret it.

**Link to work:** [photo-graph](https://github.com/PW999/photo-graph)


### Day 13: Saterday January 02, 2021
**Today's Progress:** Today I helped a friend with a Firebase project. Wrote my first Firebase functions (which are like AWS Lambda's) and got the whole emulator thing up & running.

**Thoughts:** I'm all over the place with my 100 days of code 😂. I started with Ruby, then got me some Java and now I'm doing Node.JS/Firebase. I know way to little of Node.JS and modern Javascript to write proper code so tomorrow I'll probably first setup a proper linter to aid me writing some clean code.

### Day 14: Saterday January 03, 2021
**Today's Progress:** Continued working on the Firebase project. Cleaned up a lot of my Javascript bad habbits thanks to ESLint and slowly building a whole army of Firebase functions to power the system.

**Thoughts:** This is the second week, time for a deeper thought.

I've been working on a lot of different things, my 5e Dice Roller (Ruby), Advent of Code (Ruby), my old J-Exif library (Java), Photo-graph (Ruby) and since yesterday the Firebase project (Javascript/Node.JS). Two weeks ago I hardly had any clue about what I would create and it's been like that for a loooooong time. Call it a writer's block but inspiration was lacking and it stopped me from doing things. The fact that I have a lot of (small) projects actually pretty well proofs the point Mark Manson's "Do Something" principle (for thos who've read The Subtle Art of not Giving a Fuck). The simple act of acting results in inspiration which in turns creates motivation for more action.

I already mentioned it on day 12, but I really do like programming a lot more now that I can do it in my spare time. Having spent 10 years in consultancy, working for an awesome multinational that slowly turned into the greatest nightmare of itself (spoiler alert: they stripped us from our freedom and only cared about money, not the client, not their employees) almost made me believe that software development was just not my thing.
Having put all my energy into this shitty company, losing everything I loved and lived for almost made me reconsider certain life choices. And so I did; goodbey consultancy, hello internal position close to home, hello well-balanced work-life balance and hello #100DaysOfCode motivation (and hello Corona ... wtf).

So ***if you ever doubt about starting 100DaysOfCode***, I can only recommend that you *just so something*. Even if you've only coded for 20 minutes ... at least it's something ¯\\\_(ツ)\_/¯, it's better than doing nothing at all.

If you lack inspiration, you can try [AdventOfCode](https://adventofcode.com), they have funny, little programming excercices that usually are focussed on one aspect (like arrays, regular expressions, ... you just have to figure it out). There's 5 year worth of advents to finish so it'll keep you busy for a while.

### Day 15: Monday January 04, 2021
**Today's Progress:** Not much progress, I've spent 45 minutes getting ESLint to work again.

**Thoughts:** I've had a lot of things confirmed and again I get the confirmation the the Node eco-system is a hatefull thing.

### Day 16: Tuesday January 05, 2021
**Today's Progress:** Worked on my photo-graph app. It's running but it's slow because it's iterating the images on my NAS (over wifi)

**Thoughts:** I was going to use the Pixela API (and probably will) but I think I'm going to challenge myself by creating the image myself using something like SVG.

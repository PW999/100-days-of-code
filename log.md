# 100 Days Of Code - Log

### Day 0: December 20, 2020


**Today's Progress**: Preparing environment: 
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

**Today's Progress**: Spend about 1,5h on it. Wrote very little Ruby code because my VSCode setup was still very basic and needed some tweaking. On the plus-side, I already wrote one unit test and I can run all my Ruby code with just a simple CTRL+ALT+N command in VSCode.

**Thoughts:** I still feel the headache from yesterday and my fingers are freezing off because I have the window open for some fresh air. I'm glad I have a silly project to work on and I hope to learn a lot from it. I've decided to dedicate myself to a no-zero days style instead of the very strict 1h rule.

**Link to work:**  [Todays commit](https://github.com/PW999/5e-dice-roller/commit/b7c398960be6fd8e16cede079e0db5b5f2ac287c) and a second one since I was in the mood to do some more work [click](https://github.com/PW999/5e-dice-roller/commit/7f436204bb3eaa20804e8460617919419e18e196)

### Day 2: Monday December 22, 2020

**Today's Progress**: Worked on a system to roll multiple dice, with advantage or disadvantage. Seems to work as it should. I kind of cheated with the mocks in my unit tests by exposing a method to inject these mocks (but it's not production code anyway). I didn't want to start using RSpec or Minitest yet, I first want to "master" the basics of unit tests in Ruby.

**Thoughts:** First day I'm doing this _after_ a working day. It already was a long day with lots of issues to investigate so I was kind of not in the mood but I didn't want to fail on my second day so I fired up my laptop anyway. It felt like I had already forgotten everything and I'm constantly using Java syntax in my Ruby code, but luckily the Linter warns me in time. Unit tests also save me a lot of time (though I wrote my code first and then my tests, which is kind of bad).

**Link to work:**  [Todays commit](https://github.com/PW999/5e-dice-roller/commit/b7c398960be6fd8e16cede079e0db5b5f2ac287c) and a second one since I was in the mood to do some more work [click](https://github.com/PW999/5e-dice-roller/commit/7f436204bb3eaa20804e8460617919419e18e196)
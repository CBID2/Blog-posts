---
title: "Taming My First Pull Request to  FreeCodeCamp"
datePublished: Mon Sep 18 2023 12:00:09 GMT+0000 (Coordinated Universal Time)
cuid: clmou3rjg001r09l27mw0bcuv
slug: taming-my-first-pull-request-to-freecodecamp
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1694995908621/f1c0b615-02d2-4e59-a8b2-fffa61242ec1.png
tags: opensource, freecodecamp, reflection

---

## Welcome!

Ever heard the old saying, "Sometimes the hardest thing is the simplest one?" Well, I'm here to tell you that updating FreeCodeCamp's curriculum is like trying to untangle headphones – seemingly easy yet hard.

So, grab your favorite snack and beverage, and join me in reminiscing on the hurdles, moments where I questioned my life choices and sanity, and cheering the ultimate victory, making my first pull request to FreeCodeCamp's curriculum.

![Orange Gummy Bear yells, "Adventure Awaits Us!" to their sibling, Green. ](https://media.giphy.com/media/9WgUD23Jr5gMsCu9rl/giphy.gif align="center")

## What’s the Issue?

I was casually scrolling through the Issues tab when I stumbled upon this gem:

![Screenshot of the issue from FreeCodeCamp](https://cdn.hashnode.com/res/hashnode/image/upload/v1694990571900/412aa2ff-ffb0-437f-be17-ea94e05e9cc6.png align="center")

I couldn't help but think, "Adding a new lesson? Well, that seems as easy as pie!" Little did I know that I was going in for a bumpy ride.

![Terry Crews announces that my story is about to get intense. ](https://media.giphy.com/media/JYG7cRQqqG9SkpUFLb/giphy.gif align="center")

## Things Get **Real**

At first, I just made a tiny edit to a lesson—easy, right? But then, one of the maintainers politely commented, "Hey, you need to insert a whole new lesson for the box-sizing project" "Oh, no big deal", I thought. I cracked open the Contributing Guide, ready to conquer the world... or so I thought. Turns out, I couldn't find the right spot to add my brilliant revision. So, like a lost explorer with a faulty map, I fumbled with the step tools. Heck, I fumbled so much that I had to call it quits, close that pull request and start fresh.

In Round 2, I decided to spice things up by getting my colleague, Toby, on board to help with the box-sizing property madness. Things were looking rosy—green checks were popping up, and I was celebrating each one like it was New Year's Eve. But then, my moment of triumph came crashing down when I spotted not one, but two angry red checks, glaring at me like disapproving traffic lights.

Heartbreakingly, I had to start all over again. Round 3 saw me adding even more zest to the box-sizing property lesson and tweaking a few steps. Once again, I pushed those commits, crossed my fingers, and waited for the test results. I practically jumped for joy when I saw the browser test pass, but just as I was about to break out the confetti, a red check spoiled the party—this time on the translation test.

My heart sank, and I was all out of ideas. Just when I was about to throw in the towel, an angel appeared in the form of a comment.

![Simpsons character saying "Oh Golly, it's a miracle"  ](https://media.giphy.com/media/xT5LMutNZQ7yGJJYAM/giphy.gif align="center")

## **Victory is Here!**

Remember when I mentioned that an angel came to my rescue in the form of a comment? Well, feast your eyes on this beauty:  

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1694997584429/4694b2b8-5301-402b-a108-e7257cbd8641.png align="center")

Changing JSON files. Easy peasy, right? With the help of my trusty friend, Moshe, from the FreeCodeCamp Discord community, we tackled the task like pros. Pushed those commits, and boom, the web browser test waved the green flag. I thought I had this curriculum update thing in the bag, but a new challenge emerged. The new lesson needs to be translated into Spanish and Chinese. Now, my knowledge of Chinese is "你好" (Nǐ hǎo = Hello), and in Spanish, I was limited to "¿Qué lo que mi gente?" (What's up, my people?) or just plain "Hola." Not exactly translation material. So, I made a bold move of going to FreeCodeCamp's Spanish and Chinese Discord channels and unleashed my secret weapon: Google Translate. I begged for help in translating my lesson into their languages. Luckily, I met Germán from the Spanish channel and miyaliu from the Chinese channel. They graciously submitted their translations of my lesson, but here's the kicker, I got another red X after these commits were pushed. Why? The translations were added right into instead of the designated translation tool, [Crowdin](https://crowdin.com/).

![Woman facepalms at me getting another red check ](https://media.giphy.com/media/25aA1NOirpGqteJcDp/giphy.gif align="center")

But hey, here's the bright side, the maintainers decided to keep it anyway. Victory was almost mine, but alas, there was one more twist in this comedy of errors I had to conquer.

![Homer tiredly says "Just A Few Feet More" while dragging himself up a snowy mountain](https://media.giphy.com/media/l2Je9zHYveK012EVi/giphy.gif align="center")

## Al...most...there!

A maintainer dropped a bombshell: I had to revert some commits. Panic mode activated! I never reverted a commit in my life, so I'm not wrong for feeling nervous doing the commit-reverting spell, right? So there I was, embracing my inner nerd, scouring the depths of [GitKraken's magic book](https://www.gitkraken.com/learn/git/problems/revert-git-commit#revert-using-terminal), and learning the revered art of the revert command. It was time for my commit-reverting debut! Or so I thought...

Turns out that I performed the spectacular revert-the-wrong-commits dance SMH! 🤦🏾‍♀️ After I'd finished playing musical commits, I gave the real errors the boot, pushed my shiny new commits, and glued my eyes to the screen, watching the coding tests load in anticipation.

![Medium Brown-skinned tone hands with black-painted fingers cross each other ](https://media.giphy.com/media/iIfD71D1S93Kv6BrJV/giphy.gif align="center")

## Victory!

Like a plot twist in a sitcom, it happened! More green checks flashed on my screen. Everything fell into place. The maintainers gave their stamp of approval, and just like that, [my PR was officially merged](https://insights.opensauced.pizza/feed/476)! 🥳

![Screenshot of my merged PR](https://cdn.hashnode.com/res/hashnode/image/upload/v1694994636906/328da7c6-7c4f-4e6c-aa63-8a258e9db111.png align="center")

It was a long battle, but all of the struggles were worth it. Now before I end my epic tale of triumph, tears (mostly from laughter), and a whole lot of green and red checks, let me share a few golden pieces of wisdom that I've learned:

* **Be patient**
    
* **Always Test your commits before pushing them**
    
* **Collaborate with others**
    

Now, my friend, why not take a plunge into the world of contributing to [FreeCodeCamp’s curriculum](https://github.com/freeCodeCamp/freeCodeCamp)? You’ll never know, might just become the hilarious, challenging, and incredibly rewarding adventure you never knew you needed and inspire others to join you! 😁

## Credits

Cowgirl Taming a Horse by [deskridge](https://www.deviantart.com/deskridge/art/Cowgirl-Taming-a-Horse-920662879)

Fingers Crossed GIF by [GIPHY Studios 2021](https://giphy.com/clips/studiosoriginals-wish-good-luck-fingers-crossed-oz3uZRgXqR4yBEOoe1)

Happy Season 3 GIF by [The Simpsons](https://media.giphy.com/media/xT5LMutNZQ7yGJJYAM/giphy.gif)

Lets Go Adventure GIF by [HARIBO](https://media.giphy.com/media/9WgUD23Jr5gMsCu9rl/giphy.gif)

Oh Brother No GIF by [Preity G Zinta](https://giphy.com/gifs/no-facepalm-preity-zinta-25aA1NOirpGqteJcDp)

Struggling Season 9 GIF by [The Simpsons](https://media.giphy.com/media/l2Je9zHYveK012EVi/giphy.gif)

Terry Crews Nbc GIF by [America's Got Talent](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGxnaTk2ZDU5aHp3a3c5bXU2OXdxYXVqZzMzcG1wZDVlaXl6Z2pwMyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JYG7cRQqqG9SkpUFLb/giphy.gif)
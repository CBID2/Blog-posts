---
title: "Survey Says...Let's Make A Form"
datePublished: Sun Mar 19 2023 03:14:39 GMT+0000 (Coordinated Universal Time)
cuid: clfetr2ez069lr3nvbw0b1t99
slug: survey-sayslets-make-a-form
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1678936883075/5eec2217-d648-491b-8819-3c01ec1e0c6b.png
tags: programming, web-development, projects, reflection, cocodeblogs

---

# Welcome!

If there was a tech edition of Family Feud(it's a game show where people guess the answer to funny questions and win prizes), Steve Harvey would definitely ask this question: ”What is something that you dread filling out after taking a coding course?”

A. The final project

B. The survey form

C. Both

If you picked B, congratulations you win a Ford Edge! 🎊

![](https://media.giphy.com/media/L2TXrdIfAJkIQL91GQ/giphy-downsized-large.gif align="center")

Ooh, sorry I just remembered that I do not have the funds to buy you a Ford Edge. 😔 No worries, I can share my story on how I built a survey form from scratch, so grab a snack, your favorite drink, and enjoy the show!

![A clock saying story time. ](https://media.giphy.com/media/XrwenGNux1GpYu25Qp/giphy.gif align="center")

## How it all began

For this assignment, I had to build a functional form based on an app provided by [FreeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/). As an educator turned coder, I decided to use this opportunity to combine my love for surveys with my newfound passion for web design. So, I created a survey form for a fictional company's training course, because what's more thrilling than filling out a survey, right? To get inspiration, I referred to examples from the course as well as past survey forms I've seen. And now, without further ado, let's dive into the creative process!

![Mini Dr. Strange is telling us to go into the gold ring](https://media.giphy.com/media/l0HlxJMw7rkPTN8sg/giphy.gif align="center")

## My Creative Process

I mainly relied on HTML5 and CSS to bring my vision to life. I started off using the trusty `<article>` element for the layout, but alas, it wasn't doing it for me. So, I bid ado to `<article>`, said hello to `<div>`, and voila!

[![Screenshot of my survey form](https://user-images.githubusercontent.com/105683440/191130143-adb6245a-f68a-457c-b682-65b8a4271dd4.png align="center")](https://stellar-meringue-26087c.netlify.app/)

As shown above, I went for a soothing linear-gradient effect of blue and white to create a calming vibe because let's be honest, filling out survey forms after a long course can be stressful.

If I had to pick a challenge in building this form, it would be the dropdown menu. It seemed like no matter what I did, the menu just wouldn't fit seamlessly into the form. But after some trial and error (and maybe a few frustrated sighs), I finally found a solution that worked. I won't bore you with the technical details, but let's just say it involved some creative CSS positioning and a little bit of magic. And just like that, the dropdown menu was tamed and added to the form like a pro! Now onto the next clip!

![Film countdown in 3, 2, 1](https://media.giphy.com/media/CH8pZqw2t0G7m/giphy.gif align="center")

## My Favorite Code Snippets

Ah, we’re at the best segment of the show, the Code Snippet Runway! Grab your cameras (or in this case, change your computer to screenshot) because coming up the walkway, we have the wonderful, Email Validation!!!

```html
<label id="email-label"> Email Address</label>
<input type ="email" id="email-label" pattern ="[^ @]*@[^ @]*" placeholder="e.g. dantesmith@gmail.com">
```

I know you’re thinking “Email Validation? Really Chrissy?”, but creating this line of code was awesome because I usually keep my input elements pretty simple, but for this project, I wanted to spice things up with the `<pattern ="[^ @]@[^ @]">` element. Who knew email validation could be so exhilarating?

Next up, we have the lovely resize!

```css
textarea {
  resize: none;
}
```

Now, I know what you're thinking, "How could something as simple as `resize: none` be a favorite?" Well, sometimes the best things in life are the simplest ones. Before I discovered the magic of `resize: none`, the layouts I used for `textarea` was all over the place. They were like the wild west of form elements, just doing their own thing and wreaking havoc on my carefully crafted layout. But with just one little line of code, everything changed. Suddenly, my `textarea` layouts were organized and downright pretty. It was like watching a caterpillar turn into a butterfly, or turn into a majestic swan. Okay, maybe I'm being a bit dramatic, but you get the point. `Resize: none` may seem like a small feature, but it made a big difference in my form designing game.

Thank you for attending this year’s Code Snippet Runway! Now onto the next show!

![Camera man is helping us get back on air](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOTIzOWM1ZGNjNjIzNDMzZGZhM2IyNzliMTc0NzM3OWZhZTgwNDMxOSZjdD1n/26FeWTM16icjYEmeA/giphy.gif align="center")

## Conclusion

Creating this form was a blast! It was like being a mad scientist, but instead of creating monsters, I was creating beautiful forms. Also, I learned that sometimes it’s ok to use the &lt;div&gt; element for building elements and to not be afraid of being a bit experimental with lines of code. If you’re looking for a project to develop or sharpen your layout skills, I highly recommend doing this assignment on [FreeCodecamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/). And if you need someone to cheer you on, feel free to follow me on [Hashnode](https://chrissycodes.hashnode.dev/) and my other socials via [Linkfree](https://linkfree.eddiehub.io/CBID2). Happy Coding!😊

![Grey Screen says "The End"](https://media.giphy.com/media/MCupMc20PsFIct6n1G/giphy.gif align="center")

## Credits

American Design GIF by [Namaste Car](https://media.giphy.com/media/L2TXrdIfAJkIQL91GQ/giphy-downsized-large.gif)

Let's Go GIF by [Marvel Studios](https://media.giphy.com/media/l0HlxJMw7rkPTN8sg/giphy.gif)

SNL GIF by [Saturday Night Live](https://media.giphy.com/media/MCupMc20PsFIct6n1G/giphy.gif)

Rockos Modern Life Nicksplat GIF by [NickRewind](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOTIzOWM1ZGNjNjIzNDMzZGZhM2IyNzliMTc0NzM3OWZhZTgwNDMxOSZjdD1n/26FeWTM16icjYEmeA/giphy.gif)

Young Storytellers GIF by [Young Storytellers](https://media.giphy.com/media/XrwenGNux1GpYu25Qp/giphy.gif)
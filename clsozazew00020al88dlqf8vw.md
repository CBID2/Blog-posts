---
title: "Accessible Colors: How I Brought Rainbows to Everyone"
datePublished: Fri Feb 16 2024 18:23:58 GMT+0000 (Coordinated Universal Time)
cuid: clsozazew00020al88dlqf8vw
slug: accessible-colors-how-i-brought-rainbows-to-everyone
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1708107155860/75fb15ba-5871-4d3c-854d-2181f05387eb.png
tags: opensource, accessibility, reflection

---

## Dispelling a belief

Ever wonder why Skittles encourages us to taste the rainbow? To savor the beautiful colors the world has to offer. Unfortunately, about [2.2 billion people are unable to have this experience when navigating the internet](https://www.who.int/news-room/fact-sheets/detail/blindness-and-visual-impairment) due to color-blindness. Sad right? Curious on how to go about solving this problem? Well take your color picker and join me on my journey to turning open-source project's background colors into a feast for everyone's eyes.

## The Problem

I was scavenging [Leonardo Montini’s open-source project(a really awesome where you can post your open source contributions to your resume/CV)](https://github.com/DevLeonardoCommunity/github-stats) for some issues, but I could not find anything. So, I decided to do two accessibility tests on the webpage, and found these results:

1. The website's background colors scored low on the WEB AIM color contrast checker.
    

![Screenshot of color contrast test fail](https://cdn.hashnode.com/res/hashnode/image/upload/v1708104916070/34564906-57c7-40c7-be55-b5b383b36578.png align="center")

1. There is an empty form label
    

![Screenshot of second accessibility test saying there is a empty form label](https://cdn.hashnode.com/res/hashnode/image/upload/v1708104928784/97ec291f-1cf2-4298-9731-0a240d0f6711.png align="center")

From there, I thought “this could use some improvement” and decided to get to work.

## Level 1: Change the color

At first, I was going to make the change in the project’s `global.css` file. Then, I found the tailwind.config file and realized that the change needed to be made there, but there was just one tiny problem…I had no idea how to work with Tailwind. So, I went to the copilot section in [Tublian(it’s a site where you can find open source projects, apply for jobs, find people to collaborate with, etc)](https://www.tublian.com/welcome#), and typed some questions on how to add new colors in Tailwind. Unfortunately, it did not answer provide an answer like I’d hope, so I went to the next best things…Chrome DevTools and documentation. After clicking on the Inspect button, I clicked on the section that the HTML code for the website’s header, placed a link to the original website in another tab, reread the accessibility test’s suggestion, changed the primany-color’s hex code from `#3b82f6` to `#2d63bc` in Chrome DevTools tab, ran another accessibility test, and got these results:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1708105438219/b25a14a6-4070-4257-b7e7-3b4f675f5374.png align="center")

![GIF of a video game character chanting success](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2Jhemp1Y2t5YXZ3N2NkYTFrYWJ4dHRmc2FoazRsa3RvMjdueTB2dSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/GS1VR900wmhJ6/giphy.gif align="center")

From there, I pushed my code into my PR’s branch. Here it is:

```typescript
"light",
{
"custom-dark": {

primary: "#2d63bc",
 
secondary: "#a78bfa",

      accent: "#1FB2A5",

      neutral: "#191D24",

      "base-100": "#2A303C",

      info: "#3ABFF8",

      success: "#36D399",

      warning: "#FBBD23",

      error: "#F87272",
    },
```

Now before I could break out the vanilla ice cream and celebrate, I remembered that there was another part of the challenge that needs solving.

## Level 2: Putting a label on it

The next thing I had to is add a `label` attribute that’s in the dropdown menu since it’s enclosed in a `<form>` element. At first, I was not sure what class name to give it. I wanted use `dropdown` but it was already used. After doing some brainstorming, I decided to keep it simple and go with `themeToogle` since that’s the button’s feature(no pun intended). Here it is:

```typescript
 <div className="dropdown dropdown-bottom dropdown-end">
        <label
          for="themeToggle"
          tabIndex={0}
          className="btn btn-circle btn-ghost m-1"
          data-testid="themeSelectorButton"
        >
          {buttonIcon}
        </label>
        <ul
          tabIndex={0}
          className="dropdown-content z-[1] menu p-2 shadow bg-base-100 rounded-box w-52 mt-3"
        >
```

When I tested this code for accessibility, I got these results:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1708106230568/f855d66f-4783-4373-a830-c62682d57169.png align="center")

%[https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGM5MTl6NTlqazl3cWhxaGtpcnI1bGx3a2k4OGM3cGR6YXRreDFvMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xCgeEazpis53cUqoZY/giphy.gif] 

## Lessons Learned

If I had to pick two lessons from this experience, it would be the following:

* **Devtools are your friend:** It’s a great tool to use if you want to do before and after shots of your code.
    
* **Read the docs:** As prompt as tools like co-pilot are when it comes to giving coding solutions, it’s best to read the documentation of the code as it gives more insight on how to use the language effectively.
    

## Now it’s your turn

Overall, I enjoyed making this open source contribution and can’t wait to do more of them in the future. Speaking of open source projects, if you’re looking for a place to start your journey and gain knowledge about web accessibility, I highly recommend checking [Accessibilityforall](https://github.com/AccessibleForAll/AccessibleWebDev).
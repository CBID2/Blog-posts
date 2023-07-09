---
title: "3 Easy Uncommon Accessibility Techniques You Need to Know For Coding"
datePublished: Sun Jul 09 2023 01:35:39 GMT+0000 (Coordinated Universal Time)
cuid: cljurj5p90j046pnv77uw132g
slug: 3-easy-uncommon-accessibility-techniques-you-need-to-know-for-coding
canonical: https://www.showwcase.com/show/35721/3-easy-uncommon-accessibility-techniques-you-need-to-know-for-coding
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1688865878767/ec2841ea-b443-422c-9c2c-e07c79e8df61.png
tags: web-development, accessibility, coding

---

*Note: This post originally comes from* [*Showwcase*](https://www.showwcase.com/show/35721/3-easy-uncommon-accessibility-techniques-you-need-to-know-for-coding)

## Picture this

You’re currently scrolling through the web when out of nowhere, your stomach grumbles. Having a burger and fries is something that you’ve been craving lately, so you google some restaurants and find this local restaurant and see mouthwatering images of juicy burgers, milkshakes, and crispy fries. Excitement fills you as you click on the Enter button, but after the page loads, disappointment washes over you. The website is cluttered, making it difficult to navigate. The images are missing descriptions, leaving you wondering what each burger looks like. Frustration sets in as you struggle to find the menu or contact information, causing you to finally throw your hands up in defeat and head to the fridge to get yesterday’s leftovers. This, my friends, is what occurs when a website is not accessible. It ruins something as simple as ordering food online. I know, I know, accessibility is a scary word and a complex topic. But fear not, my fellow coders. In the post, I will introduce you to three yet uncommon accessibility techniques that would empower you to create websites and other projects that are not only visually appealing but will ultimately save your users from confusion.

![Mini Dr. Strange says "Let's Go!" while bringing up a portal for you to follow him](https://media.giphy.com/media/l0HlxJMw7rkPTN8sg/giphy.gif align="center")

## Technique 1: Semantic HTML5 Elements

Remember the labels that you often see on the tags of your clothes and the bag of chips you often munch on during your coding sessions? Semantic HTML tags have a similar purpose. They explicitly describe the purpose of the line of code. I know you’ve probably heard of `<article>` and `<section>` , but let me introduce a few tags that are often not talked about:

* `<abbr>`: This tag is often used to describe abbreviations for terms. Here’s how it looks:
    

`<p>When you're writing <abbr>LGTM</abbr> in the comment section of someone's pull request, it could mean two things:   <ul>   <li> Let's get to merging!</li>   <li> Looks good to me!</li>   </ul>   </p>`

It’s best to use this when the content of your website or project refers to a specific company or defining jargon for people who are new to a field or community like in the above code snippet.

* `<details>`: This element creates a disclosure widget where a user toggles it on and off to view information. Here’s an example:
    

`<details>   <summary>Details</summary>   You can pick whatever definition you'd like.   </details>`

It’s usually coupled with the `<summary>` element. I highly recommended using these elements when you want to give a little side note about something in your website or project.

* `<address>` : This tag is used to provide contact information. Here it is in action:
    

`<p> Want to work with me? Contact me via the information below:</p>   <address>   <a href="`[`mailto:janesmith@gmail.com">janesmith@gmail.com</a><br>   <a`](mailto:janesmith@gmail.com">janesmith@gmail.com</a><br>￼<a) `href="tel:+13165452398">(316)545-2398</a>   </address>`

I highly recommend using this for your projects or website if you do freelancing or run a side business.

Now semantic HTML is one only of the ways to make your project or website more accessible. Let’s look at another! 😊

![Bearded man says "Alright Moving..on" ](https://media.giphy.com/media/HU6BhsCvQvlQ3h1eV5/giphy.gif align="center")

## Technique 2: Keyboard Accessibility

![A news alert appears as "Breaking News" in white font with a red and blue background](https://media.tenor.com/Ng2uEPPbOUAAAAAC/breaking-news-news.gif align="center")

People with low vision and/or motor skill issues use the internet too! 😃 On a serious note, [about 2.2 billion people are either blind or have a vision impairment](https://www.who.int/news-room/fact-sheets/detail/blindness-and-visual-impairment), so not keeping this demographic in mind when you’re building your website and working on other coding projects puts you at great risk of losing a potential group of fans of your work. But don’t fret, here are some simple tips to ensure that your coding projects are keyboard accessible:

* **Put your headings in order:** Think of headings as the crucial steps to cooking a perfect pot of rice. When these steps aren't placed in order, it's like a recipe gone wrong. You'll be frantically running around the kitchen, unsure whether to wash the rice first or just toss the dry grains straight into the pot of boiling water. The result? A culinary disaster! Similarly, if you put the `<h3>` tag before the `<h1>` one, it's a recipe for confusion. Users will be scratching their heads, trying to make sense of your content, and ending up with a horrible browsing experience. So, save you and your users from a horrible digital experience (and a headache) and put your headings in numerical order.
    
* **Add a “skip to the** is **main website” link:** This especially useful \*\*\*\*if your website or coding project’s navigation menu is very long. Going through many sections is like going through that long, creepy maze at the amusement park. They both leave people fatigued, so add the skip link to save your users from another headache.
    

Note: If you’re concerned about the link making your design look unattractive, [WEBAIM](https://webaim.org/techniques/skipnav/#creating) recommends creating one that’s hidden until the user navigates to it with a keyboard A great example of this is [In-N-Out Burger’s](https://www.in-n-out.com/) website.

* **Make your links descriptive:** Like headings, links are the checkpoints that guide users through the labyrinth of the internet, so you don’t want to use boring and vague phrases like “Click Here” or “Read More”. Have a link to a video about making chickpea brownies? Use a phrase like “Love Brownies, check out this video”? Want users to follow you on Twitter, say something link “Follow me for tweets about coding, jokes, and other hijinks”. All in all, with descriptive links, you'll have your users happily exploring your website, uncovering treasures without getting lost in digital traffic.
    

Now hold on, don’t go just yet. There’s just one more accessibility technique you need to learn to take your website and coding projects from a digital hellhole to a technical wonderland.

![Homer Simpson says "Almost There" while tiredly climbing a mountain](https://media.giphy.com/media/l2Je9zHYveK012EVi/giphy.gif align="center")

## Technique 3: ARIA Roles and Attributes

According to [MDN](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA), Accessible Rich Internet Applications (ARIA) is a set of roles and attributes that define ways to make web content and web applications more accessible to people with disabilities”. In other words, this label makes clickable features on your website and coding projects more accessible to people. Now, I know many sites often suggest adding them to links and buttons, but here are some other ways you can use this attribute:

* `<contentinfo>`: This ARIA role defines the content that’s on the bottom of your website. Here it is in action:
    

`<div role="contentinfo">   <h2>Privacy Statement</h2>   <!-- footer content -->   </div>      `

While it’s best to use the `<footer>` tag, I highly recommend using the `<contentinfo>` tag it takes a little while to find your contact links and privacy statement. It’ll help your viewers or potential business clients who use screen readers to quickly find this information.

* `<comment>`: This ARIA role is used to describe a reaction or emotion in some content. Here’s an example:
    

`<div role="comment" id="thread-1" data-author="jane">   <h3>Jane said</h3>   <p class="comment-text">I really think this ice cream could use more peanut butter.</p>   <p><time datetime="2023-03-30T19:28">March 302023,19:28</time></p>   </div>`

I highly recommend using this if your website and/or coding project if it contains a testimonial of your work or a quote from your favorite movie or plays. It’ll help your viewers, especially those who use screen readers understand them more.

* `<alert>` : This ARIA role is only used to convey time-sensitive information. Here’s an example:
    

`<div id="sessionendWarning" role="alert">   <p class="hidden">Your session will expire in3 minutes</p>   </div>   `

I highly recommend only using this on your website or project if you’re doing something like having your users fill out a submit a form for a giveaway by date and time.

## Conclusion

There you have it, three accessibility techniques to turn your website and/or project into a digital paradise. Remember, accessibility isn’t a fad or something to get pats on the back for. It’s something to create a better user experience. If you need more tips or want to learn more ways to improve your coding skills, subscribe to this blog and follow me on my other socials via [Linkfree](https://linkfree.io/CBID2). Now go out there and make the Internet more bearable for everyone.

![The End appears on a black screen](https://media.giphy.com/media/YOcTikSFwS3Go/giphy.gif align="center")

## Credit

Lets Go GIF by [Marvel Studios](https://media.giphy.com/media/l0HlxJMw7rkPTN8sg/giphy.gif)  
Move On Reaction GIF by [Film Riot](https://media.giphy.com/media/HU6BhsCvQvlQ3h1eV5/giphy.gif)

Struggling Season 9 GIF by [The Simpsons](https://media.giphy.com/media/l2Je9zHYveK012EVi/giphy.gif)

The End Black And White Gif by [Giphy](https://media.giphy.com/media/YOcTikSFwS3Go/giphy.gif)
# Confessions of a Code Bug Hunter

### My Epiphany

After a few months of being a coder, I've come to an interesting realization...debugging is so much like being in a romantic relationship. I know, I know, but think about it. You know how when your partner is upset and gets annoyed when they try to guess why even though this answer is obvious? That's exactly how it is with debugging. You noticed that your coding project is acting weird yet can't seem to find what's wrong even though you've tried every solution you can think of. Just like love, it can be funny and frustrating, so grab your favorite debugging snack and beverage(I highly recommend water but it's your choice) and join me as I reminisce and cringe about my humorous and annoying encounters with debugging.

![Film counting down to 3,2,1](https://media.giphy.com/media/CH8pZqw2t0G7m/giphy.gif align="center")

### The Hidden Obvious

The Hidden Obvious is a species of coding bugs that are pretty easy to solve but hard to hunt for. They're like chameleons in the jungle because they blend right into the coding solution. I first discovered this creature when I was doing [my submission](https://www.frontendmentor.io/solutions/nft-component-preview-card-with-html-css-and-a-dash-of-flexbox-z-IfvYeSrJ) for Frontend Mentor's NFT preview card component challenge. I noticed that the card’s shape was not appearing, so I tried things like changing the class’s color, using a different HTML element, and basically anything to get it to work. After hours upon hours just hitting brick wall after brick wall, I did what folks on “How To Be A Millionaire” would do…phone a friend. I shared my code with her and after a couple of minutes, she giggled and said, “You forgot to add the closing tag in the link to your CSS file”.

```xml
 <link rel="stylesheet" href="style.css"/
```

At first, I was baffled because I remembered following the steps to a CSS stylesheet tutorial to the T. But then, I checked and realized that I did not add the closing. After mentally facepalming for a few minutes, I added the closing tag and lo and behold, the CSS worked. If you think this was embarrassing, wait until you hear the next story.

![YouTuber Rosanna Pansino saying, "Anyways" ](https://media.giphy.com/media/RN1m97qF78ssFQIM6Q/giphy.gif align="center")

### The Brain Teaser

Unlike Hidden Obviouses, Brain Teasers may are not immediately apparent and can require multiple attempts to uncover. Once they are found, however, the solution to hunt this bug is difficult to execute despite being obvious. Brain Teasers are like a pesky fly buzzing around you - you know it's there, but it's just out of reach. I first encountered this creature when I was doing the HTML for the [Tribute project](https://rihanna-tribute-page.christinebelzi1.repl.co/) in freeCodeCamp’s new version of their Responsive Web Design course. I noticed that the fig caption’s link was not opening to a new tab even though I had the target blank element. After hours of redoing the format and facepalming, I went to one of the forum channels on Scrimba and expressed my concern. A few minutes later, someone showed me this:

![An incorrect example of a link needing to open a new tab. ](https://cdn.discordapp.com/attachments/1032884630614974494/1032886836244271126/unknown.png align="center")

I placed the opening quotation mark after the equal sign. 🤦🏽‍♀️

After doing another round of mental scolding, I followed the person’s suggestion, and voila, the solution worked.

![Video game character saying, "Success". ](https://media.giphy.com/media/GS1VR900wmhJ6/giphy.gif align="center")

### Conclusion

If there’s anything that I have learned from these two experiences, it’s this:

* Always reread your code like you’re proofreading an essay for school.
    

Remember, coding is like growing up. You’re bound to make mistakes from time to time, but as long as you keep learning and trying to improve things will be ok. And if you ever need a friend to cheer you up throughout your journey, I’m just a click away on [Linkfree](https://linkfree.eddiehub.io/CBID2). You got this! 😊 👍🏾

### Credits

3 2 1 Waiting GIF By [Funimation](https://media.giphy.com/media/CH8pZqw2t0G7m/giphy.gif)

Dynasty Warriors Success GIF by [wiffiegif.com](https://media.giphy.com/media/GS1VR900wmhJ6/giphy.gif)

Moving On Ok GIF By [Rosanna Pansino](https://media.giphy.com/media/RN1m97qF78ssFQIM6Q/giphy.gif)
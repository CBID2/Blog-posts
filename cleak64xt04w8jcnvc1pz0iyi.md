# How To Make A Pull Request Without Pulling Your Hair Out

### Welcome Back!!!

Congratulations! You've picked an open source project to contribute to and you're ready to start making a difference(Need a refresher? Check out this and that previous post.)! But before we can celebrate, you'll need to learn about one of the most essential tools in your open source contributor's toolkit: the pull request! So grab a snack and open that Google Doc (or whatever word-processing software you use), because

![Willow Smith in a yellow hoodie and a dreadlocked ponytail says "Class is in season" ](https://media.giphy.com/media/dZd0fvvUdMpz5DNW9A/giphy.gif align="center")

### What the heck is a Pull Request?

Before I let you go and be "pull request happy", let's define what a pull request is. It's when you add your suggestion to an open source project via a line of code.

![This is a multicolored diagram ](data:image/jpeg;base64,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 align="center")

Think of it as a software development version of putting your comments onto a shared Google Doc or presentation for a group project for school. It's essential in the open source contribution process because your line of code impacts how the project functions. Now that's settled, on to making your first pull request!

![Movie countdown(e.g., 3, 2, 1)](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZjY5ZGZlZTk1MzBlY2MyYjk3YWRjZmE0YjIwMTJkZGU1NDQ4NmM0YSZjdD1n/CH8pZqw2t0G7m/giphy.gif align="center")

### Creating a Pull Request

Now there are so many methods to making a PR(these are the initials for pull requests), but here are steps that I find helpful.  
1\. Fork the project's repository

![A repository is about to be forked. ](https://cdn.hashnode.com/res/hashnode/image/upload/v1676757278238/7be1cca2-87f7-4fe3-9a07-92f10ac3628c.png align="center")

1. Make your desired changes to the code or documentation
    
2. Click on **Commit Changes**
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676757446202/925fa63e-07de-4f9b-bac8-0d8fb7e5b364.png align="center")

1. Add your message in the commit message textbox, pick the **Create a new branch for this commit and start a pull request** option, and click on **Propose changes.**
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676759635626/5558d222-bacb-43eb-b409-7d0c744fa056.png align="center")

1. Go to the project’s repository and click on **Compare & Pull Request**
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676759685270/9ed948d0-8e52-4596-973d-594b5f08fbc5.png align="center")

1. Describe your changes in the pull request form, click on **Create Pull Request**, and wait for feedback from the project’s maintainers
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676759723886/909fe211-e671-474e-89ec-872f17954c30.png align="center")

Congratulations, you're now a pull request pro! But before you start PR-bombing every open source project out there, let's cover some best practices to make sure your contributions are effective and appreciated by the project maintainers. So, let's dive into some essential PR dos and don'ts!

### PR Do’s and Don’ts

**DOs:**

1. Use a descriptive title that summarizes your changes.
    
2. Reference any relevant issue numbers in your pull request description.
    
3. Add screenshots or other visual aids to help explain your changes (if applicable).
    
4. Refer to the checklist shown on your pull request to ensure that you have completed all necessary steps.
    

**DON'Ts:**

1. Don't make overly large or complex pull requests: it's better to break changes down into smaller, more manageable chunks.
    
2. Don't make stylistic changes that are unrelated to the main purpose of the project.
    
3. Don't disregard any code formatting or style guidelines set by the project maintainers.
    
4. Don't forget to test your changes before submitting the pull request.
    
    Remember, following these do's and don'ts will help you avoid the dreaded 'rejected pull request' club and earn you some serious open source street cred.
    

### Conclusion

Congratulations, you're now a pull request pro, woohoo! Remember, making contributions to open source projects can be a fulfilling and rewarding experience. If you need a coding buddy or more inspiration, follow me on Hashnode and my other socials on [Linkfree](https://linkfree.eddiehub.io/CBID2). May your contributions be bug-free and legendary.

![Looney Tunes ending: "That's All Folks"](https://64.media.tumblr.com/f5436f265630043b4163b3b796436229/tumblr_nerv5zwzCr1sgl0ajo1_500.gifv align="center")

### Credits

3 2 1 Waiting GIF [**by Funimation**](https://media.giphy.com/media/CH8pZqw2t0G7m/giphy.gif)

GitHub Pull Request Diagram by [Crunchify](https://crunchify.com/how-to-fork-github-repository-create-pull-request-and-merge/)

Level Up Glu GIF by [Ground Level Up](https://media.giphy.com/media/L0eLbQSACTr10Voj83/giphy.gif)

Looney Tunes Nothing to see here GIF by [Heck Yeah Reactions](https://giphy.com/gifs/the-end-thats-all-folks-lD76yTC5zxZPG)

Willow Smith GIF by [Red Table Talk](https://media.giphy.com/media/dZd0fvvUdMpz5DNW9A/giphy.gif)
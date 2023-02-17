# Sunny with a Chance of Coding

### My Confession

After doing some reflecting, I just realized that there’s one thing I share with [Storm from the X-Men](https://www.writeups.org/storm-x-men-ororo-marvel-comics/)...we both can control the weather. Okay fine, I can’t conjure thunderstorms at will or summon tornadoes like Storm but what she can’t do is build a weather app. So grab your umbrella and raincoat and join me on a stormy journey to creating an app that tells you to wear those UGGs you got for Christmas or avoid that sleeveless shirt you’ve been waiting so long to wear.

![Film countdown ](https://media.giphy.com/media/CH8pZqw2t0G7m/giphy.gif align="center")

### How it all began

This assignment was for SheCodes Plus. What is SheCodes you ask? It’s an awesome organization that helps womxn start their careers in tech. It’s also the place that helped me punch imposter syndrome in its face and start my coding journey. So, let me tell you how I went from a complete weather app newbie to a weather app creator extraordinaire (I'm only slightly exaggerating). It was a wild ride, but I'm excited to share with you how I planned and built it.

### Designing & Developing my vision

In the design phase, I initially wanted the app to be similar to the ones on the iPhone or iPad(click [here](https://christine558432.invisionapp.com/freehand/Weather-App-3UrunUpOO?dsid_h=9d17d4baffdac2ba9cad3557803db70deeef0c1fe7d151b2bd78e0662e7e7fbd&uid_h=cb19429214a0961b8c5081e50a3383cc5e14f21447eb677602387c6e952b9788) to view the design). However, as I tried to put my vision into HTML, CSS, and Bootstrap, things quickly started to go awry. It was a bit like trying to navigate a ship through a hurricane. No matter what I did, the layout just kept acting weird. Eventually, I had to swallow my pride and start over with a more simple design(click [here](https://christine558432.invisionapp.com/freehand/Weather-App-simple-version--qlw8gT3jc?dsid_h=d591e45069bba98869730ca0dac96db8eb1e1d56ca3a96fd8a3f795fb8d8c1d3&uid_h=cb19429214a0961b8c5081e50a3383cc5e14f21447eb677602387c6e952b9788) to view the design).

But even then, I thought things would get easier. Little did I know, I was still heading right toward a storm.

![Cat with a Robin Hood costume yelling "Onward & Yonward"](https://media.giphy.com/media/1YjrpKOmJD8l8XzXOu/giphy.gif align="center")

### Surviving JavaScript and API thunderstorms

If I had to pick a challenge I had to face in building this app, it would be implementing JavaScript and API. I did not have much experience with JavaScript and API before SheCodes Plus, so learning the language again felt like being in a thunderstorm.

One specific challenge I faced was creating the function and integrating the API to make the city and weather icon change based on the user's choice.

**Before**

```javascript
function search(city){
  let apiKey = "e450bc345a80a08ada69fd5c714d871d";
  let apiURL = `https://api.openweathermap.org/data/2.5/weather?q={city}&appid=${apiKey}&units=metric`;
  axios.get(apiURL).then(displayTemperature);
}
```

It took me a while to get it working properly, but I eventually overcame it by breaking it down into smaller steps and seeking help from the technical assistants on SheCodes' Slack community and coding comrades from other communities.

**After**

```javascript
function search(city){
  let apiKey = "e450bc345a80a08ada69fd5c714d871d";
  let apiURL = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}&units=metric`;
  axios.get(apiURL).then(displayTemperature);
}
```

*All the API key variable needed was a dollar sign!* 🤦🏽‍♀️

It was like being in the sun when I finally got it to work! But let's not get lost in the past, we've got bigger fish to fry with this project. Time to put my coding skills to the test and take this weather app to the next level!

![The phrase "Level Up!" shows in different colors](https://media.giphy.com/media/xNUyxiJoTYiWWyNMJw/giphy.gif align="center")

### Future Improvements

Now that the app is up and running(click [here](https://www.shecodes.io/workshops/shecodes-plus-0a53b5fe-7c61-4aa6-9b22-f305bb004b91/projects/1460870) to view), my mind is spinning like a tornado with ideas on how to make it even better. First, I want to add the five-day forecast section so users can plan their outfits and avoid any unexpected rain showers. And let's be honest, nobody wants to be caught in a downpour wearing their best clothes to their friend's wedding.

Next, I want to make the app more mobile-friendly for all those tiny screens out there(Chrissy Codes does not endorse phone screen discrimination). Finally, I want to add a daily motivational quote that pops up when users search for the weather in a city because everyone needs encouraging words in the morning. Man, I can’t wait to see those ideas come to life! 🤩

### Conclusion

Phew, building this app was quite a ride! 😮‍💨 I learned a lot about design and patience and discovered that JavaScript and APIs can be as unpredictable as the weather. Nonetheless, I loved every bit of it, and I want everyone out there to experience the same thrill. If you're a womxn who wants to step up your coding skills, I highly recommend [SheCodes Plus](https://www.shecodes.io/workshops?coupon_name=SheCodesFriend). And if you need a cheerleader, feel free to follow me on Hashnode and my other socials via [Linkfree](https://linkfree.eddiehub.io/CBID2). Let's take on some coding storms together! 😊

![Looney Tunes ending ](https://media.giphy.com/media/lD76yTC5zxZPG/giphy.gif align="center")

### Credits

3 2 1 Waiting GIF [by Funimation](https://media.giphy.com/media/CH8pZqw2t0G7m/giphy.gif)

Level Up Logo GIF by ASUS Republic of Gamers Deutchsland

Looney Tunes Nothing to See Here GIF by [Heck Yeah Reactions](https://heckyeahreactiongifs.tumblr.com/post/102176386240)

Next Step Cat GIF by [PBS Kids](https://media.giphy.com/media/1YjrpKOmJD8l8XzXOu/giphy.gif)
---
template: post
title: My Mindful Lamp
slug: my-mindful-lamp
socialImage: /media/lamp-shot.jpg
draft: false
date: 2022-01-17T23:26:29.681Z
description: "How and why I did something I had never done before: build a lamp!"
category: portfolio
tags: []
---
![](/media/lamp-shot.jpg)

![](/media/light-beauty.jpg)

![](/media/lamp-side-on.jpg)

I built a lamp to help me be more mindful about how I use my phone. I, like many, am addicted to my phone. While I’m alright with this arrangement because I find my phone extremely useful, I don’t like when I’m not in control of the interaction. Sometimes, I’ve caught myself reflexively grabbing my phone without purpose while I’m working or relaxing. Whenever this happens, I get a yucky feeling deep in my stomach since I’m unintentionally distracting myself. Distractions are fine and often useful, but I want to choose when and how and what I’m doing to distract myself. Mindlessly reaching for my phone to get a dopamine hit is not what I want. Can I design something to retrain myself?

## How it works

<iframe width="560" height="315" src="https://www.youtube.com/embed/bqbEELaH9-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Placing your phone on the base of the lamp turns on the light. If you remove your phone, the light slowly fades away. Only by returning your phone will the light come on again.

I used an Arduino Uno and a pressure sensor to check if there’s a phone on the lamp. The lampshade and base are built of laser-cut layers of chipboard (white chipboard for the lampshade).

## Process

I started with the desired outcome and worked backward. I needed to:

1. Make the act of grabbing my phone conscious 
2. Replace the reward of using my phone

If I can make myself think before I grab my phone, I’ll be able to evaluate whether using my phone is worth it or not. Usually, it’s not. In addition, I wanted to reward myself for not using my phone. Instead of the addiction-building dopamine hit of grabbing for my phone, I’d get some other more-worthwhile thing. 

Note: some productivity experts suggest removing your phone from the room altogether so you never get. It's a simple solution; however, it wasn't for me. I still wanted to have my phone nearby. It’s useful; I text my friends about dinner plans and jot down notes. Plus, I’d like to believe that I can resist the temptation to use it even if it's nearby. I want to coexist with my phone without it controlling me.

### Iteration

#### Phone Coffin

![](/media/coffin-in-desk.jpg)

My original idea to stop myself from grabbing my phone was the “phone coffin.” Inspired by the [Pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique), you would put your phone into the box and a timer would start. After 25 minutes, you could take your phone out of the box and use it for a 5-minute break. If you pulled your phone out before the 25 minutes was up or if you continued to use your phone after your 5-minute break, the box would buzz very annoyingly until you returned the phone to the box.

This buzzer certainly made me think before I reached for my phone, but I didn't like the emphasis on punishment. If I got an important call that was a worthwhile distraction from my work, I wouldn't want the box to angrily buzz at me. It also felt like more could be done to reward the user for putting their phone away. With the phone coffin, the only reward was the phone-free time to focus.

So, I iterated. After a lot of thinking, sketching, and experimenting, the lamp idea was born.

![](/media/lamp-sketch-collage.png)

I started prototyping the look and feel of the lamp. I wanted the lamp to resemble a tree, representing a natural calm and the "tree of knowledge" that could result from not looking at your phone. For the lampshade, I was inspired by an [IKEA lamp](https://media.karousell.com/media/photos/products/2020/8/16/ikea_kajuta_lamps_white_and_gr_1597546704_36c7aa3e_progressive.jpg) I had in my room when I was growing that you could bend parts of to let more or less light out. It was both fun to play with and useful if you wanted to change the light level in your room. In the final version, the lampshade's layers can be moved up and down to create openings for the light to shine through.

![](/media/lamp-layers.jpg)

The overlapping bumpy texture of the lampshade was inspired by [theta waves](https://en.wikipedia.org/wiki/Theta_wave), the neural wavelength that the brain releases when it's in deep thought. 

![](/media/theta.png)



## Final Thoughts

![](/media/in-construction.jpg)

This was an ambitious project that took me several weeks of iterating to complete. If I had more time, I would continue to iterate, but I’m proud of where I got in the time I set aside for this project. I had never worked with analog and digital electronics to this extent before. Combining the digital with the physical design of a lamp was especially tricky. There was a lot to consider and I initially struggled to prototype quickly. Testing a new lampshade design to see how it would interact with the light the light took a lot longer than mocking something up in Figma! During the project, I ran into many problems that I had never encountered before, but I came out on top. It was quite a learning experience, but the greatest benefit I felt was the confidence that I could design things physically as well as digitally.
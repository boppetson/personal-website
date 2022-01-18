---
template: post
title: My Mindful Lamp
slug: my-mindful-lamp
socialImage: /media/lamp-shot.jpg
draft: false
date: 2022-01-17T23:26:29.681Z
description: "How and why I did something I had never done before: build a lamp!"
category: portfolio
tags:
  - design
---


![](/media/lamp-shot.jpg)

![](/media/light-beauty.jpg)

![](/media/lamp-side-on.jpg)

I built a lamp to help me be more mindful about how I use my phone. I, like many, am addicted to my phone. While I’m alright with this arrangement because I find my phone extremely useful, I don’t like when I’m not in control of the interaction. Sometimes, I’ve caught myself reflexively grabbing my phone without purpose while I’m working or relaxing. Whenever this happens, I get a yucky feeling deep in my stomach since I’m unintentionally distracting myself. Distractions are fine and often useful, but I want to choose when and how and what I’m doing to distract myself. Mindlessly reaching for my phone to get a dopamine hit is not what I want. Can I design something to retrain myself?



## How it works

<iframe width="560" height="315" src="https://www.youtube.com/embed/bqbEELaH9-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Placing your phone on the base of the lamp turns on the light. If you remove your phone, the light slowly fades away. Only by returning your phone will the light come on again.

I used an Arduino Uno and a pressure sensor to check if there’s a lamp. I had a toggle system where the user could flip a switch to change between regular lamp and mindful mode. During teh regular mode, the lamp would act like a normal lamp, only turning on when the lamp switch was on. In mindful mode, the lamp would only turn on when a phone is sitting on the base. 

## Process

I started with the desired outcome and worked backward. I needed to:

1. Make the act of grabbing my phone conscious 
2. Replace the reward of using my phone

If I can make myself think before I grab my phone, I’ll be able to evaluate whether using my phone is worth it or not. Usually, it’s not. In addition, I wanted to reward myself for not using my phone. Instead of the addiction-building dopamine hit of grabbing for my phone, I’d get some other more-worthwhile thing. I eventually settled on light since it was both a functional (being able to see clearly) and an aesthetic (warm light makes my room beautiful) reward.

Some productivity experts might suggest removing my phone from the room to solve my problem. It's a simple solution; however, it wasn't for me. I still wanted to have my phone nearby. It’s useful; I text my friends about dinner plans and jot down notes. Plus, I’d like to believe that I can resist the temptation to use it even if it's nearby. I want to coexist with my phone without it controlling me.



### Iteration

![](/media/coffin-in-desk.jpg)

My original idea was for a “phone coffin.” Inspired by the [Pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique), you would put your phone into the box and a timer would start. After 25 minutes, you could then take your phone out of the box and use it for 5 minutes. Alternatively, you could just keep working. If you pulled your phone out before the 25 minutes was up or after your 5-minute break, the box would buzz very annoyingly until you returned the phone to the box.



![](/media/green-sketch.jpg)

After a lot of thinking, sketching, and experimenting, the lamp idea was born. 

![](/media/sketch.jpg)

I experiemented with hanging the lampshade from rope and liked the tangible.

![](/media/prototype.jpg)

The lampshade and base are built of laser-cut layers of chipboard (white chipboard for the lampshade). The bumpy texture was inspired by [theta waves](https://en.wikipedia.org/wiki/Theta_wave), the neural wavelength that the brain releases when it's in deep thought. 



![](/media/lamp-layers.jpg)

The lampshade's layers can be moved up and down to create openings for the light to shine through.

![](/media/closeup.jpg)

## Final Thoughts

![](/media/in-construction.jpg)

This was an ambitious project that took me several weeks of iterating to complete. Certainly, there are more iterations to go if I was to sell it, but I’m proud of what I have so far. I ran into lots of problems I had never encountered before like how to hide electronics inside a lamp and how to solder wires. Quite the learning experience and it gave me the confidence that I could design things physically as well as digitally.

I had never worked with analog and digital electronics to this extent. Combining the electronics with the physical design of a lamp was especially tricky. There was a lot to consider and I struggled to prototype quickly. Building an experimental lampshade to see how it would interact with the light took a lot longer than quickly mocking something up in Figma!
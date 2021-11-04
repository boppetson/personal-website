---
template: post
title: "Twitch Streamer Automation: Case Study"
slug: twitch-streamer-automation
socialImage: /media/streamerwork.png
draft: false
date: 2021-10-27T02:43:48.393Z
description: |
  How I designed a tool to reduce Twitch Streamers's workloads.
category: Portfolio
tags:
  - Design
  - Projects
---
During my junior year of college, I worked at a tech startup with a team of four. I was not an engineer, which means I worked on everything else.  Design, business strategy, customer acquisition, and more. This was perfect since I could learn a variety of skills and try new disciplines. During this journey of personal growth, I led my first professional project from start to finish and designed a product! Here's the story:



## User Research

We knew Twitch streamers generally had a lot of work to do to run their channel and grow their community. We wanted to know what we could build for them to reduce their workload. 

First, we had to learn about our users. I started by sitting in on a sample of Twitch streams. I noted what each streamer offered to fans in addition to their stream (Discord server, giveaways, etc) and reverse-engineered the work that they would have had to do behind the scenes to make it all happen. For example, if a streamer ran a community Discord server, they would have to moderate the server, post announcements, engage with fans, and more. Afterward, I reached out and interviewed several streamers to learn more about the specific streaming-related work they did consistent basis and their strategies for getting it done. I looked for mindless tasks that the streamer had to do weekly since that work was likely a pain point we could resolve for them through automation.

![What a streamer offers translated into the work they'll have to do](/media/streamerwork.png "What a streamer offers translated into the work they'll have to do")

I discovered that many streamers run Minecraft servers where only their Twitch subscribers are allowed to join. These “sub-only” servers were very popular with their fans and brought in a lot of subscription revenue since fans would sub to gain access. However, running a server required a lot of tedious upkeep from the streamer. From those I talked to, the server-related work was such a burden that many streamers either never started a server despite wanting to or stopped their servers soon after starting them, even though they were profitable. 

To run a server, a streamer would have to collect Minecraft usernames from fans through a form, keep those responses in a spreadsheet, manually check if someone was a Twitch sub, and then add their name to the server’s whitelist. It was painfully laborious. Perfect for us.

![Sub-only Minecraft server](/media/subonlyserver.png "Sub-only Minecraft server")

## Designing the Product

Based on what I had learned from the streamers, I developed a list of minimum requirements for our product. If we were to build a solution to their problem, it would have to check these boxes otherwise we wouldn’t be meeting their needs.

### 1. Minutes of work

Since the server-related upkeep work was a major pain point for streamers, I focused on making the process as short and simple as possible. My goal was to reduce the hours of work it normally took to just a few minutes.

### 2. Play nice with existing server infrastructure

Additionally, streamers use a variety of hosting methods to host their Minecraft servers. Some host it themselves on their own computers and others use online services. If we were to implement a solution, it would have to work with a streamer's existing server infrastructure. Otherwise, the friction of switching to a different hosting method would cause annoyance or outright stop people from trying our product. 

### 3. Faster fan access

The fan experience was also important since streamers want them to have the best possible time so they stick around. With the old process, fans would have to fill out a long form and then wait an undetermined amount of time to get access to the server. They might end up waiting 2 weeks since the process relied on the streamer setting aside time for it.  This had to be faster.

From these requirements, I created user flows for how our automation would work from both the streamer and the fan's perspective. I brought in our lead engineer and walked him through the flows to make sure they were technically feasible within our limited timeframe. I worked closely with the engineer as they built it, answering questions they had about the design and doing more user research when we were unsure about something. In the end, we managed to simplify all the upkeep work into one command that the streamer (or one of their moderators) could enter whenever a new subscriber wanted access to the server. 

## Testing and Launch

Once our product met all the requirements, I tested it with a streamer and sought feedback. It met their needs! The streamer was happy since it reduced their server-related work from several hours to only minutes each week. Fans were also excited by the change since the sign-up process was much easier for them and they got access to the server almost instantly.

The user research I'd done had paid off. Yay! Now it was time to ship and finalize the pricing. Again, collaboration with our lead engineer was invaluable since they knew the uptime costs to run our software. Based on those costs and what I had learned about the spending habits of our target customers, I set the price and we rolled it out.
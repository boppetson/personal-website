---
template: post
title: Redesigning My College's Covid-19 Testing Process
slug: covid-testing-redesign
socialImage: /media/schedule.png
draft: false
date: 2021-11-16T00:40:08.131Z
description: " "
category: Portfolio
tags:
  - Design
---


![](/media/covidtestreminder.png)

> Not again...

This is the email I get when my school decides it’s time for me to get another Covid test. Every week, a third of the student body (~750 people) is required to get tested. 

Even though I think testing is the right thing to do, I dread seeing this email. Why? Because in order to get tested, I have to go through an online tool to book an appointment and the tool sucks. Using it takes way longer and requires more brainpower than it should. If I’m going to get tested repeatedly every month, I want that process to be as efficient as possible.

But the process still works: I can sign up for a Covid test and get my results within a week. So why redesign it?

## Why Redesign?

My initial inspiration was totally selfish. I didn’t want to waste any more of my time signing up for Covid tests. While designing to not waste people’s time is a worthwhile pursuit, I discovered a more meaningful reason while doing research for this project. Students not creating appointments causes undue stress on the already-stressed medical staff at CC. 

I learned about this problem after talking to the manager at the health center where all our testing is done. She uses the number of appointments on a given day to schedule staff. If most of the students don’t make appointments (which is currently the case), she can’t predict how many staff she’ll need to handle student demand. Frequently, they end up over- or worse, understaffed, which is very stressful. A few days before we talked, she told me they had 100 appointments booked so she scheduled only a few people to work. However, when the day arrived, over 400 students walked in looking for a test and the few staff on duty had to frantically scramble to get the tests and the corresponding paperwork done.

While getting a Covid test is never going to be an amazing experience, it should at least be as stress-free as possible for the medical staff administering the tests. In order for that to happen, more students need to make appointments. 

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FbVKqu7Dlkk091eB4S1ikrq%2FAppointment-Tool-Redesign%3Fpage-id%3D0%253A1%26node-id%3D17%253A796%26viewport%3D241%252C48%252C0.05%26scaling%3Dscale-down-width%26starting-point-node-id%3D4%253A30" allowfullscreen></iframe>



### Mobile

I frequently schedule appointments on my phone and so do many of the students I talked to so making a mobile-friendly version was a priority. I personally found the current form’s mobile formatting to be too small and difficult to navigate. I added spacing between form fields to fix this. 

You can view the mobile prototype below.

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="380" height="425" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FbVKqu7Dlkk091eB4S1ikrq%2FAppointment-Tool-Redesign%3Fpage-id%3D77%253A476%26node-id%3D124%253A2843%26viewport%3D241%252C48%252C0.24%26scaling%3Dscale-down%26starting-point-node-id%3D124%253A2863" allowfullscreen></iframe>

### 1. Email Reminder and Testing Instructions

![Email reminder and testing instructions redesign](/media/email.png "Email reminder and testing instructions redesign")

##### Problem

It takes too long to get what you need from the email reminder. Almost all of the students seeing it will have already gotten tested and know how the process works. All they want to do when they see this reminder is make an appointment. In order to make an appointment, they need the link to the online appointment portal. Currently, the link is buried in an attached document. 

##### Solution

First, I put the contents of the document in the email itself so students wouldn’t have to download an email attachment just to get one link. Then, I moved the link to the top of the email so it’s one of the first things a student sees. 

 I also reorganized and reformatted the text from the email attachment. There’s a lot of important information in there that’s hidden in a ‘wall of text’ that I, and likely most students, didn’t read ([F-shaped pattern of reading](https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/)). To make it more scannable, I split the information into sections with headers and re-stylized the text so that only the most important things got special styling. If everything is bold, nothing is bold. With these changes, it’s a lot easier to quickly find the information you need.

### 2. Reason for Visit

![Initial reason for visit page redesign](/media/reason-for-visit.png "Initial reason for visit page redesign")

##### Problem

Splitting Covid-19 testing up by AM / PM doesn’t let people easily change their minds. I was making an appointment once where I selected an AM test and halfway through, I realized the time I picked didn’t work for me. Unfortunately, to push my appointment back to the afternoon, I had to pick the “Covid-19 Testing PM” option which meant losing all my progress on the form. That sucked.

##### Solution

I combined AM and PM into one option: Covid-19 testing. Then, students can pick from both AM and PM times and change their minds without having to backtrack.



### 3. Patient Form

![Patient form redesign](/media/new-or-existing-patient.png "Patient form redesign")

##### **Problem**

This is the biggest pain point for students. If anything is fixed, it should be this. Currently, you need to fill out all of your insurance and contact details *every time* you make an appointment, even if you've already filled them out before. It's extremely frustrating and it's the main reason why students don't like making appointments. The health center already has everyone’s information from the first time they signed up so why do they make them fill it out again and again? Like many students, I don’t keep my insurance card on hand at all times so retrieving it each time is painful. The final straw? The form asks you if you are a new or existing patient. What a sick slap of irony! If I’m an existing patient, don’t make me fill out all this information again!

##### **Solution**

To alleviate this frustration, I split the form into two versions for new and existing patients.

New patients fill out the complete form so the health center gets all the necessary information from them while existing patients only have to give their name and date of birth to confirm their appointment. Since almost all students are now existing patients, the process will be much faster for most of the student body. All it takes now is a little typing, click, and appointment scheduled!

I also grouped the new patient fields into sections (Personal, Contact, and Insurance) to reduce the cognitive load associated with filling out the form. That way, you can complete one information zone at a time instead of bouncing back and forth between them like you have to in the current version. The students that I showed my redesign to noted how much more approachable my design was compared to the original. It’s probably impossible to make filling out a form a wonderful experience, but small steps like grouping related items together and making the text more legible can go far in making it bearable. 



### 4. Choosing a Date and Time

![Date and time redesign](/media/date-and-time.png "Date and time redesign")

##### Problem

Improving this fell into the “general usability” bucket. When I think about dates, I always need to see a calendar. I can’t visualize time without seeing the days mapped out in a grid. Additionally, the time picker was uncomfortably precise. In a perfect world where everybody arrived on time, 1-minute intervals for appointments would work great. It would so efficient! However, we don’t live in a perfect world. As a user, I also don’t want the option to pick between 3:02 and 3:03 pm. It’s an unnecessary decision. 

##### Solution

A calendar drop-down and 15-minute time intervals where a certain number of students can sign up for each interval. 

### 5. Appointment Confirmation

![Appointment confirmation page redesign](/media/confirmation-page.png "Appointment confirmation page redesign")

##### **Problem**

I saw many students show up to the health center at a different time or even another day than what they had picked for their appointment. I talked to a couple of students after their test to understand why. They both told me some form of “I just thought you needed an appointment and then you could walk in whenever.” While it’s good these students are making appointments, them not showing up on time reduces how worthwhile the appointments are. Remember, the medical staff use appointments to gauge testing demand so they can staff accordingly. If students don’t show up on the same day as their appointment, should they have even made an appointment at all?

##### Solution

To encourage more students to show up on time, I put more emphasis on the date and time throughout the appointment-making process. Right now, the date and time don’t stand out as particularly important since they are styled the same as all the other text so I made them bigger, colorful, and at the top of the page. 

Additionally, I wanted the confirmation page to feel more like you had officially made an appointment. You made a commitment and you have to show up on time. A big title announcing that their appointment has been booked and a direct  “See you…” then will hopefully inspire that feeling.
---
layout: post
title:  "Design for Homelessness"
date:   2022-4-11 00:09:50 -0700
category: projects
preview: /assets/img/homelessness/lifemoves.png
---

Design Fellow @ Stanford d. School | March-September 2021

## Project Summary
A digital kiosk system that replaces a paper binder sign in/sign out system. Staff have a user interface to better track and manage the safety and well-being of their clients. Clients have more privacy than a paper binder where others can see if they have signed in or not.

## Motivation
Growing up in the Bay Area, we've all noticed the increase in the homelessness population. I remember when I was young, my mom and  walked past a man on the ground, and I asked my mom, "Why am I here and why is he there?" It was a naive question. As a child, I just wanted people to be happy and equal. It's a world I still strive for.

## Design Process
Design is filled with ambiguity. My team and I were tasked to find a problem and to then design a solution for LifeMoves, a homelessness organization that has been operating in the Bay Area for over 35 years. We visited eight of their shelters, spoke with over 50 clients (people experiencing homelessness), and conducted interviews with those currently on the streets.

![home]({{ site.url }}/assets/img/homelessness/process.png)

We spent most of our time at the new interim housing site in Mountain View. At this site, every client has their own room that locks.

![table]({{ site.url }}/assets/img/homelessness/site.jpg)

After talking with some clients, we quickly discovered a friction point: bed checks.

![table]({{ site.url }}/assets/img/homelessness/home1.jpg)
![table]({{ site.url }}/assets/img/homelessness/home2.jpg)

Every night, staff open their doors to check to see if the client is present. Not only do clients like them, staff were also getting threatened for doing them.

> **How might we create a dignified and independent way for trauma sensitive clients to notify staff they are present?**

We visited other LifeMoves shelters to research best practices. We discovered there was no standardized practice. Each program director differed, but the primary reason for doing them was for the safety of the clients.

![table]({{ site.url }}/assets/img/homelessness/home3.jpg)

After ideation, we came up with two solutions and piloted them for a week.
### Solution 1: The Kiosk
What if we kept better track of clients at the front entrance?

![table]({{ site.url }}/assets/img/homelessness/home5.jpg)

![table]({{ site.url }}/assets/img/homelessness/home15.jpg)

![table]({{ site.url }}/assets/img/homelessness/home7.jpg)

![table]({{ site.url }}/assets/img/homelessness/home8.jpg)

![table]({{ site.url }}/assets/img/homelessness/home14.jpg)

### Solution 2: The Button
What if we made a button that notified staff that they were present in their room?
![table]({{ site.url }}/assets/img/homelessness/home9.jpg)
![table]({{ site.url }}/assets/img/homelessness/home10.jpg)
![table]({{ site.url }}/assets/img/homelessness/home11.jpg)
![table]({{ site.url }}/assets/img/homelessness/home12.jpg)
![table]({{ site.url }}/assets/img/homelessness/home13.jpg)

Clients loved the button. I coded the buttons using ESP8266 microcontrollers and connected each button to Amazon Web Services. One client didn't want to give the button back after the pilot was over and another client who was losing his vision said he would feel a little lost without it.

## Scaling & Implementation
Although clients loved the button and it was a novel idea at a shelter, the decision to choose which one was not up to us.

We presented both the kiosk and the button results to the leadership team at LifeMoves and collectively decided on the digital kiosk. We spent the next few weeks coding a robust kiosk interface, trained and installed digital kiosks at five shelters, and transferred ownership to the organization.

## Real World Impact
Today the digital kiosk is used by five shelters, serving 500 users daily per day. We designed a scalable, low cost solution for a nonprofit alongside the most vulnerable of populations.

## Reflection
To date, this remains one of my favorite projects. We started by wanting to serve the people experiencing homelessness, but ended up designing a solution that addressed the needs of staff, program directors, and clients. Staff no longer have to print paper binders, upload them, and shred the papers each day. Staff can better keep track and care for their clients. Program directors have live metrics on their interim housing sites. Most of all, clients no longer have bed checks which would wake them up, give them nightmares, and trigger past trauma. Clients now have more privacy with checking into the housing sites. What started as a solution for one shelter, expanded into a solution for multiple shelters.

## Team
This project started with me, Eleanor Glockner, Casey Prohaska, & Kate Slunkova. Over the summer, Eleanor and I acted a co-leads, brought on Malaika Koshy and Alyssa Li to then drive the project towards completion.
![table]({{ site.url }}/assets/img/homelessness/home16.jpg)

## Gratitude
This project would not be possible with the generous support and funding by Stanford's Design for Extreme Affordability. In addition, we thank our mentors for their critique and guidance: David Kelley, Bill Burnett, Stuart Coulson, Manasa Yeturu, Nell Garcia, George Toye, Rosanne Foust, Michelle Jia, Michael Barry, & Julie Stanford.

# Design Process
Interviews - airport land
We landed upon a real need. POV, HMW
Index cards
In the process of finding we need, we uncovered another need, that of the staff.
Rapid prototypes (physical)

Who do we want to be our raving fan?
Button vs digital kiosk
Using a decision matrix and a presentation to the executive team at LifeMoves, we chose the digital kiosk to scale across LifeMoves.

Lean prototype techniques as framework

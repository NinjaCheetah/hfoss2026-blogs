---
layout: post
# If your post title is longer or more complicated
# than can be represented in the filename, uncomment the following line
# and specify a custom title
title:  "Privacy Guides Suggestion"

# Uncomment only one of the below categories
categories: 
#- Bug Fix
- Contribution


# Enter your name below
author: Tori Rigoglioso
---

For my contribution, I decided to contribute to a website database called PrivacyGuides.org.

## What is Privacy Guides?
Privacy Guides is a website dedicated to helping people, from newcomers to more tech-savvy people, learn about privacy in the digital age and take steps to protect their own digital privacy and security. It includes recommendations for privacy-respecting software and services.

## Why did you pick it?
To be honest, I wasn't even thinking about this assignment when I decided to contribute last night. I was browsing the website and I noticed that there was an app that I felt shouldbe recommended under the health and wellness section.

This was also a website that significantly helped me a few years ago when I started not only learning about digital privacy, but learning about open source software in general. I've seen the website grow over the years and I wanted to contribute in some way. Additionally, I wanted to help users who were looking for privacy-respecting apps and I wanted to recommend what I used.

## How did your CommArch experience show you it would be good to work with?
Privacy Guides is a community project with leaders committed to listening to the userbase. It has a discussion forum dedicated to talking about the project, including app and service recommendations. The CommArch assignment, both the communities I've looked at and the communities others have looked at.

## What resources were already available?
The README.md has a Contributing section but it's pretty simplistic. The Contributing tab on Github is extremely barebones. The information about how to contribute was on the website itself, which I missed because I was looking at the Github page.

I made the pull request and a maintainer added a label saying "pr:missing-discussion," which I assumed meant that I should've opened a discussion on the Privacy Guides forums alongside my pull request. I did that afterwards.

![](/assets/privacy-guides-github-contributing-guidelines.png)

## The Issue
There was not an open issue suggesting this. I decided to open a pull request suggesting the app on my own.

Under the "Recommendations" tab, there is a page for health and wellness apps. There are different subsections of this page for different types of apps, including menstrual cycle tracking, fitness tracking, and managing health records. Apple Fitness was listed under fitness tracking. Apple Health was listed as "Apple Health Records" under "Health Records" for its health records management feature.

Given the fact that Apple Health was already in the recommendations, I felt that it should recommended under "Menstrual Cycle Tracking" as that is a feature it has. It is also gender-neutral, so I felt it was especially important to mention.

## The Contribution
I looked over the Github page to find the contributing guides, which were unfortunately pretty bare bones and did not link to the information the website itself provides.

I decided to open up a pull request anyway and I used the apps already recommended as a reference for how to format the new app suggestion. I wrote a description for the app, linked to its privacy policy, and reused the Apple Health icon already there for the health records. I also edited the descriptions for Apple Fitness and Apple Health Records. Apple Health Records' description specifically mentions that it shares the privacy policy and security features of Apple Fitness. Since Apple Health as an app would've been mentioned before Apple Fitness and Apple Health Records is part of the Apple Health app, I moved that particular sentence to Apple Fitness' description and edited it to refer to Apple Health instead.

When I submitted the pull request, the github-actions bot found no conflicts with the merge and built a preview of the website's changes. I had to wait for a maintainer to review and merge the PR. A few hours later, I had my PR labeled as, "pr:missing-discussion." Assuming that I had to open a discussion on the forums before my PR could be accepted, I made an account and opened a thread about my suggestion, describing my reasoning for the suggestion and linking to the pull request.

![](/assets/privacy-guides-PR.png)
![](/assets/privacy-guides-discussion-1.png)
![](/assets/privacy-guides-discussion-2.png)

## Response to the Contribution

While I haven't gotten a response from a maintainer yet, it has sparked discussion among other users. A user had concerns about if Apple was secure enough. These concerns were valid as there have been menstrual cycle tracking apps that have sold data to users. The user was also worried about the information being accessed if a user was subpoenaed. However, other users pointed out that this isn't an issue as Apple Health is end-to-end encrypted and data mostly stored on the device.

## Was it accepted or merged?

I am currently still waiting on a response from the maintainers to review the pull request, so it is not accepted or merged at the moment.

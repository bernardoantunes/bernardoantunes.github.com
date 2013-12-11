---
layout: post
title: Google Authenticator Made Simple
byline: Can it be simpler?
category: Down to Tech
tags:
- Authentication
- UX
---

We have more and more services in the cloud and the information that we trust to those services is more and more personal, confidential and critical.
Because of that, the amount of attacks to our information have increased in quantity and complexity.
To help keeping our accounts safe, services started to implement a two way factor authentication.

##Authentication is a Technicality

Although this solution makes our information safer, it also becomes more combersome to the end user that now have to authenticate in two steps.
We should never forget that the action of having to authenticate is in the end a necessary technicality, that the user (in an ideal world) should not have to be concerned with.

##Introducing the Google Authenticator

Google's two-way factor authentication is very convenient and easy to use.
You can receive an SMS with the code to use, or have an app in your phone that is generating new codes that you can use to complete your authentication process.

<figure class="svg-figure">
  <img src="/img/posts/google-authenticator-made-simple/current-ios-interface.png" alt="Current iOS Interface">
</figure>

Until here, things look fine, you know that when you have two-way factor authentication configured, you are required to enter a second code instead of just one.
This action although simple,is in fact astressful process for some persons.
You not only have to enter two passwords, but also have to do it under a timer that is in countdown mode, and if you fail to enter the code in that time, too bad.
Personaly, I find anoying have to write a code that Google already knows that I know what it his.

##Proposed Interface

So, what I propose to Google for the next version of the Google Authenticator is simple.
Since all the two environments of the two way factor authentication is controled by Google, I just want them to ask me if I confirm the code that they are showing me in the site.

<figure class="svg-figure">
  <img src="/img/posts/google-authenticator-made-simple/proposed-ios-interface.png" alt="Proposed iOS Interface">
</figure>

In the new concept the user does not have to write the code back to the browser, nor it have to open an app, he just receives a notification with the information that he needs to confirm.

If the code in the notification is the same that he is seeing in the browser window, the user just have to press "Confirm" and the two-way authentication will proceed automatically without any more user interaction.

I believe that it would be a great improvement to the user usability.
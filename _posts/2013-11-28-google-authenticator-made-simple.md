---
layout: post
title: Google Authenticator Made Simple
byline: Can it be simpler?
category: Down to Tech
tags:
- Authentication
- UX
---

We have more and more services in the cloud and the information that we trust to those services is more and more personal, confidential and critical. Because of that, the amount of attacks to our information have increased in quantity and complexity. To help keeping our accounts safe, services started to implement a two way factor authentication.

##Authentication is a Technicality

Although all this solutions make our information more safe, it is also more combersome to the user to have to do the authentication in two steps.
And we should not forget that having to authenticate ourselves is in the end a necessary technicality that the user (in an ideal world) should not have to be concerned with.

##Introducing the Google Authenticator

Google's two-way factor authentication is in fact very convenient and easy to use.
You can receive an SMS with the code to use, or have an app in your phone that is generating new codes that you can use to complete your authentication process.

<figure>
  <img src="C:\Projects\GitHub\bernardoantunes.github.com/img/posts/google-authenticator-made-simple/current-ios-interface.png" alt="Current iOS Interface">
</figure>

When you have two-way factor authentication configured, you are required to enter a second code, if you have the Google Authenticator configured, you will have to write the code that appears in the app before the time expires.
This is in fact a very stressful process for some persons because you have a very small time to enter the code that is being shown to you.
For me, I find it just anoying have to enter a code that Google knows about in an environment that Google controls.

##Proposed Interface

So, what I propose to Google for the next version of the Google Authenticator is this:

<figure class="svg-figure">
  <img src="C:\Projects\GitHub\bernardoantunes.github.com/img/posts/google-authenticator-made-simple/proposed-ios-interface.png" alt="Proposed iOS Interface">
</figure>

The interface looks almost the same just with two new buttons, but in fact is a completly new concept.

In the new concept the user does not have to write the code in the browser, this same code is being shown in the browser and the user is being requested just to confirm if the code being shown in is device is the same that he is seing in his browser.

If the code is the same, the user will press the button "Confirm" and the two-way authentication will proceed automatically without any more user interaction, the browser will automatically advance to complete the authentication process.

Even the timer that I left in the interface is just to reminder the user that this code expires in sometime, but this time, the user just have to press a button to confirm that he is in fact the person that is trying to authenticate, so the same time feels much longer.

I believe that it would be a great improvement to the user usability, what do you think? ;)
---
title: "My New Site"
date: 2023-01-21T17:31:12-06:00
showDate: true
draft: false
tags: ['Azure','Adobe','Microsoft','Hugo']
categories: ['web']
---

I finally moved my website.

### In the beginning...

I started off with my domain registar, I think because it was a discounted price, but there was an additional charge to host it. In addition I think it was difficult to provide content, uploading images, writing files, posting, etc.. It didn't motivate me to really work on it. It was much simpler to just post to Facebook, which I didn't really want to rely on because I know there are those out there who don't want to be on Facebook, and I don't blame them; at times I wish I was not on it either.

I then realized that with my Adobe photography subscription, [Adobe Portfolio](https://kendrickcc9b07.myportfolio.com/) was included. It was simple; sync from Bridge to Lightroom to Portfolio. And it was crazy simple to connect my domain to Adobe Portfolio. I could very easily post my work. But that was it. I could not for example post other content such as panoramas, or information on what services I wanted to offer. I was searching for an alternative. 

### Enter Hugo

At this time I don't need a complicated web site i.e. dynamic. I just wanted a little more flexibility and I felt that a static web site would suffice. I quickly found [Hugo](https://gohugo.io/). The biggest deciding factor for me was that I could choose from a number of themes and begin with providing content. Further the web pages, such as this page, could be written in [Markdown](https://en.wikipedia.org/wiki/Markdown) meaning that I didn't have to write a lot of HTML for the site. And if I want to change the look and feel, I could insert a new theme, minor changes to the config file and viola, a new look and feel. After much review I felt that the [Introduction](https://themes.gohugo.io/themes/hugo-theme-introduction/) theme worked for me. 

*But where to host....* 

### Azure

*Admission:* In a former life I worked in computer infrastructure working to migrate on-premise servers to cloud computing. I became very comfortable with [Azure](https://azure.microsoft.com/en-us/). Azure, much like AWS and Google offer free hours of cloud computing time and even when those hours are consumed, it is billed on usage; no montly/yearly fees. It really is just a matter of what you are more comfortable with using. I'm not going to say one is better than the other. I could as easily have pushed this into AWS. I use Azure simply because I have a Microsoft 365 subscription and use the same account. Enough of this. 

Azure recently released a new service call ***Static Web App*** and they have a nice article that describes how to publish a Hugo page. [Tutorial: Publish a Hugo site to Azure Static Web Apps](https://learn.microsoft.com/en-us/azure/static-web-apps/publish-hugo)

Basically you write content, push the content and next thing you know you have a web site running out of Azure. Crazy.

I also use Azure for my photography backup. I don't use a backup service because more than likely they are using AWS, Azure, Google, etc.. So cut out the middleware and go direct to cold storage in Azure. 

### Why go through all this....

The biggest attraction for me is that if I feel the web site is no longer needed; a waste of resources, I can delete the web app out of Azure and that is it. I can redeploy it at a later time if warranted. I'm only billed for what Azure resources are consumed. I also have change control meaning that if I make a change and it crashes the web site, I only need to revert the commit in GitHub. 

Yes, there is a lot of upfront learning, trial and error, but now I really feel in control of my web site. 

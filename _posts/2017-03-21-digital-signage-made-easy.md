---
layout: post
title: Digital Signage made easy
---

The other day I was asked to provide a quote for digital signage. I did, but my first two options in the quote were actually just describing ways that they could implement the digital signage themselves without really requiring any input from me.

The key parameters of the project were to be fairly cheap and show a slideshow of food menu options on the screen (for Breakfast, Lunch & Dinner).

**Option 1** was to use Google Chromecasts. For around $40 per television, it's actually pretty straightforward to cast a slideshow from a computer on the same wifi to the Chromecast connected to each television. That is probably the simplest option, but does require manual intervention each time the menu needs to be changed.

**Option 2** was to use Raspberry Pis set up with a browser in kiosk mode. This is where the Raspberry Pi is set up to boot to a windows manager, start a browser in full-screen mode and automatically load a page that the client controls. 

The nice thing about option 2, is if the client have some sort of internal CMS, then there'd be no need for the Raspberry Pis to have access to the internet. And again, this would require no involvement from me.

**Option 3** was a little more fully featured. It'd be Raspberry Pis again, but this time they'd point to a web application I'd write for the client. Something simple where they could import a month's worth of data at a time (or more if they wanted) and it'd show the correct menu for the day, as well as the appropriate menu (Breakfast, Lunch or Dinner) based on the time of day.

I'd still like to build Option 3 for them, as it's a neat little project, but equally I needed to price it realistically. I don't need the extra work, and have to take into account the opportunity cost if they decide to go ahead with the project. Had it been a few months earlier or later, I'd probably have done it for free/fun.

I did have a play and set up my Raspberry Pi with the target image and it works a treat. And web applications are my bread and butter, so I have no qualms about that. The tricky part with small jobs like this is in the details. I don't like to fixed-price quote, because that's often not in the best interest of either myself, or the client.

Unless it's the supply of something that already exists, if there's even a chance of some sort of discovery phase to the project, it has to be on a *time and materials* basis. Anything else is just asking for trouble.

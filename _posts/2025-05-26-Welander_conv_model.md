---
title: Pulsating convection
mathjax: true
layout: post
categories: media
excerpt_separator: <!--more-->
---

In 1967 Pierre Welander published a curious paper about oscillatory convection (reference below). It may have in part been inspired by a movie I had made of Bénard convection in which fluid motion is driven by the temperature difference between a lower warmer and an upper cooler plate. There is only one dimension in Bénard convection, the vertical separation between the two horizontal plates. The movie shows how ‘blobs’ of water emanate from one plate boundary to quickly float up to the other or sink from the upper to the lower plate. They do this repeatedly. Although Welander’s model is far simpler, it gives a plausible explanation for what causes this pulsating motion. 
<!--more--> 

The left panel in the figure (copied from his paper) shows the model. A closed loop contains a fluid that is heated at the lower end and cooled at the upper. The side walls are insulating. This is an unstable configuration so once warm fluid starts rising on one side and cool fluid sinking on the other the system will continue to flow in that direction. As it flows past the opposite end it is cooled and the system continues to flow. But imagine that the speed is such that the fluid passes the other end without its temperature being fully reset. This lack of buoyancy loss (and symmetrically lack of buoyancy gain at the warm end) will cause the fluid to down as it descends on the opposite side such that when it gets back to the warm end, it passes through it at a slower rate causing the fluid to heat up more giving it even more buoyancy. This self-reinforcing pattern causes the fluid to speed up and slow down as these anomalies pass by since they are not erased as they pass the opposite end. Now here’s the funny thing, if the fluid slows down to the point where it stops, it will reverse and begin pulsating in the opposite direction, as shown in the right panel of the figure.

![Welander_model.jpeg](/assets/Welander_model.jpeg)

Even though I don’t know if this model is experimentally realizable (take that as a challenge!), I like the way it communicates the role of buoyancy in a simple intuitive way. I’ve written the model in matlab and happy to share it if you like, just let me know. I can also show you the movie - it is way too long to include here. 

Can the model be applied to any geophysical process? I don’t know. There was a time when I wondered whether it in some sense could be applied to the Dansgaard-Oescher events, but I doubt it since salt and ice are implicated in these. Nonetheless, their roughly periodic character suggests that a relaxation process of some kind is involved. 

- - - - -
Welander, P., (1967). On the oscillatory instability of a differentially heated fluid loop. J. Fluid Mech., 29(1), 17-30.


---
title: "A thought on ADCP processing"
mathjax: true
layout: post
categories: media
excerpt_separator: <!--more-->
---

This is a brief rather technical comment. It is based on a conversation with my colleague Peter Cornillon yesterday evening. The standard procedure for ADCP processing is to collect all good pings within a prescribed time window, say 5 minutes, to construct an average velocity profile. Typically, one requires at least 50% of the raw data to be acceptable, otherwise no output. Of course, one can lower the threshold to 30% or even less. Although the resulting profile will be noisier, it will be based on good data. Here I’d like to explore another approach.
 <!--more-->

For some time I used to think that as soon as one has collected a minimum number of good profiles, average the profiles and assign its position to a weighted average of the raw profile positions. This way all good profile data were used. Unfortunately, this means the spacing of the profiles can vary, which I didn’t like. This is where Peter’s comment comes in. Rather than fixed non-overlapping windows, consider a wider, sliding window, 15 minutes say, and step it 5 minutes at a time. For each step use all raw profiles to map out the temperature field across the 15-minute window and depth. Use data that are available at center time, but if not interpolate as necessary from preceding and following profiles to construuct the profile for that time - this way all data are available to be used. As a welcome byproduct, this approach will yield a concomitant profile of horizontal velocity gradients. Particularly in strong gradient regions like the Gulf Stream and coherent vortices this method might have special appeal. 

One would continue the existing processing protocols. This higher-level product could be included the processed data file or archived as a separate product. 



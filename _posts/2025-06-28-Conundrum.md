---
title: A mixed layer conundrum.
mathjax: true
layout: post
categories: media
excerpt_separator: <!--more-->
---

Last winter we undertook a detailed analysis of the Oleander ADCP measurements of currents between New Jersey and Bermuda and compared these with several reanalysis products. Direct integration of water velocity at 55 m depth gives us layer transport. The overall mean (1992-2018) agrees with geostrophic transport estimated from absolute dynamic topography (ADT). But this agreement does not extend to interannual variations. The reason appears to be that the ADCP also sees the wind-driven Ekman layer currents, which ADT cannot. We then looked at the reanalysis products, several of which include wind-driven surface currents, estimated from reanalyzed winds. The results were confusing. 
<!--more-->

The products we looked at that included surface currents were OSCAR, GLORYS12 and GREPV2. I can’t go into the details here, better just to read the paper (reference below). Suffice to say that the three products and our estimates of mean Ekman transport agree reasonably well. That is quite encouraging for it means that the method that we used to separate the Ekman transport from the underlying velocity which is assumed to be in geostrophic balance was effective. Essentially, we isolate the wind-driven component of velocity by subtracting the geostrophic velocity field at 155 m depth, below the reach of the Ekman layer. The integral of this component along the Oleander line yields transports that look plausible. Ekman transport per unit width = windstress/(density x Coriolis parameter). Assuming 0.1 Pa, 103 kgm-3 and 0.8*1_0-4 s-1 (34°N), we obtain 1.3 m2s-1. Multiply this by 600 km for the Sargasso Sea portion of the Oleander section gives us 0.8 Sv – which accords with our data and the reanalysis products (see Figure 5 in reference). That is good news. So why is it that we see Ekman transport variability in our data but not in the reanalysis products? In fact, it is conspicuous that all products including the geostrophic estimates of transport agree with altimetry with little or no hint of an Ekman layer signal. 

Typical Ekman velocities at 50 m depth are 0.01 ms-1. Again, multiply this by 600 km and we get 0.006 Svm-1 layer transport. This accords well with the Oleander variability which is higher than that of the reanalysis products (Figure 2 in paper). That is what I find so curious, how can it be that the reanalysis products capture the mean Ekman transport, but not its variability? 

The ongoing Oleander operation now includes a Väisälä weather station measuring winds, pressure, temperature, and humidity continuously. This will allow us to examine more closely the relationship between wind forcing and ocean response! My hope is that it will soon include a sensor that measures incoming SW radiation so we can estimate air-sea heat fluxes as well. This information will be important for restratification studies as well as for biological issues.

- - - - -
Rossby, T., M. Andres, L. Chafik, and K. Donohue (2025). A comparative study of velocity and transport estimates along the Oleander line between Bermuda and New Jersey. Earth and Space Science, 12, e2024EA004090. https://doi.org/10.1029/2024EA004090


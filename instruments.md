---
layout: page
title: Instruments
---

# The URI sound source
![The RAFOS sound source](/assets/SourceDrawing.png)
<p><br>We developed this sound source a little over 20 years ago. It was a joint project between me and Prof. Jim Miller in the URI Ocean engineering Dept. It is pretty much the standard sound source for all RAFOS navigation applications. It consists of an open aluminum tube, 0.4 m diameter, 1.78 m long and with a 1.27 cm thick wall. Mounted its center sits a 15 cm diameter piezo-electric monopole transducer that vibrates radially with a center frequency of 262 Hz. These vibrations set up resonant pressure oscillations that radiate primarily horizontally away from the tube. We have calibrated the sound source several times, and find that with 1000 VAC applied to the monopole the radiated source level will be 180 dB re 1 μbar @ 1 m. It is very efficient – 100% (as defined, meaning if the sound pressure level in the horizontal plane were the same in all directions). But it also has a Q of about 100, meaning that its 3 dB bandwidth is barely 3 Hz. This means that the tube length must be adjusted so it will resonate at the local speed of sound where it is to be deployed. The design is of course scalable to other frequencies. The latest version of the sound source has a SeaScan clock that is accurate to within 1-2 seconds per year. The sources are now built at the Woods Hole Oceanographic Institution.</p>

# Yvette
![Yvette_profiler](/assets/Yvette.001.png)
*Evans, D., H.T. Rossby, M. Mark and T. Gytre.  YVETTE-a free fall shear profiler.  Deep-Sea Res., 26, 703-718, 1979.*
<p><br>Schematic view of Yvette. The sensors at the lower end consist of a pair of orthogonal Trygve Gytre acoustic current meters, and a Neil Brown CTD. As it sinks the current meters measure velocity relative to average motion of the near 6 m long tube. Dave Evans developed an inverting algorithm to estimate vertical shear to scales roughly 10x greater than the instrument. Knowing shear and density gradient we can determine the Richardson number from about .5 to 50 m in the vertical, a very useful range of scales.</p>

# The Pegasus profiler
![Pegasus Profiler](/assets/PegasusProfiler.png)
*Spain, P.F., D.L. Dorson and H.T. Rossby.  PEGASUS:  A simple, acoustically tracked velocity profiler.  Deep-Sea Res., 28, 1553-1567, 1981.*
<p><br>The Pegasus principle of operation is very straightforward: As it sinks and ascends it measures the travel time of acoustic pings from bottom beacons (or round-trip travel times to transponders). From those slant distances together with its depth (from pressure) we can determine from its trajectory the strength of the currents at all depths. Originally developed to study the Somali Current in 1979, it was used in a number of studies in the 1980s.</p>

# The SOFAR float
![SOFAR float]/assets/(SOFAR_float.jpg)
<p><br>Photo of a polyMODE float being loaded on the RV Oceanus in spring 1978. The long tube provides the flotation for the batteries and electronics in it, the shorter tube rigidly attached at the lower end is the 250 Hz sound source. The floats were designed and built by Doug Webb (in the hard hat) at WHOI. Yours truly in shorts and long hair is standing next to him. Every 8 hours the floats emitted a 1.523 Hz swept FM signal over 80 seconds. The signals were received at SOFAR hydrophones I had instrumented at Bermuda, the Bahamas, Grand Turk (see blog) and Puerto Rico. The signals were recorded both digitally for later analysis and in visual form for real-time tracking of the floats. During the main field program an observer at the stations would phone in the arrival times so we could update the position of all floats daily; this proved to be very helpful, both in MODE and in polyMODE. Even though the aluminum tubes were much stiffer (less compressible) than water, we noticed that the earlier generation SOFAR floats (in MODE) slowly sank over time due to a very slight plastic creep of the metal. To prevent the polyMODE floats from sinking Doug mounted an insulated sacrificial zinc anode on the float. When the pressure exceeded a certain value, a relay would connect the anode to the aluminum so the zinc would corrode. With the loss of mass the float would return to its target depth, so clever! 
- - - - -
Rossby, T.  “Evolution of Lagrangian methods in Oceanography.”  Chapter 1 in Lagrangian Analysis and Prediction in Coastal and Ocean Processes. Cambridge University Press. 2007


  
# The RAFOS float
![RAFOS figures](/assets/RAFOScombo2.png)
<p>The RAFOS float principle of operation: As it drifts at depth it listens for and records the arrival times of precisely timed signals from moored sound sources. At end of mission the float surfaces and transmits to a satellite all data it has collected, pressure and temperature too. Knowing the speed of sound in sea water, the arrival times give us the float’s distance to the sources from which its position can be determined. Navigational accuracy ~3 km (depends on many factors).</p>

# The acoustic Doppler current profiler
![Figure on left shows ADCP cross-section in a vertical water column, and the image on the right shows the M/V Oleander.](/assets/ADCPinstrument.png)
<p>The ADCP transmits short acoustic pulses along four beams. The sound is reflected back at various depths primarily by zooplankton. The Doppler shifts gives velocity along each of the four beams. These can be transformed in u, v, w velocities relative to the ship. Water velocity is obtained after subtracting the ship’s velocity (from GPS). We have operated ADCPs on three ships for years and even decades (the Oleander).</p>

# Scanning the ocean with ADCPs
![Three vessels (Oleander, Norrona, and Nuka Arctica) are shown which are each equipped with ADCPs.](/assets/ADCPships.png)
<p>Starting in the early 1990s Charlie Flagg at Stony Brook University and I started a project to study the Gulf Stream and surrounding waters from the Oleander, a container vessel in weekly service between Bermuda and New Jersey. Mounted in the ship’s hull the ADCP profiles currents along the route.</p>

<p>In 1999 we teamed up with Prof. Martin Mork at the University of Bergen to operate an ADCP on the Nuka Arctica, a container vessel operating between Nuuk in Greenland and Aalborg in Denmark. In 2006 we installed an ADCP on the high-seas ferry Norröna. She operates out of the Faroes to Denmark and Iceland. We have learned so much from these operations.</p>




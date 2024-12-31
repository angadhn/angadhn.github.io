---
title:  "Some notes on BEAM"
date:   2024-12-31 14:17:00
comments: true
toc: false
categories:
  - Inflatable Space Stations
  - ISS
  - ISS modules
---

Rajib Dasgupta's 2016 interview as NASA BEAM (Bigelow Expandable Activity Module)
project manager is quite informative for those interested in inflatable space 
habitats. BEAM's addition to the ISS jas proved that expandable tech on a human-rated spacecraft (ISS) can reach TRL 9.

# Mission profile and inflation process
BEAM was added to ISS shortly after in April 2016 as an addition to
the Tranquility module, delivered on a Dragon capsule launched on a SpaceX Falcon 9
{%sidenote "1" "what a legacy!" %}. A good example of in-orbit assembly, the mission
profile involves the the Canadarm2, which extracts BEAM from the Dragon’s
unpressurised trunk 5 days after. The arm is also used in berthing Dragon, after its two day journey to the ISS, to Node 2's nadir berthing port of the ISS. Then the arm is moved via its [Mobile Transporter cart](https://en.wikipedia.org/wiki/Mobile_Servicing_System#:~:text=Mobile%20Transporter%20cart)
(at least that's how I understood Rajib) and BEAM is berthed to the Node-3 aft port. The below image of the ISS shows these directions and others.

{% maincolumn 'assets/imgs/ISS_directions.png' "ISS directional sense (courtesy: Jared Owen's [ISS video](https://www.youtube.com/watch?v=FhKOuxhGlmI))." %}

Then, the module can be deployed and inflated. The inflation process plays out
in the following way: the first part is to pressurise the vestibule, which is the 
section/region that connects BEAM and Node 3. Then, the vestibule is prepared for 
deployment by setting up the deployment controller and making the necesary 
electrical connections. Then, the crew can begins expanding the BEAM module first
by using ISS air, via the MPEV valve, to get it to its full shape at a pressure
of 0.4 PSI. Once that is done, the crew releases air in the 8 inflation
tanks attached to BEAM using the aforementioned deployment controller- this
increases pressure from 0.4 PSI to atmospheric pressure of 14.7 PSI (to equalise it
with the ISS's pressure). Then testing begins with an 80-hour leak check followed by
crew entering the module to prepare the vestibule ducting to start air flow
inside the module. This is followed by first "ingress" to the module to collect
an air sample for safety and quality checks. By this time, it's almost a month (maybe two) since launch.

# Technology Objectives
The objectives for BEAM were to:
1. study its long-term leak performance and air quality;
2. assess the radiation environment inside the module compared to the rest of the ISS's metallic modules (REM and RAM passive badges sensors);
3. deployment dynamic sensor to study the dynamic loads generated during deployment;
4. Distributed Impact Detection System (DIDS) is a sensor to measure the impact of MMOD on the outer surface of the module; and
5. sensors to measure the thermal conditions and air quality in the module.

A lot of data was envisioned to be collected over two years aligned to these objectives. After that, the plan was to jettison beam using Canadarm: it grapples BEAM using the aft side [power data and grapple fixtures](https://en.wikipedia.org/wiki/Grapple_fixture#Flight-Releasable_Grapple_Fixture:~:text=Power%20Data%20Grapple%20Fixture%20(PDGF)%20allows%20for%20grappling%20and%20latching)
and transfers BEAM to the extreme nadir position of the ISS for release. Their estimated time for jettison and uncontrolled re-entry is “less than a year”.
Fortunately, BEAM has exceeded expectations and is still in use in 2024 as additional cargo.

Video below:
<iframe width="560" height="315" src="https://www.youtube.com/embed/9tBkjUhpFj8?si=Fq23ro8nmHCwLro-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

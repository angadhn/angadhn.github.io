---
title:  "Inflatable von Braun space stations: an idea worth revisiting?"
date:   2024-10-06 21:04:59
comments: true
categories:
  - Large Space Stations
  - Space Exploration
  - Inflatable Space Stations
redirect_to: https://angadh.com/inflatable-von-braun-stations
---

<div style="margin-bottom: 20px;">
  <p>This page has moved to <a href="https://angadh.com/inflatable-von-braun-stations">https://angadh.com/inflatable-von-braun-stations</a></p>
</div>

<script>
if (!window.sessionStorage.getItem('redirected')) {
    window.sessionStorage.setItem('redirected', 'true');
    setTimeout(function() {
        window.location.href = 'https://angadh.com/inflatable-von-braun-stations';
    }, 1500);
}
</script>

## Background
{% newthought "Kepler's" %} [Somnium](https://en.wikipedia.org/wiki/Somnium_(novel)){% sidenote
`somnium` "At the time of my writing this post, his sci-fi story was
archived [here](https://frostydrew.org/papers.dc/papers/paper-somnium)"%}
in 1608 and [Edward Everett Hale](https://en.wikipedia.org/wiki/Edward_Everett_Hale)'s
[Brick Moon](https://en.wikipedia.org/wiki/Brick_Moon) [^a]
from 1865 are
early fantasy science-fiction of space-faring humans. Kepler
faced more flak than fanfare for his work{% sidenote 'flak' "Kepler's mom was put on
[trial](https://thonyc.wordpress.com/2014/07/30/johannes-keplers-somnium-and-katharina-keplers-trial-for-witchcraft-the-emergence-of-a-myth/)
for witchcraft with some connections to Somnium.
Also credit for the link where it's [due](https://skullsinthestars.com/2018/02/23/somnium-by-johannes-kepler/)." %}
but I was especially surprised to learn about his use of creative writing
as a force for exploring ideas around space-faring and
extra-terrestrial civilisations. His scientific work in astronomy influenced
Newton and others indicating an enduring impact on science, engineering, and human
civilisation stemming from a curiosity about the motion of stars.
It suffices to say that space habitation has occupied us from a fictional
and scientific lens for some time now. 

Today's technocultural space community of thinkers has conjured or
realised astonishing visions like the Apollo program and reusable rockets in
the $20^{th}$ and $21^{st}$ centuries. The technical community no longer
battles claims of heresy but politics, as if fighting to overcome the limits 
of physics isn't hard enough. Bureaucratic operators seek short-term
justifications for projects and hinder progress towards sci-fi realities
of large scale space travel and habitation{% sidenote 'inflatables-2' "not so for
space data services,
as satellites have been miniaturised, commodified, and productised out of the hands
of governments."%}, branding these pursuits as potentially irresponsible to justify with
taxpayer money. Governments want to solve the flat-lining productivity problem{% sidenote
"UKproductivity" "I believe such investment justifies technical education which
then creates skilled populations- some of whom work on new visions that generate
jobs and others work in these jobs or enter the existing labour market. I can't
definitively prove this, of course, but it feels to me a pathway to solving
the [UK's productivity puzzle](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/labourproductivity/articles/whatistheproductivitypuzzle/2015-07-07)." %}
but want to do so without investing in visions of a limitlessly abundant future.
Meanwhile, private investors want rapid returns on investment while making
bold claims, like wanting flying cars but getting $140$ characters, extending the
participation in space progress to mostly the superwealthy.

From hereon, this post will focus on the radical notion of space
superstructures, such as rotating wheel space stations, that expand our
presence in various Earth orbits and then extend our reach to go deeper into space. The
post mostly argues for a focus on developing inflatable technologies to
realise these structures in the near-term but it is possible that this is
too ambitious a goal. Note that other options for realising space superstructures
(e.g., robots) are not really considered here but are generally important. Along
the way, readers may find claims that explain why supporting the development 
of space superstructures in the near-term is potentially valuable and socially
relevant.

## The vision
Simply put, the vision I am putting forward is of deploying monolithic
space stations with crew capacities of at least $100$ astronauts, i.e., 
$>10x$ the ISS's typical crew size; I call this the Hundred Person Habitat (HPH).
To date, no station has offered an order of magnitude increase on its
predecessors and none are in the pipeline{% sidenote 'inflatables-3' "The
in-development Lunar Gateway will operate at an orbit further to the
International Space Station (ISS) with a crew of 4. See table
[here](https://www.angadhn.com/online_textbooks/UG_final_year_project/#large-space-stations-modular-or-monolithic)"%}.
Assuming that a pressurized volume $>20x$ of the ISS gives each crew member a 
hypothetical $\approx 200\,m^3$ of volume though, in practice, the habitable portion is
roughly identical to the space occupied by on-board equipment/instruments
for experiments and life support. The station will be a toroid and thus 
conceptually resembles von Braun's{% sidenote 'potocnik'
"He was apparently inspired by Herman Potočnik's $30\,m$ ring-shaped habitat
described in [*The Problem of Space Travel*](https://books.google.co.uk/books/about/The_Problem_of_Space_Travel.html?id=6m0bCwAAQBAJ&redir_esc=y)" 
at GEO over Berlin.%} rotating wheel station. The below table
compares the HPH to the ISS and von Braun station:

<!--
|              Parameters                      | ISS    | von Braun wheel        | Hundred person Habitat |
| -------------------------------------------- | ------ | ---------------------- | ---------------------- |
| crew size (# of astronauts)                  | 7-13   | 50-80                  | 100                    |
| diameter of the station (m)                  | n/a    | 75                     | ~75                    |
| total volume $m^3$                           | 916    | 6217.85                | 20x of ISS             |
| habitable %                                  | 42.35% | 60% (assumed)          | ?                      |
| Max. volume per crew $(\frac{m^3}{person})$  | 64.66  | 52.67 assuming 50 crew | 183.20                 |
| Rotational speed for artificial gravity (RPM)|  -     | 3                      | 3                      |
| Gravity on-board  ($m/s^2$)                  |  -     | 1.655                  | 1.655                  |
-->

{% marginnote 'space-station-comparison-id' '*Table 1*: Comparison of different space station designs.' %}
<div class="table-wrapper">
  <table class="booktabs">
    <thead>
      <tr>
        <th colspan="4" class="cmid">Space Station Comparison</th>
      </tr>
      <tr>
        <th class="l">Parameters</th>
        <th>ISS</th>
        <th>von Braun wheel</th>
        <th class="r">Hundred person Habitat</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Crew size (# of astronauts)</td>
        <td class="c">7-13</td>
        <td class="c">50</td>
        <td class="r">100</td>
      </tr>
      <tr>
        <td>Diameter of the station (m)</td>
        <td class="c">n/a</td>
        <td class="c">75</td>
        <td class="r">~75</td>
      </tr>
      <tr>
        <td>Total volume (m³)</td>
        <td class="c">916</td>
        <td class="c">6217.85</td>
        <td class="r">20x of ISS</td>
      </tr>
      <tr>
        <td>Habitable %</td>
        <td class="c">42.35%</td>
        <td class="c">60% (assumed)</td>
        <td class="r">?</td>
      </tr>
      <tr>
        <td>Max. volume per crew (m³/person)</td>
        <td class="c">64.66</td>
        <td class="c">52.67 </td>
        <td class="r">183.20</td>
      </tr>
      <tr>
        <td>Rotational speed for artificial gravity (RPM)</td>
        <td class="c">-</td>
        <td class="c">3</td>
        <td class="r">3</td>
      </tr>
      <tr>
        <td>Gravity on-board (m/s²)</td>
        <td class="c">-</td>
        <td class="c">1.655</td>
        <td class="r">1.655</td>
      </tr>
    </tbody>
  </table>
</div>

As opposed to von Braun's imagined multi-launch architecture, I am
imposing{% sidenote 'notproposing' 'Not proposing!'%} that this identically sized structure be achievable from a
single rocket launch by exploiting an idea as old
as NASA itself: using an inflatable
tube structure.

## Inflatable tubular space stations: a counterintuitive idea
{% maincolumn 'assets/imgs/Goodyear1961.JPG' "Testing of an inlatable
space habitat prototype by Goodyear in 1961." %}

In 1961, Goodyear Aircraft Corporation prototyped an inflatable tube
space station (see above) called the Erectable Torus Manned Space
Laboratory{% sidenote 'airlocks' "Around the same time, the Soviets
were developing inflatable airlocks; a more modestly sized appendage
to spacecraft that allows astronauts to move between a pressurized
spacecraft and the vacuum of space." %}. The idea never made it to
flight due to concerns that the soft materials it was made from{% sidenote
'goodyear-materials' 'three-ply nylon cords, held together by butyl elastomer.'%}
weren't strong enough to withstand micrometeoroid collisions.
Nonetheless, this was an early example of a monolithic space station;
a tenth of von Braun's wheel station that could be packaged to $2\%$
of its inflated volume (another cool image below).

{% maincolumn 'assets/imgs/LittekenPaper_GoodYear.png' "
[Litteken's paper on space inflatables](https://ntrs.nasa.gov/api/citations/20190001443/downloads/20190001443.pdf)
has this really nice image of GoodYear's inital testing taken from James Hansen's
[_Spaceflight Revolution_](https://www.nasa.gov/wp-content/uploads/2023/04/sp-4308.pdf).
One can see James Webb underneath the full size inflated station; the images on the
left show the packaged tube structure." %}

A long lull on habitable space inflatables followed
until NASA's TransHab program (1997) which developed
high strength materials capable of withstanding collisions with
micrometeoroids and orbital debris (MMOD). TransHab inspired
a cylindrical inflatable ISS module ($13\,ft$ in length and $10\,ft$
in diameter)- BEAM (Bigelow Expandable Activity Module)- in
operation since 2016. The period between the GoodYear and TransHab
inflatable space stations laid the foundations for today's dominant
design of rigid space stations. In my eyes, this is a classic example
of where simpler elegant solutions were traded in for ones that are more
complex when we think about scale. For example, monolithic rigid stations were
followed by the modular ones, like the ISS, that have required in-space
assembly, mostly by astronauts, or propellant-intensive rendezvous
and docking manoeuvres. Building on this, most future scalable designs I have seen
purport the idea of robotic assembly. My recent learnings on inflatables suggest
that the same outcome might be realised by a simpler single inflatable system though
the development process will be less straightforward. The decision to focus
only on rigid stations/modules for several decades has made these inflatable
solutions a forgotten one; it appears that we threw out the baby with the bathwater.

When I suggest this idea to people today, it seems a counterintuitive and
potentially outrageous solution that exposes biases in thinking- even amongst
experts who are, after all, only human. Firstly, there's a widespread belief
that inflatable structures are less safe due to the risk of MMOD collisions.
The incorrect analogy of balloons bursting is often mistakenly applied but
modern designs incorporate multiple layers of high-strength materials that are
remarkably resistant to punctures and could even self-heal. In fact, their
flexibility could make them more resilient than rigid structures. Secondly,
prevalence of robotics in automating human tasks has led to an assumption
that the same approach is optimal everywhere: we see robots building cars
and assume they should build space stations. But space presents unique
challenges where simplicity is paramount. Inflatable structures have minimal
mechanical complexity, reduce failure points, and simplify construction.
Moreover, our terrestrial experience doesn't include living in inflatable
habitats, making it non-obvious as a space solution. We're accustomed to rigid
structures so cannot envision lightweight, expandable living spaces as
a viable alternative. Yet, in the vacuum of space, these structures
provide vast habitable areas with superior radiation shielding and
thermal management. This insight has profound implications for future
space missions. By embracing inflatable technologies, we can
dramatically reduce launch costs, simplify construction processes,
and create larger, more versatile space habitats than ever before.
It's a reminder that in space engineering, sometimes the most effective
solutions are those that challenge our Earth-biased intuitions.

## Why is now a good time to return to inflatable space structures?
There are probably many more reasons than I describe below as to why
now{% sidenote 'robotics1'
"Unlike was done with inflatables, we should maintain/increase support to
mature in-space robotic assembly and maintenance technology development
as I imagine that at even larger scales, a reliance on robots is inevitable."%}
is a good time to revisit the GoodYear inflatable station idea{% sidenote 'robotics2' "In fact,
such stations are just one application of inflatable 
technologies I see. They could totally transform space robotics by using pneumatic actuation
for orbital applications thus eliminating the need for radiation-hardened components like
joint motors- a pretty massive bottleneck in the development of space robotics."%}.

The first has to do with the emerging promise of Starship, which is seeing frequent impressive
tests. In contrast, when GoodYear was developing its concept, the
[Saturn V](https://www.google.com/search?q=saturn+v+development+year)
was still in early development and the GoodYear project might have been easy to kill; I imagine
the Moon missions would have also led to a reallocation of resources and
focus. Second, the impending retirement of the ISS means there is a window
(or even a need) for a successor with a larger volume for both crew sizes
and science output. Third, there will be eventually be more commercial users of a large
inflatable orbital volume than space agencies; in-space manufacturing
companies like Varda could use these stations to scale their drug manufacturing,
with the beneficiaries being patients on Earth. Other avenues here are for materials
science research and protein crystal growth (not my domain of expertise at all).
If in-space semiconductor manufacturing in microgravity becomes a thing, then
larger inflatable volumes would, again, answer the question of scaling.
Similarly, sci-fi outcomes such as at-scale 3-D printing artificial organs
would benefit those in need of hearts and lungs- demands that are not being met
by the donor organ market.

All of which is even before we consider making these
stations rotate to produce an artificial gravity enabling safer long-haul
journeys for astronaut crews
heading to Mars or other locations away from the Earth{% sidenote 'hansen' "I am
currently reading James Hansen's
[_Spaceflight Revolution_](https://www.nasa.gov/wp-content/uploads/2023/04/sp-4308.pdf) that should
help me gain a deeper perspective on the early inflatable station. Fun fact: another of his books was adapted into
[First Man](https://en.wikipedia.org/wiki/First_Man_(film)) with Ryan Gosling playing Neil Armstrong."%}.

<!-- ## Other opportunities with space inflatables? Long-horizon projections: Where would this take us in 20 years? or Where else could inflatable structures be used? -->


## Notes
[^a]: I've only read a summary of Brick Moon, a story of workers building a 200-foot sphere that are accidentally launched into space to become first inhabitants of space. The moon was to serve as a navigational aid for sailors. It also estimates a cost for the construction at ${\$}250k$ using $12$ million bricks.

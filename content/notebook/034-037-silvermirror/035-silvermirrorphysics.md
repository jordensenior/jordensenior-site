---
title: "035 · Why the Silver Comes to the Surface"
image: "/notebook/034-037-silvermirror/smt_fomaspeed.jpeg"
description: "The photochemistry and physics of silver mirror toning—physical development, nucleation at the emulsion surface, and the percolation threshold where scattered colour becomes a mirror"
author: "Jorden Senior"
date: "2026-07-30"
tags: ["Silver Mirror Toning"]
categories: ["Darkroom", "Analogue", "Science"]
series: ["Experimental Darkroom", "Silver Mirror Toning"]
aliases: ["silver-mirror-physics"]
toc: true
live: true
---

## Why the Silver Comes to the Surface

**Part 2 of 4** in the Silver Mirror Toning series | [← Previous: Part 1](/notebook/034-037-silvermirror/034-silvermirrorprocess/) | [Next: Part 3 →](/notebook/034-037-silvermirror/036-silvermirrorpapers/)

---

In [015](/notebook/014-016-chromoskedasic/015-chromoskedasicscience/) I worked through why silver particles of a particular size look like a particular colour — Mie scattering, localised surface plasmon resonance, the whole business of structural colour from a material that contains no dye. That post answers one question well, and I am not going to repeat it here.

It does not answer the question silver mirroring actually raises. A normal print already contains silver particles; it does not shine. The mirroring sits *on top of* the emulsion rather than in it, and it is reflective rather than coloured. So: why does the silver move, why does it stop where it stops, and what has to happen for a scattering surface to become a reflecting one?

Those are three different physics problems — transport, nucleation, and film continuity — and the process in [034](/notebook/034-037-silvermirror/034-silvermirrorprocess/) is a way of driving all three at once.

## Two Ways to Make Silver

Almost everything a printer does in a darkroom is **chemical development**. The developer finds an exposed silver halide crystal, reduces it *in situ*, and the metallic silver grows where the crystal already was. The developing agent supplies electrons; the silver comes from the grain itself. The result is the familiar filamentary, tangled silver of a black and white print — high surface area, tuned by a century of emulsion engineering to absorb light efficiently. That is precisely why a print looks black rather than shiny: the silver is shaped to trap light, not bounce it.

**Physical development** is the other route, and it is the one that matters here. The silver is dissolved into solution first, moves as a soluble complex, and is then reduced onto whatever nuclei it encounters. The silver that ends up in the image did not necessarily start in that spot. Because it is deposited from solution onto a growing surface rather than reduced inside a crystal lattice, physically developed silver tends towards compact, rounded, smooth particles instead of filaments.

That single difference — grown in place versus deposited from solution — accounts for most of what makes these prints strange. Compact particles at high coverage can behave like a metal film. Filaments never do.

## What the Thiocyanate Is Doing

The toning bath in 034 is three things at once: a solvent, an activator, and a reducer. Take them in that order, because that is the order the silver experiences them.

Sodium thiocyanate is a **silver halide solvent**. Silver halides are effectively insoluble in water, but thiocyanate binds silver ions into soluble complexes — the same class of chemistry as the thiosulfate in your fixer, which is why fixer removes halide at all. The difference in intent is everything: fixer complexes silver in order to carry it out of the print and down the drain. Here, the complexed silver is meant to stay, become mobile, and be put back down somewhere new. The bath is a fixer that has been told not to finish the job.

Sodium hydroxide is the **activator**. Developing agents are far more aggressive at high pH, and a strongly alkaline bath drives the reduction fast. Speed matters for morphology, not just for convenience: a slow reduction onto few nuclei grows a small number of large particles, while a fast one throws down many nuclei at once. Fast and coarse is the goal, which is the opposite of what you want from a print developer.

The developer supplies the **electrons**. Nothing exotic — the same reducing agents doing their usual job, on silver that arrived by a different route.

So: mobilise, transport, reduce.

## Why the Surface

Mobile silver in a gelatin layer is not going anywhere in particular. What gives the process direction is where the silver gets reduced, and reduction requires a nucleus — a site where the first few atoms can assemble. Homogeneous nucleation in the bulk of a solution is expensive; heterogeneous nucleation on an existing surface is much cheaper. Silver comes out of solution preferentially at interfaces.

The gelatin–solution boundary is the most available interface in the system, and it also sits at the steep end of every gradient that matters: it is where fresh bath keeps arriving, where the alkalinity is highest, and where a complexed silver ion has the shortest distance to travel. Silver that is reduced deep in the emulsion is buried and optically irrelevant. Silver reduced at the top accumulates on a surface that is already partly covered, which makes further deposition there easier still. The process is self-reinforcing, which is why the deposit is a distinct layer rather than a general fogging.

## The Accidental Version

Here is the part that made me want to write this post at all: conservation science has already studied this process in detail, because it is one of the principal ways photographs die.

Natural silver mirroring — the bluish sheen on the dense areas of old prints — proceeds by exactly the three steps above. Oxidants in the air, helped by humidity and by residual thiosulfate left behind by poor rinsing, oxidise image silver to silver ions. Those ions are mobile in the gelatin and migrate. On reaching the surface they are reduced back to metallic silver, depositing as colloidal particles, along with some silver sulfide.[^1] Mobilise, transport, reduce.

The mechanism has been characterised directly. Moon and Curran, working with artificially aged silver gelatine prints, used transmission electron microscopy to distinguish two deterioration pathways that look different to the eye: well-processed prints that yellowed via colloidal silver formation, and insufficiently washed prints that went redder and darker through more homogeneous silver sulfide filaments.[^2] Different particle morphology, different appearance — which is the same principle as [015](/notebook/014-016-chromoskedasic/015-chromoskedasicscience/), arrived at from the other direction by people trying to stop it happening.

The toning bath is not analogous to this. It *is* this, run deliberately. Instead of atmospheric oxidants you use a bleach or the print's own undeveloped halide; instead of residual thiosulfate you use thiocyanate on purpose; instead of ambient reduction over decades you use a developer at 35 °C. The decades collapse into minutes because every accidental reagent has been replaced by a chosen one at working concentration.

I find that genuinely satisfying as a piece of practice. Most alternative processes are described as historical revivals. This one is a degradation mechanism with the sign flipped. Intentional impermanence.

## From Colour to Mirror

The last question is the one 015 sets up but does not close: when does a collection of scattering particles stop being coloured and start being a mirror?

The answer is coverage, and the physics is a percolation problem. Thin metal films grown by deposition follow a well-studied sequence: discrete islands nucleate, the islands grow and begin to touch, coalescence produces a connected but ragged network, and eventually the film becomes continuous. Optically, that sequence has a threshold in it. Below it, each island supports its own localised surface plasmon resonance and you get selective scattering and absorption — colour, in other words, the regime 015 describes. Above it, the plasmon modes delocalise across the connected network and the film starts behaving like bulk metal, which means specular reflection.[^3] It is a dielectric-to-metal transition, and it can be modelled with effective-medium approaches such as Maxwell–Garnett.

For sputtered silver, the percolation threshold falls somewhere around two-thirds to four-fifths surface coverage, depending on deposition method and substrate.[^4] I would not transfer that number to a gelatin emulsion — the geometry, the substrate and the deposition mechanism are all different — but the *shape* of the behaviour should carry, because it is a connectivity argument rather than a chemistry one.

If that framework is right, then colour and shine are not two different results of this process. They are the same result at different coverage, and everything that pushes coverage up — time in the bath, temperature, how much silver was available to mobilise in the first place — moves a print along one axis from coloured to mirrored. It would also explain why prints that carry both are so common: coverage is not uniform across an image, so different parts of the same print can sit on different sides of the threshold.

One observation from the darkroom is at least consistent with this, though it is not evidence. With a fresh bath I could not see much difference between one minute and two — which would make sense if a fresh bath drives coverage past the threshold quickly and then has nowhere further to go. What did change the result was letting the chemistry age. A tired bath produced patchier, less uniform mirroring, which is exactly what a print sitting *at* the percolation threshold rather than comfortably above it should look like: connectivity varying across the sheet, some regions percolating and some not.

<figure>
    <img src="/notebook/034-037-silvermirror/smt_fomaspeed.jpeg" align="center" width="430px" style="margin:10px;" alt="A city skyline printed on Fomaspeed, the image floating in a pale cream field with dark mottled deposit along the paper edges" />
    <figcaption>Melbourne City Skyline. Here, the coverage varies across a single sheet: heavy, broken deposit at the edges, very light in the middle. Whatever sets the local density of the deposit, it is not uniform across a print. </figcaption>
</figure>

That is a hypothesis fitted to an accident, and I want to be clear about which way round that happened. But it does suggest the cleanest test available to me without a microscope: run one bath from fresh to exhausted, print the same negative through its whole decline, and see whether the sequence moves in an orderly way from mirror to mixed to colour. A coverage ladder made out of bath fatigue. If the prints come out in that order, the framework is doing real work; if they come out in some other order, it is a nice story that happens to be wrong.

## Direct, Indirect, and Where the Silver Comes From

In these terms the two sequences in 034 stop being separate techniques and become the same physics applied to two different inventories.

**Direct** toning uses the silver that is already sitting in the highlights as undeveloped halide. It is soluble, it is exactly what the thiocyanate is designed to mobilise, and it is present in the areas that received least exposure. Mirroring lands in the highlights because that is where the raw material is.

**Indirect** toning has to manufacture its raw material. The print is finished, so the highlights have been fixed clear and the only silver left is the metallic silver of the image. The copper chloride bleach rehalogenates it — converting metallic silver back to silver halide — which recreates a soluble reservoir precisely where the image is densest. Mirroring lands in the shadows because that is where the bleach has just put something the bath can dissolve.

This also predicts the failure mode I ran into when [stacking with mordançage](/notebook/034-037-silvermirror/036-silvermirrorpapers/): both processes are competing for the same finite pool of image silver, so whichever runs first sets what the second one has left to work with.

## Why Heat

Every step above is rate-limited. Complex formation, diffusion through gelatin, nucleation, and growth all speed up with temperature, but not by the same factor — and it is the *ratio* between nucleation rate and growth rate that sets particle size. Favour nucleation and you get many small particles; favour growth and you get fewer large ones. Since particle size is what 015 says determines colour, and coverage is what determines shine, temperature is not a convenience setting. It is the main handle on morphology available without changing the chemistry.

Which is a long way of justifying a heating mat under a tray, but it does suggest the experiment worth doing: hold everything else constant and make a temperature ladder rather than a time ladder, and see whether the two behave differently.

That gives me two ladders to build — one in temperature, one in bath fatigue — and between them they should settle whether any of the above is right. Neither needs equipment I do not have. Both need more prints than I have made.

---

[^1]: For an accessible overview of the accepted mechanism, see the American Institute for Conservation's Photographic Materials Group entry on [silver mirroring](https://www.conservation-wiki.com/wiki/PMG_Silver_Mirroring).

[^2]: Moon, J., and K. Curran. "A study of the relationship between the migration of image silver and perceived yellowing of silver gelatine photographs." *Heritage Science* 5, no. 45 (2017). [Open access](https://www.nature.com/articles/s40494-017-0159-9).

[^3]: On the transition from localised to delocalised plasmon modes as coverage increases, see the literature on semicontinuous and percolating metal films — e.g. "Plasmonic Percolation: Plasmon-Manifested Dielectric-to-Metal Transition," *ACS Nano* 6, no. 10 (2012).

[^4]: Reported percolation thresholds for sputtered silver films fall in roughly the 66–80% coverage range, varying with deposition conditions and substrate. See for instance the determination via Stokes parameters and in-situ conductance in *Applied Optics* 53, no. 24 (2014).

---

*Next: [036 · How Far the Recipe Travels](/notebook/034-037-silvermirror/036-silvermirrorpapers/) — the same chemistry on fibre, lith, RA-4, and mordançage, and the places it refuses to go.*

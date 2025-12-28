---
title: "015 · The Science of Colour from Silver: Mie Scattering, Plasmons, and Counterintuitive Chemistry"
image: "/notebook/014-016-chromoskedasic/chromo_4.jpeg"
description: "The physics and chemistry behind chromoskedasic Sabattier printing—why silver nanoparticles produce colour through light scattering"
author: "Jorden Senior"
date: "2025-12-23"
live: true
tags: ["Chromoskedasic Sabattier"]
categories: ["Darkroom", "Analogue", "Science"]
series: ["Experimental Darkroom", "Chromoskedasic Sabattier"]
aliases: ["chromoskedasic-science"]
toc: true
---

# The Science of Colour from Silver: Mie Scattering, Plasmons, and Counterintuitive Chemistry

**Part 2 of 3** in the Chromoskedasic Sabattier series | [← Previous: Part 1](../014-ChromoskedasicIntro) | [Next: Part 3 →](../016-ChromoskedasicDC)

---

In the previous post, I introduced chromoskedasic Sabattier printing as a technique that creates colour from black and white materials through physics and chemistry. Now we examine exactly how this works—why silver nanoparticles of specific sizes scatter specific wavelengths of light, and how darkroom chemistry produces those particles.

This is where my professional life intersects with my darkroom practice. The physics underlying chromoskedasic printing—surface plasmon resonance, Mie scattering, colloidal nanoparticle optics—connects directly to phenomena I encounter in quantum hardware research. The same principles that govern colour formation in these prints inform the design of plasmonic sensors and nanophotonic devices. Understanding the science doesn't diminish the art; it reveals why this technique produces results achievable through no other means.

## Part One: The Physics of Structural Colour

### Beyond Rayleigh: When Particles Grow Large

Most photographers have encountered Rayleigh scattering, even if not by name—it famously explains why the sky is blue. When light encounters particles much smaller than its wavelength, shorter wavelengths scatter more efficiently than longer ones. The mathematical relationship is steep: scattering intensity scales with the inverse fourth power of wavelength (I ∝ λ⁻⁴). Blue light, with its shorter wavelength (~450 nm), scatters roughly ten times more intensely than red light (~650 nm). Hence blue skies during the day and red sunsets when light traverses more atmosphere.

But Rayleigh scattering applies only when particles are truly small—roughly less than one-tenth the wavelength of light. For visible wavelengths (approximately 400-700 nm), this means particles smaller than about 40-70 nm. Above this threshold, the physics changes fundamentally.

<!-- <figure>
    <img src="/notebook/014-ChromoskedasicScience/scattering_regimes.png" align="right" width="350px" style="margin:10px;" alt="Diagram showing Rayleigh vs Mie scattering regimes" />
    <figcaption>Scattering behaviour depends on the ratio of particle diameter to wavelength. The Mie regime begins when particles approach the scale of visible light.</figcaption>
</figure> -->

When particle diameter approaches or exceeds the wavelength of light, we enter the Mie scattering regime. Named after German physicist Gustav Mie, who published the complete mathematical solution in 1908, Mie theory describes the complex electromagnetic interactions between light waves and spherical particles of comparable size. The simple wavelength dependence of Rayleigh scattering gives way to intricate resonance phenomena where specific wavelengths interact strongly with particles of specific sizes.

Mie's original paper, "Beiträge zur Optik trüber Medien, speziell kolloidaler Metallösungen" (Contributions to the Optics of Turbid Media, Especially Colloidal Metal Solutions), was motivated precisely by the colours of colloidal gold solutions—the same class of phenomena that underlies chromoskedasic printing. The theory he developed remains foundational to understanding light-matter interactions at the nanoscale.

If Rayleigh scattering explains why the sky is blue, Mie scattering explains why the clouds are white.
<!-- In the Mie regime, scattering efficiency depends on resonances between incident light and the particle's electromagnetic response. Different wavelengths resonate with different particle sizes. This is why colloidal suspensions of identical material can appear different colours depending on particle size distribution—the resonance conditions select for different wavelengths. -->

### Surface Plasmon Resonance: The Heart of the Phenomenon

For metallic nanoparticles like silver, something particularly interesting occurs: localized surface plasmon resonance (LSPR). This effect dominates the optical properties of chromoskedasic prints and produces their distinctive metallic, iridescent character.

A plasmon is a collective oscillation of conduction electrons in a metal. In bulk metal, these oscillations propagate as waves along the surface (surface plasmon polaritons) or through the volume (bulk plasmons). In nanoparticles—where electrons are confined to a small volume—the oscillations become localized. The particle acts as a resonant cavity for electron oscillation, with resonance frequencies determined by particle geometry and surrounding medium.

When light of the right wavelength strikes a silver nanoparticle, it drives the conduction electrons to oscillate collectively. At the resonance frequency, this oscillation becomes extremely intense—the particle acts almost like a nanoscale antenna, concentrating electromagnetic energy at its surface. The resonance causes strong absorption and scattering at that specific wavelength, with scattering cross-sections that can exceed the particle's geometric cross-section by factors of 10-40×.

The resonance wavelength depends on three primary factors:

**Particle size**: Larger particles resonate at longer wavelengths. For spherical silver nanoparticles in gelatin, the approximate relationships are:

| Particle Diameter | Resonance Region | Apparent Colour |
|-------------------|------------------|-----------------|
| 10-30 nm | Blue-violet absorption | Yellow |
| 30-50 nm | Blue absorption | Orange-yellow |
| 50-70 nm | Green absorption | Amber-orange |
| 70-100 nm | Yellow-green absorption | Bronze-brown |
| >100 nm | Broad visible absorption | Grey-brown |

These ranges are approximate. In practice, particle shape, aggregation state, size distribution, and the local gelatin environment all influence the exact resonance position. The table provides a conceptual framework, not precise specifications.

**Particle shape**: Spherical particles show single resonance peaks. Elongated particles (ellipsoids, rods) show multiple resonances at different wavelengths corresponding to oscillation along different axes. Irregular particles show broadened, complex spectra. In chromoskedasic prints, particles form under rapid, non-equilibrium conditions and tend toward irregular shapes—broadening the colour response and contributing to the technique's characteristic warm, complex tones.

**Surrounding medium**: The refractive index of the embedding medium shifts the resonance wavelength. Higher refractive index produces longer resonance wavelength (red-shift). Gelatin has a refractive index of approximately 1.5 (compared to 1.33 for water and 1.0 for air), causing significant red-shift of the plasmon resonance compared to silver nanoparticles in aqueous solution. This partly explains why chromoskedasic prints show predominantly warm tones—the gelatin matrix shifts resonances toward longer wavelengths.

### Why Warm Tones Dominate

The characteristic amber-bronze-gold palette of chromoskedasic prints reflects fundamental physics rather than arbitrary chemistry.

<!-- <figure>
    <img src="/notebook/014-ChromoskedasicScience/silver_plasmon_spectrum.png" align="left" width="300px" style="margin:10px;" alt="Plot showing how silver nanoparticle plasmon resonance shifts with particle size" />
    <figcaption>Silver nanoparticle plasmon resonance red-shifts with increasing particle diameter. In gelatin, the shift is more pronounced than in aqueous solution.</figcaption>
</figure> -->

Silver nanoparticles exhibit their primary surface plasmon resonance around 390-420 nm in vacuum or air—the boundary between ultraviolet and visible violet. In gelatin, this shifts to approximately 400-450 nm. Small silver particles therefore strongly absorb violet and blue light while transmitting and scattering longer wavelengths. The visual result is yellow.

As particles grow larger, the resonance shifts to longer wavelengths. Absorption moves through blue (producing orange appearance) toward green (producing red-brown appearance). But the resonance peak also broadens and weakens as particles grow. Very large particles—above roughly 150 nm—no longer show strong, sharp resonance. They scatter light more diffusely across the visible spectrum, appearing grey or metallic silver.

The chromoskedasic process produces particles predominantly in the 30-100 nm range, with size distributions that depend on processing conditions. This range corresponds directly to the warm colour palette: yellow, amber, orange, bronze, gold, russet brown. Cool tones (pure blue, green) require very small particles (under ~25 nm) that form only under conditions difficult to achieve with the rapid, aggressive chemistry involved.

The chemistry can push toward cooler or warmer within this range—more on this below—but the basic palette is constrained by physics. Chromoskedasic printing doesn't offer the full spectral range of chromogenic colour or multi-toner combinations. It offers instead a distinctive warm palette with metallic character impossible through any other means.

### The Quantum Connection

For those familiar with quantum mechanics, surface plasmon resonance connects to deeper physics. The plasmon is a quantized collective excitation—a quasiparticle representing coherent oscillation of the electron gas. The resonance condition corresponds to the frequency at which photon energy matches the plasmon energy for a given particle geometry.
<!-- 
The strong light-matter coupling at plasmon resonance has made silver and gold nanoparticles central to several active research areas:

**Biosensing**: LSPR-based sensors detect molecular binding events through resonance wavelength shifts. A molecule adsorbing to a nanoparticle surface changes the local refractive index, shifting the resonance—detectable as colour change. This enables label-free detection with extraordinary sensitivity.

**Photovoltaics**: Plasmonic nanoparticles embedded in solar cell absorber layers can enhance light capture through near-field concentration and scattering effects, improving efficiency.

**Photothermal therapy**: Gold nanoparticles tuned to absorb near-infrared light (which penetrates tissue) can be targeted to tumours and illuminated externally, producing localised heating for cancer treatment.

**SERS (Surface-Enhanced Raman Spectroscopy)**: The intense local fields near plasmonic nanoparticles enhance Raman scattering signals by factors of 10⁶-10¹⁰, enabling single-molecule detection. -->

When making a chromoskedasic print, I'm working with the same physics. The darkroom becomes an informal nanofabrication facility; the developer tray, a colloidal synthesis reactor. The particles producing warm amber tones are the same scale as structures engineered for cutting-edge photonic applications.

## Part Two: The Chemistry of Particle Formation

Understanding the physics tells us what we want to achieve. The chemistry tells us how to achieve it.

### The Standard Darkroom: Why It Doesn't Produce Colour

In conventional black and white processing, colour doesn't appear because particle sizes fall outside the optimal range for visible plasmon resonance—and because particles form as interconnected networks rather than discrete colloidal particles.

During camera exposure, photons create latent image centres in silver halide crystals—clusters of a few silver atoms that mark where development should occur. These clusters are far too small (a few atoms) to show plasmon effects in the visible range.

During development, reducing agents (typically hydroquinone or Metol/phenidone compounds) convert silver ions to metallic silver at latent image sites. The developing silver particles grow through accretion, with new silver depositing onto existing nuclei. The particles that form are quite large by nanoparticle standards—typically 200-500 nm or more, with complex filamentary structures that interconnect to form conducting networks. These extended structures scatter light broadly across the visible spectrum, producing neutral grey-to-black tones. No resonance selectivity, no colour.

Fixation removes unexposed silver halide, leaving only the developed silver image. Particle size doesn't change during fixation—thiosulfate fixer attacks silver halide (AgBr, AgCl) but not metallic silver (Ag⁰). The final image consists of large, interconnected silver particles that appear black in dense areas and grey where sparser.

The key insight: colour requires controlling particle formation—size, shape, and dispersion—during development, not modifying particles afterward. Once large filamentary structures have formed, they cannot be broken down into discrete nanoparticles. Chromoskedasic chemistry intervenes during the development/fixation process to redirect how silver precipitates.

### The Counterintuitive Sequence: Stabilizer Before Activator

Chromoskedasic processing uses two primary solutions with names that seem to suggest the opposite of their functions:

**Stabilizer** (applied first): Despite its name, this doesn't stabilize the image in the conventional photographic sense. It's a thiocyanate-based solution that partially complexes silver ions, creating a metastable chemical state that prevents both normal development and normal fixation from proceeding.

**Activator** (applied second): This alkaline solution triggers controlled precipitation of silver as colloidal nanoparticles in the size range that produces visible colour.

The sequence defies normal darkroom logic. In standard processing, you develop (creating silver image) then fix (removing unexposed halide). Here, you partially develop, then apply something like a partial fix (stabilizer), then chemically activate to complete silver formation under controlled conditions. The fix-like step comes in the middle of development, not at the end.

### Stabilizer Chemistry: Creating the Metastable State

The stabilizer contains ammonium or potassium thiocyanate (SCN⁻) at high concentration, buffered with acetic acid to an acidic pH.

**Standard Stabilizer Formula** (after Anderson and Bean):

| Component | Amount |
|-----------|--------|
| Ammonium thiocyanate (NH₄SCN) | 200 g |
| Sodium metabisulfite (Na₂S₂O₅) | 70 g |
| Acetic acid, 5% | 340 ml |
| Water to total | 1000 ml |

Working dilution: 1:4 for tray work; approximately 20% for brush application.

**Alternative: Potassium thiocyanate formulation**

| Component | Amount |
|-----------|--------|
| Potassium thiocyanate (KSCN) | 200 g |
| Water to total | 1000 ml |

Working concentration: ~20% solution.

⚠️ **Critical safety note**: Keep potassium thiocyanate away from all acids. Contact generates hydrogen cyanide gas, which is immediately dangerous to life. The ammonium thiocyanate formulation with acetic acid is safer; if using potassium thiocyanate, work only in well-ventilated areas and never add acid.

When stabilizer contacts a partially developed print, the thiocyanate ions form complexes with silver:

Ag⁺ + 2SCN⁻ → [Ag(SCN)₂]⁻

These complexes are more stable than free silver ions but less stable than the silver thiosulfate complexes formed by conventional fixer. The acidic pH inhibits further development and slows oxidation reactions. The result is a metastable intermediate state—silver neither fully removed (as with fixer) nor fully developed (as with continued processing). The system is chemically poised, waiting for the next intervention.

The stabilizer also interacts with remaining silver halide crystals, partially converting them but not fully dissolving them. This preserves unreacted halide as a reservoir for subsequent colour formation.

### Activator Chemistry: Triggering Controlled Precipitation

The activator is dilute alkali:

**Standard Activator Formula**:

| Component | Amount |
|-----------|--------|
| Potassium hydroxide (KOH) | 30-50 g |
| Cold water | to 300-500 ml |

Working dilution: 2% for brush application; 10-20% for tray work.

⚠️ **Safety note**: Dissolving KOH in water is strongly exothermic. Always add KOH to cold water slowly, never the reverse. The solution will heat significantly. Concentrated KOH causes severe chemical burns.

Sodium hydroxide (NaOH) can substitute but produces slower reactions and reportedly different (generally less intense) colour effects. Some practitioners report that ammonia solutions produce brownish, maroon, and yellow hues—attributed to the similar ionic radii of K⁺ and NH₄⁺.

When activator contacts the stabilized print, the pH jumps dramatically—from roughly 4-5 (acidic stabilizer) to 12-14 (strongly alkaline). This triggers several simultaneous processes:

**Thiocyanate complex destabilization**: At high pH, the silver-thiocyanate complexes become unstable, releasing silver ions back into solution.

**Silver ion reduction**: Multiple reducing agents are present—residual developer, metabisulfite from stabilizer, organic compounds in gelatin. At high pH, these reduce silver ions to metallic silver. The reduction occurs rapidly at many sites simultaneously.

**Nucleation and growth**: The released and newly-reduced silver precipitates as metallic particles. Rapid pH change drives fast nucleation, producing many small particles rather than fewer large ones. The competition between nucleation and growth—controlled by local chemistry—determines the final size distribution.

**Size-selective precipitation**: The alkaline conditions and residual thiocyanate moderate growth rates, preventing runaway aggregation into large filaments. Particles tend to stabilize in the 20-100 nm range rather than growing to the micron-scale structures of conventional development.

The result is a population of silver nanoparticles in the size range exhibiting visible surface plasmon resonance. The precise distribution—and therefore the colour—depends on timing, temperature, concentration, and application method.

### Why Light Matters: The Sabattier Component

The "Sabattier" in "chromoskedasic Sabattier" indicates that light exposure during processing is essential for colour formation. This isn't optional.

Light exposure serves multiple functions:

**Latent image formation in highlights**: During partial development under safelight, shadow regions develop first (they received more camera exposure). Highlight regions retain unexposed silver halide. When room light strikes the print after stabilizer application, it exposes these remaining halides, creating new latent image centres throughout the previously unexposed areas.

**Photolytic reduction**: Light can directly reduce silver ions to metallic silver, especially in the presence of organic electron donors. This photolytic reduction produces very small initial particles—exactly the nucleation sites needed for controlled colour formation.

**Multiplication of nucleation sites**: Room light creates numerous small nucleation centres rather than the few large latent image centres from camera exposure. More nuclei means smaller average particle size after growth—pushing results toward visible colour rather than grey fog.

Without light exposure during the chromoskedasic sequence, colour formation is weak or absent. The prints fog to grey rather than developing warm tones.

### pH as the Primary Control Variable

Within the constraints of the basic chemistry, pH provides the most direct control over colour:

**More alkaline → warmer colours**: Higher activator concentration or longer activator contact favours larger particles and pushes toward red, brown, and bronze tones.

**More acidic → cooler colours**: Higher stabilizer proportion or shorter activator contact preserves smaller particles and can produce yellower tones, occasionally tending toward blue-green in highlight areas.

**Balanced conditions → golden yellow to amber**: Moderate chemistry produces the classic chromoskedasic palette.

In practice, I adjust colour primarily by controlling the ratio of stabilizer to activator application—both spatially (where on the print) and temporally (how long each acts before the other). More stabilizer time before activator intervention preserves smaller particles and cooler tones. Stronger activator or longer activator time warms the palette.

### The Silvering Phenomenon

<!-- <figure>
    <img src="/notebook/014-ChromoskedasicScience/silvering_detail.jpeg" align="right" width="280px" style="margin:10px;" alt="Detail showing silvered area of a chromoskedasic print" />
    <figcaption>Silvering produces mirror-like metallic surfaces that shift colour with viewing angle—physically distinct from the coloured nanoparticle regions.</figcaption>
</figure> -->

When paper developer enters the chromoskedasic process, affected areas can develop a mirror-like metallic sheen, shifting through blue, purple, grey, and silver depending on viewing angle. This "silvering out" is physically distinct from the coloured nanoparticle effects.

The chemistry involves physical development—silver plating out from solution onto existing nuclei rather than developing from latent image centres. Developer provides fresh reducing agent. The partially-processed silver and halide provide nucleation sites. Silver deposits in relatively large particles with high surface coverage, creating a nearly continuous metallic film rather than discrete scattered nanoparticles.

Continuous metallic films have different optical properties than discrete nanoparticles. Rather than resonant scattering at specific wavelengths, you get broadband reflection—the mirror-like appearance of bulk metal. The iridescent shifts occur because thin films also produce interference effects.

Silvering can be controlled:

**To encourage silvering**: Paint working-strength developer onto specific areas. Move prints through developer → stabilizer → developer → stabilizer sequences. Use exhausted (aged) activator, which accumulates silver particles and promotes plating.

**To prevent silvering**: Avoid developer contact during chromoskedasic treatment. Skip subsequent trays if satisfied with colour. Apply stabilizer as a final step.

Silvering works well as an accent—metallic highlights against coloured surrounds—but extensive silvering obscures the more subtle nanoparticle colours that make chromoskedasic distinctive.

## Part Three: Paper, Temperature, and Process Control

### Paper Selection: The Foundation of Results

Paper choice substantially affects chromoskedasic outcomes. Key variables include silver content, gelatin properties, and surface characteristics.

**Recommended papers**:

**Ilford Multigrade FB Warmtone (glossy)**: The consensus best choice. High silver content provides ample material for nanoparticle formation. The warmtone emulsion complements the technique's natural palette. Glossy surface shows colours clearly without surface scatter dilution.

**Ilford Multigrade IV FB Classic (glossy)**: Excellent results with slightly cooler base tonality than Warmtone. Good alternative when warmtone isn't desired.

**Fomatone papers (131, 132, 532)**: Czech papers with high silver content and distinctive gelatin properties. Produce strong colour response with somewhat different palette than Ilford.

**Ilford Multigrade RC Pearl**: Among resin-coated papers, Pearl surface shows strongest metallic effects. Colour formation is possible but typically less dramatic than fiber-based papers.

Fiber-based papers generally outperform resin-coated for chromoskedasic work. The thicker, more robust gelatin layer in FB papers holds chemistry better and permits more complex particle formation dynamics. RC paper's thin emulsion and sealed plastic base limit chemical interaction.

Surface finish matters for colour visibility. Glossy surfaces allow direct reflection of plasmon-scattered wavelengths. Matte surfaces scatter reflected light in all directions, diluting the resonant colour with diffuse white scatter. For maximum colour intensity, glossy is preferred.

### Temperature Effects

Temperature affects both chemistry and physics of the process.

Chemical kinetics accelerate with temperature. Reactions that require minutes at 20°C may complete in seconds at 35°C. The practical working range is approximately 24-40°C (75-105°F), with most practitioners working around 30-35°C.

**Warmer conditions produce**:
- Faster colour development
- More intense final colours
- Greater risk of over-processing and loss of control
- Narrower timing windows

**Cooler conditions produce**:
- Slower, more controllable reactions
- Subtler effects
- Risk of incomplete activation if too cold
- Wider timing tolerance

I work at 30-33°C for most chromoskedasic sessions—warm enough for reliable colour intensity while maintaining reasonable working time. In my outdoor workflow (discussed in the next post), ambient temperature varies seasonally, which noticeably affects results.

### Tray Method versus Brush Method

**Tray method**: All working chemicals combined in a single tray. The print moves from development through rinse into the combined chromoskedasic bath. This produces more uniform effects across the print surface, with less spatial control but greater consistency.

**Tray formula** (per Megan Crawford's method):

| Component | Amount |
|-----------|--------|
| Warm water (~30°C) | 500 ml |
| Working developer | 125 ml |
| Activator stock (10% KOH) | 250 ml |
| Stabilizer stock | 125 ml |

Agitate for 30-60 seconds, then allow the print to sit in the tray, watching for colour development and silvering. Total time varies from 1-5 minutes depending on desired effect.

**Brush method**: Apply stabilizer and activator separately using brushes, controlling where each solution contacts the print. This permits selective colour control—different areas can receive different treatment—but requires more skill and produces more variation.

For brush work, I use a calligraphy brush (holds fluid, comes to a point) for detail application and a foam brush for broad coverage. Dedicate brushes to chromoskedasic work; they'll accumulate silver with use and affect subsequent prints if used for other purposes.

**Brush method sequence**:
1. Under room light, apply dilute stabilizer (20%) to target areas
2. Observe colour shift—areas should move toward pale yellow within 30-90 seconds
3. Apply dilute activator (2-5% KOH) selectively
4. Observe colour development—treated areas shift toward amber, brown over 30-120 seconds
5. Optionally apply developer for localised silvering
6. Repeat and adjust until satisfied
7. Rinse thoroughly to arrest further change
8. Fix to complete processing

### Fixing: The Archival Trade-off

Standard fixer (sodium thiosulfate) removes unfixed silver halide—necessary for archival permanence—but also attacks the colour-forming nanoparticles, shifting colours toward grey.

Two approaches:

**Standard fixer with accepted colour shift**: Use normal thiosulfate fixer. Blues and violets shift toward silvery grey with interesting fluorescence under oblique lighting. Warm tones shift toward grey-brown. Some practitioners prefer these more muted post-fix colours.

**Colour-preserving thiocyanate fix** (after Jolly):

| Component | Ratio |
|-----------|-------|
| 5% sodium thiocyanate solution | 1 part |
| Water | 5 parts |
| Treatment time | ~20 seconds |

This removes residual halide without fully attacking the colour-forming particles. Results preserve colours closer to their wet-print appearance. However, archival stability may be reduced compared to thorough thiosulfate fixation—a trade-off each practitioner must evaluate.

After fixing, wash prints thoroughly. Fiber-based prints require 60-120 minutes in running water or equivalent archival washing sequence. RC prints need minimum 5 minutes.

Prints darken approximately one stop when dry. Stop processing when the wet print appears slightly lighter than desired.

## The Irreducible Variables

Despite understanding the physics and chemistry in detail, chromoskedasic printing remains irreducibly experimental. Some variables resist control:

**Particle size distribution**: The chemistry produces a range of sizes, not monodisperse uniform particles. Each print has a slightly different distribution.

**Local concentration gradients**: Even with careful application, concentrations vary across the print. Diffusion, pooling, evaporation, and brush loading all create gradients.

**Gelatin batch variation**: Different paper batches have subtly different gelatin formulations, affecting nucleation and growth kinetics.

**Image content feedback**: The existing silver distribution from camera exposure affects where and how colour forms. Dense shadow regions remain unchanged; sparse highlight regions transform dramatically. The chemistry responds to image content, creating content-dependent results that can't be fully predicted.

**Environmental fluctuations**: Temperature and humidity variations during processing influence reaction rates and equilibria.

These uncontrollable factors mean exact reproduction is essentially impossible. Two prints from the same negative, processed identically by the same hands, will differ. For practitioners accustomed to digital repeatability, this is frustrating. For those embracing analogue contingency, it's intrinsic to the medium.

---

## References

### Physics of Nanoparticle Optics

Mie, Gustav. "Beiträge zur Optik trüber Medien, speziell kolloidaler Metallösungen." *Annalen der Physik* 330, no. 3 (1908): 377-445. [Original theoretical treatment.]

Bohren, Craig F., and Donald R. Huffman. *Absorption and Scattering of Light by Small Particles*. New York: Wiley, 1983. [Comprehensive textbook on Mie theory and light scattering.]

Kelly, K. Lance, Eduardo Coronado, Lin Lin Zhao, and George C. Schatz. "The Optical Properties of Metal Nanoparticles: The Influence of Size, Shape, and Dielectric Environment." *Journal of Physical Chemistry B* 107, no. 3 (2003): 668-677. [Excellent review of plasmonic nanoparticle optics.]

Kreibig, Uwe, and Michael Vollmer. *Optical Properties of Metal Clusters*. Berlin: Springer, 1995. [Detailed treatment of metal nanoparticle optics.]

### Surface Plasmon Resonance

Maier, Stefan A. *Plasmonics: Fundamentals and Applications*. New York: Springer, 2007. [Modern textbook on plasmonics.]

Willets, Katherine A., and Richard P. Van Duyne. "Localized Surface Plasmon Resonance Spectroscopy and Sensing." *Annual Review of Physical Chemistry* 58 (2007): 267-297. [Review focused on LSPR sensing applications.]

### Silver Nanoparticle Chemistry

Paramelle, David, et al. "A Rapid Method to Estimate the Concentration of Citrate Capped Silver Nanoparticles from UV-visible Light Spectra." *Analyst* 139 (2014): 4855-4861. [Modern characterisation of silver nanoparticle optical properties.]

Henglein, Arnim. "Colloidal Silver Nanoparticles: Photochemical Preparation and Interaction with O₂, CCl₄, and Some Metal Ions." *Chemistry of Materials* 10 (1998): 444-450. [Silver nanoparticle chemistry.]

### Chromoskedasic Process

Lam, Dominic Man-Kit, and Bryant W. Rossiter. "Chromoskedasic Painting." *Scientific American* 265, no. 5 (November 1991): 80-85.

Jolly, William L. *Solarization Demystified: Historical, Artistic and Technical Aspects of the Sabatier Effect*. Buffalo, NY: William L. Jolly, 1997.

Anderson, Christina Z. *The Experimental Darkroom*. New York: Routledge, 2022.

Anderson, Christina Z. "Chromoskedasic Printing Revisited." *Photo Techniques* (May/June 2010).

### Online Resources

AlternativePhotography.com. "Self-made Activator and Stabilizer for Chromoskedasic Painting." https://www.alternativephotography.com/self-made-activator-and-stabilizer-for-chromoskedasic-painting/

Photrio.com forums. "Chromoskedasic Activator and Stabilizer Formulas." https://www.photrio.com/forum/threads/chromoskedasic-activator-and-stabilizer-formulas.119551/ [Community discussion of alternative formulations.]

### Further Reading: Related Processes

Crawford, William. *The Keepers of Light*. Dobbs Ferry, NY: Morgan & Morgan, 1979. [Historical photographic processes.]

James, Christopher. *The Book of Alternative Photographic Processes*. 3rd ed. Boston: Cengage Learning, 2015.

Anchell, Stephen G., and Bill Troop. *The Film Developing Cookbook*. Boston: Focal Press, 1998. [Development chemistry background.]

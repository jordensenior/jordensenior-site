---
title: "020 · Colour's Complications: C-41 and What It Costs"
image: ""
description: "Colour negative processing adds real environmental concerns beyond black-and-white—but silver remains the dominant issue"
author: "Jorden Senior"
date: "2026-01-06"
tags: ["Sustainability", "C-41"]
categories: ["Darkroom", "Analogue"]
series: ["Sustainable Darkroom"]
aliases: ["c41-colour", "colour-processing-sustainability"]
toc: true
live: true
---

# Colours Complications: C-41 and What It Costs

**Part 4 of 13** in the Sustainable Darkroom series | [← Previous: Part 3](../019-defensiblepractice) | [Next: Part 5 →](../021-ra4printing)

The first three posts in this series focused on black-and-white processing. That's where most of the sustainability discourse lives—caffenol versus Rodinal, botanical developers, fixer recovery. But I also process colour, and it seemed dishonest to write about sustainable darkroom practice without addressing it.

I'm primarily a B&W shooter, but once a month or so I process some colour—more in the brighter months when the light and colour are worth capturing, less so in the Finnish winter (at least - recent winters where it's been mostly shades of grey). I've been trying to batch my colour processing to minimise chemistry waste, but honestly, I'm too impatient. I tend to develop a roll the same week I shoot it. When that doesn't happen, I hand it to a commercial lab—especially for C-41, where the process was designed for industrial throughput anyway. B&W I keep at home for the control over developer choice and the aesthetic flexibility that brings.

This post examines C-41 colour negative development: what's in it, how it compares environmentally to black-and-white, and whether any of the available home kits are meaningfully better than others. I'll also address a question that's been nagging me: is it actually more sustainable to just let the lab do it?

The short answer: C-41 has genuinely worse chemistry than B&W in some respects, but silver remains the dominant environmental concern. If you're recovering silver from your blix or fixer, you're addressing the biggest problem regardless of colour versus monochrome.

## Whats Actually in C-41 Chemistry?

C-41 is a standardised process—unlike black-and-white, where you can choose between dozens of developers with different formulations, all C-41 developers use essentially the same active chemistry.[^1] The standardisation exists because colour negative film contains integral dye couplers that must react with specific colour developing agents to produce the final image.

### The Developer

C-41 developer contains:

**CD-4 (4-amino-3-methyl-N-ethyl-N-(β-hydroxyethyl)aniline sulfate):** The colour developing agent. This is a para-phenylenediamine (PPD) derivative—the same chemical family that causes allergic reactions in hair dye.[^2] CD-4 reduces exposed silver halides while simultaneously oxidising to react with the film's dye couplers, forming the cyan, magenta, and yellow dyes that constitute the colour image.

**Hydroxylamine sulfate:** An antioxidant that protects CD-4 from aerial oxidation. This is corrosive and can cause chemical burns.[^3]

**DTPA or other chelating agents:** Sequester metal ions that would otherwise catalyse developer oxidation or cause colour contamination.

**Carbonate buffer:** Maintains the high pH (~10.0) necessary for effective colour development.

The developer is classified as "very toxic to aquatic life" on safety data sheets, with the H412 hazard statement ("harmful to aquatic organisms with long lasting effects") appearing on most commercial C-41 developer products.[^4]

### The Bleach and Fix (or Blix)

After development, the silver must be removed—unlike black-and-white, where the metallic silver *is* the image, in colour the silver is just a catalyst for dye formation and becomes waste.

**Separate bleach and fix:**
- Bleach: Ammonium ferric EDTA oxidises metallic silver back to silver halide
- Fix: Ammonium thiosulfate dissolves the silver halide, same as B&W fixing

**Combined blix:**
- Contains both ferric EDTA and thiosulfate in one solution
- More convenient for home use
- Slightly less efficient—silver removal isn't quite as complete

Either way, the silver ends up dissolved in your spent chemistry. The concentrations are comparable to black-and-white processing: **3,000–8,000 mg/L** in exhausted solutions.[^5]

### The Environmental Concerns

C-41 introduces several issues that black-and-white processing doesn't have:

**1. CD-4 toxicity**

CD-4 is a skin sensitiser and suspected carcinogen (Category 2).[^6] Unlike hydroquinone, which biodegrades readily, PPD derivatives are more persistent and more acutely toxic to aquatic organisms. The H412 classification ("harmful to aquatic organisms with long lasting effects") on C-41 developer SDS sheets reflects this—some products carry the more severe H411 ("toxic to aquatic life").

That said, CD-4 is used at relatively low concentrations (typically 4–5 g/L in working solution), and home processing volumes are small. The per-roll chemical burden is higher than B&W developer but still in the milligram range.

**2. EDTA persistence**

The bleach component contains EDTA (ethylenediaminetetraacetic acid), a chelating agent. EDTA is one of the most persistent anthropogenic compounds found in European surface waters—it's not readily biodegradable under normal wastewater treatment conditions.[^7]

A 1997 review in *Reviews of Environmental Contamination and Toxicology* concluded that "EDTA behaves as a persistent substance in the environment" and that "its contribution to heavy metals bioavailability and remobilisation processes in the environment is a major concern."[^8]

EDTA itself has low acute toxicity to aquatic organisms, but its environmental persistence—and its ability to mobilise heavy metals from sediments—is problematic in ways that aren't captured by simple LC₅₀ values.

**3. Temperature and energy**

C-41 requires processing at 38°C ± 0.5°C. Maintaining this temperature precision requires either a water bath or a sous vide circulator, both of which consume energy. The tight tolerance also means more potential for failed batches—chemistry that doesn't quite work because temperature drifted, producing waste without usable negatives.

Black-and-white processing tolerates temperature variations of several degrees; C-41 does not.

**4. Silver—still the elephant**

Despite all the above, silver remains the dominant environmental concern in C-41 processing, just as in B&W. The ferric EDTA bleach and ammonium thiosulfate fix (or combined blix) accumulate silver at the same concentrations as B&W fixer. The total silver burden per roll varies by film type, but colour negative films typically contain comparable amounts to B&W—and all of it ends up in your blix, since C-41 bleaches out the developed silver completely.[^9]

If you're doing C-41 at home and not recovering silver, you're making the same mistake as the B&W printer who ignores fixer: focusing on secondary concerns while the primary impact goes unaddressed.

## Home C-41 Kits: A Comparison

I use CineStill Cs41 because it's what's readily available to me. But I wanted to know: are any of the alternatives meaningfully better from an environmental perspective?

### The Major Kits

**CineStill Cs41** (powder or liquid)
- Two-bath process: Developer + Blix
- Flexible temperature (published times for 24°C–39°C)
- No stabiliser required for modern films
- 8–24 rolls per kit depending on usage

**Bellini C-41 Monopart**
- Three-bath process: Developer + Bleach + Fix (separate)
- Single-part developer (simpler mixing)
- Separate bleach and fix allows for silver recovery from fix only

**Tetenal Colortec** 
- Three-part developer concentrate
- Separate bleach and fix or combined blix depending on kit
- Long track record, professional-grade results

**Kodak Flexicolor** (professional)
- As far as I'm aware, the reference standard—what many labs use
- Available in large quantities (5L, 20L)
- Separate bleach and fix
- Replenishment system designed for high volume

### Environmental Comparison

From a sustainability perspective, the kits differ primarily in two ways:

**Blix versus separate bleach and fix:**

Kits with combined blix (CineStill, some Tetenal) put silver into a solution that also contains ferric EDTA. This complicates silver recovery—the steel wool method works less efficiently when iron is already present in the solution, and the chemistry is more complex.

Kits with separate bleach and fix (Bellini, Kodak Flexicolor) allow you to treat the fix independently. The fix behaves exactly like B&W fixer for silver recovery purposes. The bleach contains no silver and can be disposed of separately (though EDTA persistence remains a concern).

**If you plan to recover silver, separate bleach and fix is preferable.**

**Capacity and waste:**

All home kits produce similar waste volumes per roll. The differences in rated capacity (8 rolls versus 24 rolls) primarily reflect conservative versus optimistic estimates, not fundamental chemical differences. As far as I'm aware, most home users get 15–20 rolls from a one-litre kit before colour shifts become unacceptable.

Professional chemistry (Flexicolor) is designed for replenishment—you add small amounts of fresh chemistry to maintain the working tank rather than discarding exhausted solutions. This dramatically reduces waste per roll, but requires processing volumes that exceed what most home darkrooms generate.

### My Recommendation

If you're choosing a C-41 kit primarily for environmental reasons:

1. **Consider Bellini or Kodak Flexicolor** for separate bleach/fix, enabling straightforward silver recovery from the fixer
2. **CineStill and other blix-based kits are fine** if you're disposing of spent chemistry via hazardous waste collection rather than recovering silver yourself
3. **Don't stress about it too much**—the differences between kits are marginal compared to the difference between recovering silver and not recovering silver

I continue to use CineStill because it's available, the flexible temperature range suits my workflow, and I take my spent blix to hazardous waste collection. If I were setting up silver recovery at home, I would switch to a separate bleach/fix system.

## Would Lab Processing Be More Sustainable?

This is a question I've been wrestling with, especially given my impatient habit of developing rolls immediately rather than batching.

**Arguments for lab processing:**

Commercial labs process at scale. A minilab running continuously through a replenishment system uses far less chemistry per roll than my one-litre kit sitting half-oxidised between monthly sessions. The chemistry-per-image ratio improves dramatically with volume.

Labs are also required (in most jurisdictions) to comply with silver recovery regulations. Commercial photo processors typically use electrolytic recovery or metallic replacement cartridges that capture silver efficiently. My home blix goes to hazardous waste where the silver recovery rate is uncertain.

Temperature control is automated and precise—no failed batches from temperature drift, no wasted chemistry on unusable negatives.

**Arguments for home processing:**

Transport has environmental costs—though this depends entirely on your situation. I walk to my lab, so the transport impact is zero. If you're driving or shipping film, those emissions add up.

Not all labs practice responsible chemistry management. I'm reasonably confident my local lab handles their waste properly, but I don't have perfect visibility into their practices. Your situation may vary. At least with home processing, you control the disposal chain entirely.

Home processing eliminates the lab's facility footprint—heating, lighting, equipment manufacturing—though this is probably negligible per roll.

**My current compromise:**

For C-41, I increasingly lean toward lab processing when I can't batch. I'm in the fortunate position that there are at least 4 local labs, including one on the street where I live, and I believe they are responsible (except for the one who for inexplicable reasons, sends film from [Finland to Spain](https://kamerastore.com/en/pages/sending-your-film-to-us) to be developed...). The industrial efficiency argument is strong, and the chemistry is standardised anyway—I'm not making aesthetic choices about colour developer the way I do with B&W.

For B&W, I continue to process at home because developer choice matters to how my negatives look, and the environmental profile of B&W chemistry is more manageable.

If you're processing C-41 at home, batch your rolls. If you're processing them one at a time like I often do, and you have access to a trustworthy lab within walking or cycling distance, that might actually be the more sustainable choice.

## Is C-41 Worse Than B&W?

Yes, in several respects:

- **Developer toxicity:** CD-4 is more acutely toxic and more persistent than most B&W developing agents
- **EDTA persistence:** The bleach component introduces a compound that doesn't readily biodegrade
- **Energy use:** Temperature control requirements increase energy consumption
- **Handling risk:** CD-4 is a known sensitiser; long-term exposure risks are higher than with B&W chemicals

But the magnitude of these differences is smaller than the magnitude of the silver problem that both processes share.

If I had to rank the environmental interventions for C-41 processing:

1. **Silver recovery or proper disposal** — addresses ~80% of environmental concern
2. **Proper PPE and ventilation** — addresses human health risk
3. **Choosing separate bleach/fix** — enables better silver recovery
4. **Efficient temperature control** — reduces energy waste
5. **Kit choice** — marginal differences

## My Honest Assessment

C-41 home processing is environmentally worse than B&W processing. The developer is more toxic, the bleach introduces persistent chemicals, and temperature requirements increase energy use.

But it's not dramatically worse. The silver burden is similar (actually higher per roll). The disposal requirements are similar. The fundamental hierarchy—silver >> water >> chemistry >> developer choice—remains valid.

If you're already practising responsible B&W processing (silver recovery, efficient washing, proper disposal), extending those practices to C-41 addresses most of the additional concern. The CD-4 and EDTA are genuine issues, but they're secondary to the heavy metal problem that dominates both processes.

Process C-41 at home if you want to. Wear gloves, ensure ventilation, recover silver or dispose of chemistry properly. The environmental cost is real but manageable—and significantly lower than sending film to labs that may not practice silver recovery at all (or send them halfway across Europe to be developed).

---

## References

[^1]: Kodak. "Using KODAK FLEXICOLOR Chemicals: Process C-41." Publication Z-131. Rochester, NY: Eastman Kodak Company, 2000.
 
[^2]: ECHA Registration Dossier. "4-(N-Ethyl-N-2-hydroxyethyl)-2-methylphenylenediamine sulfate (CD-4)." European Chemicals Agency, 2023. Skin sensitiser Category 1.

[^3]: Flic Film. "Safety Data Sheet: C41 Developer - Part A." 2021. Available: freestylephoto.com/static/pdf/msds/flicfilm/FLIC_FILM_ECO_C41_SDS.pdf

[^4]: CineStill Film. "Safety Data Sheet: Cs41 Developer Powder." 2019. Hazard statement H412. Available: fotoimpex.de

[^5]: US EPA. "RCRA in Focus: Photo Processing." EPA 530-K-99-002. Washington, DC: January 1999.

[^6]: IARC Monographs. "Some Aromatic Amines and Related Compounds." Volume 127. Lyon: International Agency for Research on Cancer, 2021. PPD derivatives classified Group 2B (possibly carcinogenic).

[^7]: Nörtemann, B. "Biodegradation of EDTA." *Applied Microbiology and Biotechnology* 51 (1999): 751–759. DOI: 10.1007/s002530051458

[^8]: Sillanpää, M. "Environmental fate of EDTA and DTPA." *Reviews of Environmental Contamination and Toxicology* 152 (1997): 85–111. DOI: 10.1007/978-1-4612-1964-4_3

[^9]: James, T.H., ed. *The Theory of the Photographic Process*. 4th ed. New York: Macmillan, 1977. Chapter 12: "Color Photography."

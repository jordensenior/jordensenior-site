---
title: "030 · Lith Printing: The Chemistry of Chaos"
image: "/"
description: "Understanding infectious development—the autocatalytic chemistry that makes lith printing unlike anything else in the darkroom"
author: "Jorden Senior"
date: "2026-02-01"
tags: ["Lith Printing",]
categories: ["Darkroom", "Analogue"]
series: ["Experimental Darkroom", "Lith Printing"]
aliases: ["lith-printing-chemistry"]
toc: true
live: true
---

# Lith Printing: The Chemistry of Chaos

<!-- **Part 1 of 3** in the Lith Printing series | [Next: Part 2 →](../031-lithprintingcontrol) -->

---

The first time I watched a lith print develop, I thought something had gone wrong. The paper sat in the tray for what felt like an eternity—two minutes, three minutes, four—showing almost nothing. Then faint highlights emerged, ghostly and uncertain. Then midtones, slowly. Then the shadows began to move, and suddenly everything accelerated. The image didn't develop so much as erupt, shadows darkening visibly, racing toward black while I scrambled to snatch the print before it went too far.

<figure>
    <img src="/notebook/030-032-lith/lith_acidsquad.jpeg" align="right" width="350px" style="margin:10px;" alt="Lith print showing characteristic warm highlights and gritty shadows" />
    <figcaption></figcaption>
</figure>

This was at [Mörk](https://pimiotaiteilijat.fi/en/) in Helsinki, during a workshop led by [Åsmund Lahaug](https://www.instagram.com/aaklahaug/) as part of the [Nordic Analogue Network](https://www.nordicanalognetwork.com/) residency programme. Åsmund had warned us: lith printing doesn't behave like conventional development. The chemistry follows different rules. But understanding those rules intellectually is one thing; watching them unfold in the tray is another entirely.

What I saw that afternoon—and what I've been exploring ever since—is a process that produces results impossible through any other means: creamy, grainless highlights sitting alongside high-contrast, textured shadows, warm colours emerging from black and white materials without toning, and a distinctive gritty aesthetic that feels simultaneously vintage and contemporary. The technique has become one of my most trusted ways of making prints, particularly using Moersch EasyLith chemistry with FomaTone 132 and FomaBrom 152—among the last papers still manufactured that will properly lith.

This post begins a three-part series on lith printing. Here I'll examine the chemistry—what actually happens in the developer tray that makes lith so distinctive, why hydroquinone behaves unlike other developing agents, and how understanding the mechanism transforms mysterious alchemy into controllable craft. The second post covers practical control: exposure, the snatch point, temperature, and the characteristic effects like snowballs and peppercorns. The third documents materials currently available and my working process.

## What Makes Lith Development Different

Every darkroom printer understands basic development: exposed silver halide crystals reduce to metallic silver in the presence of a developing agent, with the rate depending on exposure, developer activity, temperature, and time. More exposure means faster development. Longer development means more density. The relationship is essentially linear and predictable.

Lith development violates these assumptions fundamentally. The process is autocatalytic — development accelerates itself. The more silver reduces in a given area, the faster reduction proceeds in that area. Shadows don't just develop; they explode. And while shadows race toward maximum black, highlights develop slowly, linearly, at a fraction of the pace. The result is extreme tonal separation achieved not through paper grade or contrast filtration, but through differential chemistry occurring simultaneously across the image.

This phenomenon is called infectious development, and understanding it requires looking at what happens to hydroquinone—the developing agent—as it works.

## The Semiquinone Cascade

In conventional developers, hydroquinone oxidises to quinone as it reduces silver. Quinone is essentially inert—it doesn't participate further in development. The reaction proceeds, products accumulate, and eventually the developer exhausts.

Lith development works differently because hydroquinone doesn't oxidise directly to quinone. Instead, it passes through a transient intermediate state: the semiquinone radical. This partially oxidised molecule exists only briefly, but during its short lifetime it's highly reactive—Wolfgang Moersch describes it as many times more aggressive than the original hydroquinone. The semiquinone is itself a powerful developing agent, far more active than the hydroquinone that produced it.

<!-- <figure>
    <img src="/notebook/016-LithPrinting/semiquinone_diagram.png" align="left" width="300px" style="margin:10px;" alt="Diagram showing hydroquinone to semiquinone to quinone oxidation pathway" />
    <figcaption>The semiquinone intermediate is key to infectious development. Unlike the direct oxidation pathway in conventional developers, lith chemistry passes through this highly reactive state.</figcaption>
</figure> -->

In heavily exposed areas—your shadows—many silver halide crystals begin developing simultaneously. Each developing crystal generates semiquinone. As local semiquinone concentration builds, development accelerates exponentially. The more development occurs, the faster it proceeds. Tim Rudman captured this feedback loop precisely in his foundational work on lith printing: the darker a tone becomes, the faster it develops; the faster it develops, the darker it becomes, and so it develops even faster still.

Meanwhile, in lightly exposed areas—your highlights—few crystals develop. Little semiquinone accumulates locally. Development proceeds slowly, at a pace closer to conventional linear development. The highlights creep forward while the shadows race.

This differential is the source of lith printing's characteristic look. Highlights remain soft, delicate, often warmly coloured. Shadows become dense, gritty, high-contrast. The tonal separation isn't imposed by the paper or the enlarger filtration—it emerges from the chemistry itself, from the physics of how semiquinone radicals catalyse their own production.

## Why Hydroquinone Alone

Conventional black and white developers typically combine multiple developing agents. Metol and hydroquinone (MQ developers) or phenidone and hydroquinone (PQ developers) work synergistically—the combination develops faster than either agent alone, a phenomenon called superadditivity. Most darkroom chemistry exploits this.

Lith developers use hydroquinone alone, or hydroquinone with minimal additions. The reason is precisely that semiquinone pathway. Other developing agents don't produce the same autocatalytic intermediate. Metol oxidises directly. Phenidone actually suppresses infectious development—which is why papers containing phenidone in their emulsion (some Adox batches, for instance) won't lith properly regardless of developer choice.

The hydroquinone must also be present in specific conditions. The developer needs to be highly alkaline (pH 11-12) for hydroquinone to be active, but the formulation must carefully control other components that might interfere with the semiquinone cascade.

## The Role of Sulfite and Formaldehyde

Here's where lith chemistry becomes genuinely subtle. Conventional developers contain sodium sulfite as a preservative—it scavenges oxidation products, preventing aerial oxidation and extending developer life. But sulfite also scavenges semiquinone. In a high-sulfite developer, the autocatalytic cascade never develops because the intermediate gets neutralised as fast as it forms.

Traditional lith developers solve this problem with formaldehyde. This might seem counterintuitive—formaldehyde is primarily known as a preservative and hardener, not a development modifier. Its role in lith chemistry is indirect but essential: formaldehyde binds sulfite into a stable adduct called hydroxymethylsulfonate. This effectively locks up the sulfite, preventing it from scavenging semiquinone while retaining some antioxidant protection for the developer.

The formaldehyde-bisulfite adduct is remarkably stable—reportedly many orders of magnitude more stable than alternatives like acetone-bisulfite, according to practitioner research documented in community forums. This stability explains why formaldehyde works where other aldehydes fail, and why traditional lith developers (Kodalith, the original formulations) contained it despite the health concerns. The exact chemistry remains somewhat empirical; what matters practically is that formaldehyde enables the process while other aldehydes do not.

<figure>
    <img src="/notebook/030-032-lith/lith_sea.jpeg" align="left" width="350px" style="margin:10px;" alt="Lith print of landscape showing tonal separation" />
    <figcaption>The extreme tonal separation in lith prints—soft highlights against dense shadows—emerges from the chemistry itself, not from paper grade selection.</figcaption>
</figure>

Modern formaldehyde-free developers, including the Moersch EasyLith I use, achieve similar results through different means: minimal sulfite levels, careful pH control, and formulations that simply accept shorter working life in exchange for avoiding formaldehyde entirely. This matters practically—heated formaldehyde fumes are problematic, and formaldehyde absorbs through skin. If you're working with traditional developers, ventilation isn't optional. With EasyLith or SE5 Master, health concerns diminish substantially.

## Bromide Dynamics and the Importance of Old Brown

As silver bromide crystals develop, they release bromide ions into solution. In conventional development, this bromide accumulation gradually restrains development—one reason why developers exhaust and development times extend with use.

In lith printing, bromide dynamics are more complex and more useful. Bromide restrains the infectious cascade, providing some control over the otherwise exponential acceleration. Bromide also affects image colour, shifting tones from pink-sepia toward yellow-sepia as concentration increases.

This is why experienced lith printers save their used developer. "Old Brown"—the oxidised, bromide-rich developer remaining after a printing session—isn't waste to be discarded. It's a valuable additive that improves results.

Fresh lith developer produces somewhat disappointing results: development is fast, colours are muted, the characteristic lith look is diminished. The chemistry needs to be "seasoned" with accumulated oxidation products and bromide. Adding ten to one hundred millilitres of Old Brown per litre of fresh working solution allows good results from the first print rather than sacrificing initial sheets to condition the developer.

I keep a dedicated bottle of Old Brown, topping it up after each session. The developer darkens progressively—hence the name—and develops increasingly complex chemistry that enhances the lith effect. Some practitioners maintain Old Brown stocks for months or even years, adding fresh developer as needed while preserving the accumulated character.

## Why Extreme Dilution Is Essential

Lith developers are used at dilutions that would seem absurd for conventional work. Where a typical film developer might be diluted 1:1 to 1:9, lith developers run at 1:20 to 1:40 or beyond. This isn't about economy—it's functionally necessary for the process to work.

At normal concentration, development would complete in seconds. The semiquinone cascade would fire immediately upon immersion, shadows would race to maximum density before you could react, and the entire process would be essentially uncontrollable. There would be no snatch point—just instant development.

Extreme dilution slows everything enough to allow observation and intervention. Development times of six to twelve minutes become standard. You can watch the image emerge, monitor the acceleration phase, and make decisions about when to stop. The snatch point—perhaps the most critical variable in lith printing—only exists because dilution creates the time window for it.

Wolfgang Moersch recommends 1:20 to 1:25 as a starting point with EasyLith (for instance, 20ml Part A plus 20ml Part B plus 800ml water). More exposure requires more dilution; less exposure allows stronger concentration. You can push beyond 1:30, but developer behaviour changes significantly—each additional print causes more variation, and very dilute developers may not achieve proper maximum black before exhausting.

The relationship between dilution and development time is roughly proportional. Double the dilution approximately doubles development time. This becomes a practical tool: if development is happening too fast to control, increase dilution; if prints are taking unreasonably long (more than fifteen to twenty minutes), concentrate slightly.

## The Induction Period: Patience Before the Storm

One of the most disorienting aspects of lith printing for newcomers is the induction period—the interval between immersing the paper and seeing any image at all. In conventional development, the image appears within seconds. In lith development, you might wait two to five minutes seeing essentially nothing.

This isn't a sign of problems. The induction period reflects the time required for semiquinone concentration to build to active levels. Development is occurring, but slowly and invisibly. The latent image centres are reducing silver, generating semiquinone, establishing the conditions for the cascade to come.

Then highlights emerge, faint and ghostly. Midtones follow. The image becomes recognisable but remains light, underdeveloped by conventional standards. And then—if you're watching carefully—you notice the shadows beginning to move. Development is accelerating. The cascade is engaging. From here, events proceed quickly.

The practical advice: don't panic during the induction period, and don't increase developer concentration thinking something is wrong. Patience during induction is rewarded with proper lith characteristics. Rushing—whether by strengthening developer or raising temperature—produces faster development but weaker lith effects.

## What the Chemistry Means for Practice

Understanding the semiquinone cascade, bromide dynamics, and dilution effects transforms lith printing from trial-and-error experimentation into directed practice. The chemistry explains observations that would otherwise seem arbitrary:

Why does more exposure produce lower contrast? Because heavily exposed highlights develop more, generating more semiquinone locally, reducing the differential between highlight and shadow development rates.

Why do longer development times produce cooler, grainier results? Because extended development allows silver grains to grow larger, and larger grains scatter light differently (appearing cooler) while becoming more visually distinct (grainier).

Why does Old Brown improve results? Because accumulated bromide moderates the cascade while accumulated oxidation products enhance colour.

Why must you snatch quickly once shadows start moving? Because the exponential nature of infectious development means seconds matter—the feedback loop accelerates continuously until you physically intervene.

<figure>
    <img src="/notebook/030-032-lith/lith_tampere.jpeg" align="right" width="300px" style="margin:10px;" alt="Detail showing lith grain structure" />
    <figcaption>The distinctive grain of lith printing—visible texture in the shadows—results from the uneven, explosive nature of infectious development.</figcaption>
</figure>

The chemistry also explains why lith printing requires specific papers. The emulsion must contain chlorobromide or bromide silver (not just chloride), and it must be free of incorporated developing agents like phenidone that would suppress the semiquinone pathway. Many modern papers fail one or both requirements, which is why the list of lithable papers has shrunk dramatically since the technique's heyday.

## From Understanding to Control

When Åsmund first explained infectious development during that workshop at Mörk, the mechanism made intellectual sense but felt abstract. It was only after making prints—watching that strange delayed emergence, feeling the sudden acceleration, learning through many snatched-too-early and snatched-too-late attempts—that the chemistry became real. The equations describe something you can see happening, something you learn to read and anticipate.

In the second post of this series, I'll move from chemistry to control: how exposure affects contrast (counterintuitively), what the snatch point actually looks like, how temperature changes the game, and how to manage—or encourage—the characteristic effects like snowballs and peppercorns that make lith prints distinctive.

The chemistry is foundational, but practice is where it becomes craft. Understanding why infectious development works is the beginning. Learning to work with it—to ride the cascade rather than fight it—takes time in the darkroom, prints in the tray, and the willingness to let controlled chaos produce images impossible through any other means.

---

## References

### Books

Rudman, Tim. *The Master Photographer's Lith Printing Course*. Argentum, 1998. [The foundational text on lith printing technique; establishes the conceptual framework still used today.]

Rudman, Tim. *The Photographer's Toning Book: The Definitive Guide*. Amphoto, 2002. [Comprehensive treatment of toning including lith print toning.]

### Technical Documentation

Moersch, Wolfgang. "Lithprinting Guide (Lessons 1-6)." Moersch Photochemie, revised January 2023. https://www.moersch-photochemie.de/wp-content/uploads/2023/03/Lith-Anleitung-Lessons-1-6-ENGLISH.pdf [Comprehensive technical guide to lith printing with Moersch chemistry.]

Moersch, Wolfgang. "EasyLith Technical Data Sheet." Moersch Photochemie. https://www.moersch-photochemie.de/

### Scientific Literature

Austin, J.B. "The Theory of Infectious Development." *Journal of Photographic Science* 22 (1974): 156-162. [Academic treatment of the semiquinone mechanism.]

Mason, L.F.A. *Photographic Processing Chemistry*. 2nd ed. Focal Press, 1975. [General reference on photographic chemistry including oxidation pathways.]

### Online Resources

Unblinking Eye. "Lith Printing." https://unblinkingeye.com/Articles/Lith/lith.html [Historical overview and technical discussion.]

AlternativePhotography.com. "The Lithprint Process." https://www.alternativephotography.com/the-lithprint-process/ [Accessible introduction with practical guidance.]

EMULSIVE. "A Practical Guide to Lith Printing." https://emulsive.org/articles/darkroom/darkroom-printing/a-practical-guide-to-lith-printing [Contemporary practical guide.]

### Community and Network

Nordic Analogue Network. https://www.nordicanalognetwork.com/ [Darkroom exchange residency connecting Scandinavian analog communities.]

Mörk (Finnish Darkroom Association). https://pimiotaiteilijat.fi/en/ [Community darkroom in Helsinki.]

Lith Printing Group (Facebook). [Active community for questions and print sharing.]

Photrio.com Alternative Processes Forum. https://www.photrio.com/forum/forums/alternative-processes.67/ [Technical discussions and paper compatibility research.]

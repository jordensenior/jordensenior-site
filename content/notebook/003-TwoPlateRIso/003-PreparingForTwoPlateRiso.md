---
title: "003 · From Photo to Two-Plate Riso"
image: ""
description: "Manual seperation workflow for 2-plate prints"
author: "Jorden Senior"
date: "2025-08-12"
live: true
tags: ["Risography"]
categories: ["Digital","Printmaking"]
series: ["Riso"]
aliases: ["riso-workflow-two-plate"]
toc: true
---

# From Photo to Two-Plate Riso (notes from a work-in-progress)

I’m not chasing CMYK here. Two reasons: **(1)** it burns through inks and setup, **(2)** it sands off a lot of what makes Riso feel like Riso. Two plates is a sweet spot for photos — enough tone and mood, still honest about the medium.

I don’t think in ink names while I work. I think in **plates**:

- **Cool plate** → structure / shadows / distance  
- **Warm plate** → highlights / presence / near-field  

Colour choices come later. Files stay monotone all the way through; the *only* place I write colour is the filename for the studio/tool.

---

## What I actually use

- **Affinity Photo** for separations (I prefer owning my tools)  
- **Spectrolite** for halftoning + overprint preview  
- **Uncoated paper** (preferably) with a bit of tooth  
- A local studio (for me: [**If By Magic**](http://ifbymagic.space) in Helsinki - find yours on [Stencil](https://www.stencil.wiki/atlas))

---

## The short version

1. Decide what the **cool** plate does and what the **warm** plate does.  
2. Split the photo into two monotone plates in Affinity: by colour (for colour photos) or tonal range (for B&W).  
3. Preview inks with **Recolour** / blend overlays per plate (then **turn them off** before export).  
4. (Optional) add a small **trap** to the under-plate (≈ 0.25–0.5 mm).  
5. (Optional) Halftone both plates in **Spectrolite** (pick LPI + angles).  
6. Export 600 dpi plates. Put ink names in filenames only.  
7. Proof 3–5 sheets, tweak per plate, then print the run.

---

## 0) Prep the source (boring, essential)

- Work at **final size** (300–600 dpi).  
- Clean dust/scratches now — halftones immortalise rubbish.  
- Keep some headroom in shadows/highlights; we’ll shape per plate.

---
## For colour photos: manual colour separation

The goal is two grayscale plates built from different colour regions of your image.

### My Affinity process

1. **Duplicate your image twice**: name them `PLATE_cool` and `PLATE_warm`

2. **Make each plate grayscale-looking** (but keep the doc in RGB):
   - Add a Black & White adjustment or Channel Mixer set to Monochrome
   
3. **Build masks using Select by Colour**:
   - Select → Select Sampled Colour
   - Sample the hues you want this plate to carry
   - Adjust tolerance, add more samples
   - With selection active, Cmd/Ctrl+J to copy to new layer inside the plate group
   - Repeat for other colour regions

4. **Shape each plate with Curves and Levels**:
   - Cool plate: emphasize structure and lower-mids, protect the top end
   - Warm plate: own the upper-mids and highlights, keep shadows light
   - Constrain outputs to ~8-92% (Levels output: Black 20-30, White 225-235)

> Could Spectrolite do the colour split automatically? Yes, and it's decent. But I prefer deciding which objects live on which plate.

## For black and white: tonal separation

1. **Duplicate to two plates** as before

2. **Use tonal masks**:
   - Select → Tonal Range → Shadows/Highlights
   - Or paint masks manually for more control

3. **Cool plate (structure)**: emphasize 0-70% tones, pull top end down
   
4. **Warm plate (presence)**: emphasize 30-100% tones, keep deep shadows lighter

That 30-70% overlap is where the print breathes. If midtones get muddy, reduce the overlap rather than just cranking contrast.

## Preview colours without baking them in

Everything stays monotone for export, but you want to see how plates interact:

1. Group each plate (`GROUP_PLATE_cool`, `GROUP_PLATE_warm`)
2. Add a Recolour adjustment above each group
3. Pick your intended inks to preview the overprint
4. **Turn these off before export** (seriously, I've made this mistake)

## Registration drift: add trap

Riso registration varies by 1-2mm. Plan for it:

- Pick your under-plate (usually the structure/cool plate)
- Add Layer → New Live Filter → Maximum, radius 1-2px at 300 dpi (≈0.25-0.5mm on paper)
- Optionally add Minimum (1px) to the top plate to tighten joins
- You're hiding white slivers, not drawing outlines—keep it subtle

## Halftoning in Spectrolite

Export each plate from Affinity as 8-bit grayscale TIFF at 600 dpi, then:

- **Dot shape**: Round or elliptical are safe; lines work nice on skies
- **Frequency**: 35-45 LPI for photos (coarser = softer, finer = more detail but fussier)
- **Angles**: Offset pairs like 15°/75° or 22.5°/82.5° to avoid moiré
- Use the overprint preview to check balance
- Export as TIFFs at 600 dpi
---

## Things I’m borrowing from people who do it better

### 1) Flat-tone layering (threshold / posterise)
Turn parts of a photo into **solid shapes** instead of dots. One plate can be a [thresholded shadow map](https://en.exploriso.info/exploriso/colour/separations/tonal-separation-by-setting-a-threshold-value/); the other a mid-tone map. Where they overlap you get a third tone/hue. Looks more like silkscreen; inks look richer because you’re laying flats, not pepper. 

### 2) Stochastic grain or custom textures
Swap tidy dot grids for **diffusion dither** or **bitmap textures**. Error-diffusion reads like film grain; custom patterns (stipples, scribbles, scanned paper grain) make tones feel hand-made.

### 3) Bold-plus-neutral, or no black at all
Pair one **neutral** plate (for edges/legibility) with one **bold** plate for mood — or try two colours with no black and let overlap create a “third” tone. Studios focused on photo books (e.g., Outer Space Press) lean into two-ink interpretations, aiming for quality while embracing Riso’s rough, textured character.

### 4) Design with misregistration
Plan for a **1–2 mm wobble**. Put fine linework on one plate; use the other as a forgiving fill so any offset becomes a pleasant halo. [Pip Lu (O.OO)](https://art4d.com/en/2024/05/no-magic-in-riso) frames imperfection as the source of Riso’s personality — treat drift as material, not a bug.  

### 5) Layer order as a creative tool
Dark last usually preserves detail; light last can **tint** the first pass and feel more “printed.” Test both in proofs; don’t be afraid if the “wrong” order looks more alive. [(Spectrolite’s overprint preview helps you pre-judge how layers will mix.)](https://spectrolite.app/how-to/overview/riso-ify)

### 6) Coarse screens on purpose
Big visible dots (or line screens) can be the aesthetic, not a compromise — especially for skies, seas, concrete, anything that welcomes texture. If you want that look, set a lower LPI or choose halftone shapes accordingly rather than fighting toward smooth CMYK-ish blends.


## References & further reading

- [**Outer Space Press**](https://www.outerspacepress.com/) — on “slow and calculated” Riso for photographic reproduction, embracing texture & imperfections.  
- [**O.OO — *No Magic in Riso***](https://odotoo.com/NO-MAGIC-IN-RISO) — two years of separation experiments; tritone colour charts; design with imperfection.
- [**Exploriso**](ttps://en.exploriso.info/exploriso/colour/separations/tonal-separation-by-setting-a-threshold-value/) — threshold/posterise separations for flat-tone layering.  
- [**Spectrolite**](https://spectrolite.app/how-to/overview/riso-ify) — RISO-ify overview; halftone & dithering guides; practical LPI/angle context. 




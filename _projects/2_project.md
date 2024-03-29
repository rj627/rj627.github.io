---
layout: page
title: Oblique Pulsators
description: on the hunt for roAp stars and TTPs
img:  assets/img/ttp.png
importance: 2
category: work
---

TESS's 2-minute and 20-s cadence light curves are invaluable for asteroseismology. TESS has 
facilitated the discovery of a new type of pulsating star in a binary, wherein the gravitational
field of the companion pulls the pulsations in line with the tidal axis of the binary. The
observational signatures of this include pulsation modes split by the orbital frequency that occur
at the same ``echelle phase'' (pulsation frequency `mod` orbital frequency, normalized to the orbital frequency).

I've developed a pipeline that searches the 2-minute and 20-s cadence data for these stars, and
we've found over 50 examples of these stars. I led the 
<a href="https://ui.adsabs.harvard.edu/abs/2022ApJ...928L..14J/abstract">discovery paper</a> of the first <b>evolved</b>
tidally tilted pulsator, in an subdwarf B-white dwarf binary that is a Type Ia supernova progenitor. This
pipeline also discovered the <a href="https://ui.adsabs.harvard.edu/abs/2024MNRAS.528.3378Z/abstract">first 
''tri-axial'' pulsator</a>, and has been instrumental in searches for other stars that don't necessarily
fit established asteroseismic models (e.g., <a href="https://ui.adsabs.harvard.edu/abs/2023MNRAS.521.4765K/abstract">HD 42477</a>).

My pipeline has also been able to identify a unique long-period sdB-delta Scuti binary. In the discovery paper,
we propose a novel evolutionary pathway for these long-period binaries that can explain these observations, 
and allows for intermediate-period sdB stars in binaries.

<div class="row justify-content-sm-center">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/265435_ech.png" title="Echelle for HD 265435" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sdb_dsct_sed.png" title="SED fit of HD 265435" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: A zoom in into features of the echelle showing the numerous tidally split modes in HD 265435. Right: A fit to the 
    spectral energy distribution of TIC 5724661, a potential intermediate-period sdB-delta Scuti binary.
</div>
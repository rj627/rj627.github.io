---
layout: page
title: Transient Searches
description: utilizing the TESS FFIs
importance: 1
img: assets/img/tess_overlap.png
category: work
---

TESS has a 2300 sq. deg field of view that's amenable to searching for counterparts to poorly-localized transient events, including
gamma-ray burst prompt emission and afterglows, as well as optical counterparts to gravitational-wave mergers detected by 
LIGO-Virgo-KAGRA. My primary thesis project centers on the development of a transient detection pipeline for the TESS full-frame
images, with the goal of searching for counterparts to these transients. 

The full set of transients, with the contemporaneous TESS field of view overlaid, can be found on the TGIF Web Server
<a href="https://tess.mit.edu/public/tgif/">(link)</a>. A list of all known transients 
(from the <a href="https://www.wis-tns.org/">Transient Name Server</a>)
that TESS observed can be found at <a href="https://tess.mit.edu/public/tesstransients/">here</a>.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/tess_overlap.png" title="TESS overlap with GRB 231012A" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/230307a_lc.png" title="TESS light curve of GRB 230307A" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: An overlap between the TESS field of view and the Fermi-GBM localization of the short GRB 231012A (using tools developed for
    <a href="https://ui.adsabs.harvard.edu/abs/2023ApJ...948L...3M/abstract">Mo et al. 2023</a>). Right: The TESS light curve of
    GRB 230307A, found to be associated with a binary neutron star merger, shows a clear prompt emission component followed by a 
    rising and falling afterglow (<a href="https://ui.adsabs.harvard.edu/abs/2023arXiv230805148J/abstract">Jayaraman et al. 2023</a>).
</div>

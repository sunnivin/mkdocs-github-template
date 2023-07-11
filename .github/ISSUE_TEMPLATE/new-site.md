---
name: New site
about: Request a new site to be added to the NorESM-LSP
title: 'New site request:'
labels: enhancement


---
### NB! Adding a new site still requires some manual work from a developer, so please be patient and reach out to us if you have questions. If you publish model experiments with the new site, please acknowledge this support appropriately and remember to cite the [NorESM-LSP paper](). New sites will by default be openly available like the existing sites.

### Fill in the variables below for the new site, examples provided from Adventdalen site.

Adventdalen # Full name of the new site

ADV # Site code, determines naming of the output dirs/files. Should be three capital letters, if necessary with numbers for related sites (E.g. FNS, ALP1, ALP2)

version: 1.0.0 # Generally not necessary to change - OBS! Sites with the same version must use the same .nc files

coordinates: # Geographic coordinates, decimal (WGS84)

  lat: 78.18333

  lon: 15.91667

elevation: 21 # metres above sea level [m.a.s.l.]

### Additional information about the site, to be included in the [technical documentation](https://noresmhub.github.io/noresm-land-sites-platform/land-sites/)
For example land cover characteristics, climatic conditions, ongoing projects, or available data sets.

flare-grid
==========

Flare colors for SDSS and 2MASS bands for M0-M6 dwarf stars

**For details of these data/code, consult the published paper [here](http://adsabs.harvard.edu/abs/2012ApJ...748...58D).**

This repository contains IDL code and save files to produce the relative response between SDSS and 2MASS bands for a flare on stars with spectral types ranging from M0 to M6 (`flaregrid.pro` and `flaregrid.sav`)

I have also included the extended stellar templates, from NUV to IR, for these spectral types (`mX_template.dat.gz`). The extended version of Fig 11 from the paper is below:

![](m0-m6.png?raw=true =450x)


**Notes:**

- The "IRTF" label indicates the range of the template used in the paper
- These templates span a wider wavelength range than published in the paper (Fig 11)
- These templates have not been resampled to a uniform wavelength grid, and there are gaps (e.g. around 2.5micron)
- The template files should be unpacked with gunzip on a *nix system


### See Also

- [GJ1243-Flares](https://github.com/jradavenport/GJ1243-Flares) - a catalog of 6107 Kepler flare events from GJ 1243
- [FBEYE](https://github.com/jradavenport/FBEYE) - an IDL based flare-finding suite
- [flare-fit](https://github.com/jradavenport/flare-fit) - IDL code to deconstruct complex flare events

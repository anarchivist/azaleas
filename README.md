# The Azaleas Project

Text versions of Kim Sowol's "진달래꽃" ("Azaleas") for recombination, in preparation for Unpoetry at the Frye, September 17, 2026.

This site/corpus is built using [Hugo](https://gohugo.io/) using the [Ed](https://github.com/sergeyklay/gohugo-theme-ed/) theme and deployed to Netlify. To build locally:

```bash
git clone https://github.com/anarchivist/azaleas.git
cd azaleas
hugo mod get
hugo build # make sure there are no errors
hugo serve # http://localhost:1313
```

It's pretty much a stock Hugo site with a few template overrides and the addition of a plaintext output format; that gets output to `public/txt` for feeding into cutup generators, [Argeïphones Lyre](https://akirarabelais.com/lyre/), etc.

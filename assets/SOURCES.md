# Profile artwork and logo sources

The header and affiliation cards are original, static SVG artwork created for
Xiaoyang Liu's profile. Each SVG is self-contained: no fonts, scripts, images or
other assets are fetched from third-party services. The README uses GitHub's
`#gh-dark-mode-only` and `#gh-light-mode-only` theme fragments to select artwork
for the viewer's current GitHub theme, including a manually selected theme.
The fragments are applied to the wrapping links as well as the images: GitHub's
theme styles hide the entire inactive link so it cannot leave a blank image row.
All artwork has a transparent background, so it inherits the page's actual
background, including dark theme variants. Text is bold white in dark mode and
bold black in light mode, with Microsoft YaHei and system sans-serif fallbacks.
This uses GitHub's [theme-context image fragments](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/),
which remain present in GitHub's current page styles. Unlike a plain browser
`prefers-color-scheme` image query, these selectors use GitHub's `data-color-mode`
setting; when GitHub follows the system theme, its styles use the corresponding
light or dark media query.
The affiliation destinations are preserved; the Waterloo role is Research Assistant.

## Huawei

- Source: [Simple Icons Huawei SVG](https://github.com/simple-icons/simple-icons/blob/develop/icons/huawei.svg).
- Original vector geometry is preserved; the icon is displayed in Huawei red (`#FF0000`).
- Simple Icons is released under [CC0 1.0](https://github.com/simple-icons/simple-icons/blob/develop/LICENSE.md).
- The standalone copy is `logos/huawei.svg`; the same geometry is embedded in both Huawei cards.

## University of Waterloo

- Source: the complete horizontal colour-reversed University logo served by the
  [official Cheriton School of Computer Science website](https://cs.uwaterloo.ca/).
- [Original SVG asset](https://cs.uwaterloo.ca/computer-science/profiles/uw_base_profile/modules/custom/uw_wcms_ohana/dist/images/uwaterloo-logo.svg).
- The full shield and wordmark retain their original colours, proportions and
  vector geometry, with clear space around the full logo. The standalone original
  is `logos/waterloo.svg`; the same geometry is embedded in both Waterloo cards.
  In the light card, only the wordmark is set to black, an approved wordmark
  colour in the guidelines; the shield and its white border remain unchanged.
- [University logo guidelines](https://uwaterloo.ca/brand/how-express-our-brand/waterloo-logo)
  and [official logo downloads](https://uwaterloo.ca/brand/uw-logos/university-logos/all).

Retrieved 2026-10-06. Logos remain the property of their respective owners;
their use identifies the profile owner's stated affiliations, and does not imply
that this personal profile is an official institutional page. Source-project
licensing does not grant trademark rights. No blanket licence is applied to
the University of Waterloo logo.

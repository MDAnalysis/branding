# Style Guide for MDAnalysis

## Name
When referring to the project we always capitalize as 

* ✔️ MDAnalysis

and _not_
* ✖️ ~~MDanalysis~~
* ✖️ ~~Mdanalysis~~
* ✖️ ~~mdanalysis~~
* ✖️ ~~MDANALYSIS~~

In logo art we _may_ break the name as

 MD<br/>
 Analysis


*MDAnalysis* is a proper noun when we refer to the project/organization or the library itself so it is typeset in the standard typeface of the surrounding text. It is _not_ set in `monospace` typeface.  It _may_ be set in italics (*MDAnalysis*) or another common style (e.g., sans serif) to visually distinguish software names.

* ✔️ MDAnalysis
* ✔️ *MDAnalysis*
* ✖️ ~~`MDAnalysis`~~
* ✔️ "The MDAnalysis library is one of the most used Python-based packages for the analysis of molecular dynamics simulations."

If we refer to the importable Python package of the MDAnalysis library or if we write code then we do typeset in monospace (if available):

* ✔️ "Most scripts start with `import MDAnalysis as mda`."
* ✔️ "Importing the `MDAnalysis` package is a form of linking as far as the GPL is concerned."
* ✖️ ~~"When loading the MDAnalysis package you can alias it to the short form mda."~~

## Colors
### Logo Colors

* black #000000 (RGB 000000)
* gray #808080 (RGB 808080)
* orange #FF9200 (RGB FF9200) 

### Web site colors

MDAnalysis theme

* MDAnalysis orange: #FF9200
* MDAnalysis gray:   #808080
* RTD dark gray: #343131      (from User Guide RTD dark gray)
* RTD light grey: #E6E6E6
* MDAnalysis black:  #000000
* MDAnalysis white:  #FFFFFF

### Documentation colors

* MDAnalysis orange: #FF9200 
* MDAnalysis gray: #808080
* MDAnalysis white: #FFFFFF
* MDAnalysis black: #000000
* Very light orange: #FFEBD0
* Code orange: #ca6500
* RTD dark grey: #343131
* RTD light grey: #e6e6e6

The [User Guide CSS theme](https://github.com/MDAnalysis/UserGuide/blob/develop/doc/source/_static/custom.css) has some others for coloured elements, where we needed to differentiate between notes, warnings, etc. -- they have some pastel red/orange/yellows (backgrounds) and darker red/orange/yellows (text).

## Typefaces

* The MDAnalysis logo typeface is "ZAG Bold" from https://www.dafont.com/de/zag.font (see MDAnalysis/UserGuide#11).
* We generally prefer sans serif fonts for our materials (Helvetica, Arial)

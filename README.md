# Guideline

This project for the edition of *Voyage au pays de la quatrième dimension* by Gaston de Pawlowski which is marked up with following TEI rules.

- Do not support hyphenation.
- Each newspaper's edition is described in sourceDesc with msDesc. (<u>future work</u>)
- All Chapters has `<div>` and `<head>`.
- Each paragraph has `<p>`.
- All pages is marked as `<fw type="pagenum">`.
- If words had a inccorect spell, it'd be marked as `<choice><sic></sic> <corr cert="high" resp="#dion"></corr></choice>`. This represents to `[sic]` in ordinary annotation.
- Those sentences have superscript letters. It is marked up with `[<hi rendition="superscript">]`. In the header, I define it with `<rendition>`.

- if you use this file, take care about one tag, `<fw>`, please. I marked up the text with `<fw>` tag for citing some phrases very strictly when I write a paper or something kind of documents. That is, in the point of the XML structural view, this tag means unuseful. Analyzing this text as the corpus, you delete or comment out these tags. 
  - In 1923 edition is based on Images Modernes edition. Because of its co@yright, I publish only non-tagging version concerning 1923 TEI edition.

---

This edition is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).


This work was supported by JSPS KAKENHI Grant Number 18J22570.

## FontBakery report

fontbakery version: 0.13.3





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Menaion-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- uni2044 (U+2044)</p>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[17] Menaion-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking font version fields (head and name table). <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-font-version">opentype/font_version</a></summary>
    <div>







* 🔥 **FAIL** <p>head version is &quot;2.00200&quot; while name version string (for platform 3, encoding 1) is &quot;2.1; ttfautohint (v1.8.4.7-5d5b)&quot;.</p>
 [code: mismatch]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#case-mapping">case_mapping</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+00D8: LATIN CAPITAL LETTER O WITH STROKE</td>
<td align="left">U+00F8: LATIN SMALL LETTER O WITH STROKE</td>
</tr>
<tr>
<td align="left">U+00E1: LATIN SMALL LETTER A WITH ACUTE</td>
<td align="left">U+00C1: LATIN CAPITAL LETTER A WITH ACUTE</td>
</tr>
<tr>
<td align="left">U+00E2: LATIN SMALL LETTER A WITH CIRCUMFLEX</td>
<td align="left">U+00C2: LATIN CAPITAL LETTER A WITH CIRCUMFLEX</td>
</tr>
<tr>
<td align="left">U+00E4: LATIN SMALL LETTER A WITH DIAERESIS</td>
<td align="left">U+00C4: LATIN CAPITAL LETTER A WITH DIAERESIS</td>
</tr>
<tr>
<td align="left">U+00EE: LATIN SMALL LETTER I WITH CIRCUMFLEX</td>
<td align="left">U+00CE: LATIN CAPITAL LETTER I WITH CIRCUMFLEX</td>
</tr>
<tr>
<td align="left">U+00F3: LATIN SMALL LETTER O WITH ACUTE</td>
<td align="left">U+00D3: LATIN CAPITAL LETTER O WITH ACUTE</td>
</tr>
<tr>
<td align="left">U+00F9: LATIN SMALL LETTER U WITH GRAVE</td>
<td align="left">U+00D9: LATIN CAPITAL LETTER U WITH GRAVE</td>
</tr>
<tr>
<td align="left">U+00FA: LATIN SMALL LETTER U WITH ACUTE</td>
<td align="left">U+00DA: LATIN CAPITAL LETTER U WITH ACUTE</td>
</tr>
<tr>
<td align="left">U+00FB: LATIN SMALL LETTER U WITH CIRCUMFLEX</td>
<td align="left">U+00DB: LATIN CAPITAL LETTER U WITH CIRCUMFLEX</td>
</tr>
<tr>
<td align="left">U+00FC: LATIN SMALL LETTER U WITH DIAERESIS</td>
<td align="left">U+00DC: LATIN CAPITAL LETTER U WITH DIAERESIS</td>
</tr>
<tr>
<td align="left">U+00FD: LATIN SMALL LETTER Y WITH ACUTE</td>
<td align="left">U+00DD: LATIN CAPITAL LETTER Y WITH ACUTE</td>
</tr>
<tr>
<td align="left">U+0101: LATIN SMALL LETTER A WITH MACRON</td>
<td align="left">U+0100: LATIN CAPITAL LETTER A WITH MACRON</td>
</tr>
<tr>
<td align="left">U+0103: LATIN SMALL LETTER A WITH BREVE</td>
<td align="left">U+0102: LATIN CAPITAL LETTER A WITH BREVE</td>
</tr>
<tr>
<td align="left">U+0113: LATIN SMALL LETTER E WITH MACRON</td>
<td align="left">U+0112: LATIN CAPITAL LETTER E WITH MACRON</td>
</tr>
<tr>
<td align="left">U+011B: LATIN SMALL LETTER E WITH CARON</td>
<td align="left">U+011A: LATIN CAPITAL LETTER E WITH CARON</td>
</tr>
<tr>
<td align="left">U+012D: LATIN SMALL LETTER I WITH BREVE</td>
<td align="left">U+012C: LATIN CAPITAL LETTER I WITH BREVE</td>
</tr>
<tr>
<td align="left">U+01D0: LATIN SMALL LETTER I WITH CARON</td>
<td align="left">U+01CF: LATIN CAPITAL LETTER I WITH CARON</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-license-OFL-copyright">googlefonts/license/OFL_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B8 (CEDILLA)


- 0x00BF (INVERTED QUESTION MARK)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-version-format">googlefonts/name/version_format</a></summary>
    <div>







* 🔥 **FAIL** <p>The NameID.VERSION_STRING (nameID=5) value must follow the pattern &quot;Version X.Y&quot; with X.Y greater than or equal to 1.000. The &quot;Version &quot; prefix is a recommendation given by the OpenType spec. Current version string is: &quot;2.1; ttfautohint (v1.8.4.7-5d5b)&quot;</p>
 [code: bad-version-strings]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni032A (U+032A), uni20DB (U+20DB), uniFE00 (U+FE00), uniFE01 (U+FE01), uniFE02 (U+FE02) and uniFE03 (U+FE03)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni040C	Contours detected: 3	Expected: 2

- Glyph name: uni041A	Contours detected: 2	Expected: 1

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni043A	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: uni040C	Contours detected: 3	Expected: 2

- Glyph name: uni041A	Contours detected: 2	Expected: 1

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni043A	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 564 among a set of 4 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 399:
uni00AC</p>
<p>Width = 533:
uni00D7</p>
<p>Width = 543:
uni00F7</p>
<p>Width = 910:
uni223B, uni223C</p>
<p>Width = 909:
uni223D, uni2241</p>
<p>Width = 913:
uni223E</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, old-permic, tai-le, hebrew, tifinagh, malayalam, syriac, coptic, duployan, math, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar</li>
<li>U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: try adding ethiopic</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: todhri, old-permic</li>
<li>U+0314 COMBINING REVERSED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0315 COMBINING COMMA ABOVE RIGHT: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+032A COMBINING BRIDGE BELOW: not included in any glyphset definition</li>
<li>U+033D COMBINING X ABOVE: not included in any glyphset definition</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+033F COMBINING DOUBLE OVERLINE: try adding coptic</li>
<li>U+0340 COMBINING GRAVE TONE MARK: not included in any glyphset definition</li>
<li>U+0341 COMBINING ACUTE TONE MARK: not included in any glyphset definition</li>
<li>U+0342 COMBINING GREEK PERISPOMENI: not included in any glyphset definition</li>
<li>U+0343 COMBINING GREEK KORONIS: not included in any glyphset definition</li>
<li>U+0345 COMBINING GREEK YPOGEGRAMMENI: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+0350 COMBINING RIGHT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+0351 COMBINING LEFT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+0357 COMBINING RIGHT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+035E COMBINING DOUBLE MACRON: try adding one of: todhri, caucasian-albanian, coptic</li>
<li>U+0360 COMBINING DOUBLE TILDE: not included in any glyphset definition</li>
<li>U+0361 COMBINING DOUBLE INVERTED BREVE: try adding coptic</li>
<li>U+1DC0 COMBINING DOTTED GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+1DC1 COMBINING DOTTED ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+1DC3 COMBINING SUSPENSION MARK: not included in any glyphset definition</li>
<li>U+1DCD COMBINING DOUBLE CIRCUMFLEX ABOVE: try adding coptic</li>
<li>U+1DFE COMBINING LEFT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: hanunoo, sogdian, balinese, gujarati, khmer, siddham, sundanese, syloti-nagri, masaram-gondi, manichaean, khojki, brahmi, javanese, nko, saurashtra, tibetan, mongolian, avestan, gurmukhi, modi, thai, lepcha, oriya, tamil, tai-tham, mahajani, mandaic, meetei-mayek, chakma, sharada, kharoshthi, tai-le, thaana, tifinagh, bengali, kannada, limbu, warang-citi, syriac, newa, tagbanwa, hatran, telugu, new-tai-lue, kayah-li, buginese, zanabazar-square, lao, tagalog, dogra, grantha, phags-pa, khudawadi, bhaiksuki, duployan, devanagari, gunjala-gondi, cham, kaithi, takri, buhid, pahawh-hmong, yi, tai-viet, hebrew, rejang, sinhala, tirhuta, malayalam, hanifi-rohingya, myanmar, batak, arabic, psalter-pahlavi</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: hanunoo, sogdian, balinese, gujarati, khmer, siddham, sundanese, syloti-nagri, masaram-gondi, manichaean, khojki, brahmi, javanese, nko, saurashtra, tibetan, mongolian, avestan, gurmukhi, modi, thai, lepcha, oriya, tamil, tai-tham, mahajani, mandaic, meetei-mayek, chakma, sharada, kharoshthi, tai-le, thaana, tifinagh, bengali, kannada, limbu, warang-citi, syriac, newa, tagbanwa, telugu, new-tai-lue, kayah-li, buginese, zanabazar-square, lao, tagalog, dogra, grantha, phags-pa, khudawadi, bhaiksuki, duployan, devanagari, gunjala-gondi, cham, kaithi, takri, buhid, pahawh-hmong, yi, tai-viet, hebrew, rejang, sinhala, tirhuta, malayalam, hanifi-rohingya, old-hungarian, myanmar, batak, arabic, psalter-pahlavi</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, phags-pa, nko, syriac, arabic</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, thaana, phags-pa, nko, syriac</li>
<li>U+2010 HYPHEN: try adding one of: sundanese, yi, syloti-nagri, kharoshthi, hebrew, lisu, kayah-li, armenian, coptic, sora-sompeng, arabic, kaithi, cham</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: arabic, yi, syloti-nagri</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2016 DOUBLE VERTICAL LINE: try adding math</li>
<li>U+2017 DOUBLE LOW LINE: try adding math</li>
<li>U+201B SINGLE HIGH-REVERSED-9 QUOTATION MARK: try adding adlam</li>
<li>U+201F DOUBLE HIGH-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2023 TRIANGULAR BULLET: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2031 PER TEN THOUSAND SIGN: not included in any glyphset definition</li>
<li>U+2034 TRIPLE PRIME: try adding math</li>
<li>U+2035 REVERSED PRIME: try adding math</li>
<li>U+2036 REVERSED DOUBLE PRIME: try adding math</li>
<li>U+2037 REVERSED TRIPLE PRIME: try adding math</li>
<li>U+2038 CARET: try adding math</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+203C DOUBLE EXCLAMATION MARK: try adding math</li>
<li>U+203D INTERROBANG: not included in any glyphset definition</li>
<li>U+203E OVERLINE: not included in any glyphset definition</li>
<li>U+203F UNDERTIE: not included in any glyphset definition</li>
<li>U+2040 CHARACTER TIE: try adding math</li>
<li>U+2041 CARET INSERTION POINT: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+2043 HYPHEN BULLET: try adding math</li>
<li>U+2045 LEFT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2046 RIGHT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2053 SWUNG DASH: try adding coptic</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205B FOUR DOT MARK: not included in any glyphset definition</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: old-hungarian, carian, meroitic, meroitic-hieroglyphs</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+20DB COMBINING THREE DOTS ABOVE: try adding one of: old-permic, math</li>
<li>U+20DD COMBINING ENCLOSING CIRCLE: try adding symbols</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, yi, tai-tham, math</li>
<li>U+2227 LOGICAL AND: try adding math</li>
<li>U+2228 LOGICAL OR: try adding math</li>
<li>U+223B HOMOTHETIC: try adding math</li>
<li>U+223C TILDE OPERATOR: try adding math</li>
<li>U+223D REVERSED TILDE: try adding math</li>
<li>U+223E INVERTED LAZY S: try adding math</li>
<li>U+2240 WREATH PRODUCT: try adding math</li>
<li>U+2241 NOT TILDE: try adding math</li>
<li>U+2329 LEFT-POINTING ANGLE BRACKET: try adding symbols</li>
<li>U+232A RIGHT-POINTING ANGLE BRACKET: try adding symbols</li>
<li>U+25AB WHITE SMALL SQUARE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BA BLACK RIGHT-POINTING POINTER: try adding symbols</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C4 BLACK LEFT-POINTING POINTER: try adding symbols</li>
<li>U+25C7 WHITE DIAMOND: try adding symbols</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: hanunoo, javanese, symbols, tai-tham, tifinagh, dogra, wancho, tirhuta, myanmar, gujarati, ahom, nko, gurmukhi, tamil, music, oriya, chakma, tai-le, thaana, bengali, telugu, buginese, zanabazar-square, lao, bhaiksuki, duployan, elbasan, tai-viet, rejang, bassa-vah, sogdian, canadian-aboriginal, khmer, sundanese, manichaean, khojki, marchen, armenian, tibetan, modi, sharada, kannada, limbu, syriac, tagbanwa, adlam, grantha, phags-pa, math, devanagari, buhid, miao, caucasian-albanian, hanifi-rohingya, coptic, batak, balinese, old-permic, siddham, syloti-nagri, masaram-gondi, brahmi, saurashtra, mongolian, thai, lepcha, mahajani, mandaic, meetei-mayek, kharoshthi, mende-kikakui, warang-citi, newa, new-tai-lue, kayah-li, osage, tagalog, khudawadi, kaithi, gunjala-gondi, cham, takri, pahawh-hmong, yi, hebrew, sinhala, malayalam, psalter-pahlavi, soyombo</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
<li>U+2626 ORTHODOX CROSS: try adding symbols</li>
<li>U+271A HEAVY GREEK CROSS: try adding symbols</li>
<li>U+2720 MALTESE CROSS: try adding symbols</li>
<li>U+2722 FOUR TEARDROP-SPOKED ASTERISK: try adding symbols</li>
<li>U+2734 EIGHT POINTED BLACK STAR: try adding symbols</li>
<li>U+274B HEAVY EIGHT TEARDROP-SPOKED PROPELLER ASTERISK: try adding symbols</li>
<li>U+2758 LIGHT VERTICAL BAR: try adding symbols</li>
<li>U+2E26 LEFT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E27 RIGHT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E46 INVERTED LOW KAVYKA WITH KAVYKA ABOVE: not included in any glyphset definition</li>
<li>U+2E47 LOW KAVYKA: not included in any glyphset definition</li>
<li>U+2E48 LOW KAVYKA WITH DOT: not included in any glyphset definition</li>
<li>U+2E49 DOUBLE STACKED COMMA: not included in any glyphset definition</li>
<li>U+E001 : not included in any glyphset definition</li>
<li>U+E003 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+E020 : not included in any glyphset definition</li>
<li>U+E021 : not included in any glyphset definition</li>
<li>U+E024 : not included in any glyphset definition</li>
<li>U+E025 : not included in any glyphset definition</li>
<li>U+E026 : not included in any glyphset definition</li>
<li>U+E029 : not included in any glyphset definition</li>
<li>U+E02A : not included in any glyphset definition</li>
<li>U+E02B : not included in any glyphset definition</li>
<li>U+E02C : not included in any glyphset definition</li>
<li>U+E02D : not included in any glyphset definition</li>
<li>U+E02E : not included in any glyphset definition</li>
<li>U+E030 : not included in any glyphset definition</li>
<li>U+E033 : not included in any glyphset definition</li>
<li>U+E034 : not included in any glyphset definition</li>
<li>U+E2F1 : not included in any glyphset definition</li>
<li>U+E5EF : not included in any glyphset definition</li>
<li>U+E5F0 : not included in any glyphset definition</li>
<li>U+E60F : not included in any glyphset definition</li>
<li>U+E612 : not included in any glyphset definition</li>
<li>U+E6CA : not included in any glyphset definition</li>
<li>U+E6DB : not included in any glyphset definition</li>
<li>U+E700 : not included in any glyphset definition</li>
<li>U+E70A : not included in any glyphset definition</li>
<li>U+E743 : not included in any glyphset definition</li>
<li>U+E748 : not included in any glyphset definition</li>
<li>U+E74B : not included in any glyphset definition</li>
<li>U+E751 : not included in any glyphset definition</li>
<li>U+E7C0 : not included in any glyphset definition</li>
<li>U+E7CB : not included in any glyphset definition</li>
<li>U+E7E0 : not included in any glyphset definition</li>
<li>U+E7E1 : not included in any glyphset definition</li>
<li>U+E7E3 : not included in any glyphset definition</li>
<li>U+E7EA : not included in any glyphset definition</li>
<li>U+E800 : not included in any glyphset definition</li>
<li>U+E809 : not included in any glyphset definition</li>
<li>U+E811 : not included in any glyphset definition</li>
<li>U+E81A : not included in any glyphset definition</li>
<li>U+E81B : not included in any glyphset definition</li>
<li>U+E81C : not included in any glyphset definition</li>
<li>U+E92A : not included in any glyphset definition</li>
<li>U+E92B : not included in any glyphset definition</li>
<li>U+E92C : not included in any glyphset definition</li>
<li>U+E92F : not included in any glyphset definition</li>
<li>U+ECE0 : not included in any glyphset definition</li>
<li>U+ECE1 : not included in any glyphset definition</li>
<li>U+ECE2 : not included in any glyphset definition</li>
<li>U+ECE3 : not included in any glyphset definition</li>
<li>U+ECE4 : not included in any glyphset definition</li>
<li>U+ECE5 : not included in any glyphset definition</li>
<li>U+ECE6 : not included in any glyphset definition</li>
<li>U+ECE7 : not included in any glyphset definition</li>
<li>U+EDE0 : not included in any glyphset definition</li>
<li>U+FE00 VARIATION SELECTOR-1: try adding one of: manichaean, yi, phags-pa</li>
<li>U+FE01 VARIATION SELECTOR-2: not included in any glyphset definition</li>
<li>U+FE02 VARIATION SELECTOR-3: not included in any glyphset definition</li>
<li>U+FE03 VARIATION SELECTOR-4: not included in any glyphset definition</li>
<li>U+FE26 COMBINING CONJOINING MACRON: try adding one of: caucasian-albanian, coptic</li>
<li>U+1D000 BYZANTINE MUSICAL SYMBOL PSILI: try adding music</li>
<li>U+1D001 BYZANTINE MUSICAL SYMBOL DASEIA: try adding music</li>
<li>U+1D002 BYZANTINE MUSICAL SYMBOL PERISPOMENI: try adding music</li>
<li>U+1D003 BYZANTINE MUSICAL SYMBOL OXEIA EKFONITIKON: try adding music</li>
<li>U+1D004 BYZANTINE MUSICAL SYMBOL OXEIA DIPLI: try adding music</li>
<li>U+1D005 BYZANTINE MUSICAL SYMBOL VAREIA EKFONITIKON: try adding music</li>
<li>U+1D006 BYZANTINE MUSICAL SYMBOL VAREIA DIPLI: try adding music</li>
<li>U+1D007 BYZANTINE MUSICAL SYMBOL KATHISTI: try adding music</li>
<li>U+1D008 BYZANTINE MUSICAL SYMBOL SYRMATIKI: try adding music</li>
<li>U+1D009 BYZANTINE MUSICAL SYMBOL PARAKLITIKI: try adding music</li>
<li>U+1D00A BYZANTINE MUSICAL SYMBOL YPOKRISIS: try adding music</li>
<li>U+1D00B BYZANTINE MUSICAL SYMBOL YPOKRISIS DIPLI: try adding music</li>
<li>U+1D00C BYZANTINE MUSICAL SYMBOL KREMASTI: try adding music</li>
<li>U+1D00D BYZANTINE MUSICAL SYMBOL APESO EKFONITIKON: try adding music</li>
<li>U+1D00F BYZANTINE MUSICAL SYMBOL TELEIA: try adding music</li>
<li>U+1D010 BYZANTINE MUSICAL SYMBOL KENTIMATA: try adding music</li>
<li>U+1D011 BYZANTINE MUSICAL SYMBOL APOSTROFOS: try adding music</li>
<li>U+1D012 BYZANTINE MUSICAL SYMBOL APOSTROFOS DIPLI: try adding music</li>
<li>U+1D013 BYZANTINE MUSICAL SYMBOL SYNEVMA: try adding music</li>
<li>U+1D014 BYZANTINE MUSICAL SYMBOL THITA: try adding music</li>
<li>U+1F540 CIRCLED CROSS POMMEE: try adding symbols</li>
<li>U+1F541 CROSS POMMEE WITH HALF-CIRCLE BELOW: try adding symbols</li>
<li>U+1F542 CROSS POMMEE: try adding symbols</li>
<li>U+1F543 NOTCHED LEFT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F544 NOTCHED RIGHT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F545 SYMBOL FOR MARKS CHAPTER: try adding symbols</li>
<li>U+1F908 DOWNWARD FACING HOOK: try adding symbols</li>
<li>U+1F909 DOWNWARD FACING NOTCHED HOOK: try adding symbols</li>
<li>U+1F90A DOWNWARD FACING HOOK WITH DOT: try adding symbols</li>
<li>U+1F90B DOWNWARD FACING NOTCHED HOOK WITH DOT: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>glagolitic</code>, <code>greek</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ i̍ i̓ j̀ j́ j̃ j̄ j̈ j̑ і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ì í ĩ ī i̅ i̇ ỉ i̎ ȉ ȋ i̒ i̔ i̽ i̾ i̿ i͂ i͐ i͑ i͗ i҃</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* u1D009 (U+1D009): L&lt;&lt;124.0,648.0&gt;--&lt;164.0,658.0&gt;&gt; -&gt; L&lt;&lt;164.0,658.0&gt;--&lt;220.0,675.0&gt;&gt;

* u1E00F (U+1E00F): L&lt;&lt;-87.0,793.0&gt;--&lt;18.0,792.0&gt;&gt; -&gt; L&lt;&lt;18.0,792.0&gt;--&lt;136.0,792.0&gt;&gt;

* uni004B (U+004B): L&lt;&lt;499.0,568.0&gt;--&lt;400.0,468.0&gt;&gt; -&gt; L&lt;&lt;400.0,468.0&gt;--&lt;299.0,367.0&gt;&gt;

* uni0103 (U+0103): L&lt;&lt;134.0,376.0&gt;--&lt;135.0,348.0&gt;&gt; -&gt; L&lt;&lt;135.0,348.0&gt;--&lt;135.0,346.0&gt;&gt;

* uni0103 (U+0103): L&lt;&lt;134.0,379.0&gt;--&lt;134.0,376.0&gt;&gt; -&gt; L&lt;&lt;134.0,376.0&gt;--&lt;135.0,348.0&gt;&gt;

* uni035E (U+035E): L&lt;&lt;-359.0,672.0&gt;--&lt;247.0,671.0&gt;&gt; -&gt; L&lt;&lt;247.0,671.0&gt;--&lt;327.0,671.0&gt;&gt;

* uni03B3 (U+03B3): L&lt;&lt;314.0,281.0&gt;--&lt;314.0,275.0&gt;&gt; -&gt; L&lt;&lt;314.0,275.0&gt;--&lt;305.0,162.0&gt;&gt;

* uni04220420 (U+E811): L&lt;&lt;467.0,12.0&gt;--&lt;465.0,92.0&gt;&gt; -&gt; L&lt;&lt;465.0,92.0&gt;--&lt;465.0,544.0&gt;&gt;

* uni04220420 (U+E811): L&lt;&lt;584.0,15.0&gt;--&lt;576.0,-385.0&gt;&gt; -&gt; L&lt;&lt;576.0,-385.0&gt;--&lt;576.0,-386.0&gt;&gt;

* uni0440 (U+0440): L&lt;&lt;125.0,-2.0&gt;--&lt;117.0,-411.0&gt;&gt; -&gt; L&lt;&lt;117.0,-411.0&gt;--&lt;117.0,-412.0&gt;&gt;

* uni04420440 (U+E7E3): L&lt;&lt;387.0,12.0&gt;--&lt;385.0,92.0&gt;&gt; -&gt; L&lt;&lt;385.0,92.0&gt;--&lt;385.0,554.0&gt;&gt;

* uni203C (U+203C): L&lt;&lt;112.0,178.0&gt;--&lt;85.0,557.0&gt;&gt; -&gt; L&lt;&lt;85.0,557.0&gt;--&lt;85.0,716.0&gt;&gt;

* uni203C (U+203C): L&lt;&lt;194.0,716.0&gt;--&lt;194.0,557.0&gt;&gt; -&gt; L&lt;&lt;194.0,557.0&gt;--&lt;169.0,178.0&gt;&gt;

* uni203C (U+203C): L&lt;&lt;305.0,178.0&gt;--&lt;278.0,557.0&gt;&gt; -&gt; L&lt;&lt;278.0,557.0&gt;--&lt;278.0,716.0&gt;&gt;

* uni203C (U+203C): L&lt;&lt;387.0,716.0&gt;--&lt;387.0,557.0&gt;&gt; -&gt; L&lt;&lt;387.0,557.0&gt;--&lt;362.0,178.0&gt;&gt;

* uni203D (U+203D): L&lt;&lt;244.0,176.0&gt;--&lt;244.0,257.0&gt;&gt; -&gt; L&lt;&lt;244.0,257.0&gt;--&lt;223.0,557.0&gt;&gt;

* uni203D (U+203D): L&lt;&lt;244.0,257.0&gt;--&lt;223.0,557.0&gt;&gt; -&gt; L&lt;&lt;223.0,557.0&gt;--&lt;223.0,634.0&gt;&gt;

* uni203D (U+203D): L&lt;&lt;332.0,636.0&gt;--&lt;332.0,557.0&gt;&gt; -&gt; L&lt;&lt;332.0,557.0&gt;--&lt;320.0,380.0&gt;&gt;

* uni2C3E (U+2C3E): L&lt;&lt;369.0,173.0&gt;--&lt;369.0,148.0&gt;&gt; -&gt; L&lt;&lt;369.0,148.0&gt;--&lt;370.0,137.0&gt;&gt;

* uni2C3F (U+2C3F): L&lt;&lt;144.0,463.0&gt;--&lt;320.0,466.0&gt;&gt; -&gt; L&lt;&lt;320.0,466.0&gt;--&lt;510.0,466.0&gt;&gt;

* uni2DEC (U+2DEC): L&lt;&lt;-27.0,581.0&gt;--&lt;-32.0,315.0&gt;&gt; -&gt; L&lt;&lt;-32.0,315.0&gt;--&lt;-32.0,314.0&gt;&gt;

* uniA65E (U+A65E): L&lt;&lt;386.0,367.0&gt;--&lt;328.0,281.0&gt;&gt; -&gt; L&lt;&lt;328.0,281.0&gt;--&lt;214.0,79.0&gt;&gt;

* uniA65F (U+A65F): L&lt;&lt;592.0,70.0&gt;--&lt;502.0,177.0&gt;&gt; -&gt; L&lt;&lt;502.0,177.0&gt;--&lt;460.0,233.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni1F8D (U+1F8D): B&lt;&lt;354.0,-50.0&gt;-&lt;363.0,-50.0&gt;-&lt;365.0,-60.0&gt;&gt;/B&lt;&lt;365.0,-60.0&gt;-&lt;364.0,-56.0&gt;-&lt;361.0,-56.0&gt;&gt; = 2.726310993906212

* uni1F8E (U+1F8E): B&lt;&lt;354.0,-50.0&gt;-&lt;363.0,-50.0&gt;-&lt;365.0,-60.0&gt;&gt;/B&lt;&lt;365.0,-60.0&gt;-&lt;364.0,-56.0&gt;-&lt;361.0,-56.0&gt;&gt; = 2.726310993906212

* uni2C08 (U+2C08): B&lt;&lt;384.5,301.0&gt;-&lt;382.0,308.0&gt;-&lt;382.0,310.0&gt;&gt;/L&lt;&lt;382.0,310.0&gt;--&lt;374.0,261.0&gt;&gt; = 9.272601777200284

* uni2C0E (U+2C0E): L&lt;&lt;606.0,258.0&gt;--&lt;597.0,238.0&gt;&gt;/B&lt;&lt;597.0,238.0&gt;-&lt;605.0,250.0&gt;-&lt;632.5,255.0&gt;&gt; = 9.462322208025613

* uni2C1B (U+2C1B): B&lt;&lt;239.0,326.0&gt;-&lt;248.0,334.0&gt;-&lt;263.0,336.0&gt;&gt;/L&lt;&lt;263.0,336.0&gt;--&lt;104.0,336.0&gt;&gt; = 7.594643368591447

* uni2C25 (U+2C25): B&lt;&lt;556.5,188.5&gt;-&lt;553.0,229.0&gt;-&lt;548.0,263.0&gt;&gt;/B&lt;&lt;548.0,263.0&gt;-&lt;548.0,262.0&gt;-&lt;545.5,259.5&gt;&gt; = 8.365886124032546

* uni2C28 (U+2C28): B&lt;&lt;330.0,359.0&gt;-&lt;332.0,376.0&gt;-&lt;340.0,377.0&gt;&gt;/B&lt;&lt;340.0,377.0&gt;-&lt;284.0,377.0&gt;-&lt;230.0,383.5&gt;&gt; = 7.125016348901757

* uni2C58 (U+2C58): B&lt;&lt;243.5,248.0&gt;-&lt;245.0,260.0&gt;-&lt;251.0,261.0&gt;&gt;/B&lt;&lt;251.0,261.0&gt;-&lt;184.0,261.0&gt;-&lt;130.5,273.0&gt;&gt; = 9.462322208025613

* uniECE7 (U+ECE7): B&lt;&lt;195.0,298.0&gt;-&lt;173.0,300.0&gt;-&lt;150.0,304.0&gt;&gt;/L&lt;&lt;150.0,304.0&gt;--&lt;153.0,304.0&gt;&gt; = 9.865806943084365
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* uni032A (U+032A): L&lt;&lt;-351.0,-56.0&gt;--&lt;-350.0,-188.0&gt;&gt;

* uni032A (U+032A): L&lt;&lt;-407.0,2.0&gt;--&lt;-76.0,3.0&gt;&gt;

* uni035E (U+035E): L&lt;&lt;-359.0,672.0&gt;--&lt;247.0,671.0&gt;&gt;

* uni0448 (U+0448): L&lt;&lt;328.0,433.0&gt;--&lt;538.0,434.0&gt;&gt;

* uni2C2E (U+2C2E): L&lt;&lt;594.0,668.0&gt;--&lt;734.0,669.0&gt;&gt;

* uni2C33 (U+2C33): L&lt;&lt;170.0,0.0&gt;--&lt;52.0,1.0&gt;&gt;

* uni2C3A (U+2C3A): L&lt;&lt;456.0,433.0&gt;--&lt;262.0,434.0&gt;&gt;

* uni2C5E (U+2C5E): L&lt;&lt;483.0,459.0&gt;--&lt;601.0,460.0&gt;&gt;

* uni2DF1 (U+2DF1): L&lt;&lt;80.0,692.0&gt;--&lt;79.0,575.0&gt;&gt;

* uniA69A (U+A69A): L&lt;&lt;188.0,342.0&gt;--&lt;336.0,343.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 6 | 12 | 107 | 7 | 104 | 0 | 
| 0% | 0% | 3% | 5% | 45% | 3% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG

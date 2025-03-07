## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[19] SolenneNova.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 816, but got 811 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (1638) and hhea ascent (2097) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-glyphs">whitespace_glyphs</a></summary>
    <div>







* 🔥 **FAIL** <p>Whitespace glyph missing for codepoint 0x00A0.</p>
 [code: missing-whitespace-glyph-0x00A0]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check family name for GF Guide compliance. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-family-name-compliance">googlefonts/family_name_compliance</a></summary>
    <div>







* 🔥 **FAIL** <p>&quot;SolenneNova&quot; is a CamelCased name. To solve this, simply use spaces instead in the font name.</p>
 [code: camelcase]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Web Designer (c) 2025, All rights reserved&quot;</p>
 [code: bad-notice-format]



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
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;SolenneNova-Book.ttf. Got SolenneNova.ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>SolenneNova</strong></td>
<td align="left"><strong>SolenneNova Book</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left"><strong>SolenneNova Book</strong></td>
<td align="left"><strong>SolenneNova Book Regular</strong></td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>SolenneNova</strong></td>
<td align="left"><strong>SolenneNovaBook-Regular</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>SolenneNova</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Book</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



* ⚠️ **WARN** <p>Regular missing from full name</p>
 [code: lacks-regular]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A0 (NO-BREAK SPACE)


- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x00A2 (CENT SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A7 (SECTION SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AB (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B0 (DEGREE SIGN)


- 0x00B4 (ACUTE ACCENT)


- 0x00B6 (PILCROW SIGN)


- 0x00B7 (MIDDLE DOT)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00BB (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00BF (INVERTED QUESTION MARK)


- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


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


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


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


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


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


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


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


- 0x2013 (EN DASH)


- 0x2014 (EM DASH)


- 0x2018 (LEFT SINGLE QUOTATION MARK)


- 0x2019 (RIGHT SINGLE QUOTATION MARK)


- 0x201A (SINGLE LOW-9 QUOTATION MARK)


- 0x201C (LEFT DOUBLE QUOTATION MARK)


- 0x201D (RIGHT DOUBLE QUOTATION MARK)


- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


- 0x2022 (BULLET)


- 0x2026 (HORIZONTAL ELLIPSIS)


- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;184&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>hhea.lineGap is &quot;184&quot; it should be 0</p>
 [code: bad-hhea.lineGap]



* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.509765625x (3092)</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: A	Contours detected: 3	Expected: 2

- Glyph name: G	Contours detected: 2	Expected: 1

- Glyph name: H	Contours detected: 3	Expected: 1

- Glyph name: L	Contours detected: 3	Expected: 1

- Glyph name: N	Contours detected: 2	Expected: 1

- Glyph name: Q	Contours detected: 1	Expected: 2

- Glyph name: R	Contours detected: 3	Expected: 1 or 2

- Glyph name: S	Contours detected: 2	Expected: 1

- Glyph name: Z	Contours detected: 3	Expected: 1

- Glyph name: d	Contours detected: 3	Expected: 2

- Glyph name: f	Contours detected: 3	Expected: 1

- Glyph name: h	Contours detected: 2	Expected: 1

- Glyph name: j	Contours detected: 3	Expected: 2

- Glyph name: k	Contours detected: 3	Expected: 1 or 2

- Glyph name: l	Contours detected: 2	Expected: 1

- Glyph name: q	Contours detected: 3	Expected: 2

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 2	Expected: 1

- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: z	Contours detected: 2	Expected: 1

- Glyph name: A	Contours detected: 3	Expected: 2

- Glyph name: G	Contours detected: 2	Expected: 1

- Glyph name: H	Contours detected: 3	Expected: 1

- Glyph name: L	Contours detected: 3	Expected: 1

- Glyph name: N	Contours detected: 2	Expected: 1

- Glyph name: Q	Contours detected: 1	Expected: 2

- Glyph name: R	Contours detected: 3	Expected: 1 or 2

- Glyph name: S	Contours detected: 2	Expected: 1

- Glyph name: Z	Contours detected: 3	Expected: 1

- Glyph name: d	Contours detected: 3	Expected: 2

- Glyph name: f	Contours detected: 3	Expected: 1

- Glyph name: h	Contours detected: 2	Expected: 1

- Glyph name: j	Contours detected: 3	Expected: 2

- Glyph name: k	Contours detected: 3	Expected: 1 or 2

- Glyph name: l	Contours detected: 2	Expected: 1

- Glyph name: q	Contours detected: 3	Expected: 2

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 2	Expected: 1

- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: z	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 767 among a set of 1 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 619:
less</p>
<p>Width = 828:
equal</p>
<p>Width = 697:
greater</p>
 [code: width-outliers]



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
<li>U+0000 : try adding one of: cham, garay, old-persian, hanunoo, tirhuta, kawi, tagbanwa, inscriptional-pahlavi, kirat-rai, palmyrene, cherokee, soyombo, tangut, masaram-gondi, balinese, lisu, armenian, bengali, saurashtra, hatran, signwriting, batak, tai-viet, ahom, kaithi, tifinagh, ugaritic, nyiakeng-puachue-hmong, anatolian-hieroglyphs, lepcha, buhid, symbols2, wancho, tai-le, modi, gurmukhi, makasar, syloti-nagri, symbols, elymaic, kharoshthi, pau-cin-hau, arabic, thai, toto, grantha, hebrew, indic-siyaq-numbers, nandinagari, music, old-permic, kayah-li, linear-a, znamenny, inscriptional-parthian, meetei-mayek, coptic, old-hungarian, tamil-supplement, imperial-aramaic, old-north-arabian, osage, avestan, nko, sinhala, greek-ext, malayalam, yezidi, cyrillic-ext, bassa-vah, khitan-small-script, kana-extended, javanese, brahmi, new-tai-lue, devanagari, cuneiform, deseret, khojki, lao, chinese-hongkong, cypriot, mayan-numerals, thaana, mro, ol-chiki, khudawadi, ethiopic, caucasian-albanian, adlam, syriac, phags-pa, chinese-simplified, old-south-arabian, todhri, bamum, lycian, yi, multani, duployan, oriya, georgian, cypro-minoan, braille, elbasan, gujarati, gothic, egyptian-hieroglyphs, marchen, psalter-pahlavi, myanmar, carian, sogdian, kannada, latin, hanifi-rohingya, limbu, runic, vietnamese, chorasmian, nushu, shavian, takri, vai, warang-citi, tai-tham, pahawh-hmong, latin-ext, cyrillic, bhaiksuki, tangsa, japanese, greek, sunuwar, mongolian, linear-b, miao, dives-akuru, meroitic, meroitic-hieroglyphs, old-sogdian, zanabazar-square, nabataean, ogham, buginese, chinese-traditional, gurung-khema, ottoman-siyaq-numbers, ol-onal, samaritan, manichaean, telugu, old-turkic, sharada, meroitic-cursive, phoenician, vithkuqi, lydian, medefaidrin, siddham, sundanese, mandaic, mahajani, korean, math, rejang, osmanya, tibetan, newa, tamil, gunjala-gondi, glagolitic, tagalog, nag-mundari, dogra, old-uyghur, canadian-aboriginal, mende-kikakui, chakma, tulu-tigalari, old-italic, sora-sompeng</li>
<li>U+000D : try adding one of: cham, garay, old-persian, hanunoo, tirhuta, kawi, tagbanwa, inscriptional-pahlavi, kirat-rai, palmyrene, cherokee, soyombo, tangut, masaram-gondi, balinese, lisu, armenian, bengali, saurashtra, hatran, signwriting, batak, tai-viet, ahom, kaithi, tifinagh, ugaritic, nyiakeng-puachue-hmong, anatolian-hieroglyphs, lepcha, buhid, symbols2, wancho, tai-le, modi, gurmukhi, makasar, syloti-nagri, symbols, elymaic, kharoshthi, pau-cin-hau, arabic, thai, toto, grantha, hebrew, indic-siyaq-numbers, nandinagari, music, old-permic, kayah-li, linear-a, znamenny, inscriptional-parthian, meetei-mayek, coptic, old-hungarian, tamil-supplement, imperial-aramaic, old-north-arabian, osage, avestan, nko, sinhala, greek-ext, malayalam, yezidi, cyrillic-ext, bassa-vah, khitan-small-script, kana-extended, javanese, brahmi, new-tai-lue, devanagari, cuneiform, deseret, khojki, lao, chinese-hongkong, cypriot, mayan-numerals, thaana, mro, ol-chiki, khudawadi, ethiopic, caucasian-albanian, adlam, syriac, phags-pa, chinese-simplified, old-south-arabian, todhri, bamum, lycian, yi, multani, duployan, oriya, georgian, cypro-minoan, braille, elbasan, gujarati, gothic, egyptian-hieroglyphs, marchen, psalter-pahlavi, myanmar, carian, sogdian, kannada, latin, hanifi-rohingya, limbu, runic, vietnamese, chorasmian, nushu, shavian, takri, vai, warang-citi, tai-tham, pahawh-hmong, latin-ext, cyrillic, bhaiksuki, tangsa, japanese, greek, sunuwar, mongolian, linear-b, miao, dives-akuru, meroitic, meroitic-hieroglyphs, old-sogdian, zanabazar-square, nabataean, ogham, buginese, chinese-traditional, gurung-khema, ottoman-siyaq-numbers, ol-onal, samaritan, manichaean, telugu, old-turkic, sharada, meroitic-cursive, phoenician, vithkuqi, lydian, medefaidrin, siddham, sundanese, mandaic, mahajani, korean, math, rejang, osmanya, tibetan, newa, tamil, gunjala-gondi, glagolitic, tagalog, nag-mundari, dogra, old-uyghur, canadian-aboriginal, mende-kikakui, chakma, tulu-tigalari, old-italic, sora-sompeng</li>
<li>U+0020 SPACE: try adding one of: cham, garay, old-persian, hanunoo, tirhuta, kawi, tagbanwa, inscriptional-pahlavi, kirat-rai, palmyrene, cherokee, soyombo, tangut, masaram-gondi, balinese, lisu, armenian, bengali, saurashtra, hatran, signwriting, batak, tai-viet, ahom, kaithi, tifinagh, ugaritic, nyiakeng-puachue-hmong, anatolian-hieroglyphs, lepcha, buhid, symbols2, wancho, tai-le, modi, gurmukhi, makasar, syloti-nagri, symbols, elymaic, kharoshthi, pau-cin-hau, arabic, thai, toto, grantha, hebrew, indic-siyaq-numbers, nandinagari, music, old-permic, kayah-li, linear-a, znamenny, inscriptional-parthian, meetei-mayek, coptic, old-hungarian, tamil-supplement, imperial-aramaic, old-north-arabian, osage, avestan, nko, sinhala, greek-ext, malayalam, yezidi, cyrillic-ext, bassa-vah, khitan-small-script, kana-extended, javanese, brahmi, new-tai-lue, devanagari, cuneiform, deseret, khojki, lao, chinese-hongkong, cypriot, mayan-numerals, thaana, mro, ol-chiki, khudawadi, ethiopic, caucasian-albanian, adlam, syriac, phags-pa, chinese-simplified, old-south-arabian, todhri, bamum, lycian, yi, multani, duployan, oriya, georgian, cypro-minoan, braille, elbasan, gujarati, gothic, egyptian-hieroglyphs, marchen, psalter-pahlavi, myanmar, carian, sogdian, kannada, latin, hanifi-rohingya, limbu, runic, vietnamese, chorasmian, nushu, shavian, takri, vai, warang-citi, tai-tham, pahawh-hmong, latin-ext, cyrillic, bhaiksuki, tangsa, japanese, greek, sunuwar, mongolian, linear-b, miao, dives-akuru, meroitic, meroitic-hieroglyphs, old-sogdian, zanabazar-square, nabataean, ogham, buginese, chinese-traditional, gurung-khema, ottoman-siyaq-numbers, ol-onal, samaritan, manichaean, telugu, old-turkic, sharada, meroitic-cursive, phoenician, vithkuqi, lydian, medefaidrin, siddham, sundanese, mandaic, mahajani, korean, math, rejang, osmanya, tibetan, newa, tamil, gunjala-gondi, glagolitic, tagalog, nag-mundari, dogra, old-uyghur, canadian-aboriginal, mende-kikakui, chakma, tulu-tigalari, old-italic, sora-sompeng</li>
<li>U+0021 EXCLAMATION MARK: try adding one of: cham, gunjala-gondi, latin, mongolian, math, thaana, masaram-gondi, adlam, syriac</li>
<li>U+0022 QUOTATION MARK: try adding one of: cham, latin, mongolian, wancho, math, masaram-gondi, adlam</li>
<li>U+0023 NUMBER SIGN: try adding one of: symbols, adlam, math, latin</li>
<li>U+0024 DOLLAR SIGN: try adding one of: adlam, math, latin</li>
<li>U+0025 PERCENT SIGN: try adding one of: latin, adlam, math, masaram-gondi, gunjala-gondi</li>
<li>U+0026 AMPERSAND: try adding one of: adlam, math, latin</li>
<li>U+0027 APOSTROPHE: try adding one of: cham, gunjala-gondi, latin, wancho, math, warang-citi, masaram-gondi, adlam</li>
<li>U+0028 LEFT PARENTHESIS: try adding one of: cham, gunjala-gondi, latin, mongolian, wancho, math, thaana, masaram-gondi, adlam, syriac</li>
<li>U+0029 RIGHT PARENTHESIS: try adding one of: cham, gunjala-gondi, latin, mongolian, wancho, math, thaana, masaram-gondi, adlam, syriac</li>
<li>U+002A ASTERISK: try adding one of: latin, adlam, math, symbols, masaram-gondi, gunjala-gondi, syriac</li>
<li>U+002B PLUS SIGN: try adding one of: latin, adlam, math, masaram-gondi, gunjala-gondi, syriac</li>
<li>U+002C COMMA: try adding one of: cham, gunjala-gondi, latin, nushu, wancho, math, coptic, masaram-gondi, adlam, thaana</li>
<li>U+002D HYPHEN-MINUS: try adding one of: cham, kharoshthi, mongolian, hebrew, syriac, adlam, kayah-li, coptic, masaram-gondi, lisu, armenian, sundanese, math, gunjala-gondi, kaithi, latin, nushu, wancho, sora-sompeng</li>
<li>U+002E FULL STOP: try adding one of: avestan, gunjala-gondi, cham, latin, nushu, wancho, math, thaana, coptic, masaram-gondi, adlam, syriac</li>
<li>U+002F SOLIDUS: try adding one of: cham, gunjala-gondi, latin, wancho, math, masaram-gondi, adlam, syriac</li>
<li>U+0030 DIGIT ZERO: try adding one of: symbols, nushu, math, latin</li>
<li>U+0031 DIGIT ONE: try adding one of: symbols, nushu, math, latin</li>
<li>U+0032 DIGIT TWO: try adding one of: symbols, nushu, math, latin</li>
<li>U+0033 DIGIT THREE: try adding one of: symbols, nushu, math, latin</li>
<li>U+0034 DIGIT FOUR: try adding one of: symbols, nushu, math, latin</li>
<li>U+0035 DIGIT FIVE: try adding one of: symbols, nushu, math, latin</li>
<li>U+0036 DIGIT SIX: try adding one of: symbols, nushu, math, latin</li>
<li>U+0037 DIGIT SEVEN: try adding one of: symbols, nushu, math, latin</li>
<li>U+0038 DIGIT EIGHT: try adding one of: symbols, nushu, math, latin</li>
<li>U+0039 DIGIT NINE: try adding one of: symbols, nushu, math, latin</li>
<li>U+003A COLON: try adding one of: cham, gunjala-gondi, latin, math, meroitic, thaana, coptic, masaram-gondi, adlam, syriac</li>
<li>U+003B SEMICOLON: try adding one of: cham, latin, math, coptic, masaram-gondi, adlam, thaana</li>
<li>U+003C LESS-THAN SIGN: try adding one of: latin, adlam, math, masaram-gondi, gunjala-gondi</li>
<li>U+003D EQUALS SIGN: try adding one of: latin, adlam, math, masaram-gondi, gunjala-gondi, syriac</li>
<li>U+003E GREATER-THAN SIGN: try adding one of: latin, adlam, math, masaram-gondi, gunjala-gondi</li>
<li>U+003F QUESTION MARK: try adding one of: cham, gunjala-gondi, latin, mongolian, math, masaram-gondi, balinese, adlam</li>
<li>U+0040 COMMERCIAL AT: try adding one of: adlam, math, latin</li>
<li>U+0041 LATIN CAPITAL LETTER A: try adding one of: symbols, nushu, math, latin</li>
<li>U+0042 LATIN CAPITAL LETTER B: try adding one of: symbols, nushu, math, latin</li>
<li>U+0043 LATIN CAPITAL LETTER C: try adding one of: symbols, nushu, math, latin</li>
<li>U+0044 LATIN CAPITAL LETTER D: try adding one of: symbols, nushu, math, latin</li>
<li>U+0045 LATIN CAPITAL LETTER E: try adding one of: symbols, nushu, math, latin</li>
<li>U+0046 LATIN CAPITAL LETTER F: try adding one of: symbols, nushu, math, latin</li>
<li>U+0047 LATIN CAPITAL LETTER G: try adding one of: symbols, nushu, math, latin</li>
<li>U+0048 LATIN CAPITAL LETTER H: try adding one of: symbols, nushu, math, latin</li>
<li>U+0049 LATIN CAPITAL LETTER I: try adding one of: symbols, nushu, math, latin</li>
<li>U+004A LATIN CAPITAL LETTER J: try adding one of: symbols, nushu, math, latin</li>
<li>U+004B LATIN CAPITAL LETTER K: try adding one of: symbols, nushu, math, latin</li>
<li>U+004C LATIN CAPITAL LETTER L: try adding one of: symbols, nushu, math, latin</li>
<li>U+004D LATIN CAPITAL LETTER M: try adding one of: symbols, nushu, math, latin</li>
<li>U+004E LATIN CAPITAL LETTER N: try adding one of: symbols, nushu, math, latin</li>
<li>U+004F LATIN CAPITAL LETTER O: try adding one of: symbols, nushu, math, latin</li>
<li>U+0050 LATIN CAPITAL LETTER P: try adding one of: symbols, nushu, math, latin</li>
<li>U+0051 LATIN CAPITAL LETTER Q: try adding one of: symbols, nushu, math, latin</li>
<li>U+0052 LATIN CAPITAL LETTER R: try adding one of: symbols, nushu, math, latin</li>
<li>U+0053 LATIN CAPITAL LETTER S: try adding one of: symbols, nushu, math, latin</li>
<li>U+0054 LATIN CAPITAL LETTER T: try adding one of: symbols, nushu, math, latin</li>
<li>U+0055 LATIN CAPITAL LETTER U: try adding one of: symbols, nushu, math, latin</li>
<li>U+0056 LATIN CAPITAL LETTER V: try adding one of: symbols, nushu, math, latin</li>
<li>U+0057 LATIN CAPITAL LETTER W: try adding one of: symbols, nushu, math, latin</li>
<li>U+0058 LATIN CAPITAL LETTER X: try adding one of: symbols, nushu, math, latin</li>
<li>U+0059 LATIN CAPITAL LETTER Y: try adding one of: symbols, nushu, math, latin</li>
<li>U+005A LATIN CAPITAL LETTER Z: try adding one of: symbols, nushu, math, latin</li>
<li>U+005B LEFT SQUARE BRACKET: try adding one of: latin, wancho, math, adlam, syriac</li>
<li>U+005C REVERSE SOLIDUS: try adding one of: latin, wancho, math, adlam, syriac</li>
<li>U+005D RIGHT SQUARE BRACKET: try adding one of: latin, wancho, math, adlam, syriac</li>
<li>U+005E CIRCUMFLEX ACCENT: try adding one of: adlam, math, latin</li>
<li>U+005F LOW LINE: try adding one of: adlam, math, latin</li>
<li>U+0060 GRAVE ACCENT: try adding one of: math, latin</li>
<li>U+0061 LATIN SMALL LETTER A: try adding one of: symbols, nushu, math, latin</li>
<li>U+0062 LATIN SMALL LETTER B: try adding one of: symbols, nushu, math, latin</li>
<li>U+0063 LATIN SMALL LETTER C: try adding one of: symbols, nushu, math, latin</li>
<li>U+0064 LATIN SMALL LETTER D: try adding one of: symbols, nushu, math, latin</li>
<li>U+0065 LATIN SMALL LETTER E: try adding one of: symbols, nushu, math, latin</li>
<li>U+0066 LATIN SMALL LETTER F: try adding one of: symbols, nushu, math, latin</li>
<li>U+0067 LATIN SMALL LETTER G: try adding one of: symbols, nushu, math, latin</li>
<li>U+0068 LATIN SMALL LETTER H: try adding one of: symbols, nushu, math, latin</li>
<li>U+0069 LATIN SMALL LETTER I: try adding one of: symbols, nushu, math, latin</li>
<li>U+006A LATIN SMALL LETTER J: try adding one of: symbols, nushu, math, latin</li>
<li>U+006B LATIN SMALL LETTER K: try adding one of: symbols, nushu, math, latin</li>
<li>U+006C LATIN SMALL LETTER L: try adding one of: symbols, nushu, math, latin</li>
<li>U+006D LATIN SMALL LETTER M: try adding one of: symbols, nushu, math, latin</li>
<li>U+006E LATIN SMALL LETTER N: try adding one of: symbols, nushu, math, latin</li>
<li>U+006F LATIN SMALL LETTER O: try adding one of: symbols, nushu, math, latin</li>
<li>U+0070 LATIN SMALL LETTER P: try adding one of: symbols, nushu, math, latin</li>
<li>U+0071 LATIN SMALL LETTER Q: try adding one of: symbols, nushu, math, latin</li>
<li>U+0072 LATIN SMALL LETTER R: try adding one of: symbols, nushu, math, latin</li>
<li>U+0073 LATIN SMALL LETTER S: try adding one of: symbols, nushu, math, latin</li>
<li>U+0074 LATIN SMALL LETTER T: try adding one of: symbols, nushu, math, latin</li>
<li>U+0075 LATIN SMALL LETTER U: try adding one of: symbols, nushu, math, latin</li>
<li>U+0076 LATIN SMALL LETTER V: try adding one of: symbols, nushu, math, latin</li>
<li>U+0077 LATIN SMALL LETTER W: try adding one of: symbols, nushu, math, latin</li>
<li>U+0078 LATIN SMALL LETTER X: try adding one of: symbols, nushu, math, latin</li>
<li>U+0079 LATIN SMALL LETTER Y: try adding one of: symbols, nushu, math, latin</li>
<li>U+007A LATIN SMALL LETTER Z: try adding one of: symbols, nushu, math, latin</li>
<li>U+007B LEFT CURLY BRACKET: try adding one of: wancho, adlam, math, latin</li>
<li>U+007C VERTICAL LINE: try adding one of: adlam, math, latin</li>
<li>U+007D RIGHT CURLY BRACKET: try adding one of: wancho, adlam, math, latin</li>
<li>U+007E TILDE: try adding one of: math, latin</li>
<li>U+00A3 POUND SIGN: try adding latin</li>
<li>U+20AC EURO SIGN: try adding latin</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font:</p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* D (U+0044): X=1035.0,Y=1.0 (should be at baseline 0?)

* E (U+0045): X=501.0,Y=-0.5 (should be at baseline 0?)

* J (U+004A): X=375.5,Y=2.0 (should be at baseline 0?)

* L (U+004C): X=1399.0,Y=1498.0 (should be at cap-height 1496?)

* N (U+004E): X=352.0,Y=2.0 (should be at baseline 0?)

* O (U+004F): X=316.0,Y=1.0 (should be at baseline 0?)

* P (U+0050): X=1471.5,Y=1495.5 (should be at cap-height 1496?)

* P (U+0050): X=321.5,Y=0.5 (should be at baseline 0?)

* T (U+0054): X=397.5,Y=1.0 (should be at baseline 0?)

* V (U+0056): X=625.5,Y=1.5 (should be at baseline 0?)

* W (U+0057): X=1121.0,Y=1.0 (should be at baseline 0?)

* Z (U+005A): X=1224.0,Y=-1.0 (should be at baseline 0?)

* b (U+0062): X=179.5,Y=2.0 (should be at baseline 0?)

* backslash (U+005C): X=915.0,Y=1.0 (should be at baseline 0?)

* comma (U+002C): X=50.0,Y=1.0 (should be at baseline 0?)

* d (U+0064): X=525.0,Y=1.0 (should be at baseline 0?)

* d (U+0064): X=233.0,Y=-2.0 (should be at baseline 0?)

* d (U+0064): X=539.0,Y=664.0 (should be at x-height 663?)

* f (U+0066): X=240.0,Y=1.0 (should be at baseline 0?)

* h (U+0068): X=542.0,Y=1.0 (should be at baseline 0?)

* h (U+0068): X=117.0,Y=1.0 (should be at baseline 0?)

* i (U+0069): X=161.5,Y=0.5 (should be at baseline 0?)

* l (U+006C): X=181.5,Y=2.0 (should be at baseline 0?)

* m (U+006D): X=169.0,Y=661.0 (should be at x-height 663?)

* n (U+006E): X=113.5,Y=0.5 (should be at baseline 0?)

* numbersign (U+0023): X=392.0,Y=1.0 (should be at baseline 0?)

* percent (U+0025): X=502.0,Y=1.0 (should be at baseline 0?)

* plus (U+002B): X=281.0,Y=2.0 (should be at baseline 0?)

* question (U+003F): X=142.5,Y=-0.5 (should be at baseline 0?)

* seven (U+0037): X=104.0,Y=0.5 (should be at baseline 0?)

* six (U+0036): X=424.0,Y=-2.0 (should be at baseline 0?)

* sterling (U+00A3): X=1097.0,Y=1494.0 (should be at cap-height 1496?)

* two (U+0032): X=481.0,Y=-2.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



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







* ⚠️ **WARN** <p>OS/2 VendorID is 'PfEd', a font editor default. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: bad]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-use-typo-metrics">googlefonts/use_typo_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/SolenneNova.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 13 | 7 | 123 | 6 | 87 | 0 | 
| 0% | 0% | 6% | 3% | 52% | 3% | 37% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG

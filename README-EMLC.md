# Early Modern Low Countries (EMLC) Citation Style

(Unofficial) Citation Style Language (CSL) file for the journal *Early Modern Low Countries*.

## Installation

### In Zotero:

1. Download the file `early-modern-low-countries.csl`
2. Open Zotero
3. Go to Edit → Settings → Cite
4. Click the "+" button under "Styles"
5. Select the downloaded CSL file
6. The style will now appear in your style selector as "Early Modern Low Countries"

## Key Features

This citation style follows the author guidelines of *Early Modern Low Countries*:

* **Shortened citations in all footnotes** — even the first occurrence uses shortened format (Author, Short title, page)
* **No ibid.** — consecutive references to the same work repeat the shortened title
* **Single quotation marks** for article and chapter titles
* **British English** conventions throughout
* **Oxford commas** in enumerations

## Citation Format Examples

### Footnotes (always shortened):

```
1. Soen, Vredehandel, 56.
2. Pollmann, 'Iconoclasts', 157-159.
3. Soen, Vredehandel, 56; Pollmann, 'Iconoclasts', 157-159.
```

### Bibliography:

**Books:**

```
Soen, Violet, Vredehandel. Adellijke en Habsburgse verzoeningspogingen tijdens de 
Nederlandse Opstand (1564-1581) (Amsterdam 2012).
```

**Journal articles:**

```
Pollmann, Judith, 'Iconoclasts Anonymous. Why Did It Take Historians So Long to 
Identify the Image-Breakers of 1566', BMGN/Low Countries Historical Review 131 
(2016/1) 155-176.
```

**Book chapters:**

```
Prak, Maarten, 'The People in Politics. Early Modern England and the Dutch Republic 
Compared', in Margaret C. Jacob and Catherine Secretan (eds.), In Praise of Ordinary 
People. Early Modern Britain and the Dutch Republic (New York 2014) 141-161.
```

## Important Notes \& Limitations

### Title and Subtitle Separator

EMLC requires a **period** (full stop) between title and subtitle, not a colon.

**EMLC format:** `Title. Subtitle`  
**Default CSL format:** `Title: Subtitle`

**Workaround:** In Zotero, combine the title and subtitle manually in the "Title" field with a period:

* ❌ Wrong: Title field: "Vredehandel" + Subtitle field: "Adellijke en Habsburgse verzoeningspogingen"
* ✅ Correct: Title field: "Vredehandel. Adellijke en Habsburgse verzoeningspogingen"

### Archival Sources

EMLC requires full citation of archival sources in footnotes. The CSL specification does not have native support for manuscript/archival citations in the required EMLC format.

**Recommendation:** Add archival sources manually to your footnotes and bibliography following the EMLC guidelines:

```
Amsterdam, Stadsarchief, Notarissen ter standplaats Amsterdam 15729, Probate 
inventory of Jan Bloemsaat, 10 August 1780, fols. 46-63.
```

### Et al. in Footnotes

EMLC uses "et al." after the first author for works with 4+ authors in footnotes, but lists all authors in the bibliography. This CSL file implements this correctly.

### Multi-volume Works

For multi-volume works, cite the volume number in Roman numerals:

* Bibliography: `6 vols.`
* Footnote: `III, 159` (volume III, page 159)

## Zotero Field Mapping

|EMLC Element|Zotero Field|
|-|-|
|Author name|Author (Last, First)|
|Title \& subtitle|Title (combine with period)|
|Editor|Editor|
|Translator|Translator|
|Place|Place|
|Publisher|Publisher (for pre-1800 sources only)|
|Year|Date|
|Journal title|Publication|
|Volume|Volume|
|Issue|Issue|
|Pages|Pages|

## Known Limitations

Due to CSL specification constraints, the following EMLC requirements cannot be fully automated:

1. **Title/subtitle separator** — Must be entered manually with a period in the Title field
2. **Archival sources** — Must be formatted manually
3. **Headline-style capitalization** for English titles — Zotero does not distinguish language, so this must be handled manually

## Feedback \& Contributions

This style was created based on the EMLC Author Guidelines (2025). If you encounter any issues or have suggestions for improvements, please contact:

**Author:** C.A. Romein  
**ORCID:** 0000-0003-3682-0126

## License

CC BY-SA 4.0 International

## Version

**Version:** 1.0  
**Last updated:** April 2026  
**Based on:** EMLC Author Guidelines 2025


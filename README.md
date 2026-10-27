# Luigi Bianchi, *Lezioni* — Italian text, English and Chinese translations

Two lecture courses by Luigi Bianchi: Volume I of the second edition of the *Lezioni di geometria differenziale*
(1902), complete in
Italian, English and Simplified Chinese, and the beginning of the *Lezioni sulla teoria dei gruppi continui finiti di
trasformazioni* (1902–1903) in Italian and English.

## *Lezioni di geometria differenziale*, second edition, Volume I (Pisa: Spoerri, 1902)

| | PDF | LaTeX |
| --- | --- | --- |
| Italian | [PDF](geometria-differenziale/pdf/Bianchi_Geometria_differenziale_I_Italiano.pdf) (356 pages) | [LaTeX](geometria-differenziale/tex/Bianchi_Geometria_differenziale_I_Italiano.tex) |
| English | [PDF](geometria-differenziale/pdf/Bianchi_Differential_Geometry_I_English.pdf) (356 pages) | [LaTeX](geometria-differenziale/tex/Bianchi_Differential_Geometry_I_English.tex) |
| Simplified Chinese | [PDF](geometria-differenziale/pdf/Bianchi_Differential_Geometry_I_Chinese.pdf) (320 pages) | [LaTeX](geometria-differenziale/tex/zh-hans/tex/Bianchi_Lezioni_geometria_differenziale_Volume_I_zh-Hans.tex) |

**Completeness.** All three readers contain the whole volume: title matter, preface, the fourteen chapters and the
index. Volumes II (1903) and III (1909) are not transcribed.

- The Italian keeps Bianchi's text as printed, including his own mistakes in formulas and references.
- The English and Chinese correct a mistake of the print only where it is proved, and then with a note at that
  place giving the printed reading.
- Figures 7, 8 and 9 of Chapter XII are reproduced from the scan; the other figures are redrawn in LaTeX.
- The readers do not mark the page breaks of the print; page references in the text refer to the 1902 volume.

## *Lezioni sulla teoria dei gruppi continui finiti di trasformazioni*, 1902–1903 (Pisa: Spoerri, 1903)

| | PDF | LaTeX |
| --- | --- | --- |
| Italian | [PDF](gruppi-continui/pdf/Bianchi_Gruppi_continui_Italiano_pp001-116.pdf) (69 pages) | [LaTeX](gruppi-continui/tex/Bianchi_Gruppi_continui_Italiano_pp001-116.tex) |
| English | [PDF](gruppi-continui/pdf/Bianchi_Continuous_Groups_English_pp001-116.pdf) (69 pages) | [LaTeX](gruppi-continui/tex/Bianchi_Continuous_Groups_English_pp001-116.tex) |

**Completeness.** This is a partial edition of the handwritten lecture notes: the table of contents and pages 1–116 of
708, ending in §35
after equation (3₁). Pages 117–708 are not yet transcribed.

## How it was made

Both works were transcribed from the scans, and translated, by AI (OpenAI models in ChatGPT and Codex). The Chinese
was translated from the Italian, with the English as an aid.

## Checks

- During production the transcription of the *Geometria differenziale* was checked against the scan by AI wherever a
  reading was in doubt, and every page of the finished readers was reviewed visually. This was not a
  character-by-character comparison of every page.
- On 27 October 2026 Claude Opus 5.5 (Anthropic) compared §112 of the *Geometria differenziale* (printed page 247) in
  all three languages, and page 50 (§14) of the *Gruppi continui* in Italian, with the scans. Text and formulas
  agree with the print, and the translations are faithful.
- Other pages have not had a second check by a different model.

## Sources

- *Geometria differenziale*: the Internet Archive scan
  [lezionidigeomet00unkngoog](https://archive.org/details/lezionidigeomet00unkngoog) (Google digitization).
- *Gruppi continui*: the photographs of the TIB Hannover copy (shelfmark Mr.I 583),
  [doi:10.14463/GBV:885209656](https://doi.org/10.14463/GBV:885209656).

## Building

- Italian and English: run `pdflatex` twice in `geometria-differenziale/tex/` and in `gruppi-continui/tex/`.
- Chinese: in `geometria-differenziale/tex/zh-hans/`, run
  `lualatex tex/Bianchi_Lezioni_geometria_differenziale_Volume_I_zh-Hans.tex` twice. It uses the Fandol fonts of
  the TeX distribution.

## Rights

Bianchi's texts are in the public domain. The transcriptions, translations and typesetting are dedicated to the
public domain under [CC0 1.0](LICENSE).

## Earlier versions

Earlier versions were published on Zenodo, [doi:10.5281/zenodo.20615814](https://doi.org/10.5281/zenodo.20615814).
That record is no longer updated.

---

[Sponsor this work](https://github.com/sponsors/KokunoYumeto)

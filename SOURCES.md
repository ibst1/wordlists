# Word-list sources & licensing

This repo holds the word lists Expanto loads as dictionaries (real-word
spell-check + typing hints). Each list is a flat `*.txt` of one term per line,
**extracted/derived** from the sources below — they are not the original
databases. If you redistribute widely, verify the current terms at the sources.

---

## `allmant/` — general dictionaries

- **`words_sv.txt`** — lowercased / cleaned derivative (~403k forms) of
  `swe_wordlist` from **[martinlindhe/wordlist_swedish](https://github.com/martinlindhe/wordlist_swedish)**,
  **MIT licensed** (© 2014 Martin Lindhe; symbols, uppercase forms and
  multi-word entries removed). See `allmant/swe_wordlist.LICENSE.md` for the
  full MIT notice.

- **`words_en.txt`** — `words_alpha.txt` (370,105 words) from
  **[dwyl/english-words](https://github.com/dwyl/english-words)**, compiled from
  public-domain sources (originally the infochimps "350,000+ Simple English
  Words", released to the public domain). Common-word lists are factual data.

- **`runeberg_*.txt`** — word forms extracted from public-domain Swedish texts
  digitised by **[Project Runeberg](https://runeberg.org/)**. The underlying
  texts are old enough to be in the **public domain**; these extracted word
  lists are factual data.

## `genetik/` — gene symbols

- **`genetik.txt`** — human gene symbols + aliases/previous symbols
  (lowercased), derived from the **HGNC** gene nomenclature
  ([genenames.org](https://www.genenames.org/)) and/or **NCBI Gene**
  ([ncbi.nlm.nih.gov/gene](https://www.ncbi.nlm.nih.gov/gene)). Gene symbols are
  **factual data** and both sources provide them freely (NCBI is U.S. public
  domain).

## `medicin/` — medical subject headings (MeSH)

- **`mesh_sv.txt`** — word list derived from **Svensk MeSH**, **Karolinska
  Institutet (KI)**. Free to use; **attribution to Karolinska Institutet**.
  <https://mesh.kib.ki.se/>

- **`mesh_en.txt`** — word list derived from **MeSH (Medical Subject
  Headings)**, **U.S. National Library of Medicine (NLM)**. MeSH is in the
  **public domain**. <https://www.nlm.nih.gov/mesh/>

## `fysik/` & `filosofi-teologi/` — seed term lists

- **`fysik/fysik.txt`** and **`filosofi-teologi/filosofi-teologi.txt`** —
  Swedish specialist terminology lists **originally compiled for this repo** as
  seed lists (intended to be expanded over time). Released to the **public
  domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)** —
  no rights reserved, use freely.

---

These lists are derivatives/extracts of the above; they are not the original
databases. Attributions and links are provided so you can verify and re-source
the data. If you redistribute, keep the attributions for Karolinska Institutet
(Svensk MeSH) and Martin Lindhe (swe_wordlist / MIT) intact.

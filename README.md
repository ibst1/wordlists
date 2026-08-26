# Word lists/ordlistor

Bundled **word-list / dictionary** content for the
[Expanto](https://github.com/ibst1/expanto) phrase manager. Expanto uses these
lists for **real-word spell-check** and **typing hints / autocomplete** — the
more relevant words it knows, the better its suggestions.

## What's in here

Each subfolder is a **separately downloadable specialist dictionary** in
Expanto. Pick the ones that match what you write.

| Subfolder | Innehåll |
|-----------|----------|
| `general/` | General Swedish + English dictionaries (everyday vocabulary). |
| `genetik/` | Human gene symbols and aliases. |
| `medicin/` | Medical Subject Headings (MeSH) — Swedish and English. |
| `fysik/` | Swedish physics terms (facktermer) — **seed list**, expanding. |

The `fysik/` list is a **seed list**: a solid starting point that will grow
over time.

## File format

Each `*.txt` file is a plain **word list — one term per line**, lowercase. A
"term" is usually a single word, but a short multi-word term may sit on one
line:

```
acceleration
rörelsemängd
svart hål
```

No headers, no metadata — just one term per line.

## How Expanto uses this

Expanto offers to download these on **first run**, or at any time via the
**"Ladda ner innehållspaket"** (Download content pack) dialog. Each subfolder
can be downloaded **independently** as a specialist dictionary. When you accept,
the folder is added to the app's **word-list folders** under
**Inställningar / Settings**, and the words load automatically on the next
start. You can enable or disable individual dictionaries there.

## Licensing

Provenance and licensing for every list are documented in
[`SOURCES.md`](SOURCES.md). Please read it before redistributing.

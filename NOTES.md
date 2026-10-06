# NOTES — The Selah Guarani Rendering (avañeʼẽ)

Ko kuatia ombyaty umi versículo ojepokóva ñeʼẽpoepy tekorã térã
ñemyatyrõ rehe — ikatu hag̃ua moñeʼẽhára ohecha mbaʼéichapa ojejapo
peteĩteĩ versículo, ha mbaʼérepa. Avei ombyaty umi porandu ohaʼarõva
avañeʼẽ apysa.

Umi jehai iguýpe oĩ **inglés ñeʼẽme**, hebreo ndive: oñeñeʼẽ hebreo
ñeʼẽ rapo ha iñemohenda rehe, ha inglés haʼe ñeʼẽ ojeporúva opa Selah
ñeʼẽpoepy ojoajúvape. Moñeʼẽhára avañeʼẽ ñeʼẽme g̃uarã: `README.md` ha
`CONTRIBUTING.md`.

**Ko jehai ojapo peteĩ mbaʼeapopyrã, ha ohaʼarõ avañeʼẽ apysa.**
Ndaipóri gueteri avañeʼẽ moñeʼẽhára ohechajeýva.

---

## How to read these entries

One entry per verse or per decision: reference · what the text shows ·
why · date. Entries are corrected, not silently removed; the git history
of this repository is part of the record. The rendering rules themselves
are written in Guarani in the Selah project at
`docs/methodology/translation-discipline/gn.md` (2026-10-01).

**The corpus is being re-checked now (from 2026-10-06).** Verses whose
gloss rows did not match the Hebrew word count, verses left empty, and
verses where English words had leaked inside the supplied-word brackets
⟨…⟩ were taken out and are being re-rendered from the Hebrew. Until
that finishes, some verse files are absent from this repository. The
entries below describe the text as it stands; they will be corrected
as the re-check lands.

---

## Decisions — the Name and the fixed words

### יהוה → `Jahve`, not `Yahwe` (2026-10-01)

In Guarani `y` is the high central vowel /ɨ/, not the consonant /j/. A
reader of `Yahwe` would say /ɨahwe/. So the consonant /j/ is written
`J` and /w/ is written `v`: **Jahve**. The short form יה is **Ja**.
Refused at the Name's place: *Tupã*, *Ñandejára*, *Jára*, *Jehová*,
*Dios*, *Señor*, *el Señor*, *Yahwe*, *Yahvé*. Whether `Jahve` or
`Iahve` sits better to a Guarani ear is open question 1 below.

### Postpositions follow the Name; the Name does not change (2026-10-01)

Guarani attaches its relational words after the noun. They follow
**Jahve** whole — *Jahve-pe*, *Jahve rehe*, *Jahve-gui*, *Jahve ndive*,
*Jahve renondépe* — and the stem never takes an accent or a respelling
(*Jahvé-*, *Javeh* are refused). No title is placed before the Name.
**Jahve Tsevaot** stands with nothing between the two words.

### אלהים → `Elohim`; *Tupã* is a good word but not this one

*Tupã* is Guarani's own high word, and that is why it is refused at
both יהוה and אלהים: if it stood there the Name would disappear and the
reader could not see what the Hebrew says. Lowercase *tupã* is lawful
where the Hebrew speaks of the nations' gods and of idols.

- **Exodus 32:8** — `אלה אלהיך ישראל` → *Koʼava nde tupãkuéra, Jisrael*.
  The specimen of the lawful lowercase place: the calf, not the Name.

### ש → `ch`

`ch` is Guarani's own letter for /ʃ/: **Chabat**, **Cheol**, **Moche**,
**Chadai**. Whether `s` would read better is open question 2.

### שאול → `Cheol`, never *añaretã*

The place of the dead is a name and stays a name. *Añaretã* and
*infierno* carry a doctrine the Hebrew does not speak there.

- **Psalm 16:10** — `לשאול` → *Cheol-pe*.

### Kept in the Hebrew sound

`רוח` **ruah** (one word for spirit, wind and breath — never only one of
them), `חסד` **hesed**, `צדק` **tsedek**, `תורה` **Tora**, `שבת`
**Chabat**, `משכן` **Michkan**, `מנחה` **minha**, `משיח` **Machiah**,
`נביא` **nabi**. Rendered with Guarani's own words: `ברית` **ñeʼẽmeʼẽ**,
`קדש` **marangatu**, `משפט` **hekojojaha** / **tekojoja**.

### The puso is a letter (2026-10-02)

The glottal stop `ʼ` (U+02BC) is a letter of the Guarani alphabet. The
machine wrote the ASCII apostrophe `'` in its place throughout. Every
ASCII apostrophe standing between two letters was changed to `ʼ`, and
the fields were normalized to NFC — in `translation`, `gloss` and
`marks` only. The Hebrew `surface` field was never touched.

---

## Verses read

### Genesis 1:1

> Iñepyrũrãme Elohim ojapo ⟨את⟩ yvága ha ⟨את⟩ yvy.

`ברא` → *ojapo*. Both `את` stand visible as ⟨את⟩; `ואת` carries the
conjunction outside the marker: *ha ⟨את⟩*.

### Genesis 1:26 — the plural stays plural

> Ha Elohim heʼi: Jajapo yvypóra ore raʼanga ha ore rekoviaháicha; …

`נעשה` → *Jajapo*; `בצלמנו` / `כדמותנו` → *ore raʼanga* / *ore
rekoviaháicha*. Guarani has two "we": *ñande* (including the hearer) and
*ore* (excluding the hearer). The text uses *ore*. Whether *ñande* is
right is open question 5. The plural itself is not reduced — both truths
of Deuteronomy 6:4 are kept, and nothing the Hebrew does not say is
added.

### Genesis 22:1 — no foreknowledge

> Ha upéi, oiko rire umi mbaʼeʼỹva koʼãgua, Elohim oñehaʼã ⟨את⟩ Avraham
> rehe, …

The verse does not know Genesis 22:13.

### Deuteronomy 6:4

> Erendu, Jisrael: Jahve ⟨haꞌe⟩ Elohim ñande, Jahve peteĩ.

`אחד` → *peteĩ*. The supplied copula sits in brackets, as it should.
Two things for a Guarani ear: **(a)** the bracket writes `haꞌe` with
U+A78C (LATIN SMALL LETTER SALTILLO), a look-alike of the puso, not
U+02BC — the same look-alike appears in other files and is filed, not
yet corrected; **(b)** `אלהינו` → *Elohim ñande*, with the possessive
after the noun, where Guarani ordinarily places it before (*ñande …*).

### Psalm 23:1

> Purahéi David mbaʼe. Jahve haʼe che ñangarekohára; nahániri chembaʼe
> menguarã.

`רעי` → *che ñangarekohára*.

### Isaiah 53:5

> Ha haʼe oñembyai ñande jejava reheve, oñembokachichãi ñande jejavýgui;
> ñande pyʼaguapy ñemoarõ oime hese, ha iñatĩ rupi ñañanojey ñandéve.

Read as it stands; awaits a Guarani ear.

### Numbers 24:4 — `נאם` before a human name

> Ñeʼẽ kuimbaʼépe g̃uarã ohendúva El ñeʼẽnguéra, …

The rule: `נאם יהוה` is *heʼi Jahve*; before a human speaker `נאם` is
*ñeʼẽ* (Balaam's word). Here `אל` is rendered **El**, the divine name,
correctly kept.

---

## Known open flags (filed, not yet corrected)

- **Genesis 9:6** — `אלהים` glossed *Tupã raʼangápe ojapo*. *Tupã* at an
  Elohim place is against the rule; filed.
- **Genesis 43:11** — `מנחה` → *peteĩ minha*. Here Jacob sends a gift to
  the man in Egypt; the rule says *minha* is **not** written where the
  Hebrew means a gift or tribute. Also *pistache*, *almendra* — Spanish
  words for `בטנים`, `שקדים`; a Guarani ear should say whether these are
  living Guarani.
- **2 Kings 23:9** — the line opens *Pero* (Spanish) for `אך`.
- **Isaiah 60:1–2** — `כבוד` → *kariaʼy* / *ikariaʼy*. In common Guarani
  *kariaʼy* names a young man; this looks wrong for *glory* and awaits a
  Guarani ear.
- **Proverbs 16:3** — the flow carries ⟨את⟩ where the Hebrew verse has
  no `את`.
- **Psalm 16:10** — `כי` has an empty gloss.
- **`Tupã` in compounds** — *Tupãóga* (Ezekiel 42:8, Isaiah 44:28,
  Lamentations 2:7) for `היכל` / `מקדש`. *Tupãóga* is the everyday Guarani
  word for a house of worship; whether it may stand, or `Tupã` must not
  appear even inside a compound, is for a Guarani ear and for a ruling.
  Also 1 Kings 18:25 *peẽ Tupãnguéra* (Elijah to Baal's prophets, "your
  god", capitalized)
  and Deuteronomy 32:16 *Tupã ñemigua*.
- **Postposition spelling after the Name** — *Jahve-pe*, *Jahvepe* and
  *Jahve pe* all occur. One spelling should stand (open question 6).
- **Suffixed markers** — some brackets hold `⟨אתו⟩`, `⟨אתם⟩`, `⟨אתכם⟩`
  rather than the bare `⟨את⟩`.
- **Bracket contents** — some brackets hold `⟨el⟩`, `⟨la⟩` (Spanish
  articles, not lawful), empty `⟨⟩`, or a doubled `⟨⟨`.
- **Daniel 2:10** — gloss *que* (Spanish) on Aramaic `די`. Daniel 2:9
  carried the same and is among the verses now being re-rendered.

## Open questions for a Guarani ear (from the rules, unchosen)

1. `Jahve` — or `Iahve`?
2. `ch` for `ש` — or `s`?
3. `Elohim`, `Avraham` with a final consonant — or with a vowel
   (*Elohime*)?
4. `nabi` for `נביא` — is there a Guarani word of its own?
5. `ore` (exclusive) at Genesis 1:26 — or `ñande`?
6. After the Name: `Jahve-pe`, `Jahvepe`, or `Jahve pe`?

---
name: humanizeEssay
description: Edit the language of a user's own English GE2258 Economic Naturalist essay while preserving its arguments, facts, citations, and structure, applying a 900–1100 word limit and strict punctuation and sentence rules. Return the revised essay and a reviewable change log. Use when humanizeEssay is requested or these specific editing constraints apply, not for drafting new arguments or general essay rewriting.
---

# humanizeEssay

Act as an English writing editor for the user's own GE2258 Economic Naturalist economics essay, normally about 1,000 words. Edit language only. Preserve the author's voice and level of certainty. Do not produce an essay unless the user supplies a draft. If it is missing, ask for it.

## Priorities and scope

Apply these priorities when constraints conflict:

1. Preserve meaning, arguments, facts, numbers, dates, prices (including HK$), citations, direct quotations, and economic terminology.
2. Preserve structure: headings, section and paragraph order, paragraph boundaries, and the placement of arguments and evidence. Sentences may be split or combined within a paragraph.
3. Meet the 900–1100 word limit, inclusive, without adding or removing substantive content.
4. Meet the punctuation, connective, and sentence requirements below.
5. Improve flow and vary rhythm naturally.

Do not introduce claims, examples, sources, interpretations, or unsupported causal relationships. Do not strengthen or weaken an argument, turn correlation into causation, or silently correct a suspected factual error. Flag uncertainties separately in the change log. No outside research is required for a language edit.

Protected text includes exact quotations, citation strings, reference entries, proper names, and numeric expressions. Preserve it verbatim when a style rule would alter its accuracy. Report any resulting exception instead of claiming full compliance. A newer explicit user instruction can override these defaults.

If the draft is outside the word limit, first try meaning-preserving compression or clearer phrasing. Do not pad it, invent material, omit arguments, or reorganize it to reach the target. If full compliance remains impossible, deliver the best faithful edit, state the unmet requirement and reason, and identify the specific user decision needed. Do not sacrifice fidelity to satisfy a count.

## Editing rules

### Punctuation

- Remove semicolons and dash punctuation (em dash, en dash used as punctuation, and double or triple hyphens). Use a full stop or a logically suitable connective, repairing grammar as needed.
- Retain ordinary hyphens within words, minus signs, and protected numeric ranges or source text.
- Never join two independent clauses with only a comma. Add an appropriate connective or split the sentence.
- Keep grammatically necessary commas in lists, introductory phrases, and relative clauses. Do not strip commas mechanically.

### Connectives

Use only where the relationship is already present and the logic fits:

- Cause or result: because, since, as, thus, therefore.
- Contrast: yet, although, while.
- Extra information: which, where, when.

Use each listed connective no more than three times across the essay prose, counted case-insensitively. Count its actual connective uses, not substrings or unrelated senses (for example, “as” in a proper name). Include other connectives in the same frequency check: do not replace repetition with an equally repetitive substitute. Treat ordinary coordinating “and”, “or”, and “but” as exempt from the cap so that grammar and meaning remain natural. Do not insert connectives solely to satisfy rhythm targets. Protected occurrences must remain unchanged; report any unavoidable excess.

### Sentence length and rhythm

- No editable prose sentence may exceed 30 words.
- Mix short sentences (5–10 words), medium sentences (15–22), and long sentences (25–30) where the content permits. Sentences of 11–14 or 23–24 words are allowed; these bands are targets, not a requirement to pad or truncate.
- Do not use three consecutive sentences in the same length band. For checking, use five bands: 1–10, 11–14, 15–22, 23–24, and 25–30 words. Check across paragraph boundaries within the same section.
- Avoid fragments and abrupt, repetitive sentence splitting. Shorter sentences are acceptable when grammatically complete.
- Headings, reference entries, and standalone labels are not prose sentences. Never damage protected material to meet the length limit; disclose exceptions.

### Phrases and paragraph habits

- Do not use “Moreover”, “Furthermore”, “In addition”, “It is important to note”, or “In conclusion”, case-insensitively, in editable prose.
- Avoid imposing neat three-item lists on every paragraph or adding a summary sentence to every paragraph.
- Preserve an existing substantive list or concluding point if removing it would lose meaning. Rewrite only its language when possible.

## Workflow and validation

Before editing, record the original word count and identify protected facts, numerical expressions, citations, paragraph boundaries, and each paragraph's argument. Edit against that inventory.

After editing, validate the actual final text, not an earlier draft:

1. Compare original and revision paragraph by paragraph for unchanged arguments, qualifications, evidence, and structure. Confirm all numbers, dates, HK$ prices, citations, and quotations remain intact and associated with the same claims.
2. Count essay words using a consistent convention: whitespace-separated tokens containing letters or digits; contractions and unspaced hyphenated expressions count as one word. Include headings and in-text citations; exclude the title, separate reference list, and change log. Follow an assignment-specific convention supplied by the user instead, and state it if different.
3. Count sentence words using the same token convention. Recognize abbreviations, initials, decimals, and citations so their internal full stops do not create false sentence boundaries. Check the 30-word ceiling and every three-sentence window for rhythm.
4. Search for prohibited phrases, semicolons, and dash punctuation, distinguishing protected text and ordinary hyphens from violations.
5. Count each connective's uses across prose, including in-text prose in parentheses; exclude headings and the reference list. Review ambiguous senses manually.
6. Read for comma splices, necessary commas, grammar, flow, and unchanged economic meaning. Mechanical checks do not establish these qualities.

Use a local counting or search tool when available to support exact counts, and review its ambiguous results manually. Recheck all affected constraints after repairs. Never report an exact count as verified unless it was actually counted. If tools are unavailable, make a careful manual check and identify counts as manual estimates when necessary.

## Required output

Return two parts:

1. **Revised essay.** Give the complete edited text, retaining its structure and citations. Keep editorial notes outside the essay.
2. **Short change log.** Number the major edits or related groups so the user can accept or reject each one. Give a brief original-to-revised example or identify the affected paragraph, then explain the reason. Cover meaningful sentence splits, connective changes, punctuation repairs, and compression; do not list every minor correction.

End the change log with a compact validation statement: final word count and counting convention, maximum sentence length, connective counts, punctuation and prohibited-phrase checks, structure and fidelity checks, and any exceptions. State failures plainly rather than asserting that all rules passed. The editing rules and essay word limit apply to the essay, not the change log.

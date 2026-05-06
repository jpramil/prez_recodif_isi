# Recoding Administrative Data with LLMs — Quarto Slides

A 20-minute Quarto Reveal.js presentation in English describing Insee's
experience using Large Language Models to handle the transition from
**NACE Rev. 2** to **NACE Rev. 2.1** in the SIRENE business register.

## Files

- `index.qmd` — the slide deck. Speaker notes (~20 min total) are embedded in
  `::: {.notes}` blocks and shown in Reveal.js Speaker View (press **`S`** while
  presenting).

## Build

```bash
quarto render index.qmd
```

To open in presenter mode locally:

```bash
quarto preview index.qmd
```

In Reveal.js, press `S` to open the speaker view (with notes and a timer),
`F` for fullscreen, `O` for overview, `?` for the full keyboard shortcut list.

## Structure (target: 20 minutes)

| Section | Slides | Approx. time |
|---|---|---|
| Introduction | 4 | 3 min |
| 1. The problem | 4 | 3 min |
| 2. NACE 2.1 and multivocal codes | 3 | 2 min |
| 3. Human and virtual annotation | 2 | 2 min |
| 4. Methodology | 5 | 4 min |
| 5. Infrastructure | 1 | 1 min |
| 6. Results | 3 | 2.5 min |
| 7. RAG alternative | 3 | 1.5 min |
| 8. Conclusion | 4 | 1 min |

## Notes on the speaker notes

Each `::: {.notes}` block is a verbatim spoken script in English designed to
be read aloud at a natural pace, tuned to the time budget above. Adjust freely
to your own delivery style.

## Suggested customisations before you present

- Replace `img/insee-logo.png` and any `![]()` placeholders with the actual
  diagrams from the source presentations
  (`InseeFrLab/codif-ape-prez/slides/jms2025-llm-relabeling` and
  `slides/grp-veille-codif-auto-9`).
- Update the `footer:` field in the YAML header with the actual conference
  name.
- Add or refine the `bibliography:` references as needed.

## License

Same as the source repositories
([InseeFrLab/codif-ape-prez](https://github.com/InseeFrLab/codif-ape-prez)).

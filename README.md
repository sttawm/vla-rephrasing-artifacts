Prompts and distilled rulebooks accompanying a conference submission on
reducing the instruction-phrasing sensitivity of a frozen VLA policy.

- prompts/: rephrase generation, rule distillation (Bridge, and the
  one-clause LIBERO variant), rule application, and the single-rule no-rules-rephraser baseline
- rules/: nine distilled Bridge rulebooks (three evidence types x three
  draws) and the two LIBERO rulebooks reported in the paper
- swings_full.pdf: the significant single-edit swing sets the searches
  found, listed in the paper's format (phrases with highlighted edits,
  exact p-values); the paper charts these sets, this lists their phrases
- data/: per-phrase records behind the swing charts, one row per phrase
  (set id, task, edit category, phrase, success rate, set gap, test stat)

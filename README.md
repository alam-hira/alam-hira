# Hira Alam

MSc Artificial Intelligence (Distinction, University of Sussex) · London, UK
NLP · ASR · LLM evaluation · Open to AI/NLP/data roles

I build evaluation-first ML systems: pre-registered success criteria, held-out splits, honest negative results, byte-reproducible runs, and adversarial audits committed to the repo.

## Featured: a two-part research arc

**[lecturefix](https://github.com/alam-hira/lecturefix)** — the control. An offline, byte-reproducible evaluation harness for LLM correction of ASR transcripts. Finding: context-free correction harms good ASR — full rewrite makes WER ~7.5x worse (99.65% of that harm is hallucinated insertion), and targeted correction, while ~11x less harmful, is still net-negative. The harness caught four of its own measurement bugs before publication.

**[lecturefix-context](https://github.com/alam-hira/lecturefix-context)** — the treatment. A pre-registered experiment on 21 accented scientific talks (MCIF): does the talk's own paper context fix the technical-term errors context-free correction can't? **Criterion met** — context turned the corrector from term-breaking (12% → 15%) into term-repairing (12% → 10%) at 2.3x the fix rate and no overall-WER cost.

**[gridlens](https://github.com/alam-hira/gridlens)** — deterministic GB electricity analytics with two-layer validation ([live](https://alam-hira.github.io/gridlens)).

Everything free and local · fail-loud, never fabricate · Pydantic-validated boundaries · offline CI · fix-forward public history

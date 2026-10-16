# From L¹ to Lᵖ: Self-Similar Measures and Bernoulli Convolutions

**Authors of the main paper:** [Samuel Kittle](https://github.com/samuel-kittle) and [Constantin Kogler](https://github.com/ckkogler).

This repository is a collection of supplementary material on upgrading L¹ densities to Lᵖ densities for self-similar measures and Bernoulli convolutions. The initial collection contains seven research manuscripts on quantitative sufficient conditions for continuous Bernoulli convolution densities, developed through model-assisted work with [Constantin Kogler](https://github.com/ckkogler).

Its organization follows [kk26-supplementary-material](https://github.com/ckkogler/kk26-supplementary-material), but this is a separate collection concerning density regularity. No bibliographic label or publication status for a main paper is assigned here.

## Research manuscripts

| Manuscript | Contents | Source |
| --- | --- | --- |
| [A cubic criterion for continuous algebraic Bernoulli convolutions](bernoulli_algebraic_cubic.pdf) | Algebraic cubic criterion; contains the analytic lemmas used in the later degree-dependence note. | [TeX](tex/bernoulli_algebraic_cubic.tex) |
| [Continuous Bernoulli convolutions under a double-logarithmic criterion](bernoulli_double_logarithmic.pdf) | Double-logarithmic sufficient condition for rational parameters. | [TeX](tex/bernoulli_double_logarithmic.tex) |
| [A cubic criterion for continuous Bernoulli convolutions](bernoulli_cubic_small_cutoff.pdf) | Rational cubic criterion with a smaller denominator cutoff, including 93/94 and 99/100. | [TeX](tex/bernoulli_cubic_small_cutoff.tex) |
| [Continuous algebraic Bernoulli convolutions beyond the fourth power](bernoulli_algebraic_beyond_four.pdf) | Algebraic refinements, including an entropy-sensitive logarithmic criterion. | [TeX](tex/bernoulli_algebraic_beyond_four.tex) |
| [A single-logarithmic degree loss for algebraic Bernoulli convolutions](bernoulli_single_log_degree_2026-10-16.pdf) | Extension of the cubic draft that reduces the degree loss to a single logarithm. Complete degree removal remains unproved. | [TeX](tex/bernoulli_single_log_degree_2026-10-16.tex) |
| [Continuous Bernoulli convolutions with an explicit fourth-power criterion](bernoulli_continuity_power_four.pdf) | Earlier fourth-power criterion and cubic refinements with cutoffs. | [TeX](tex/bernoulli_continuity_power_four.tex) |
| [Continuous Bernoulli convolutions with an explicit fifth-power criterion](bernoulli_continuity_power_five.pdf) | Earlier fifth-power argument using Gaussian approximation and a stopping criterion. | [TeX](tex/bernoulli_continuity_power_five.tex) |

The PDFs and LaTeX sources are preserved as supplied. The fourth- and fifth-power manuscripts record earlier stages of the argument. The algebraic cubic draft is the analytic reference for the single-logarithmic degree note.

## Status and use

These are working research manuscripts. Their inclusion records the arguments and their development; it does not constitute an independent verification of every claim. The single-logarithmic degree note states its dependence on the earlier analytic lemmas and explicitly leaves complete degree removal unproved. Consult each manuscript for its precise assumptions and limitations.

No conversation transcripts are included in this initial collection. Refer to individual manuscripts by title and filename.

## LaTeX sources

Sources are in `tex/`. With a suitable TeX installation, compile an individual manuscript using, for example:

```sh
latexmk -pdf -outdir=build tex/bernoulli_single_log_degree_2026-10-16.tex
```

The other manuscripts use their original preambles and may require additional TeX packages. The bundled PDFs can be read without building the sources.

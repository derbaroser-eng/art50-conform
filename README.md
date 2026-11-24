# AURUM Article 50(2) Evidence Report

A dated engineering evidence report on whether your AI output marking satisfies the four
statutory properties in **Regulation (EU) 2024/1689, Article 50(2)** — effective,
interoperable, robust and reliable, as far as technically feasible.

**EUR 490 one-time · one pipeline per report**

**Get the report:** https://buy.stripe.com/7sY6oK5HQ8ogg1jgWs4ko07

## What you receive

- A dated report covering your pipeline's synthetic audio, image, video or text outputs.
- Each finding mapped to the statutory wording of Article 50(2), quoted verbatim.
- An assessment against the four properties: effective, interoperable, robust, reliable.
- A reproducible method note so the result can be re-run after any model or prompt change.

## Why now

- Article 50 transparency duties applied from **2 August 2026**.
- Systems placed on the market before that date have a transitional window ending
  **2 December 2026** for the machine-readable marking duty under Article 50(2)
  (Article 111(4), inserted by Regulation (EU) 2026/1744).
- Systems placed on the market on or after 2 August 2026 have no grace period.

## Field note

Two teams showed me a policy. Neither showed me evidence. A short, practical note
on the four things an auditor can actually check, written eleven days out from
the deadline:
https://derbaroser-eng.github.io/art50-conform/field-note/

## Write-ups

A hands-on account of what actually survives a re-encode, with the raw command
output and the failure modes:
https://dev.to/aurum_revenue/i-marked-a-png-for-the-eu-ai-act-then-re-encoded-it-the-mark-was-gone-2m82

## The deadline is close

As of 24 November 2026 the transitional window for systems placed on the market before 2 August 2026 closes in eight days, on 2 December 2026. The rule and the date come from the EUR-Lex text of Regulation (EU) 2026/1744:
https://eur-lex.europa.eu/eli/reg/2026/1744

A measured check on a 64x64 PNG: embedding the IPTC trainedAlgorithmicMedia XMP block took the file from 161 to 974 bytes and the verifier reported it marked. One ordinary re-encode brought it back to 161 bytes and the mark was gone. That gap is what the report measures.

New write-up, published 24 November 2026:
https://dev.to/aurum_revenue/eight-days-to-the-eu-ai-act-marking-deadline-i-re-encoded-my-own-image-and-the-mark-disappeared-1fji

The primary source for the 2 December date, checked directly rather than through
a summary: https://eur-lex.europa.eu/eli/reg/2026/1744/oj/eng

## Not legal advice

This is engineering evidence, not legal advice. It does not create a lawyer-client
relationship and is not a conformity certificate. Legal conclusions about your
obligations remain with qualified counsel.

## Contact

derbaroser@gmail.com

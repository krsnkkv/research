# Formal Verification of a Realistic Compiler — CompCert

---

## Overview

A critical report and presentation on:

> Xavier Leroy. *Formal Verification of a Realistic Compiler.*  
> Communications of the ACM, 52(7), 2009.  
> [Read the paper](https://dl.acm.org/doi/10.1145/1538788.1538814)

This was completed as part of an extended Masters-level module involving independent paper analysis, written critique, and an oral viva examination. Please note that the final report and presentation are not uploaded, however further research after has been included.

---

## Contents

| File | Description |
|---|---|
| [`Paper Analysis`](./compcert_paper.docx) | Analysis of Paper |
| [`viva_slides.pdf`](./PresentationCompCert.pdf) | SlideSet |
| [`leroy_2009_compcert.pdf`](./CompcertPaper.pdf) | Original paper (Xavier Leroy, CACM 2009) |

---

## Paper Summary

Leroy presents CompCert — a C compiler verified in Coq whose compilation correctness is formally proved rather than tested. The central claim is that every observable behaviour of the compiled code is a valid behaviour of the source program.

The paper addresses a fundamental gap in software verification: even formally verified source programs can have their guarantees broken by an unverified compiler. CompCert closes this gap for a realistic subset of C.

---

## Key Concepts

- Formal semantics of source and target languages
- Simulation relations and semantic preservation proofs
- Coq proof assistant and extracted OCaml implementation
- Trusted computing base and verification boundaries

---


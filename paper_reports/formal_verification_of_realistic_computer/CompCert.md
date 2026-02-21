# Formal Verification of a Realistic Compiler — CompCert
**Paper Report & Viva · Programming Languages: Principles, Design and Implementation (Extended)**  
University of Birmingham · 2025/26

---

## Overview

A critical report and viva presentation on:

> Xavier Leroy. *Formal Verification of a Realistic Compiler.*  
> Communications of the ACM, 52(7), 2009.  
> [Read the paper](https://dl.acm.org/doi/10.1145/1538788.1538814)

This was completed as part of an extended Masters-level module involving independent paper analysis, written critique, and an oral viva examination.

---

## Contents

| File | Description |
|---|---|
| [`report.pdf`](./report.pdf) | 2-page critical report on the paper |
| [`viva_slides.pdf`](./viva_slides.pdf) | Presentation slides used in viva examination |
| [`leroy_2009_compcert.pdf`](./leroy_2009_compcert.pdf) | Original paper (Xavier Leroy, CACM 2009) |

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

## Module Context

**Module:** Programming Languages: Principles, Design and Implementation (Extended)  
**Level:** Masters (Year 4)  
**Format:** Independent paper study + written report + oral viva

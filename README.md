GOX — Generative Object eXtraction for Elliott Wave Research

TryElliottWave · Research MVP

GOX is an early-stage research MVP developed under the TryElliottWave initiative.
The project explores how traders conceptualize, draw, and validate Elliott Wave structures on financial charts, and how those human-generated structures can be transformed into structured datasets suitable for computational analysis and machine learning research.

At its core, GOX bridges human technical analysis cognition with programmatic representation, enabling the systematic study of subjective chart annotations at scale.

Research Motivation

Elliott Wave Theory is widely used in discretionary trading, yet remains difficult to formalize due to its interpretive and subjective nature. Most existing tools focus on visualization or post-hoc labeling, but do not capture the decision process behind wave construction.

GOX approaches this gap by treating chart drawings as first-class data objects, allowing researchers to:

Observe how humans encode market structure visually

Measure consistency, variance, and rule adherence across users

Explore whether subjective wave interpretations can be modeled, evaluated, or assisted algorithmically

Core Objectives

Enable users to draw Elliott Wave and Fibonacci structures directly on interactive financial charts

Programmatically capture each drawing as structured data:

Anchor points and geometry

Wave hierarchy and labeling

Timestamps and chart context

Apply real-time structural validation against formal Elliott Wave principles

Persist datasets for downstream research and ML/LLM experimentation

Provide feedback mechanisms that surface rule violations, ambiguities, or alternative interpretations

System Overview

Frontend
Integrated with TradingView’s Advanced Charts library to allow native drawing tools and high-fidelity chart interaction.

Extraction Layer (GOX)
Converts user-generated chart drawings into normalized, machine-readable representations.

Validation Engine
Applies deterministic rule checks (e.g. wave relationships, retracements, overlaps) to assess structural consistency.

Research Dataset Pipeline
Stores anonymized drawing events and metadata to support:

Pattern analysis

Label quality evaluation

Training or evaluation of ML/LLM-based assistants

Current Status

MVP live at: https://www.tryelliottwave.com

Demonstrates:

Advanced Charts integration

Drawing capture and persistence

Core validation logic and data workflow

Active focus on:

Data schema refinement

Rule formalization

Research-oriented instrumentation rather than trading signals

Research Scope (Non-Exhaustive)

Potential research directions enabled by GOX include:

Modeling human variability in Elliott Wave interpretation

Rule-based vs probabilistic validation of technical structures

Assisted technical analysis via AI feedback loops

Feature extraction from subjective chart annotations

Hybrid symbolic + statistical representations of market structure

Educational & Institutional Context

The project is currently developed for educational and research purposes, in collaboration with the Instituto de Análisis Técnico Bursátil (IAT) in Mexico, an educational partner of TradingView.

There is no trading execution, brokerage connectivity, or automated decision-making in the current scope.

Future Directions

If validated successfully, GOX could evolve into:

A public research platform for technical analysis cognition

A dataset foundation for AI-assisted market structure interpretation

An educational tool to improve analyst training through structured feedback

Any future commercial deployment would pursue the appropriate licensing agreements and ethical research considerations.

Disclaimer

GOX is a research prototype.
It does not provide financial advice, trading signals, or execution capabilities.

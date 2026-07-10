
# Accesss the app: https://zoeliu-duke.github.io/RNAseqExplorer/

# RNA-seq Explorer — Tutorial

An interactive guide to **RNA-seq Explorer**, a single-file HTML app for bulk RNA-seq
differential-expression analysis — QC, volcano, PCA, heatmap, pathways and TF activity,
all in your browser, with an optional bridge to real **DESeq2** in R for publication figures.

## 📖 Read the guide

**https://zoeliu-duke.github.io/RNAseq_explorer_tutorial/**

## What the tool does

RNA-seq Explorer runs the whole workflow from one HTML file — no server, and your count
data never leaves your machine. It works in two tiers:

- **In-browser** — a fast DESeq2-*style* approximation for instant exploration: quality
  control, differential expression, volcano / PCA / heatmap / scatter, pathway enrichment
  and transcription-factor activity.
- **Real DESeq2 in R** — export a small bundle (count matrices + a ready-to-run R script),
  run genuine DESeq2 with one command, then import the results back so every figure shows
  authoritative DESeq2 numbers.

> The RNA-seq Explorer application is a standalone HTML file — contact the lab for a copy.

## What the guide covers

1. Opening the tool and loading count files
2. Running the in-browser analysis and reading each tab
3. One-time R / DESeq2 setup
4. Exporting to real DESeq2 and importing the results back for every view
5. Exporting publication figures (SVG / PNG, adjustable size)

…plus a button cheat-sheet and troubleshooting.

## Contact

**Yaxin (Zoe) Liu** · zoe.liu@duke.edu
Edward Miao Lab, Duke University

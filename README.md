# PQGuard-MC JSON Configuration Package

This package provides machine-readable configuration files for the PQGuard-MC numerical study.

## Contents
- `config/`: dataset, plant, proposed-controller, baseline, Protocol A/Protocol B, random-seed, statistical, metric, and reported-result JSON files.
- `indices/`: exact 0-based tuning, held-out, paired-trial, Protocol A, and Protocol B signal indices.
- `implementation/PQGuard_MC_Revised_Test.ipynb`: manuscript-aligned reproducibility notebook.
- `implementation/Code_original.ipynb`: supplied source notebook.
- `manifest/sha256_manifest.json`: SHA-256 hashes for package files.

## Protocol mapping
- Protocol A: six-condition held-out composite evaluation used for the main internal baseline comparison and headline results.
- Protocol B: separate fixed composite sequence used for ablation and the same-platform recent predictive-controller comparison.

## Indexing
All sample indices are 0-based row indices within the corresponding SEED-PQD-v1 class CSV.

## Reproduction note
The JSON files freeze the deterministic selections and settings used by the manuscript-aligned reproducibility workflow. The SEED-PQD-v1 dataset itself is not redistributed in this archive.

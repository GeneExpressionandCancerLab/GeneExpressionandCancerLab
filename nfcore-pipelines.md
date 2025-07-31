# 🔬 nf-core Pipelines – Usage at GIGA

This page provides quick access and internal documentation for running [nf-core](https://nf-co.re/) pipelines on the **GIGA cluster**.  

---

## 🔗 Official nf-core Pipelines

| Pipeline       | Description                                                      | GitHub Repo |
|----------------|------------------------------------------------------------------|-------------|
| **ATAC-seq**   | A pipeline for ATAC-seq chromatin accessibility data             | [nf-core/atacseq](https://github.com/nf-core/atacseq) |
| **ChIP-seq**   | A pipeline for ChIP-seq data processing and peak calling         | [nf-core/chipseq](https://github.com/nf-core/chipseq) |
| **Hi-C**       | A pipeline for Hi-C data analysis and visualization              | [nf-core/hic](https://github.com/nf-core/hic) |
| **RNA-seq**    | A pipeline for reference-based transcriptome analysis            | [nf-core/rnaseq](https://github.com/nf-core/rnaseq) |

---

## 📄 Pipeline Usage (Lab Documentation)

We have internal documentation for using each pipeline on GIGA:

- [nfcore-atacseq.md](nfcore-atacseq.md)
- [nfcore-chipseq.md](nfcore-chipseq.md)
- [nfcore-hic.md](nfcore-hic.md)
- [nfcore-rnaseq.md](nfcore-rnaseq.md)

Each page contains:
- ✅ Version used
- ✅ GIGA-specific `submit.sh` script
- ✅ Sample sheet format
- ✅ Parameter tips

---

## 📁 Templates and Examples

This repository includes reusable templates:

| File | Purpose |
|------|---------|
| `submit.sh` | Cluster submission script (edit per pipeline) |
| `samplesheet.csv` | Input sample sheet format |
| `params.json` or `params.yaml` | Optional custom parameters |

You can reuse and adapt these for new projects. Each pipeline doc links to the correct format and example.

---

## 💡 Need Help?

Visit [nf-co.re](https://nf-co.re/) for full pipeline documentation, parameter options, and schema validation tools.

For GIGA-specific questions, refer to your local admin or internal documentation.


---
layout: page
title: Call for Papers
---

## Overview

The {{site.iteration}} RECOMB Satellite Conference on Hardware Acceleration of Bioinformatics Workloads ({{ site.title }} {{site.year}}) will be held on {{site.dates}} in {{site.location}}, just before the main RECOMB conference. {{ site.title }} aims to bring together researchers in the bioinformatics, computational biology, and computer architecture communities to strengthen the progress in accelerating bioinformatics analysis (e.g., genome, transcriptome, proteome analysis) with efficient system designs that include hardware acceleration and software systems tailored for new hardware technologies, including compiler optimizations, APIs, and DSLs that support acceleration platforms.




## Topics

Papers reporting on original research on acceleration of computing in all areas of computational molecular biology are suitable for submission. The emphasis will be on new hardware-algorithm co-design, hardware accelerators (e.g., FPGA, NPU, GPU, PIM),  and domain-specific languages for bioinformatics workloads.

Topics of interest include, but are not limited to:

#### Hardware-Accelerated Genomic Data Processing
- Optimized hardware/algorithms for read mapping, whole-genome alignment, and de novo assembly acceleration
- Architectures for high-throughput genomic data streaming and pre-processing (e.g., base calling, demultiplexing)

#### Hardware Acceleration Techniques and Architectures
- FPGA, GPU, ASIC, PIM (Processing-In-Memory), and NPU (Neural Processing Unit) accelerators for core bioinformatics algorithms
- Hardware/software co-design for computational biology
- Domain-Specific Architectures (DSAs) for bioinformatics workloads (e.g., aligners, variant callers)   
- Novel memory architectures and I/O optimization for large genomic datasets

#### Accelerating Downstream Bioinformatics Analysis
- Hardware-aware algorithms for metagenomics, pan-genomics, and genome graph traversal
- High-speed solutions for single-cell and spatial transcriptomics data processing (e.g., UMI counting, clustering, dimensionality reduction)
- Structural biology and drug design
- Optimization of machine learning/deep learning models (e.g., CNNs, RNNs, Transformers) used in omics for specialized hardware

####  Tools, Languages, and Infrastructure
- Domain-Specific Languages (DSLs) and high-level synthesis tools for programming bioinformatics hardware accelerators
- Static and dynamic optimization passes for bioinformatics workloads
- Optimized Application Programming Interfaces (APIs) for heterogeneous computing platforms for bioinformatics pipelines
- Benchmarking, performance modeling, and energy-efficiency analysis of bioinformatics accelerators
- Cloud and edge computing architectures for accelerated bioinformatics

#### Specific Accelerated Bioinformatics Workloads

- Accelerating dynamic programming algorithms (e.g., Smith-Waterman, Needleman-Wunsch) and their approximations
- Efficient hardware implementations of compression algorithms for genomic data
- Accelerated methods for genome-wide association studies (GWAS) and population genetics
- Hardware-optimized data structures (e.g., k-mer indices, Bloom filters, FM-index, learned indexes)


### Key Dates

Proceedings and Overlay tracks

- **Abstract submission deadline**: {{ site.deadlines.abstract_submission }}
- **Full paper submission deadline**: {{ site.deadlines.paper_submission }}
- **Author notification**: {{ site.deadlines.author_notification }}
- **Conference dates**: {{ site.deadlines.conference_dates }}

Short talks / Posters 

- **Abstract submission deadline**: {{ site.deadlines.poster_and_short_talk_submission }}
- Authors will be notified shortly after submission


## Tracks

We solicit contributions in three categories (“tracks”) as follows.

### Proceedings Track

Manuscripts describing original work on computational aspects of genomic research involving large genomic datasets. Manuscripts in this track will be considered for publication in a special issue of the Bioinformatics journal. At the time of submission, and for the entire review period, the work should not be under review by any other conference or scientific journal. In some rare cases, manuscripts may be deemed to not be suitable for iScience after review but still invited for an oral presentation at {{ site.title }}. In this case, authors will be required to post their manuscripts on a public preprint server (bioRxiv, arXiv, etc.) prior to the conference.

To indicate your submission should be considered for the proceedings track, please include “[Proceedings]” at the end of the paper title.

### Overlay Track

Manuscripts submitted to this track will be reviewed by the program committee, and selected submissions will be invited for oral presentation. The manuscript should be hosted on a public preprint server (bioRxiv, arXiv, etc.) at the time of submission. There are no specific formatting requirements, but the paper should generally be formatted in a way that emphasizes the methodological contributions. We also encourage authors to keep the manuscripts within similar length limits as for the proceedings track. Manuscripts can be submitted elsewhere at the same time but should not be published or in press at the time of submission. For manuscripts that are in press or published, please consider the Highlights track of the main RECOMB conference.

To indicate your submission should be considered for the overlay track, please include “[Overlay]” at the end of the paper title.

### Abstracts for Short Talks or Posters

Regular abstracts describing original work, including software applications. These will be considered for short oral presentations or posters. A 1-2 page abstract describing the methods and key results should be submitted via the EasyChair system.

## Partnership with Bioinformatics

All submissions to the proceedings track will be simultaneously considered for publication in a special issue of the journal Bioinformatics if the authors agree. Bioinformatics is an open-access journal published by Oxford University Press for original research in developments in bioinformatics.

In addition to the program committee of RECOMB-Arch, editors of Bioinformatics will evaluate the proceedings-track papers for biological impact and suitability for publication. In particular, the following criteria will be used to evaluate relevance:

Is the methodology proposed applicable in useful and practical settings and is it open source?
Actual biological data must be used and, in appropriate cases, can be complemented with simulated data.

Authors who do not wish their manuscript to be considered for Bioinformatics should use the overlay track for submission. Publication in Bioinformatics is subject to an Open Access charge. Reduced Open Access charges are available for authors in developing countries and others experiencing financial hardship, and a 15% discount is available for ISCB members.

## Submission Guidelines

Manuscripts for the “proceedings track” should not exceed 10 pages using at least 10-point font on U.S. standard 8 1/2 by 11-inch paper with no less than one-inch margin all around. This excludes the cover page and references. The cover page should have the title, the corresponding author’s email address, and the abstract. An optional short appendix can be included if necessary, but reading it will be at the discretion of the program committee. Manuscripts must be submitted electronically in PDF format via the EasyChair system.

In EasyChair, please select {{ site.title }} {{site.year}}” track when you click “New Submission” in the “author” portal within the [RECOMB conference]({{ site.links.easychair }}).

Authors **must post their submission on a preprint server like bioRxiv**. They should not assume that a formal proceedings volume will be published, as a final decision is still pending. All accepted papers will have opportunities for publication through our journal partners.

### Formatting instructions for paper submission

- **Main paper format**: All paper submissions must be in PDF format. The maximum length is **10 pages (Letter or A4 format)**, including all figures/tables and their captions, using **a minimum font size of 10pt and 1-inch margins**. An additional title page containing the paper title, author list, and abstract is permitted. The bibliography does not count toward the page limit. Submissions that violate the formatting requirement (e.g., by decreasing margins or font sizes) or exceed the page limit may be rejected without review. There is no specific template requirement beyond these guidelines. Authors may choose to use the Springer Lecture Notes in Computer Science template available [here](https://www.overleaf.com/latex/templates/springer-lecture-notes-in-computer-science/kzwwpvhwnvfj#.WtR5Hy5ua71), as long at the above-mentioned page limit and margin requirements are respected.

- **Optional Appendix**: If necessary, an Appendix can be submitted as Supplementary Material in a single PDF file. The Appendix should contain materials directly supporting the paper content. There is no page limit for the Appendix, but please note that reviewing the Appendix is at the discretion of the reviewers.

- **Source code availability**: Importantly, if the paper involves the development of new software or analysis methods, the source code must be made publicly accessible via e.g. a GitHub repository, with a README file that is sufficiently documented by the submission deadline for reviewers to examine. A minimal test dataset must be provided so that the software can be tested on a small example. The link to the public repository must be clearly indicated in the paper.

### Abstract registration

There is a mandatory abstract submission deadline on **{{ site.deadlines.abstract_submission }}**, three days prior to the full paper submissions deadline. This deadline allows the Program Committee to begin planning review assignments ahead of full paper submissions. After the abstract submission deadline has passed, new submissions will not be accepted, but authors can update the full paper submission before the paper submission deadline on **{{ site.deadlines.paper_submission }}**. Please ensure the abstract registration closely aligns with full paper submission in terms of title, author list, and abstract content. "Placeholder" abstract registrations without meaningful descriptions will not be accepted. While minor updates to the abstract are allowed before the full paper submission deadline, any substantial changes to the title or abstract content risk being removed without consideration.


### Contact

All questions about submissions should be emailed to the PC Chair, [{{site.pc_chair1}}]({{ site.links.pc_chair1 }}).






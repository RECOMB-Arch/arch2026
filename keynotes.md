---
layout: page
title: Keynote and Invited Talk
---

{%- assign sp1_path = "images/speakers/SantiagoMarcoSola.jpeg" | relative_url -%}
{%- assign sp2_path = "images/speakers/onur-mutlu.png" | relative_url -%}

<section class="keynote-page">
  <article class="keynote-card">
    <div class="keynote-speaker">
      <img src="{{ sp1_path }}" alt="Santiago Marco-Sola" class="keynote-photo">
      <div>
        <div class="keynote-label">Keynote Speaker</div>
        <h2>Santiago Marco-Sola</h2>
        <p>Barcelona Supercomputing Center</p>
      </div>
    </div>

    <div class="keynote-content">
      <h3>Scale and Complexity: Co-Designing Algorithms and Architectures for Emerging Challenges in Genomics</h3>

      <h4>Abstract</h4>
      <p>
       Genome data analysis is often regarded primarily as a large-scale data problem, driven by the
rapid growth of sequencing throughput and population-scale datasets. Scale, however, is only
part of the challenge. Emerging fields such as pangenomics are changing not only the size of
the data, but also the complexity of the computation. Methods for pangenome graph analysis,
such as graph-based read alignment, haplotype-resolved variant calling, and structural-variation
discovery, rely on richer models, more irregular data structures, and more complex
computational patterns.</p>
<br>

<p>This talk argues that future progress in computational genomics will require algorithms
that exploit problem and input structure to reduce unnecessary work, rather than scaling brute-
force computation with the data. Accelerating these algorithms also requires a broader view of
algorithm and architecture co-design, in which the goal is not only to accelerate today&#39;s
bottlenecks, but to expose reusable algorithmic structures and build flexible hardware
accelerators capable of adapting to new methods and biological questions. Through a critical
review of selected case studies in genomics and pangenomics, this talk argues for moving
beyond monolithic, narrowly targeted accelerator designs, toward systems that combine
specialization and programmability to cope with the ever-increasing scale and complexity of
modern genomics analyses. The future of computational genomics will require algorithms that
compute less, and efficient architectures that can adapt more.
      </p>

      <h4>Bio</h4>
      <p>
        Santiago Marco-Sola is a Tenure-track Professor in the Department of Computer
Science at the Universitat Politècnica de Catalunya (UPC) and a Senior Researcher at the
Barcelona Supercomputing Center (BSC). His research focuses on algorithms, data structures,
high-performance computing, and hardware acceleration for computational biology,
bioinformatics, and precision medicine. He has contributed to widely used bioinformatics tools
and methods, including GEM-Mapper and the Wavefront Alignment algorithm (WFA), and has
published in venues such as Nature Methods, Bioinformatics, PNAS, ISCA, and MICRO. His
recent work explores scalable algorithms and heterogeneous accelerators for genome and
pangenome analysis.
      </p>
    </div>
  </article>
</section>


<section class="keynote-page" id="invited-talk">
  <article class="keynote-card">
    <div class="keynote-speaker">
      <img src="{{ sp2_path }}" alt="Onur Mutlu" class="keynote-photo">
      <div>
        <div class="keynote-label">Invited Talk</div>
        <h2>Onur Mutlu</h2>
        <p>ETH Zurich</p>
      </div>
    </div>

    <div class="keynote-content">
      <h3>Accelerating Genome Analysis</h3>

      <h4>Abstract</h4>
      <p>
       Genome analysis is the foundation of many scientific and medical discoveries as well as a key pillar of personalized medicine. After an individual's genome is sequenced, many computational steps are taken to reconstruct and analyze the genome. Unfortunately, these computational tasks are often very slow and energy hungry, in many cases requiring very expensive computational resources. As a result, even though sequencing technology improvements have enabled high-throughput and portable sequencing devices, like nanopore sequencers, interesting and potentially critical analyses still take days or even weeks and also cannot be performed in portable devices.</p>
<br>

<p>This talk describes our ongoing journey in greatly improving the performance and energy efficiency of genome analysis (with a focus on at least two major issues in genome analysis, i.e., read mapping and metagenomics analysis). We show that significant improvements are possible with both algorithmic and hardware-based approaches and their combination. We conclude with a foreshadowing of future challenges brought about by very low-cost new sequencing technologies and their potential use cases in public health, science, and medicine.</p>
<br>

<p>A short accompanying paper, which appeared at DAC 2023, can be found here and serves as recommended reading:
<a href="https://arxiv.org/abs/2305.00492">"Accelerating Genome Analysis via Algorithm-Architecture Co-Design"</a>.</p>
<br>
<p>A longer overview & survey of modern genome analysis and how to make it intelligent and efficient can be found here and also serves as recommended reading:
<a href="https://arxiv.org/abs/2205.07957">"Going From Molecules to Genomic Variations to Scientific Discovery: Intelligent Algorithms and Architectures for Intelligent Genome Analysis"</a>.
      </p>

      <h4>Bio</h4>
      <p>
        Onur Mutlu is a Professor of Computer Science at ETH Zurich. He previously held the William D. and Nancy W. Strecker Early Career Professorship at Carnegie Mellon University. His research interests are in computer architecture, computing systems, hardware security, memory & storage systems, and bioinformatics, with a major focus on designing fundamentally energy-efficient, high-performance, and robust computing systems. Many techniques he, with his group and collaborators, has invented over the years have largely influenced industry and have been employed in commercial microprocessors and memory & storage systems used daily by billions of people. He obtained his PhD and MS in ECE from the University of Texas at Austin and BS degrees in Computer Engineering and Psychology from the University of Michigan, Ann Arbor. He started the Computer Architecture Group at Microsoft Research (2006-2009), and held product, research and visiting positions at Intel Corporation, Advanced Micro Devices, VMware, Google, and Stanford University. He received various honors for his impactful research, including the 2025 IEEE Computer Society Harry H. Goode Memorial Award “for seminal contributions to computer architecture research and practice, especially in memory systems,” 2024 IFIP Jean-Claude Laprie Award in Dependable Computing (for the original RowHammer work), 2021 IEEE High Performance Computer Architecture Conference Test of Time Award (for the Runahead Execution work), 2022 Persistent Impact Prize of the Non-Volatile Memory Systems Workshop (for the original architectural work on Phase Change Memory), 2025 IEEE/IFIP International Conference on Dependable Systems and Networks Test-of-Time Award (for the AVATAR work), 2023 Huawei OlympusMons Award in Storage Systems, 2021 Intel Outstanding Researcher Award, 2019 ACM SIGARCH Maurice Wilkes Award, and dozens of best paper, “Top Pick” paper, and Best Artifact recognitions at various leading computer systems, architecture, and security venues. He is an AAAS Fellow, ACM Fellow, IEEE Fellow, and an elected member of the Academy of Europe. He enjoys teaching, mentoring, and enabling & democratizing access to high-quality research and education. He has supervised 26 PhD graduates, many of whom received major dissertation & other awards, more than 20 postdoctoral trainees, and more than 70 Master’s and Bachelor’s students. His computer architecture and digital logic design course lectures and materials are freely available on YouTube (<a href="https://www.youtube.com/OnurMutluLectures">Onur Mutlu Lectures</a> and <a href="https://www.youtube.com/@CMUCompArch">CMU Computer Architecture</a>), and his research group (<a href="https://safari.ethz.ch/">SAFARI Research Group</a>) makes a wide variety of open-source artifacts freely available online (<a href="https://github.com/CMU-SAFARI">CMU-SAFARI on GitHub</a>). For more information, please see his webpage at <a href="https://people.inf.ethz.ch/omutlu/">people.inf.ethz.ch/omutlu</a>.
      </p>
    </div>
  </article>
</section>

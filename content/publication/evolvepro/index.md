---
title: "Rapid protein evolution by few-shot learning with a protein language model"
authors:
- Kaiyi Jiang*
- Zhaoqing Yan*
- Matteo Bernardo
- Samantha Sgrizzi
- Lukas Villiger
- Alisan Kayabolen
- BJ Kim
- Josephine Carscadden
- Masahiro Hiraizumi
- Hiroshi Nishimasu
- Jonathan S. Gootenberg 
- Omar O. Abudayyeh

date: "2024-07-18T00:00:00Z"
doi: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: ""

abstract: Directed evolution of proteins is critical for applications in basic biological research, therapeutics, diagnostics, and sustainability. However, directed evolution methods are labor intensive, cannot efficiently optimize over multiple protein properties, and are often trapped by local maxima. In silico-directed evolution methods incorporating protein language models (PLMs) have the potential to accelerate this engineering process, but current approaches fail to generalize across diverse protein families. We introduce EVOLVEpro, a few-shot active learning framework to rapidly improve protein activity using a combination of PLMs and protein activity predictors, achieving improved activity with as few as four rounds of evolution. EVOLVEpro substantially enhances the efficiency and effectiveness of in silico protein evolution, surpassing current state-of-the-art methods and yielding proteins with up to 100-fold improvement of desired properties. We showcase EVOLVEpro for five proteins across three applications, T7 RNA polymerase for RNA production, a miniature CRISPR nuclease, a prime editor, and an integrase for genome editing, and a monoclonal antibody for epitope binding. These results demonstrate the advantages of few-shot active learning with small amounts of experimental data over zero-shot predictions. EVOLVEpro paves the way for broader applications of AI-guided protein engineering in biology and medicine.

# Summary. An optional shortened abstract.
summary: We developed a novel machine learning model to rapidly evolve protein in silico for higher activity. We demonstrated SOTA performance for EVOLVEpro across DMS benchamarks and used it evolve a highly active genome editing toolbox and T7 RNAP that are orders of magnitude higher fiedlity than current used wild-type. 

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.biorxiv.org/content/10.1101/2024.07.17.604015v1

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: (featured.jpg)'
  focal_point: 'Center'
  preview_only: false
  placement: 1
---



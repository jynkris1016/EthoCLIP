# 👀 About AnimalBand and EthoCLIP
Code release for "EthoCLIP: Ontology-Enhanced Video-Language Pretraining for Animal Behavior Understanding"

Vision-language models (VLMs) have achieved remarkable success across numerous domains, yet they lag significantly in animal behavior understanding due to severe data scarcity. Annotated animal behavior videos are prohibitively expensive and time-consuming to collect, requiring domain expertise and controlled observation conditions.

To address this challenge, we leverage structured domain knowledge as an inductive bias from the Neuro Behavior Ontology (NBO), which provides professional annotations, hierarchical behavior structures, and comprehensive semantic coverage. We present EthoCLIP, an ontology-enhanced vision–language contrastive learning framework that explicitly embeds ontology semantics through an ontology-aware graph module to capture hierarchical relationships among behaviors and learn structured semantic dependencies. Incorporating ontological information reduces the burden of learning purely from data, thereby alleviating requirements for large-scale datasets. 

To enhance EthoCLIP training, we construct AnimalBand, an NBO-consistent dataset integrating 74,671 videos across multiple species and behaviors with semantic standardization and extended knowledge coverage.

Extensive experiments validate both our method and dataset. Results demonstrate that EthoCLIP pretrained on AnimalBand substantially improves behavior recognition accuracy and transfer learning performance across diverse benchmarks, confirming that ontology-driven semantic enrichment effectively addresses data scarcity in animal behavior understanding.

<img width="808" height="632" alt="image" src="https://github.com/user-attachments/assets/9bd3b4f0-b0a1-4272-91cf-502865154272" />


# Todo
- [x] AnimalBand data mapping
- [ ] EthoCLIP code and pretrained weights (currently under organization)

## Acknowledgement
Thanks to the open source of the following datasets:
[MammalNet](https://mammal-net.github.io/),[Animal Kingdom](https://sutdcv.github.io/Animal-Kingdom/),[LoTE-Animal](https://lote-animal.github.io/),[Mammalps](https://eceo-epfl.github.io/MammAlps/),[PanAf20K](https://obrookes.github.io/panaf.github.io/)

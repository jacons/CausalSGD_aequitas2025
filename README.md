
# Causal Synthetic Data Generation in Recruitment

The importance of synthetic data generation (SDG) has increased significantly in domains where data quality is poor or access is limited due to privacy and regulatory constraints. One such domain is recruitment, where publicly available datasets are scarce due to the sensitive nature of information typically found in curricula vitae -- such as gender, disability status, or age.
This lack of accessible, representative data presents a major obstacle to the development of fair and transparent machine learning (ML) models, particularly ranking algorithms that require large volumes of data to effectively learn how to recommend candidates. In the absence of such data, these models are prone to poor generalization and may fail to perform reliably in real-world scenarios.
Recent advances in Causal Generative Models (CGMs) offer a promising solution. CGMs enable the generation of synthetic datasets that preserve the underlying causal relationships within the data, providing greater control over fairness and interpretability in the data generation process.
In this study, we present a specialized SDG method involving two CGMs: one modeling job offers and the other modelling curricula. Each model is structured according to a causal graph informed by domain expertise. We use these models to generate synthetic datasets and evaluate the fairness of candidate rankings under controlled scenarios that introduce specific biases.


## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```
    
## Demo

Insert gif or link to demo


## Authors

- [@jacons](https://www.github.com/jacons)


## License

[MIT](https://choosealicense.com/licenses/mit/)


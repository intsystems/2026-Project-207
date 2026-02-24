# LinkReview

- Here we collect all the works that may be useful for writing our paper
- We divide these works by topic in order to structure them

> [!NOTE]
> This review table will be updated, so it is not a final version.

| Topic | Title | Year | Authors | Paper | Code | Summary |
| :--- | :--- | :---: | :--- | :---: | :---: | :--- |
| Topic #1 | Paper Title | Publishing Year | Author #1 et al. | [arXiv/DOI]() | [GitHub]() | Short summary to be inserted in the Related Work section |
| Intrinsic Dimension | Intrinsic Dimension Estimation for Robust Detection of AI-Generated Texts | 2023 | Eduard Tulchinskii et al. | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/file/7baa48bc166aa2013d78cbdc15010530-Paper-Conference.pdf) | [GitHub](https://github.com/ArGintum/GPTID) | Предложен метод PHD для оценки собственной размерности текста. Экспериментально на 10 языках показана стабильность размерности человеческих текстов (9 для европейских, 7 для азиатских),инвариантность к перефразированию. Для нашей работы полезно: код для вычисления PHD, методология вычислений и экспериментов, датасет со статьями Википедии WikiM. |
| Intrincis Dimension | A fractal dimension for measures via persistent homology | 2020 | H. Adams et al. | [arXiv](https://arxiv.org/abs/1808.01079) | [GitHub](https://github.com/CSU-PHdimension/PHdimension) | Теоретические основы PHD. Полезно для работы: код для вычисления PHD. |
| Intrincis Dimension | Paper Title | 2021| B. Schweinhart. | [arXiv](https://arxiv.org/abs/1802.00533) |  | Теоретические основы PHD. Вводится для метрических пространств через экстремальные подмножества. |
| Intrincis Dimension | Intrinsic dimension, persistent homology and generalization in neural networks | 2021 | T. Birdal et al. | [arXiv/DOI](https://arxiv.org/abs/2111.13171) | [GitHub](https://github.com/tolgabirdal/PHDimGeneralization) | Устанавливает связь между PHD и обобщающей способностью нейросетей. Предлагает эффективный алгоритм вычисления PHD через персистентную гомологию с реализациями на CPU (Ripser) и GPU. Полезно для работы: код для вычисления PHD. |
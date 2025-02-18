## 📄 Description
This repository contains the instances used in the paper:

> **"Workflow Scheduling in Cloud Computing using Evolutionary Algorithms"**
>
> Presented at **IWINAC 2024**.
>
> Authors: Pablo Barredo, Jorge Puente
>
> DOI: [10.1007/978-3-031-61137-7_17](https://doi.org/10.1007/978-3-031-61137-7_17)

Scheduling problems require evolutionary methods, but they often struggle with complexity. To enhance solutions, heuristic knowledge can be integrated into fitness functions, although this may introduce bias towards local minima. This paper proposes a cooperative multi-fitness approach that combines genetic diversity with heuristic solutions to support a standard fitness function. Lamarckism can assist in the reconstruction of chromosomes, for direct evaluation by the standard fitness decoder. This combination of genetic diversity and heuristic knowledge aims to achieve superior solutions. This evaluation approach is applied to a genetic algorithm for scientific workflow scheduling, minimizing total execution time in cloud computing.

---

## 📂 Repository Content
- `data/instances/` → Set of instances used in the experiments.
- `results/` → Results obtained after running the algorithm.
- `README.md` → This file with information about the repository.

---

## 📊 Workflow Instances
The instances used in this study come from the original repository:

🔗 **Original Repository**: [https://wfcommons.org/](https://wfcommons.org/)

Since versions have changed over time, this repository stores an exact copy of the instances used in our experiments to ensure reproducibility.

---

## 📥 Using the Instances
To access the instances, download the repository and navigate to the `data/instances/` folder:

```bash
git clone https://github.com/iScOp-uniovi/Paper_IWINAC_2024.git
cd Paper_IWINAC_2024/data/instances/
```

---

## 🔍 Cite this Work
If you use these instances or the results of this study in your work, please cite our paper as follows:

```
@inproceedings{Barredo2024IWINAC,
  author    = {Pablo Barredo and Jorge Puente},
  title     = {Workflow Scheduling in Cloud Computing using Evolutionary Algorithms},
  booktitle = {Proceedings of the International Work-Conference on Artificial and Natural Computation (IWINAC)},
  year      = {2024},
  doi       = {10.1007/978-3-031-61137-7_17}
}
```

---

## 📧 Contact
For any questions or inquiries about this work, please contact:  
✉️ **[puente@uniovi.es](mailto:puente@uniovi.es)**

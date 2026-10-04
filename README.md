# 📚 Paper & Book Notes

A personal reading archive for academic papers, literature, and nonfiction.

The goal of this repository is not only to keep summaries, but to leave a searchable record of what I understood, questioned, and want to revisit.

## Repository Structure

```text
.
├── papers/
│   ├── README.md
│   └── network-science/
│       ├── README.md
│       └── YYYY-short-title.md
├── books/
│   ├── README.md
│   ├── literature/
│   │   └── README.md
│   └── nonfiction/
│       └── README.md
└── templates/
    ├── paper-review-template-eng.md
    ├── paper-review-template-kr.md
```

## Status

| Status | Badge | Meaning |
| :---: | :---: | :--- |
| Done | ![Done](https://img.shields.io/badge/Done-brightgreen) | Finished reading and review |
| In Progress | ![In Progress](https://img.shields.io/badge/In--Progress-orange) | Reading or drafting |
| To Read | ![To Read](https://img.shields.io/badge/To--Read-lightgrey) | Backlog |

## Academic Papers

### Network Science

| Status | Year | Title | Venue | Keywords | Review |
| :---: | :---: | :--- | :--- | :--- | :---: |
| ![Done](https://img.shields.io/badge/Done-brightgreen) | 1983 | Stochastic blockmodels: First steps. | Social Networks | SBM, Network Analysis | [Review](./papers/network-science/1983-SBM.md) |
| ![In Progress](https://img.shields.io/badge/In--Progress-orange) | 2008 | Mixed membership stochastic blockmodels. | NeurIPS | MMSBM, Network Analysis | [Review](./papers/network-science/2008-MMSBM.md) |
| ![To Read](https://img.shields.io/badge/To--Read-lightgrey) | 2022 | A Statistical Model of Bipartite Networks: Application to Cosponsorship in the United States Senate | Political Analysis | Bipartite Networks, MMSBM, Variational Inference | [Review](./papers/network-science/2022-biMMSBM.md) |

More details: [`papers/README.md`](./papers/README.md)

## Books

Book notes are separated by the type of reading because the questions worth recording are different.

- **Literature** — novels, short stories, plays, poetry, and other literary works: [`books/literature/`](./books/literature/)
- **Nonfiction** — philosophy, history, science, technology, society, essays, and other general books: [`books/nonfiction/`](./books/nonfiction/)

See [`books/README.md`](./books/README.md) for conventions.

## Naming Convention

- Papers: `YYYY-short-title.md`
- Books: `author-short-title.md`
- Use lowercase/kebab-case when practical; established abbreviations such as `SBM` or `MMSBM` are fine.
- Keep one review per file.

## Templates

- Paper review (English): [`templates/paper-review-template-eng.md`](./templates/paper-review-template-eng.md)
- Paper review (Korean): [`templates/paper-review-template-kr.md`](./templates/paper-review-template-kr.md)
- Literature review: [`templates/literature-review-template.md`](./templates/literature-review-template.md)
- Nonfiction review: [`templates/nonfiction-review-template.md`](./templates/nonfiction-review-template.md)

Review files can be written in Korean, English, Japanese, or any other language as needed.

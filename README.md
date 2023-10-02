# a template electronic lab notebook
_with a little help from jupyter_

## overview
[what project is this repo for?]

## structure
by default, we divide this repository into several subdirectories which you're likely to find useful.

```
.
├── experiments/
│   └── YYYYMMDD_experiment_name/
│       ├── notebook.ipynb
│       └── data/
│           └── results.csv
├── data/
│   └── master.csv
├── code/
│   └── script.py
├── protocols/
│   └── sample_prep.md
├── tests/
│   └── testing.py
├── README.md
└── LICENSE
```

- `experiments` is home to notebooks describing daily progress on experiments, alongside any (smallish) raw data they've generated. musings, rants, observations, logs, and hypotheses all live here.
- `data` is for bigger datasets, especially any that have been transformed, concatenated, or are otherwise widely used.
- `code` hosts custom modules, scripts, and pipelines created for this project.
- `protocols` contains template files describing oft-repeated experimental procedures for easy reference.
- `tests` is for the unit tests that you will definitely, um, get around to writing someday.
- every high-level directory ought to have descriptive `README`.
- an appropriate `LICENSE` should be chosen to protect your work as needed.

## instructions
1. click 'use this template'
2. add a title and description
3. adjust licensing as needed
4. go do transparent, reproducible science!

### acknowledgements
all this is heavily inspired by (and forked from!) Griffin Chure's [template for reproducible research](https://github.com/gchure/reproducible_research). you can make your own ASCII filetrees at [tree.nathanfriend.io](https://tree.nathanfriend.io).


# Practice Project Two: Napoleon's Russian Campaign

## Introduction

This project, "Napoleon's Russian Campaign," recreates the renowned data visualization [Charles Minard's Napoleon's disastrous Russian campaign of 1812](https://en.wikipedia.org/wiki/Charles_Joseph_Minard#/media/File:Minard.png). We used `pandas` and `sqlite3` to build the database, and used `matplotlib` and `basemap` for proof of concept and to produce the finished product.

## How to Reproduce

- Install [Miniconda](https://docs.anaconda.com/miniconda)
- Build the environment based on `environment.yml`

```bash
conda env create -f environment.yml
```

- Place `minard.txt` from the `data/` folder into a `data/` folder in your working directory.
- Activate the environment and run `python create_minard_db.py` to create `minard.db` in the `data/` folder.
- Activate the environment and run `python plot_with_basemap.py` to generate `minard_clone.png`

![minard_clone](minard_clone.png)
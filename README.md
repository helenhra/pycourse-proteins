# Protein structures in RCSB PDB
This project was created as an exam project for the python course HEL-8048 at the UiT.

It explores data from RCSB PDB (Research Collaboratory for Structural Bioinformatics Protein Data Bank) - e.g., how many and what kind of structures are stored in the database.

## File overview
`env.yml` environment file with dependencies

`project.ipynb` jupyter notebook containing code and explanations

`project.pdf` pdf version of the jupyter notebook with outputs

`pdb_data_no_dups.csv` dataset with part of data from  RCSB PDB, retrieved from [kaggle](https://www.kaggle.com/datasets/shahir/protein-data-set)

`LICENSE` includes the terms and conditions of the GNU General Public Licence

## How to use
Project can be cloned from GitHub:
```bash
git clone https://github.com/helenhra/pycourse-proteins
```
Instalation of a conda environment with all required Python packages:
```bash
conda env create -f env.yml
```

## Required Python packages
`pandas` (version 2.2.3)

`altair` (version 5.5.0)

`biotite` (version 1.2.0)


## Authors
[@helenhra](https://github.com/helenhra)

## How to cite
```tex
@misc{
    title = {Protein structures in RCSB PDB}
    author = {Helena Hradiská}
    year = {2025}
    url = {https://github.com/helenhra/pycourse-proteins}
}
```

## Contributing
Pull requests are welcome. For major changes, please discuss with the author.

## License
[MIT](https://choosealicense.com/licenses/mit/)

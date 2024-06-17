![LOGO](https://github.com/dsushnikova/xlr/figs/logo.png)

<!-- Reproducible material for **XXX -
Ravasi M., Author M., Author C.** submitted to XXX. -->

## Intro

In this project, we propose a novel method for solving linear systems with large dense operators, right-hand side, and unknown matrices by simultaneously approximating all three matrices using a shared bases assumption. Our approach showcases its effectiveness in the challenging field of seismic imaging, specifically in Multidimensional Deconvolution (MDD) for redatuming applications, where it offers more accuracy and efficiency than conventional methods. Additionally, we introduce a novel H2-like approximation for 3D applications to further streamline MDD implementations, enhancing robustness and reducing computational overhead.

## Project structure
This repository is organized as follows:

<!-- * :open_file_folder: **package**: python library containing routines for ....; -->
* :open_file_folder: **data**: folder containing data (or instructions on how to retrieve the data
* :open_file_folder: **examples**: set of jupyter notebooks reproducing the experiments in the paper (see below for more details);
* :open_file_folder: **scripts**: set of python scripts used to run multiple experiments ...

## Examples
The following notebooks are provided:

- :orange_book: ``vsv_lr_ds1.ipynb``: xlr method with global low-rank approximation, dataset 1;
- :orange_book: ``vsv_ds2.ipynb``: xlr method with global low-rank approximation, dataset 2;
- :orange_book: ``h2_ds1.ipynb``: xlr method with H2 approximation, dataset 1;
- :orange_book: ``h2_ds2.ipynb``: xlr method with H2 approximation, dataset 2;


<!-- ## Getting started :space_invader: :robot:
To ensure reproducibility of the results, we suggest using the `environment.yml` file when creating an environment.

Simply run:
```
./install_env.sh
```
It will take some time, if at the end you see the word `Done!` on your terminal you are ready to go. After that you can simply install your package:
```
pip install .
```
or in developer mode:
```
pip install -e .
```

Remember to always activate the environment by typing:
```
conda activate my_env
```

Finally, to run tests simply type:
```
pytest
``` -->

<!-- **Disclaimer:** All experiments have been carried on a Intel(R) Xeon(R) CPU @ 2.10GHz equipped with a single NVIDIA GEForce RTX 3090 GPU. Different environment
configurations may be required for different combinations of workstation and GPU. -->

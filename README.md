# Uplift Modeling for Preventing Student Dropout in Higher EducationUplift Modeling for Preventing Student Dropout in Higher Education </br><sub><sub>D. Olaya, S. Maldonado - J. M. Pina - W. Verbeke [[DSS 2020]](https://doi.org/10.1016/j.dss.2020.113320)</sub></sub>

Uplift modeling is an approach for estimating the incremental effect of an action or treatment at the individual level. This project implements the uplift modeling framework to maximize the effectiveness of retention efforts in higher education institutions i.e., improvement of academic performance by offering tutorials. The objective is to improve the design of retention programs by tailoring them to students who are more likely to be retained if targeted. Students who participated in the tutorials are considered the treatment group, otherwise, they are assigned to the nontreatment group.

## Repository structure
This repository is organised as follows:
```bash
|- notebooks/
    |- main.ipynb
|- src/
    |– _init_.py
    |- bias_check.py
    |- plots.py
    |- predictive_models.py
    |- preprocess.py
    |- stratified_cv.py
    |– uplift_models.py
```

## Installing
We have provided a `requirements.txt` file:
```bash
pip install -r requirements.txt
```
Please use the above in a newly created virtual environment to avoid clashing dependencies.

## Citations
Please cite our paper and/or code as follows:

```tex

@article{olaya2020uplift,
  title={Uplift Modeling for preventing student dropout in higher education},
  author={Olaya, Diego and V{\'a}squez, Jonathan and Maldonado, Sebasti{\'a}n and Miranda, Jaime and Verbeke, Wouter},
  journal={Decision Support Systems},
  volume={134},
  pages={113320},
  year={2020},
  publisher={Elsevier}
}

```

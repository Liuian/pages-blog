---
layout: default
title: Miniconda
---
-  create new environment
    - `conda create -n {env name} python={version}`
    - ex: `conda create -n py3.8 python=3.8`
- list all envs
    - `conda env list`
- list packages in env
    - `conda list`
- Install package:
    - `conda install`
    - `pip install`
    - 最好首先使用conda install
- Installation Channel
    - `conda-forge` & `pip`
    - `conda install -c conda-forge osmium-tool==1.14.0`
    - `conda install -c pip pyyaml`
    - -c 是channel的意思


### In codespace 

#### Creation of new codespace 
1. Create a new  Codespace (click the button above!) using this repo. 
2. Select repository, branch, Region and machine type (8-core [32GBRAM 64GB] if it is available)
3. (Optional) Press `Ctrl+Shit+p` to select `Add Dev Container`> `Create a new env` > Anaconda (python3) > Conda, Mamba (Miniforge) > Keep Defaul
4. Open one of the notebooks `deep_leaarning_mab>1-Intro-dl_MLPs.ipynb`
5. Click `Select kernel` button in the upper-right and select `Install and Enable suggested extensions` > `Python Env` > `base Python (opt/conda/bin/python)`
6. Have fun! 🚀

* Add packages to `base`` virtual env in the terminal for codespace
```
conda update -n base pip -c conda-forge # environment location: /opt/conda/envs/base
pip install ipykernel torch torchvision matplotlib
python -c 'import torch; torch.cuda.is_available()'
```



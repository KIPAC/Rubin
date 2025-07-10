#### 1. Cloning the env

In a NERSC terminal

```console
source /global/cfs/cdirs/lsst/groups/PZ/DP1/pz/software/config/nersc_conda.bashrc
pz_miniconda3_setup
conda create --name <new_environment_name> --clone rail-1.2
```

#### 2. Adding a jupytner kernelspec

In a NERSC terminal

```console
python -m ipykernel install --user --name <new_environment_name> --display-name <new_environment_name>
```


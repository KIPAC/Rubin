#### 1. Using the shared RAIL environment at NERSC

In a NERSC terminal

```console
source /global/cfs/cdirs/lsst/groups/PZ/DP1/software/config/nersc_conda.bashrc
pz_miniconda3_setup
conda activate rail-1.2
```

#### 2. Adding a jupytner kernelspec 

In a NERSC terminal

```console
python -m ipykernel install --user --name rail-1.2 --display-name rail-1.2
```

#### 3. Getting the notebooks

In a NERSC terminal

```console
cd <somewhere nice>
git clone git@github.com:eacharles/rail_raruma.git
```

Then look in ```rail_raruma/nb/DP1``` for notebooks


#### 4. Running the notebooks

Go to https://jupyter.nersc.gov/ and pick rail-1.2

You might also have to re-pick rail-1.2 inside of the notebook interface

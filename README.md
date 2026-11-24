# GRA-41624-Deep-Learning

To install a consistent environment that works both for mac and windows laptop I suggest following the steps:
1. If you don't have [Ana/mini]conda in your mac 
    curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh
    bash Miniconda3-latest-MacOSX-arm64.sh
2. conda create -n DL_EXAM_env python=3.13 ipykernel numpy pandas matplotlib
3. After running the create script, activate the environment
    conda activate DL_EXAM_env
4. pip install --upgrade pip
5. pip install tensorflow
6. pip install tensorflow-metal
# pytorch learning sources

```bash
git clone --recurse-submodules git@github.com:yanyongyu/pytorch-learning.git
```

To create an python environment using [`conda`](https://docs.conda.io/en/latest/miniconda.html) and [`poetry`](https://python-poetry.org/):

```bash
conda create -n pytorch python=3.8  # or higher
conda activate pytorch

# install pytorch by conda
# https://pytorch.org/get-started/locally/#start-locally

# CUDA 10.2
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
# CUDA 11.1
# conda install pytorch torchvision torchaudio cudatoolkit=11.1 -c pytorch -c nvidia

# install base dependencies
poetry install
# install extra dependencies: jupyter notebook
# poetry install -E jupyter
```

## d2l

[book](https://zh-v2.d2l.ai/), [course](https://courses.d2l.ai/zh-v2/)

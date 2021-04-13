Notebook to convert some microscopic videos
-------------------------------------------

Notebook uses pim-s python library that is using bioformats conversion library under the hood. 
All dependences (including jupyter lab and pims) are included in the conda environment. 
You can use micromamba, conda or anaconda to set it up. 
Here are the instructions for micromamba:
* install micromamba with:
```
wget -qO- https://micromamba.snakepit.net/api/micromamba/linux-64/latest | tar -xvj bin/micromamba
./bin/micromamba shell init -s bash -p ~/micromamba
source ~/.bashrc
```
* create the environment from file
```
micromamba create -f environment.yaml
micromamba activate microscope_video_conversion
```
Run jupyter lab notebooks inside micromamba environment:
```
jupyter lab notebooks
```

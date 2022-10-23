# Using Conda

### Install Conda

https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html

---

### If conda command not found:

> export PATH="<a>{file_path}</a>/miniconda3/bin:$PATH"

---

### if need to preset environment

> conda env create -f conda.yaml -n my_env
> 
create environment according conda.yaml file, which name (my_env) override the file name setting.

Example of conda.yml: 

> /conda.yml

Env File Path:
> <a>{path}</a>/miniconda3/envs

---

### Other:

Install the jupyer:
> conda install -y jupyter

Go to the virtual environment of Conda:
> conda activate base
> 
Similar to source create virtual environment of Python:
> python3 -m venv path/venv
> 
> source path/venv/bin/activate
> 
Finally, deactivate the environment of conda:
> conda deactivate

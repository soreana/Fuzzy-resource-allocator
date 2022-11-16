# Fuzzy Resource allocator

Install the following package

* matplotlib
* jupyterlab
* numpy
* pandas

My python version was 3.10.6, but the code should work with python version 3.6+, I didn't use any magical thing in background.

## Run

```bash
sina@ccc ~ []$ pip install matplotlib jupyterlab numpy pandas # access libraries
sina@ccc ~ []$ jupyter-lab --generate-config # generate configuration
sina@ccc ~ []$ vim .jupyter/jupyter_lab_config.py # edit the "c.ServerApp.notebook_dir" field and change it to the directory were you cloned this project for example c.ServerApp.notebook_dir = u'/root/labs/'
sina@ccc ~ []$ jupyter-lab # run jupyter, it gives you a link to access the web interface
```


## TODO
* add references
* add docker
* add more algorithms
* add Documentations
* make it run on github

https://matplotlib.org/stable/gallery/misc/table_demo.html#sphx-glr-gallery-misc-table-demo-py

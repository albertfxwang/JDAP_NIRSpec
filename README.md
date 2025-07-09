# JDAP_NIRSpec

data and code for hands-on training on JWST NIRSpec MSA spectroscopy

Steps to setup a new working conda env to run through the notebooks

```
$ conda deactivate
$ conda create -n msaexp python=3.12 numpy cython scipy
$ conda activate msaexp
$ bash msaexp_setup.sh
```


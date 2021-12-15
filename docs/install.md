The easiest way to install phrokka is via conda using

`conda install phrokka -c gbouras13`

This will install all the dependencies along with phrokka.

Alternatively, phrokka can be installed manually via github

`git clone https://github.com/gbouras13/phrokka.git`

The dependencies found in other_files/requirements.yaml will then need to be installed manually.

For example using conda:

```
conda env create -f environment.yml
conda activate phrokka_env
git clone https://github.com/gbouras13/phrokka.git
```
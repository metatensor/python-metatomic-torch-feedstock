About python-metatomic-torch-feedstock
======================================

Feedstock license: [BSD-3-Clause](https://github.com/metatensor/python-metatomic-torch-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/metatensor/metatomic

Package license: BSD-3-Clause

Summary: Python bindings for metatomic-torch

Documentation: https://docs.metatensor.org/metatomic/

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-python--metatomic--torch-green.svg)](https://anaconda.org/metatensor/python-metatomic-torch) | [![Conda Downloads](https://img.shields.io/conda/dn/metatensor/python-metatomic-torch.svg)](https://anaconda.org/metatensor/python-metatomic-torch) | [![Conda Version](https://img.shields.io/conda/vn/metatensor/python-metatomic-torch.svg)](https://anaconda.org/metatensor/python-metatomic-torch) | [![Conda Platforms](https://img.shields.io/conda/pn/metatensor/python-metatomic-torch.svg)](https://anaconda.org/metatensor/python-metatomic-torch) |

Installing python-metatomic-torch
=================================

Installing `python-metatomic-torch` from the `metatensor` channel can be achieved by adding `metatensor` to your channels with:

```
conda config --add channels metatensor
conda config --set channel_priority strict
```

Once the `metatensor` channel has been enabled, `python-metatomic-torch` can be installed with `conda`:

```
conda install python-metatomic-torch
```

or with `mamba`:

```
mamba install python-metatomic-torch
```

It is possible to list all of the versions of `python-metatomic-torch` available on your platform with `conda`:

```
conda search python-metatomic-torch --channel metatensor
```

or with `mamba`:

```
mamba search python-metatomic-torch --channel metatensor
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search python-metatomic-torch --channel metatensor

# List packages depending on `python-metatomic-torch`:
mamba repoquery whoneeds python-metatomic-torch --channel metatensor

# List dependencies of `python-metatomic-torch`:
mamba repoquery depends python-metatomic-torch --channel metatensor
```




Updating python-metatomic-torch-feedstock
=========================================

If you would like to improve the python-metatomic-torch recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`metatensor` channel, whereupon the built conda packages will be available for
everybody to install and use from the `metatensor` channel.
Note that all branches in the metatensor/python-metatomic-torch-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@Luthaf](https://github.com/Luthaf/)


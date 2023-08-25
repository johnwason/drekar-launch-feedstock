About drekar-launch-feedstock
=============================

Feedstock license: [BSD-3-Clause](https://github.com/wasontech/drekar-launch-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/johnwason/drekar-launch

Package license: Apache-2.0

Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <img src="https://img.shields.io/badge/noarch-disabled-lightgrey.svg" alt="noarch disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-drekar--launch-green.svg)](https://anaconda.org/wasontech/drekar-launch) | [![Conda Downloads](https://img.shields.io/conda/dn/wasontech/drekar-launch.svg)](https://anaconda.org/wasontech/drekar-launch) | [![Conda Version](https://img.shields.io/conda/vn/wasontech/drekar-launch.svg)](https://anaconda.org/wasontech/drekar-launch) | [![Conda Platforms](https://img.shields.io/conda/pn/wasontech/drekar-launch.svg)](https://anaconda.org/wasontech/drekar-launch) |

Installing drekar-launch
========================

Installing `drekar-launch` from the `wasontech` channel can be achieved by adding `wasontech` to your channels with:

```
conda config --add channels wasontech
conda config --set channel_priority strict
```

Once the `wasontech` channel has been enabled, `drekar-launch` can be installed with `conda`:

```
conda install drekar-launch
```

or with `mamba`:

```
mamba install drekar-launch
```

It is possible to list all of the versions of `drekar-launch` available on your platform with `conda`:

```
conda search drekar-launch --channel wasontech
```

or with `mamba`:

```
mamba search drekar-launch --channel wasontech
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search drekar-launch --channel wasontech

# List packages depending on `drekar-launch`:
mamba repoquery whoneeds drekar-launch --channel wasontech

# List dependencies of `drekar-launch`:
mamba repoquery depends drekar-launch --channel wasontech
```




Updating drekar-launch-feedstock
================================

If you would like to improve the drekar-launch recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`wasontech` channel, whereupon the built conda packages will be available for
everybody to install and use from the `wasontech` channel.
Note that all branches in the wasontech/drekar-launch-feedstock are
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

* [@johnwason](https://github.com/johnwason/)


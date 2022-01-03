About r-modes
=============

Home: http://www.sdeevi.com/modes_package https://github.com/sathish-deevi/modes-Package/

Package license: CC-BY-NC-SA-4.0

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-modes-feedstock/blob/master/LICENSE.txt)

Summary: Designed with a dual purpose of accurately estimating the mode (or modes) as well as characterizing the modality of data. The specific application area includes complex or mixture distributions particularly in a big data environment. The heterogeneous nature of (big) data may require deep introspective statistical and machine learning techniques, but these statistical tools often fail when applied without first understanding the data. In small datasets, this often isn't a big issue, but when dealing with large scale data analysis or big data thoroughly inspecting each dimension typically yields an O(n^n-1) problem. As such, dealing with big data require an alternative toolkit. This package not only identifies the mode or modes for various data types, it also provides a programmatic way of understanding the modality (i.e. unimodal, bimodal, etc.) of a dataset (whether it's big data or not). See <http://www.sdeevi.com/modes_package> for examples and discussion.

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=2274&branchName=master">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-modes-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--modes-green.svg)](https://anaconda.org/conda-forge/r-modes) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-modes.svg)](https://anaconda.org/conda-forge/r-modes) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-modes.svg)](https://anaconda.org/conda-forge/r-modes) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-modes.svg)](https://anaconda.org/conda-forge/r-modes) |

Installing r-modes
==================

Installing `r-modes` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-modes` can be installed with:

```
conda install r-modes
```

It is possible to list all of the versions of `r-modes` available on your platform with:

```
conda search r-modes --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-modes-feedstock
==========================

If you would like to improve the r-modes recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-modes-feedstock are
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

* [@conda-forge/r](https://github.com/conda-forge/r/)


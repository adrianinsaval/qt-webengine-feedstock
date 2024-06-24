About qt-webengine-feedstock
============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/qt-webengine-feedstock/blob/main/LICENSE.txt)

Home: http://qt.io

Package license: LGPL-3.0-only

Summary: Qt is a cross-platform application and UI framework.

Development: https://github.com/qt

Documentation: http://doc.qt.io/

Qt helps you create connected devices, UIs & applications that run
anywhere on any device, on any operating system at any time.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-qt--webengine-green.svg)](https://anaconda.org/freecad/qt-webengine) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/qt-webengine.svg)](https://anaconda.org/freecad/qt-webengine) | [![Conda Version](https://img.shields.io/conda/vn/freecad/qt-webengine.svg)](https://anaconda.org/freecad/qt-webengine) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/qt-webengine.svg)](https://anaconda.org/freecad/qt-webengine) |

Installing qt-webengine
=======================

Installing `qt-webengine` from the `freecad` channel can be achieved by adding `freecad` to your channels with:

```
conda config --add channels freecad
conda config --set channel_priority strict
```

Once the `freecad` channel has been enabled, `qt-webengine` can be installed with `conda`:

```
conda install qt-webengine
```

or with `mamba`:

```
mamba install qt-webengine
```

It is possible to list all of the versions of `qt-webengine` available on your platform with `conda`:

```
conda search qt-webengine --channel freecad
```

or with `mamba`:

```
mamba search qt-webengine --channel freecad
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search qt-webengine --channel freecad

# List packages depending on `qt-webengine`:
mamba repoquery whoneeds qt-webengine --channel freecad

# List dependencies of `qt-webengine`:
mamba repoquery depends qt-webengine --channel freecad
```




Updating qt-webengine-feedstock
===============================

If you would like to improve the qt-webengine recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/qt-webengine-feedstock are
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

* [@Tobias-Fischer](https://github.com/Tobias-Fischer/)
* [@andfoy](https://github.com/andfoy/)
* [@ccordoba12](https://github.com/ccordoba12/)
* [@duncanmmacleod](https://github.com/duncanmmacleod/)
* [@gillins](https://github.com/gillins/)
* [@mingwandroid](https://github.com/mingwandroid/)
* [@msarahan](https://github.com/msarahan/)
* [@ocefpaf](https://github.com/ocefpaf/)
* [@stuarteberg](https://github.com/stuarteberg/)


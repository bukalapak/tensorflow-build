This repository contains custom builds of tensorflow. To install
one of these on your system, download the correct file according
to your version of python and gcc and run the following command.
```
pip install --ignore-installed --upgrade /path/to/binary.whl
```
You can also install directly from github using
```
pip install --ignore-installed --upgrade "Download URL"
``

| TF       | HW       | OS           | Python        | Supports                    |                                         |
|----------|----------|--------------|---------------|-----------------------------|-----------------------------------------|
| 1.10.1  | CPU      | Debian Stretch | 3.5 | XLA, AVX, AVX2, FMA, SSE4.2 | [Link](https://github.com/mind/wheels)  |
| 1.10.1   | CPU      | Debian Stretch | 3.6         | XLA, AVX, AVX2, FMA, SSE4.2 | [Link](https://github.com/yaroslavvb/tensorflow-community-wheels/issues/26) |`

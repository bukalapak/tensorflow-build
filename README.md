This repository contains custom builds of tensorflow. To install
one of these on your system, download the correct file according
to your version of python and gcc and run the following command.
```
pip install --ignore-installed --upgrade /path/to/binary.whl
```
You can also install directly from github using
```
pip install --ignore-installed --upgrade "Download URL"
```

| TF       | HW       | OS           | Python        | Supports                    |                                         |
|----------|----------|--------------|---------------|-----------------------------|-----------------------------------------|
| 1.10.1  | CPU      | Debian Stretch | 3.5 | XLA, AVX, AVX2, FMA, SSE4.2 | [Link](https://github.com/bukalapak/tensorflow-build/releases/download/1.10.1-py3.5/tensorflow-1.10.1-cp35-cp35m-linux_x86_64.whl)  |
| 1.10.1   | CPU      | Debian Stretch | 3.6         | XLA, AVX, AVX2, FMA, SSE4.2 | [Link](https://github.com/bukalapak/tensorflow-build/releases/download/1.10.1-py3.6/tensorflow-1.10.1-cp36-cp36m-linux_x86_64.whl) |`

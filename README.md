# ds_tut

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

This file will become your README and also the index of your
documentation.

## Install

``` sh
pip install ds_tut
```

## How to use

## Download Datasets

``` python
from pathlib import Path

print("this should not be testet!")
assert False

archive_name = "reuters21578.tar.gz"
training_data_url = "http://www.daviddlewis.com/resources/testcollections/reuters21578/{}".format(archive_name)
data_root = Path.cwd() / "data"
training_data_path = data_root / archive_name
data_size = download_from_url(training_data_url, training_data_path)
print(data_size)
```

    this should not be testet!

    AssertionError: 

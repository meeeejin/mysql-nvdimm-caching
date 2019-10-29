# NVDIMM Caching for MySQL

Optimize MySQL/InnoDB using NVDIMM 

## Build and install

1. Clone the source code: 

```bash
$ git clone https://github.com/meeeejin/mysql-nvdimm-caching.git
```

2. Change the value of `BASE_DIR` in the `build.sh` file to the desired value.

```bash
$ vi build.sh
#!/bin/bash

BASE_DIR=/home/xxx/mysql-nvdimm-caching
...
```

3. Run the script file:

```bash
$ ./build.sh
```

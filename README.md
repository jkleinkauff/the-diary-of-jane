# the-diary-of-jane



# Conda

## Create Environments

### Python 2.7

```bash
conda create --name env-dir1-p27 python=2.7
```

### Python 3.6

```bash
conda create --name env-dir2-p36 python=3.6
```

## List environments

```bash
conda env list
```

## Activate environments

```bash
$ conda activate env-dir1-p27
$ python --version
Python 2.7.18 :: Anaconda, Inc.
$ conda install boto3
$ pip list
...
boto3           1.17.7             
botocore        1.20.7 
...

$ conda activate env-dir2-p36
$ python --version
Python 3.6.12 :: Anaconda, Inc.
$ conda install requests
$ pip list
...
requests     2.25.1
...
```




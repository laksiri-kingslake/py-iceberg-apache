# PyIceberg - Apache Iceberg
A practical guide for PyIceburg. This guide is arranged in a way that you can practice using Jupyter or Colab notebooks.

## Part - I
In the first part, we will be using SQLite database as our data store. However, it is best practice to use an object storage. Part - I is based on the official quick start guide arranged in a way that you can practice using Jupyter or Colab notebooks.

## Step by Step Instruction

1. Setting-up environment and activate

If you are running notebook files directly in vscode, it is always a good idea to activate a virtual environment.

```bash
# linux or mac
# create a virtual environment
python3 -m venv venv
# activate the virtual environment
source venv/bin/activate
# deactivate the virtual environment
deactivate

# windows
# create a virtual environment
python -m venv venv
# activate the virtual environment
venv\Scripts\activate
```

Select activated virtual environment as the kernel.

**Note:** Below Code blocks can be copied to Jupyter notebook files. In Colab notebooks replace %pip with !pip.

2. Install dependencies

```python
# install dependencies
%pip install --upgrade pip
%pip install "pyiceberg[s3fs,hive]"
%pip install "pyiceberg[sql-sqlite]"
%pip install pyarrow
```

## Reference

1. [Getting started with PyIceberg](https://py.iceberg.apache.org/)
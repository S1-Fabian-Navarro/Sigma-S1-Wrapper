# Sigma-S1-Wrapper

Jupyter Notebook to convert sigma rules to S1 PQ, using sigma libraries and backend for S1


## How to use it:

Replace the sentinelone_pq.py with the one provided in this repo
``C:\Users\USER_NAME\AppData\Local\anaconda3\Lib\site-packages\sigma\pipelines\sentinelone_pq\sentinelone_pq.py``

Set the path to your sigma rules on the variable ``file_path = ``


## Dependencies
    - Anaconda or JupyterNotebooks
    - Libraries:
                            !pip install sigma-cli
                            !pip install pysigma
                            !pip install pysigma-backend-sentinelone-pq

## Limitations:

The official ``pysigma-backend-sentinelone-pq`` pipeline file lacks some field mapping, hence not all event categories or fields are supported, eventhough a modified pipeline file is provided, this includes some of the fields missing on the original repo

## References:
[sigma-cli](https://github.com/SigmaHQ/sigma-cli)
[PySigma](https://github.com/SigmaHQ/pySigma/)
[Sigma Backends](https://sigmahq.io/docs/digging-deeper/backends)


# setup 

## date

```bash
date - Wed Nov 20 09:57:40 AM CET 2024
```

## base system

```bash
uname -a
Linux debian 6.1.0-27-amd64 #1 SMP PREEMPT_DYNAMIC Debian 6.1.115-1 (2024-11-01) x86_64 GNU/Linux
```

## install python

```bash
sudo apt update  
sudo apt upgrade 
sudo apt autoclean
```

## test / install python

```bash
python3 --version
> Python 3.11.2

[install python](https://reintech.io/blog/install-python3-pip-debian-12)

pip3 --version
> pip 24.2 from /home/trapapa/workspace_python/yt_vid_alg_trading/.venv/lib/python3.11/site-packages/pip (python 3.11)

[install venv — Creation of virtual environments](https://docs.python.org/3/library/venv.html)

```

## [install lib](https://www.interactivebrokers.com/campus/ibkr-quant-news/ib_insync-guide-interactive-brokers-api/)

 ```bash
 pip install ib_insync
 ```


 ## test tws connection TWS must running on the SAME host

 ```python
from ib_insync import *

util.startLoop()  # only use in interactive environments (i.e. Jupyter Notebooks)
 ```
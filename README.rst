PRM
---
pip repository manager

Use
---
.. code-block:: shell
$ prm list
pypi                https://pypi.org/simple

douban              https://pypi.douban.com/simple

tencent             https://mirrors.cloud.tencent.com/pypi/simple

aliyun              https://mirrors.aliyun.com/pypi/simple/
$ prm show
Current: https://mirrors.cloud.tencent.com/pypi/simple
$ prm use pypi
Setting to pypi
$> prm show
Current: https://pypi.org/simple
$ prm --help
Usage: prm [OPTIONS] COMMAND [ARGS]...

Options:
  --help  Show this message and exit.

Commands:
  list
  show
  use

Install
-------
.. code-block:: shell
pip install prm

Author
------
Yixian Du

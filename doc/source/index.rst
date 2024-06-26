..
   Just reuse the root readme to avoid duplicating the documentation.
   Provide any documentation specific to your online documentation
   here.


.. toctree::
   :hidden:
   :maxdepth: 3

   api
   contribute


=====================================================
``ansys-tools-path``: 一个查找 Ansys 产品的工具
=====================================================

How to install
==============

.. include:: ../../README.rst
   :start-after: .. howtoinstallusers_start
   :end-before: .. howtoinstallusers_end


How to use
----------

您可以使用 :ref:`ref_api` 中的任何可用函数来识别本地 ANSYS 安装的路径。

例如，可以使用 :func:`find_ansys <ansys.tools.path.find_ansys>` 查找 ANSYS 最新安装的可用路径：

.. code:: python

   >>> from ansys.tools.path import find_ansys
   >>> find_ansys()
   'C:/Program Files/ANSYS Inc/v211/ANSYS/bin/winx64/ansys211.exe', 21.1


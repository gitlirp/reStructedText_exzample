.. reStructedTest exzamples documentation master file, created by
   sphinx-quickstart on Wed Sep  2 17:28:43 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

reStructedTest 代码示例
====================================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

常用示例
=======================

表格
--------------

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

* www
* www

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
|                        |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
|                        | column 2   | column 3            |
+                        +------------+----------+----------+
| body row 2             | ...        | addr     |  op      |
+------------------------+------------+----------+----------+


====================  ==========  ===============
Header row, column 1  Header 2    Header 3
====================  ==========  ===============
body row 1, column 1  column 2    column 3
body row 2            Cells may    span columns
====================  ==========  ===============

列表
--------------

* 条目
* 条目


- 条目
- 条目

a. 条目
#. 条目
#. 条目

正文
-------
普通的文本段落之间，还有块级元素之间，必须使用一个空行加以区分，否则会被
reStructuredText 折叠到上一行。

第二个段落，与上一段落分开了。

第三个段落，这个段落我换行但不空行，你将看到这个段落没有换行。
这是因为最初创建 reStructuredText
这个项目是为了写代码文档，而程序员都习惯硬换行，而为了区隔英语单词，
折叠上去的每一行前都加了一个空格。
如果希望硬断行且不自动添加空格（例如中文文章），在行尾添加一个反斜杠。\
折上去的部分就不会有空格。注意所有的硬换行都要对齐缩进。\

| 第四个段落，段内的换行。
| 用竖线和空格开头，之后的每一行
| 在渲染时都会单独成行。
| 这功能不常用，因为用列表会更美观。

看不懂也没关系，你只要记住一个段落就一直往下写，新段按两下回车。

.. note::

    写完本文我发现我用的渲染器对中文自动消除了空格，行尾不加反斜杠也行，但我不\
    保证其他渲染器也这么智能，所以原样保留了文内的反斜杠。

Test Setion0
=======================
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www

Test Setion1
=======================
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www

Test Setion2
=======================
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www

Test Setion3
=======================
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www

Test Setion4
=======================
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www

Test Setion5
=======================
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www

Test Setion6
=======================
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
#. www
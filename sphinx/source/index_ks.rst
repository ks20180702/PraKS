.. Sample documentation master file, created by
   sphinx-quickstart on Fri Oct 12 17:22:09 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
.. .. image:: ../uml_generated/test.png
.. 	:align: center
.. :height: 100px (length)
.. :width: 200px (length or percentage of the current line width)
.. :scale: integer percentage (the "%" symbol is optional)
.. :alt: alternate text
.. :align: "top", "middle", "bottom", "left", "center", or "right"
.. :target: text (URI or reference name)

整个首页,此处展现的是各种用法的例子
======================================

.. toctree::
      :maxdepth: 2
      :caption: 目录:

      myThink/myTIndex
      umlTest
      projectDetail/projectDIndex
      privateByKs/privateBKIndex

Indices and tables
==================

二级标题
------------
   我是有空格的,
   我是下面一部分。

   我是没有空格的,
   我是下面一部分。

*一个星号*

**两个星号**

`一个反引号`
``两个反引号``

列表
~~~~~~~~

* 无序列表，
* 无序列表，
   我是第二部分

1. 有序。

   #. 有序11
   #. 有序22 

2. 有序2


.. csv-table:: 使用csv生成表格
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out,
   it wouldn't becrunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"

.. list-table:: Frozen Delights!
   :widths: 15 10 30
   :header-rows: 1

   * - Treat
     - Quantity
     - Description
   * - Albatross
     - 2.99
     - On a stick!
   * - Crunchy Frog
     - 1.49
     - If we took the bones out, it wouldn't be
       crunchy, now would it?
   * - Gannet Ripple
     - 1.99
     - On a stick!

这个段落包含一个 `超链接ks`_.


中间最少空一行即可

.. _超链接ks: https://domain.invalid/

这里94-101是引用

.. _my-reference-label:

Section to cross-reference
--------------------------

This is the text of the section.

| It refers to the section itself, see :ref:`my-reference-labelks`.

.. | 如果标签没有放在标题之前，则需要使用 :ref:`Link title <label-name>` 来指定名称。

Lorem ipsum [Ref]_ dolor sit amet.

.. [Ref] Book or article reference, URL or whatever.

有点像论文里面引用的感觉

Lorem ipsum [1]_ dolor sit amet ... [2]_

.. rubric:: Footnotes

.. [1] Text of the first footnote.
.. [2] Text of the second footnote.

Since Pythagoras, we know that :math:`a^2 + b^2 = c^2`.

.. graphviz::

   digraph foo {
      "bar" -> "baz";
   }


.. 这里不支持这个扩展mermaid，部署上去会报包找不到的问题，本地是没问题的

..    sequenceDiagram
..       participant Alice
..       participant Bob
..       Alice->John: Hello John, how are you?
..       loop Healthcheck
..           John->John: Fight against hypochondria
..       end
..       Note right of John: Rational thoughts <br/>prevail...
..       John-->Alice: Great!
..       John->Bob: How about you?
..       Bob-->John: Jolly good!



* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


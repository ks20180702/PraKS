pandoc 想法
=====================

特性
~~~~~~~~~~

* 用于文档间类型转变
    * 常见：docx->markdown
    * 最常用：docx->docx，将word按指定格式(另一个模板word)，重新排版
* 使用命令行操作(类型python，不使用ide)
    * 注意：使用3个文档，template.docx为模板文档，为预设格式文件。

a.md为当前已有文档，需要进行格式修改。a.docx为生成文档。
    * 按照指定模板文件格式转变文档：pandoc --reference-doc=template.docx a.md -o a.docx
    * markdown 转 html5 独立文件       pandoc -s -o output.html input.md
    * markdown 转 latex               pandoc -f markdown -t latex -o hello.tex hello.txt
    * markdown 转 reveal.js html      pandoc -s -t revealjs slides.md
    * 合并多个文件生成一个 pandoc file1.md file2.md file3.md -o result.docx
    * 还有很多常用的其他命令，查百度

**当输出为word文档时，一些记录**

模板文档一般里面为无实际内容但包含许多‘样式’的文档。当前已有文档中符合指定样式条件的段落、表格、标题等会自动变成模板文件中的样式。
且生成的文件中的样式会包含模板中的所有样式(例如：通常创建的word只包含标题，正文等，若在模板中有‘巨巨标题’这个样式，则生成的文件也可选择此样式)。

初试pandoc,可访问 `markdown转word文档`_

.. _markdown转word文档: https://www.cnblogs.com/kofyou/p/14932700.html

# About This Guide #
本文档介绍了Apache Solr的所有重要特性和功能。可以从这里免费下载：[http://lucene.apache.org/solr/](http://lucene.apache.org/solr/.)。

本文档写作之初的定位就是要提供一个较高层次的文档，提供更为广博的内容，而不是一本手把手的入门手册。可以提供多层次的需要，从新手入门到有经验的开发者扩展自己应用或者解决难题。在软件开发生命周期的任何时候，它都可以提供一份权威的指南帮助你了解Solr。

本文档假定你已经熟悉搜索引擎的基础概念，并且你能够阅读XML。并不要求你一定是Java开发者，但有一定的Java知识，可以更好的直接使用Lucene或者开发Lucene/Solr的自定义扩展。

## 内部注释 ##
文档中包含了以下特殊的注释。
<table>
<tr>
<th>注释类型</th><th>展现样式</th>
</tr>
<tr>
<td>信息</td><td><img src="images/icon-hint.png" /> 提示有重要的信息需要关注</td>
</tr>
<tr>
<td>提示</td><td><img src="images/icon-success.png" /> 有帮助的建议提示</td>
</tr>
<tr>
<td>警告</td><td><img src="images/icon-problem.png" /> 警告信息</td>
</tr>
<tr>
<td>注释</td><td><img src="images/icon-warning.png" /> 标明在使用Solr中需要特别注意的关键点</td>
</tr>
</table>

## Hosts和Port示例 ##
启动Solr的默认端口是8983，在本文档中的示例、URL、截图可能会使用不同的端口号，是因为Solr使用的端口号是可以自定义设置的。如果你没有进行自定义设置，在接下来的例子中，你需要使用默认的8983端口，或者使用自己定义的端口号。关于设置端口号参见[管理Solr]()。

同样的，示例中的URL使用的都是'localhost',如果你访问的是远程机器上的Solr，需要把'localhost'换成具体的域名或者IP。

## 路径 ##
路径信息都是相对于solr.home的相对路径，solr.home是安装的Solr目录下保存Solr collections和它们的conf、data目录的路径。当运行本文档中的示例时，比如：bin/solr -e techproducts，solr.home是自动为你创建的example/目录的子目录。

本文档是开源搜索引擎Apache Solr的参考手册，你可以从Solr的官方网站下载Solr：[http://lucene.apache.org/solr/](http://lucene.apache.org/solr/.)。

本文档包含以下主题：

**Getting Started**：介绍Solr的安装与配置

**Solr管理后台的使用**：介绍Solr的Web管理后台，在浏览器中可以查看配置文件、提交查询、查看日志文件配置、Java环境参数以及监控和控制分布式配置等功能。

**Documents、Fields以及Schema的设计**：介绍Solr是怎样给数据建立索引的，怎样在schema文件中定义字段以及字段类型，来实现对数据索引。

**理解分析器(Analyzers)、分词器(Tokenizers)和过滤器(Filters)**：介绍Solr如何对文本进行索引和检索。分析器Analyzers)解析文本并产生一连串的字符(tokens)和词法单元(lexical units)用于建立索引和检索。分词器(Tokenizers)将字段的数据解析成字符单元(tokens)。过滤器(Filters)对tokens进行其他的转换处理和过滤操作。

**建索引(Indexing)及索引操作基础**：介绍建索引的过程以及基础的索引管理操作，如commit、optimize和rollback。

**检索(Searching)**：对Solr的检索过程进行了整体介绍，介绍了检索过程中用到的组件，包括request handlers、query parsers、response writers。介绍了可用的查询参数，以及boosting、faceting等高级特性。

**Solr实例配置详解**：介绍Solr性能调优,以及如何配置solrconfig.xml、solr.xml、Lucene index writer等。

**管理Solr**：介绍运行和监控Solr的关键点，如何备份Solr实例，如何在Solr中使用JMX(Java Management Extensions)等。

**SolrCloud**：介绍Solr最新的特性，支持分布式检索的SolrCloud。

**遗留系统的扩展与切分**：介绍如何将已有的比较大的索引切分成可部署到多台机器上的shards，或者把单个索引复制成多个来提供多个服务。

**Client APIs**：介绍各种连接Solr的客户端APIs，包括JavaScript、JSON、Ruby等。
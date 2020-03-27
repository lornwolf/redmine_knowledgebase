# Redmine Knowledgebase Plugin

克隆自：
https://github.com/southbridgeio/redmine_knowledgebase

1、修复了与redmine_questions插件的冲突。

2、与redmineup_tags插件冲突解决方法：

从数据库中删掉tags和taggings这两个表，和其相关的索引，再安装redmine_knowledge。

由redmine_knowledge生成的tags和taggings表，tags插件也能用，所以两个插件可以共存。
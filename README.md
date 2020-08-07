# Redmine Knowledgebase Plugin

克隆自：
https://github.com/southbridgeio/redmine_knowledgebase

1、修复了与redmine_questions插件的冲突。

2、平铺显示文章时，原版是显示缩略图，模糊不清影响体验，我改成了显示高清原图。

3、本插件与redmineup_tags插件有冲突，需手动解决，解决方法如下：

&ensp;&ensp;&ensp;从数据库中删掉tags和taggings这两个表，和其相关的索引，再安装redmine_knowledge。

&ensp;&ensp;&ensp;※ 由redmine_knowledge生成的tags和taggings表，tags插件也能用，所以两个插件可以共存。
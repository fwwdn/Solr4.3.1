# Solr4.3.1
配置好的Solr，分词器使用IK。

使用步骤：
1. 拷贝solr目录到web服务器，如：tomcat的webapp目录下。
2. 拷贝solr_home到任意目录，如：/home目录下。
3. 修改solr目录中的web.xml，配置solr_home的路径为:/home/solr_home。
4. 启动web服务器，访问:http://localhost:8080/solr即可看到solr后台页面。


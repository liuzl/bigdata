# ElasticSearch
[Getting Started](https://www.elastic.co/guide/en/elasticsearch/reference/current/getting-started.html).

## 基本命令
1. 启动服务 `./bin/elasticsearch`
2. 检查cluster健康状况 `curl 'localhost:9200/_cat/health?v'`
3. 查看cluster中的nodes `curl 'localhost:9200/_cat/nodes?v'`
4. 查看cluster中的Index `curl 'localhost:9200/_cat/indices?v'`

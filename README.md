# logstash_opensearch

plugin issue reinstall plugins 

bin/logstash-plugin uninstall logstash-output-opensearch
bin/logstash-plugin install logstash-output-opensearch


for plugins refer https://docs.aws.amazon.com/opensearch-service/latest/developerguide/managedomains-logstash.html

If IAM based authentication use logstash-output-amazon_es plugin
```
bin/logstash-plugin install logstash-output-amazon_es
```
https://github.com/awslabs/logstash-output-amazon_es

else 
use logstash-output-opensearch
```
bin/logstash-plugin install logstash-output-opensearch
```
https://github.com/opensearch-project/logstash-output-opensearch

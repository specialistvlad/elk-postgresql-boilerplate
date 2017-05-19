* Postgresql > csv files > filebeat > logstash
Setup your Postgresql to write csv files
`log_destination = 'csvlog'`

Download filebeat (download, unzip)
`https://www.elastic.co/downloads/beats/filebeat`

Run filebeat with config from project folder
filebeat/filebeat -e -c filebeat.yml


* Logstash > Elastic > Kibana > User
Start apps
`docker-compose up`

Check elastic cluster health
`curl http://elastic:changeme@127.0.0.1:9200/_cat/health`

Access kibana web interface(wait up to 1min for first run)
`http://localhost:5601`
credentials: elastic:changeme

How to stop containers?
`docker-compose down`

This app work with your existing postgres data, so you need to stop postgres:
`brew services stop postgresql`

Start apps
`docker-compose up`

Check elastic cluster health
`curl -u elastic http://127.0.0.1:9200/_cat/health`
credentials: elastic:changeme

Access kibana web interface
`http://localhost:5601`
credentials: kibana:changeme

How to stop and remove containers?
`docker-compose down`

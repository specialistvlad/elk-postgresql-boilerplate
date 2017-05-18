This app work with your existing postgres data, so you need to stop postgres:
`brew services stop postgresql`

Start apps
`docker-compose up`

Access kibana web interface
`http://localhost:unknown`

How to stop and remove containers?
`docker rm elastic-kibana-pg-postgres -f`

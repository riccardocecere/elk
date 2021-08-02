# elk

# Le porte esposte dello stack ELK solo le seguenti

- 5044: Logstash Beats input
- 5000: Logstash TCP input
- 9600: Logstash monitoring API
- 9200: Elasticsearch HTTP
- 9300: Elasticsearch TCP transport
- 5601: Kibana

# Deploy Elastic stack with the command:
$ docker stack deploy -c docker-stack.yml elk

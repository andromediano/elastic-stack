ARG VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${VERSION}

# https://www.elastic.co/guide/en/elasticsearch/plugins/current/analysis-nori.html
RUN elasticsearch-plugin install analysis-nori

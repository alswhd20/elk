ARG ELK_VERSION

# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch:7.3.2


RUN bin/elasticsearch-plugin install analysis-nori

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu

# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch:5.3.0

#RUN elasticsearch-plugin install x-pack
RUN elasticsearch-plugin install mapper-attachments
RUN elasticsearch-plugin install ingest-attachment

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu

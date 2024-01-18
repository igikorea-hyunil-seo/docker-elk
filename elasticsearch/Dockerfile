ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION}

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
# 언어 교정기
RUN elasticsearch-plugin install analysis-icu
# 노리 - 한글 분석기
RUN elasticsearch-plugin install analysis-nori
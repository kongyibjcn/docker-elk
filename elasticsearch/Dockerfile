FROM elasticsearch:5.5.1

COPY ./config/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml

# 数据存储文件不在版本库中
VOLUME [ "/usr/share/elasticsearch/data" ]

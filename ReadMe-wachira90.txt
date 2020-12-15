

docker-compose up -d

docker-compose ps

hdfs dfsadmin -safemode leave
#Safe mode is OFF

hdfs dfs -chmod -R 0775  /tmp

docker exec -it datanode3  bash


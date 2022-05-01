Redis Cluster Docker
==========

Docker compose로 구성된 Redis cluster

- 클러스터를 구성하기 위해서는 최소 3개의 이상의 레디스 노드가 필요해 3개의 레디스 노드를 각각 다른 포트로 구성됨
- 레디스 노드들은 각각 6300, 6301, 6302번 포트로 실행됨
- 실행되는 포트 번호를 변경하려면 compose와 redis*.conf 파일의 port를 수정
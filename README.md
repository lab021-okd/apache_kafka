Apache Kafka
============

OKD 클라우드 플랫폼 구축 시 각 세부를 지원하기 위해 Apache Kfafa에 대한 Docker 이미지와 OKD Cateogry Templdate를 구축하였다.

## Apache Kafka
Apache Kafka(아파치 카프카)는 LinkedIn에서 개발된 분산 메시징 시스템으로써 2011년에 오픈소스로 공개되었다. 대용량의 실시간 로그처리에 특화된 아키텍처 설계를 통하여 기존 메시징 시스템보다 우수한 TPS를 보여주고 있다


## Docker
이미지의 모든 버전은 약간의 변형 만있는 동일한 스크립트 세트로 빌드된다 (즉, 특정 기능은 이전 버전에서는 지원되지 않는다). 버전 형식은 Kafka 형식 인 <scala version>-<kafka version>과 같다. 처음에 모든 이미지는 http://kafka.apache.org/downloads에 문서화 된 권장 스칼라 버전으로 빌드된다.

## Template
OKD에서 실행 가능한 template 파일로서 기본적인 구성을 통해 사용자가 컴스텀하게 변경 가능하도록 구성을 했다.


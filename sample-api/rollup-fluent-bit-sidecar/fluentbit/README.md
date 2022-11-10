fluent-bit을 sidecar injection하기 위한 별도 docker image 생성파일

다음과 같이 수행합니다.

docker build . -f ./Dockerfile -t oscka/fluent-bit-sidecar:0.1

# k8s-Infra-repo

별도로 K8s 기본 인프라 레포지토리를 remote로 따로 생성
레포지토리에 deployment에 변경된 새로운 버전의 이미지가 항상 반영
새로운 도커이미지가 빌드되면 해당 이미지의 빌드넘버가 k8s 인프라에 반영되서 새롭게 커밋 발생
이 작업은 jenkins 프리스타일 내에서 Shell 스크립트로 실행

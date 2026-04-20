# gemma4-fork

플랫폼 통합 저장소입니다.

이 저장소는 게임 서비스와 배치 서비스를 서브모듈로 연결하여 운영하는 상위 오케스트레이션 레이어 역할을 합니다.

## 서브모듈 구성
- services/stockgod-game -> https://github.com/janny0902/StockGOD-Game.git
- services/jadiss-learn-batch -> https://github.com/janny0902/jadiss-learn-batch.git

## 시작 방법
1. 저장소 복제
   - git clone --recurse-submodules https://github.com/janny0902/gemma4-fork.git
2. 서브모듈 동기화
   - git submodule update --init --recursive

## 운영 원칙
- 게임/배치는 각 서브모듈에서 독립 배포 가능
- 플랫폼 저장소는 공통 문서, 배포 오케스트레이션, 운영 규약 중심으로 관리

## 공개 문서 정책
- README와 운영 문서는 국문 우선
- 비밀정보(비밀번호, 토큰, 키) 커밋 금지

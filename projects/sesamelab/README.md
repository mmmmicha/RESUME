# SESAMELAB(참깨연구소)
- 회사 정보: https://www.sesame-lab.com/

### 엘리베이터 로컬 에이전트
- 분류: ``실무``
- 소개: TK, 현대, OTIS 등의 CRT 모니터 서버와 통신할 수 있는 로컬 에이전트 서버
- 기간: 2023.05 ~ 2023.07
- 역할
  - OTIS_EMS 모니터 서버에 커맨드를 주고 받는 에이전트 서버 개발 및 유지보수
- 기술스택: C#, Dotnet Core, AWS(rds(mysql)) ...
<br/>

### Background worker
- 분류: ``실무``
- 소개: Keyring 앱 통계를 위해 만든 프로세스
- 기간: 2023.01 ~ 2023.07
- 역할
  - 생성된 유저 / 단지 / 발급된 키를 통계내는 배치 프로그램 개발 및 유지보수
  - 키 사용현황을 통계내는 배치 프로그램 개발 및 유지보수
- 기술스택: Nodejs, typescript, nextjs, mongoDB, docker, linux, AWS(ec2, vpc, rds(mysql)) ...
<br/>

### Backoffice
- 분류: ``실무``
- 소개: Keyring 등 사내 서비스 사용 및 관리의 편의를 위한 툴
- 기간: 2022.04 ~ 2023.07
- 역할
  - keyring notice 관리 시스템 풀스택 개발 및 유지보수
  - keyring pushnotification 관리 시스템 풀스택 개발 및 유지보수
  - 파일 업로드 시스템 풀스택 개발 및 유지보수
- 기술스택: typescript, nextjs, mongoDB, vercel, linux, AWS(s3, beanstalk, ECS, ECR, codepipeline ...), FCM ...
<br/>

### [![Keyring](https://github.com/wjdrhkd456/RESUME/blob/main/projects/sesamelab/keyring/images/keyring_logo.jpg)](https://play.google.com/store/apps/details?id=com.keywe.keyring) [Keyring](https://www.keyring.life/)
- 분류: ``실무``
- 소개: 블록체인을 적용한 공동현관 키 통합 플랫폼
- 기간: 2021.08 ~ 2023.07
- 역할
  - 배포시스템 구축(codepipeline 기반 / github action 기반)
  - 앱 API 및 블록체인 릴레이 기능의 서버 개발 및 유지보수
  - hyperledger fabric chaincode 개발 및 유지보수
  - certification 서버 개발 및 유지보수
  - timer 서버 개발 및 유지보수
  - pushnotification 서버 개발 및 유지보수
- 기술스택: Nodejs, typescript, nextjs, mongoDB, docker, linux, AWS(ec2, vpc, rds(mysql), s3, beanstalk, ECS, ECR, codepipeline ...), FCM, Redis, hyperledger fabric ...
<br/>

### [![Keyin](https://github.com/wjdrhkd456/RESUME/blob/main/projects/sesamelab/keyin/images/keyin_logo.jpg)](https://play.google.com/store/apps/details?id=com.keywe.keyring) Keyin
- 분류: ``실무``
- 소개: Raonark 도어락을 제어 및 관리하기 위해 만들어진 프로젝트
- 기간: 2021.06 ~ 2021.10
- 역할
  - 도어락 CRUD, 파트너 관리, 도어락 제어 및 핀코드 변경등을 수행하는 앱 API 서버 개발 및 유지보수
    - docker 를 이용한 컨테이너, 로그 관리 및 배포
- 기술스택: C#, Dotnet Core, docker, linux, AWS(ec2, vpc, rds(mysql)), FCM, Redis ...
<br/>

### KeyweOn
- 분류: ``실무``
- 소개: 자체 생산한 도어벨을 제어 및 관리하기 위해 만들어진 프로젝트
- 기간: 2021.06 ~ 2021.10
- 역할
  - 도어벨 제어서버 앞단에 위치하는 도어벨 CRUD, 파트너 관리 등을 수행하는 앱 API 서버 개발 및 유지보수
    - docker 를 이용한 컨테이너, 로그 관리 및 배포
- 기술스택: C#, Dotnet Core, docker, linux, AWS(ec2, vpc, rds(mysql)), FCM, Redis ...
<br/>

### Premo IoT
- 분류: ``실무``
- 소개: ZWave 프로토콜을 이용하는 도어락 및 허브 정보 / 파트너정보 / 핀코드 등을 관리하며, ZWave 장치들을 제어하기 위해 만들어진 프로젝트
- 기간: 2021.04 ~ 2023.07
- 역할
  - 서버 모니터링 및 유지보수(mgrv, onda 등의 업체들의 개발cs 대응)
    - docker 를 이용한 컨테이너, 로그 관리 및 배포
    - 비동기로 구성된 API를 동기로 변환하는 작업 수행
- 기술스택: C#, Dotnet Core, docker, linux, AWS(ec2, vpc, rds(mysql)), Redis ...
<br/>
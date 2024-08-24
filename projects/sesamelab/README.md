# SESAMELAB(참깨연구소)

- 회사 정보: https://www.sesame-lab.com/

## 프로젝트

### 엘리베이터 로컬 에이전트

- 소개: TK, 현대, OTIS 등의 CRT 모니터 서버와 통신할 수 있는 로컬 에이전트 서버
- 구성원: 2명
- 기간: 2023.05 ~ 2023.07
- 역할
  - OTIS_EMS 모니터 서버에 커맨드를 주고 받는 에이전트 기능 구현 및 유지보수
- 기술스택: C#, Dotnet Core, AWS(rds(mysql)) ...
  <br/>

### 아파트 단지 정보 스케쥴러

- 소개: 전국 아파트 단지 정보를 지속적으로 관리하기 위해 구축한 스케쥴러
- 구성원: 1명
- 기간: 2023.01 ~ 2023.07
- 역할
  - 네이버 부동산 api를 통해 받아온 단지 정보들을 기반으로 내부 DB에 최신화하는 기능 구현 및 유지보수
- 기술스택: Expressjs, Nodejs, typescript, docker, linux, AWS(ec2, vpc, rds(mysql)) ...

### 통계 스케쥴러

- 소개: Keyring 앱 통계를 위해 구축한 스케쥴러
- 구성원: 1명
- 기간: 2023.01 ~ 2023.07
- 역할
  - 생성된 유저 / 단지 / 발급된 키에 대한 통계 기능 구현 및 유지보수
  - 키 사용현황에 대한 통계 기능 구현 및 유지보수
- 기술스택: Expressjs, Nodejs, typescript, mongoDB, docker, linux, AWS(ec2, vpc, rds(mysql)) ...
  <br/>

### 백오피스

- 소개: Keyring 등 사내 서비스 관리를 위한 백오피스 어플리케이션
- 구성원: 1명
- 기간: 2022.04 ~ 2023.07
- 역할
  - keyring notice 관리 시스템 풀스택 개발 및 유지보수
  - keyring pushnotification 관리 시스템 풀스택 개발 및 유지보수
  - 파일 업로드 시스템 풀스택 개발 및 유지보수
- 기술스택: typescript, nextjs serverless, mongoDB, vercel, linux, AWS(s3, beanstalk, ECS, ECR, codepipeline ...), FCM ...
  <br/>

### [![Keyring](./keyring/images/keyring_logo3.jpg)](https://play.google.com/store/apps/details?id=com.keywe.keyring)

### [Keyring](https://www.keyring.life/)

- 소개: 블록체인을 적용한 공동현관 키 통합 플랫폼
- 구성원: 2명(백엔드 한정)
- 기간: 2021.08 ~ 2023.07
- 역할
  - 블록체인 릴레이 서버 개발, 운영 및 유지보수
  - certification 서버 개발, 운영 및 유지보수
  - timer 서버 개발, 운영 및 유지보수
  - AWS lambda 기반의 serverless framework 를 통한 pushnotification 서버 개발, 운영 및 유지보수
  - Auto CI/CD 시스템 구축(ECS + codepipeline 기반)
  - hyperledger fabric 환경 설정 및 구축 / 유지보수
  - hyperledger fabric chaincode 개발 및 유지보수
- 기술스택: Expressjs, typescript, mongoDB, docker, linux, AWS(ec2, vpc, rds(mysql), s3, beanstalk, ECS, ECR, codepipeline ...), FCM, Redis, hyperledger fabric, serverless framework(aws lambda) ...
  <br/>

### [![Keyin](./keyin/images/keyin_logo2.jpg)](https://play.google.com/store/apps/details?id=com.keywe.keyring)

### Keyin

- 소개: Raonark 도어락 제어 및 관리 어플리케이션
- 구성원: 1명(백엔드 한정)
- 기간: 2021.08 ~ 2022.01
- 역할
  - 도어락 CRUD, 파트너 관리, 도어락 제어 및 핀코드 변경등을 수행하는 앱 API 서버 개발 및 유지보수
    - docker 를 이용한 컨테이너, 로그 관리 및 배포
- 기술스택: C#, Dotnet Core, docker, linux, AWS(ec2, vpc, rds(mysql)), FCM, Redis ...
  <br/>

### KeyweOn

- 소개: 자체 생산한 도어벨을 제어 및 관리하기 위해 만들어진 어플리케이션
- 구성원: 2명(백엔드 한정)
- 기간: 2021.06 ~ 2021.10
- 역할
  - 도어벨 제어서버 앞단에 위치하는 도어벨 CRUD, 파트너 관리 등을 수행하는 앱 API 서버 개발 및 유지보수
    - docker 를 이용한 컨테이너, 로그 관리 및 배포
- 기술스택: C#, Dotnet Core, docker, linux, AWS(ec2, vpc, rds(mysql)), FCM, Redis ...
  <br/>

### Premo IoT

- 소개: ZWave 프로토콜을 이용하는 도어락 및 허브 정보 / 파트너정보 / 핀코드 등을 관리하며, ZWave 장치들을 제어하기 위해 만들어진 서버
- 구성원: 2명(백엔드 한정)
- 기간: 2021.04 ~ 2023.07
- 역할
  - 서버 모니터링 및 유지보수(mgrv, onda 등의 업체들의 개발cs 대응)
    - docker 를 이용한 컨테이너, 로그 관리 및 배포
    - 비동기로 구성된 API를 동기로 변환하는 작업 수행
- 기술스택: C#, Dotnet Core, docker, linux, AWS(ec2, vpc, rds(mysql)), Redis ...
  <br/>

## 저는 도전전문가입니다.

이전 회사(klnet)에서는 주로 자바와 JSP를 사용하여 웹개발을 진행했습니다. 그러나 지금의 회사(sesamelab)에서는 완전히 다른 환경과 기술을 사용하고 있었습니다. C#이 주 언어로 사용되며, AWS와 Docker와 같은 비교적 신기술들을 활용하고 있었습니다.

회사 내에는 백엔드 개발자가 저를 포함하여 3명뿐이었으며, 각자가 담당한 업무가 많다보니 자세한 인수인계와 도움을 받기란 어려운 상황이었습니다. 그러던 중 선임 개발자가 퇴사하며 메인 서비스의 유지보수까지 맡게 되었습니다.

가까스로 적응을 하고 있던 무렵, 회사에서는 블록체인 개발자가 없는 상황에서 블록체인을 도입하고자 했고, 기반지식이 없는 상태에서 도전을 시도했습니다. 이 무렵 우리팀은 C#을 벗어나 Node.js 기반의 프로그래밍을 시도하고 있기도 했습니다.

여러모로 막막했지만 팀장님께 받은 많은 도움과 웹에서 얻은 레퍼런스들을 기반으로 앱을 런칭하게 되었습니다. 블록체인을 도입하는 과정에서 레퍼런스가 부족하여 적용하는 데 어려움이 컸지만 시행착오 끝에 메인 서비스에 적용할 수 있었던 부분은 뿌듯함이 컸습니다. AWS 인프라를 공부하여 CodePipeline을 기반으로한 배포 자동화 시스템을 구축하기도 했습니다.

도전은 늘 두렵지만 어떻게든 시작하고 헤쳐나가다보면 시행착오 끝에 배움과 성공이 있다고 믿고 있습니다. 이런 새로운 도전을 통해 끊임없이 성장하고 있습니다.

## 서비스 운영 중 큰 장애를 해결해 본 경험이 있습니다.

키링 서비스 유지보수 중 로그 시스템을 새롭게 도입한 당일날, 충분한 모니터링을 마쳤다고 생각하고 퇴근했습니다. 회사는 신사동에 위치해 있었고 저는 가까운 강남에서 친구들과 시간을 보내고 있었습니다.

얼마지나 직원들로부터 앱에 문제가 있는 것 같다는 메시지를 받았습니다. 간담이 서늘해지며 폰으로 모니터링을 했는데, 퇴근 후 어느 정도 시간이 지난 뒤에 서버 트래픽이 급격히 증가하면서 CPU 사용률이 100%로 치솟고 서버가 다운되었습니다. 다행인건지 서버가 재시작 및 오토스케일링을 하며 간간이 동작되고 있었습니다.

장애가 지속된지 어느 덧 30분이 지난 시점이었고, 즉시 약속장소를 뛰쳐나와 회사로 복귀했습니다. 다행히 원인을 빠르게 파악했습니다. 로그 미들웨어에서 동작하는 함수가 일부 인수에 대해 정합성 문제를 일으켰고 이 에러가 에러 처리 인터셉터에 잡히지 않아 그대로 서버가 다운되어버린 것이었습니다. 이후 핫픽스를 통해 서버를 정상화시켰습니다. 팀원들은 단한명도 저를 타이르지 않았고 오히려 고생했다고 얘기해줬습니다. 팀원들께 너무 죄송한 마음이 들었고 관련하여 에러 회고를 작성했습니다.

다 수습이 되고 나서야 든 생각은, 서버에 문제가 생겼을 시 받아볼 수 있는 경고알림의 구축이 시급하다는 것이었습니다. 그 결과, AWS 내 cloudwatch 솔루션과 연동하여 이메일을 통해 경보를 받아볼 수 있는 시스템을 구축했습니다. 이후 어디서든 경보를 받게되면 팀원들과 소통하며 즉각적인 대처를 할 수 있는 시스템을 미약하게나마 갖출 수 있었습니다.

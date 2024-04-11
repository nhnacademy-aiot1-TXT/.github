# NHN Academy 최종 프로젝트 2팀 - TxT
NHN Academy 최종 프로젝트


## 팀원

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/GaHyoung"><img src="https://avatars.githubusercontent.com/u/140566942?s=96&v=4"width="100px;" alt=""/><br /><sub><b>남가형</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/woooyas"><img src="https://avatars.githubusercontent.com/u/99152474?v=4" width="100px;" alt=""/><br /><sub><b>남지민</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/pass0210"><img src="https://avatars.githubusercontent.com/u/87704860?v=4" width="100px;" alt=""/><br /><sub><b>박상원</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/GGilook"><img src="https://avatars.githubusercontent.com/u/92835879?v=4" width="100px;" alt=""/><br /><sub><b>서길우</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/jongsikk"><img src="https://avatars.githubusercontent.com/u/161236047?v=4" width="100px;" alt=""/><br /><sub><b>윤종식</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/joohyeon98"><img src="https://avatars.githubusercontent.com/u/80081712?v=4" width="100px;" alt=""/><br /><sub><b>이주현</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/halo-eunsu"><img src="https://avatars.githubusercontent.com/u/99951904?v=4" width="100px;" alt=""/><br /><sub><b>정은수</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/jjunho50"><img src="https://avatars.githubusercontent.com/u/44630047?v=4" width="100px;" alt=""/><br /><sub><b>정준호</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

## 기술 스택

<div align="center">
  <h3 align="center"> Languages & Tools </h3>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/> 
</div>

<div align="center">
<h3 align="center"> Framework </h3>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot"/> <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white"/> <img src="https://img.shields.io/badge/Eureka-22ADF6?style=for-the-badge&logo=Spring&logoColor=white"/>
</div>

<div align="center">
  <h3 align="center"> Database </h3>
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=InfluxDB&logoColor=white"/>
</div>

<div align="center">
  <h3 align="center"> CI/CD </h3>
<img src="https://img.shields.io/badge/Sonarqube-5190cf?style=for-the-badge&logo=sonarqube&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white"/>
</div>


## 와이어프레임
링크 : https://www.figma.com/file/GugzS1krwmv4w0w8RzK2QJ/TXT?type=design&node-id=0%3A1&mode=design&t=liBJTyjXHIDNVLut-1

## 도메인
링크 : https://contxt.co.kr

## Architecture 구조도
링크 : https://drive.google.com/file/d/1eai237ikC1wwMD1JFQpnBdK9lpWvkeiA/view?usp=sharing
![image](https://github.com/nhnacademy-aiot1-TXT/.github/assets/87704860/b9b74c4c-5918-431e-8ad9-eda36f146af3)


## ERD

## 요구사항

**문서** : https://docs.google.com/spreadsheets/d/1i29hHcz0Vs1TE9rX25X1P9sBV4n3-KYcTEr3zKWq_7g/edit?usp=sharing

### 🌱 IoT 
- 담당 : 정준호, 남지민
1. 센서정보 수집
   - 온도
   - 습도
   - 공기질
   - 재실 감지
   - 조명
3. 기기 제어

### 🌱 Backend 
- 담당 : 박상원, 윤종식
1. 센서 데이터별 서버 구성 (데이터 읽기)
2. 데이터 수집, 가공 (날씨정보 - 기상청)
3. 유저관리 서버
4. 유레카 서버
5. 인증 서버
6. 프론트 서버
7. gateway

### 🌱 Frontend
- 담당 : 서길우, 정은수
1. 각 센서별 그래프 그리기
2. 유저(메인) 페이지
   - 현재 재실 인원
   - 센서 결과 (온도, 습도)
   - 알림 (에어컨, 공기청정기 on/off)
4. 관리자 페이지
   - 회원관리 (수정, 삭제, 조회, 승인 대기)
   - 상세 센서 정보
   - 알림 (에어컨, 공기청정기 on/off, 침입 기록)
   - (부가) 수동 전환 페이지
   - (부가) 오늘의 날씨
   - (부가) 게시판
### 🌱 AI
- 담당 : 남가형, 이주현
1. 에어컨 on/off
2. 공기청정기 on/off + 날씨정보 학습
3. 침입 탐지 (이상치) -> 학원 12시 폐쇄. 경비원 고려.

## 개발 계획서

**문서** : https://docs.google.com/document/d/1YxccoXC3w690PXhy7PwKs554dly0-71KKP9yUywxLnE/edit?usp=sharing

### 프로젝트명: 재실기반 자동화 시스템

 
### 1. 프로젝트 개요
재실기반 자동화 시스템은 스마트 아카데미를 위해 개발되는 IoT 기반 시스템입니다. 이 시스템은 다양한 센서를 사용하여 아카데미 내부의 환경을 모니터링하고 제어하는 기능을 제공하여 학습 환경을 개선하고 안전성을 높입니다.

### 2. 프로젝트 목표:
 - 다양한 센서를 활용하여 온도, 습도, 공기질 등의 환경 데이터를 실시간으로 수집하고 모니터링합니다.

- 웹 애플리케이션을 통해 사용자는 시설 환경 데이터를 기반으로 시각화하고, 각 시설들을 제어할 수 있습니다.
    - 관리자
        - 온도, 습도, 공기질, 재실인원 데이터의 상세 로그를 확인할 수 있습니다.
        - 관리자가 설정한 시간 이후, 재실 센서를 이용하여 사무실을 침입한 비관계자를 관리자 알림을 통해 확인할 수 있습니다.
        - 현재 실내의 온도, 습도 등 여러 환경적 요소들을 AI 시스템으로 적절한 조치를 취해 관리자가 별도의 조작없이 실내의 환경을 쾌적하게 구성할 수 있습니다.
        - 관리자가 이를 원하지 않을 경우, 각 환경 요소마다 수동조작을 할 수 있도록 AI 시스템 비활성화 기능을 사용할 수 있습니다.
    - 유저
        - 현재 온도, 습도 및 센서 데이터를 조회할 수 있습니다.
        - 현재 날씨에 대해 파악할 수 있습니다.
        - 현재 재실 인원에 대해 파악할 수 있습니다.

- 유저는 게시판을 통해 관리자에게 실내 환경의 조정에 대해 건의할 수 있습니다.

- 관리자는 유저가 작성한 게시물을 관리할 수 있습니다.

- 관리자는 회원 관리 시스템을 통해 유저에 대해 관리할 수 있습니다.
    - 관리자는 유저 관리 기능을 통해 유저의 회원가입/ 탈퇴를 승인할 수 있습니다.
    - 관리자는 각 유저의 관리자 / 멤버 역할을 수정할 수 있습니다.
 
- 메인 페이지 및 다른 기능을 사용할 때, 알림 버튼을 통해 실시간 데이터에 대한 조회가 가능합니다.


 
### 3. 개발 계획
- IoT 개발
    - 센서 데이터 수집 및 전송을 위한 소프트웨어 개발
    - 센서 데이터 관리를 위한 MQTT, Modbus 통신 프로토콜 기반 룰 엔진 구현
    - 센서 데이터 전처리 및 가공


- Backend 개발
    - 센서 데이터 처리를 위한 Spring boot 기반 서버 개발
    - 외부 데이터 수집 및 가공을 위한 API 연동
    - JWT 토큰 기반 사용자 인증 및 권한 관리를 위한 서버 개발


- Frontend 개발:
    - 사용자 인터페이스 설계 및 개발
    - 실시간 센서 데이터를 반영한 화면 구성
    - 사용자 제어 기능 구현
    - 사용자의 요청을 반영하여 데이터를 요청하고 요청된 데이터를 시각화
    
- AI 개발
    - 환경 데이터 분석을 위한 AI 알고리즘 개발
    - 실내 환경 조정 정보를 통해 실내 최적 환경에 대한 기준치 도출
    - 환경 최적화 및 이상 징후 감지 기능 구현


### 4. 테스트 및 통합:
- 각 모듈별로 단위 테스트 및 통합 테스트 수행
### 5. 일정 및 마일스톤:
- Milestone (2주): 요구사항 분석 및 개발 계획 수립
    - 요구사항 명세서 및 개발 계획서 작성
    - 요구사항에 따른 역할분담 완료
- Milestone (4주): IoT 및 Backend 시스템 개발 및 테스트 완료
    - 센서 데이터를 수집 및 전처리 기능 개발
    - Api 요청에 대해 알맞은 데이터를 제공하는 시스템 개발
    - 각 시스템에 대한 단위 테스트
- Milestone (6주): Frontend 및 AI 기능 개발 및 시스템 통합 테스트 완료
    - 사용자에게 보여지는 페이지 화면 개발 
    - 필요한 데이터를 Backend 시스템에 요청하는 Frontend 로직 개발
    - Frontend와 Backend의 연결이 요구사항 명세서의 항목에 충족하는지 테스트
    - 전체적인 시스템의 오류사항에 대한 통합 테스트

### 6. 프로젝트 관리:
- git action을 이용한 CICD 환경 수립
- 위험 관리 및 변경 관리 프로세스 수립
- 주기적인 프로젝트 회의 및 팀원 간 커뮤니케이션 확보


### 7. 배포 및 운영 계획:
- 클라우드 기반 서버 구축 및 시스템 배포
    - NHN 클라우드 기반 서버 구축
    - Git action을 통한 시스템 배포
- 모니터링 및 로깅 시스템 구축
    - 센서 데이터를 네트워크 서버를 통해 실시간으로 전송받아 갱신함으로서, 데이터 기반 실시간 모니터링 구현
    - 가공된 센터 데이터를 로그 데이터로 저장하는 서비스 구현
- AI 알고리즘을 적용한 대응 시스템 구축
    - 축적된 센서 데이터를 통해 현재와 미래의 실내 환경을 예측하여 최적의 상태를 유지하도록 적시에 조정
    - 시설 내 이상 징후를 감지하여 적시에 대응





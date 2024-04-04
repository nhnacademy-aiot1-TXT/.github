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


## 요구사항

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

### 🌱 Frontent
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

**프로젝트명: 재실기반 자동화 시스템**

**1. 프로젝트 개요:**
이 프로젝트는 스마트 홈 IoT 시스템을 개발하는 것을 목표로 합니다. 이 시스템은 다양한 센서를 사용하여 홈 환경을 모니터링하고 제어하는 기능을 제공합니다. 이를 통해 사용자는 편리하고 안전한 홈 환경을 조성할 수 있습니다.

**2. 프로젝트 목표:**
- 다양한 센서를 통해 온도, 습도, 공기질 등의 홈 환경 정보를 수집하고 모니터링합니다.
- 사용자는 웹 애플리케이션을 통해 실시간 홈 환경 정보를 확인하고 제어할 수 있습니다.
- AI 알고리즘을 사용하여 홈 환경을 자동으로 최적화하고 사용자에게 편의 기능을 제공합니다.

**3. 개발 계획:**

**3.1 IoT 개발:**
- 센서 데이터 수집 및 전송을 위한 소프트웨어 개발
- 센서 데이터를 관리하고 제어하기 위한 통신 프로토콜 구현

**3.2 Backend 개발:**
- 센서 데이터를 처리하고 저장하기 위한 서버 구축
- 외부 데이터 (날씨 정보 등) 수집 및 가공을 위한 API 연동
- 사용자 관리 및 인증을 위한 서버 개발
- 프론트엔드 및 IoT 시스템과의 통신을 위한 Gateway 개발

**3.3 Frontend 개발:**
- 사용자 및 관리자를 위한 웹 및 모바일 애플리케이션 UI/UX 설계 및 개발
- 실시간 센서 데이터를 시각화하고 사용자에게 제공하는 그래프 및 차트 개발
- 사용자 및 관리자가 시설 환경을 제어할 수 있는 인터페이스 개발

**3.4 AI 개발:**
- AI 알고리즘을 사용하여 시설 환경을 자동으로 최적화하는 기능 개발
- 에어컨 및 공기청정기의 자동 제어 알고리즘 개발
- 이상 징후를 탐지하고 보안 조치를 취하는 기능 개발

**4. 테스트 및 통합:**
- 각 모듈별로 단위 테스트 수행
- 시스템 전체를 통합하고 테스트하는 과정 진행

**5. 일정 및 마일스톤:**
- **Milestone (2주):** 요구사항 분석 및 개발 계획서 작성 및 수정
- **Milestone (4주):** IoT 시스템 개발 및 테스트 완료
- **Milestone (4주):** Backend 및 Frontend 시스템 개발 및 통합 테스트 완료
- **Milestone (4주):** AI 기능 개발 및 전체 시스템 최종 테스트

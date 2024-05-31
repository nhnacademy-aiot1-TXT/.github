# NHN Academy 최종 프로젝트 2팀 - TxT
NHN Academy 최종 프로젝트

<p align="center">
  <img src = "https://github.com/nhnacademy-aiot1-TXT/.github/assets/92835879/d3886830-f227-486d-8a26-db7dc860d09d">
</p>


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
![image](https://github.com/nhnacademy-aiot1-TXT/.github/assets/87704860/c5e0e7a5-ddd1-4ae5-bb35-c5e5e967f938)

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

### 프로젝트명: Smart Academy

### 1. 프로젝트 개요
Smart Academy는 학생들에게 쾌적한 학습환경을 제공하기 위해 개발되는 IoT 기반 시스템입니다. 이 시스템은 다양한 센서를 사용하여 아카데미 내부의 환경을 모니터링하고 제어하는 기능을 제공하여 학습 환경을 개선하고 안전성을 높입니다.


### 2. 프로젝트 목표
* 다양한 센서를 활용하여 temperature, humidity, co2, illumination, totalcount, voc, occupancy, door 등의 데이터를 실시간으로 수집하고 모니터링합니다.


* 웹 애플리케이션을 통해 사용자는 Academy 환경 데이터를 기반으로 시각화하고, 각 시설들을 제어할 수 있습니다.
   * 관리자
      * 온도, 습도, co2, 재실인원 데이터의 상세 로그를 확인할 수 있습니다.
      * 관리자가 설정한 시작시간부터 종료시간까지 재실 센서를 이용하여 사무실의 침입자 알림을 확인할 수 있습니다.
      * 현재 실내의 시간, 내부 온도, 내부 습도, 외부 온도, 외부 습도, 인원수 등 여러 환경적 요소들을 학습시킨 AI Model을 사용하여 나온 결과로 관리자가 별도의 조작없이 실내의 환경을 쾌적하게 구성할 수 있습니다.
      * 관리자가 자동조작을 원하지 않을 경우, 각 환경 요소마다 수동조작을 할 수 있도록 AI Model 사용 비활성화 기능을 사용할 수 있습니다.
      * 조명을 제어할 때, 사용자는 주기를 설정하여 설정한 주기 내 조건을 만족하면 꺼지도록 할 수 있습니다.
      * 공기청정기를 제어할 때, 사용자는 쾌적모드와 일반모드 중 하나를 택하여 선택 할 수 있고, 주기를 설정하여 설정한 주기 내 조건을 만족하면 꺼지도록 할 수 있습니다. 
      * 에어컨을 제어할 때 온도를 직접 설정할 수 있고, 주기를 설정하여 원하는 주기마다 조건을 만족하면 꺼지도록 할 수 있습니다.
      * 침입 감지 알림을 제어할 때 시작시간과 종료시간을 설정하고 시작시간 이후부터 종료시간까지 재실이 감지되면 알림을 보내도록 할 수 있습니다.
   * 유저
      * 현재 온도, 습도,  센서 데이터를 조회할 수 있습니다.
      * 현재 날씨에 대해 파악할 수 있습니다.
      * 현재 재실 인원에 대해 파악할 수 있습니다.
      * 관리자가 설정한 조명 제어 주기를 확인할 수 있습니다.
      * 공기청정기의 쾌적모드와 일반모드 중 하나를 선택 할 수 있고, 관리자가 설정한 공기청정기 제어 주기를 확인 할 수 있습니다.
      * 에어컨 온도를 설정할 수 있고, 관리자가 설정한 에어컨 제어 주기를 확인할 수 있습니다.
      * 관리자가 설정한 침입 감지 시간을 볼 수 있습니다.


* 사용자는 게시판을 통해 관리자에게 실내 환경의 조정에 대해 건의할 수 있습니다.
   * 관리자
      * 일반 유저가 등록한 게시물을 삭제할 수 있습니다.
   * 유저
      * 게시물을 등록할 수 있습니다.
      * 자신이 등록한 게시물을 수정, 삭제할 수 있습니다.
   * 공통
      * 게시물에 댓글을 달 수 있습니다.


* 관리자는 회원 관리 시스템을 통해 유저에 대해 관리할 수 있습니다.
   * 관리자는 현재 가입한 유저들의 정보를 확인 할 수 있습니다.
   * 관리자는 유저 관리 기능을 통해 유저의 회원가입을 승인할 수 있습니다.
   * 관리자는 각 유저에게 관리자 권한을 부여할 수 있습니다.
 
*  메인 페이지 및 다른 기능을 사용할 때, 알림 버튼을 통해 알림을 확인할 수 있습니다.
   * 관리자
      * 기기제어
      * 침입
   * 유저
      * 기기제어

### 3. 개발 계획
* IoT 개발:
   * 센서 데이터 수집 및 전송
      * 센서 데이터 관리를 위한 MQTT, Modbus 통신 프로토콜 기반 룰 엔진 구현
      * 센서 데이터 전처리 및 가공
   * 장비 제어 신호 전송
      * 센서 데이터를 조합해서 디바이스 제어 신호 판단 및 전송
   * 장비 제어 서버 개발
      * 에어컨, 공기청정기, 조명제어 및 알림 전송


* Backend 개발:
   * 센서 데이터 조회 API 구현
      * Temperature API 단일, 일간, 주간, 월간 정보 조회 기능
      * Humidity API 단일, 일간, 주간, 월간 정보 조회 기능
      * Illumination API 단일, 일간, 주간, 월간 정보 조회 기능
      * Co2 API 단일, 일간, 주간, 월간 정보 조회 기능
      * Voc API 단일 정보 조회 기능
      * PeopleCount API 단일 정보 조회 기능
   *  범용 API 구현
      * Device API : 장비 정보 추가, 수정, 조회
      * Sensor API : 센서 정보 추가, 수정, 조회
      * DeviceSensor API 조회 : 
      * Weather API : 날씨 온도 조회
      * Notification API : 권한에 맞는 알림 정보 리스트 조회와 알림 저장


   * 사용자 관리 API
      * 관리자 API : 모든 사용자 조회, 사용자 권한수정, 사용자 삭제
      * 사용자 API : 사용자 단일 조회, 생성, 수정, 로그인, 상태변경, Role 조회
   * 인증 API
      * 로그인 API : 로그인 성공 시 access token, refresh token 발급
      * 토큰 재발급 API : access token 만료 시 refresh token 확인 후 access token 재발급
   * Gateway
      * 권한 헤더 체크 필터
      * 토큰 검증 필터
      * 사용자 아이디 헤더 추가 필터
      * 권한 체크 필터
      * Path별 라우팅
   * Eureka
      * 로드밸런싱
      * 프로젝트 이름에 따른 url 제공
      * 프로젝트 상태 모니터링
* Frontend 개발:
   * 사용자 인터페이스 설계 및 개발
      * 로그인 페이지
      * 회원가입 페이지
      * 메인페이지(관리자/유저)
      * 마이페이지
      * 탈퇴 계정 복구 페이지
      * 회원가입 승인 페이지
      * 상세 센서 정보 페이지
      * 수동 전환 페이지
      * 조명 제어 정보 설정 페이지
      * 공기청정기 제어 상세 페이지
      * 에어컨 제어 상세 페이지
      * 침입감지 설정 페이지
      * 회원 권한 수정 페이지
      * 온도 로그 페이지
      * 습도 로그 페이지
      * Co2 로그 페이지
      * 재실 기록 로그 페이지
      * 게시판 페이지
      * 게시글 상세 페이지
      * 게시글 작성 페이지
   * 실시간 센서 데이터, 날씨 정보를 반영한 화면 구성
      * 실시간 날씨 정보
      * 조도, 온도, 습도, co2 Line graph
      * 온도, 습도, co2, voc, 조도 gauge graph
   * 장치 제어 기능 구현
      * 전등 제어
      * 에어컨 제어
      * 공기 청정기 제어
      * AI Mode on / off
   * 사용자 관리 기능 구현
      * 사용자 계정 복구
      * 회원가입 승인
      * 가입된 회원 목록 확인
      * 사용자 권한 수정
* AI 개발:
   * 환경 데이터 분석을 통한 AI 알고리즘 학습 모델 개발
      * 시간, 실내외 온습도, 재실인원 학습
   * 모델을 활용한 아카데미 환경 최적화
      * 학습된 AI를 통한 에어컨 제어


### 4. 테스트 및 통합
* 각 모듈별로 단위 테스트 및 통합 테스트 수행


### 5. 프로젝트 관리
* Git Action 및 Jenkins를 이용한 CI/CD 환경 수립
* 위험 관리 및 변경 관리 프로세스 수립
* 주기적인 프로젝트 회의 및 팀원 간 커뮤니케이션 확보
* JavaDoc, Swagger 등을 이용한 빠른 문서작업


### 6. 배포 및 운영 계획
* 클라우드 기반 서버 구축 및 시스템 배포
   * NHN 클라우드 기반 서버 구축
   * Git action, Jenkins를 통한 시스템 배포
* 모니터링 및 로깅 시스템 구축
   * 센서 데이터를 네트워크 서버를 통해 실시간으로 전송받아 갱신함으로서, 데이터 기반 실시간 모니터링 구현
   * 가공된 센터 데이터를 로그 데이터로 저장하는 서비스 구현
* AI 알고리즘을 적용한 대응 시스템 구축
   * 축적된 센서 데이터를 통해 현재와 미래의 실내 환경을 예측하여 최적의 상태를 유지하도록 적시에 조정
   * 시설 내 이상 징후를 감지하여 적시에 대응

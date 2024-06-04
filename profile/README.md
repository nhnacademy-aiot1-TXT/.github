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
![스크린샷 2024-05-31 09-06-45](https://github.com/nhnacademy-aiot1-TXT/.github/assets/87704860/48f08b84-4ba1-4c73-817d-aeae7870801c)


## 세부 Architecture 구조도

### Architecture - WEB

![image](https://github.com/nhnacademy-aiot1-TXT/TxT-AI-predict/assets/99951904/31ee7d09-d550-4962-bb77-42f7f360575f)

### Architecture - WEB

![image](https://github.com/nhnacademy-aiot1-TXT/TxT-AI-predict/assets/99951904/cfd155b0-745e-4290-ab67-161a52df4493)


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
2. 기기 제어


### 🌱 Backend 
- 담당 : 박상원, 윤종식
1. 센서 데이터별 서버 구성 (데이터 읽기)
2. 데이터 수집, 가공 (날씨정보 - 기상청)
3. 유저관리 서버
4. 유레카 서버
5. 인증 서버
6. 프론트 서버
   - 장치 설정 페이지
7. gateway

### 🌱 Frontend
- 담당 : 서길우, 정은수
1. 각 센서별 그래프 그리기
2. 메인 페이지
   - 현재 재실 인원
   - 센서 결과 (온도, 습도)
   - 알림 (에어컨, 공기청정기 on/off)
   - 오늘의 날씨
3. 마이페이지
   - 회원정보 수정
4. 관리자 페이지
   - 회원관리 (수정, 삭제, 조회, 승인 대기)
   - 관리자 권한 부여
   - 탈퇴회원 관리

5. 상세 센서 정보 페이지
6. 알림 (에어컨, 공기청정기 on/off, 침입 기록)

   
### 🌱 AI
- 담당 : 남가형, 이주현
1. 에어컨 on/off
2. 공기청정기 on/off + 날씨정보 학습
3. 침입 탐지 (이상치) -> 학원 12시 폐쇄. 경비원 고려.
4. 데이터를 바탕으로 환경 예측


## 개발 계획서

**문서** : https://docs.google.com/document/d/1YxccoXC3w690PXhy7PwKs554dly0-71KKP9yUywxLnE/edit?usp=sharing


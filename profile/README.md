# # 함께, 하나? 
<img src="https://github.com/user-attachments/assets/53bc23af-bca3-40e3-b48a-6c3fbfe6b32b" alt="프로젝트소개" style="width:70%; height:auto;"> <br/>

[디지털하나로 금융서비스개발 2기] - 2차 프로젝트
> 하나은행은 타행 대비 다양한 종목의 스포츠를 후원하고 있고, MZ 세대들의 스포츠 직관 열풍을 배경으로 모임통장 서비스를 제공하여 스포츠 문화를 장려

> 스포츠를 관람하는데 있어 재미적인 요소를 제공하거나, 공용 자금을 사용하는데 있어 편리한 기능들을 제공하여 스포츠 문화를 ‘함께, 하나?’ 서비스를 통해 즐길 수 있도록 한다.
 
<br/>

## 목차
[1. 프로젝트 개요](#1-프로젝트-개요)

[2. 기술 스택](#2-기술-스택)

[3. ERD](#3-erd)

[4. 서비스 아키텍처](#4-서비스-아키텍처)

[5. 기능 설명](#5-기능-설명)

[6. 팀원 소개](#6-팀원-소개)
<br/><br/><br/>

## 1. 프로젝트 개요
| 항목 | 내용 |
| --- | --- |
| 프로젝트 소개 | 스포츠에 진심인 하나은행과 스포츠에 진심인 MZ세대를 결합할 수 있는 플랫폼 |
| 개발 인원 | 총 5명 |
| 개발 기간 | 총 29일 (2024. 06. 13 ~ 2024 07. 11) |
<br/>

## 2. 기술 스택
| 기술               | 사용 |
|------------------| --- |
| Frontend         | <img src="https://img.shields.io/badge/react-%2320232a.svg?style=flate&logo=react&logoColor=%2361DAFB"/> <img src="https://img.shields.io/badge/-React%20Query-FF4154?style=flate&logo=react%20query&logoColor=white"/> <img  src="https://img.shields.io/badge/PWA-5A0FC8?style=flate&logo=pwa&logoColor=white" /> <img  src="https://img.shields.io/badge/Vercel-000000?style=flate&logo=vercel&logoColor=white" /> <img  src="https://img.shields.io/badge/Storybook-FF4785?style=flate&logo=storybook&logoColor=white" />|
| Backend        | <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=Spring Security&logoColor=white"> <img src="https://img.shields.io/badge/JWT-black?style=flate&logo=JSON%20web%20tokens">  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=Swagger&logoColor=black"> |
| Server           | <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=amazonec2&s&logoColor=white"> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=flat&logo=amazonrds&s&logoColor=white">  <img src="https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=flate&logo=apache-tomcat&logoColor=black"> |
| Database         | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=Redis&logoColor=white"> |


<br/>

## 3. ERD



<br/><br/>

## 4. 서비스 아키텍처
<img src="https://github.com/user-attachments/assets/c53b4c45-52d2-4668-a5a3-ddda86bd4c47" alt="시스템아키텍처" style="width:70%; height:auto;">

<br/><br/>

## 5. 기능 설명
### ❶ 홈
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><홈 화면></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
   </td>
  </tr>
  <tr>
    <td>
    -   참여하고 있는 모임통장 리스트를 확인할 수 있습니다. <br/>
	-   스포츠 마일리지를 확인하고, 충전 및 환전하기로 이동할 수 있습니다. <br/>
	-   자신의 응원팀을 확인할 수 있으며, 경기 일정을 확인할 수 있습니다.
    </td>
  </tr>
</table>

<br/>

### ❷ 모임통장
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><모임통장 생성></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -  본인 정보 확인 후, 모임 통장 이름을 입력하고 목적(축구, 야구, e-스포츠) 을 선택하여 모임통장을 생성합니다.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><모임통장 초대 및 가입></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   총무는 초대코드를 생성할 수 있습니다. <br/>
    -   다른 사용자는 해당 초대코드로 모임통장에 참여할 수 있습니다.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><회비 걷기></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   총무가 걷을 금액을 입력 후 수금을 요청합니다. <br/>
    -   모임통장 내 모임원에게 수금 요청 알림이 갑니다.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><모임통장 홈화면></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   입출금 내역과 계좌 잔액을 확인할 수 있습니다. <br/>
	-   모임원을 확인할 수 있습니다. <br/>
	-   현재 모임통장 내 열린 빅매치를 확인할 수 있으며 클릭 시 빅매치 겨루기 화면으로 이동합니다.
    </td>
  </tr>
</table>

<br/>

### ❸ 모임통장 빅매치
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><빅매치 생성></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   내기 제목, 선택지, 투표 마감일, 벌금을 입력한 후 빅매치를 생성합니다.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><빅매치 겨루기></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   모임원은 선택지에 투표하여 빅매치에 참여합니다.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><빅매치 종료></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   총무는 투표 마감 시간이 지나면 승리자를 선택할 수 있습니다. <br/>
	-   패배자들에게는 자동으로 벌금 송금 요청이 갑니다.
    </td>
  </tr>
</table>

<br/>

### ❹ 시스템 이벤트
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><승리팀 맞추기 이벤트></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   승리팀을 예측하고, 승패를 모두 맞출 경우 스포트 마일리지가 지급됩니다.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><선착순 이벤트></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   선착순으로 빠르게 클릭하면 스포츠 마일리지나, 경기 티켓이 지급됩니다.
    </td>
  </tr>
</table>

<br/>

### ❺ 스포츠 마일리지
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><마일리지 충전 및 전환></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   스포츠 마일리지를 충전할 수 있습니다.
	-   스포츠 마일리지를 현금으로 전환할 수 있습니다.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><마일리지 굿즈샵></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진
    </td>
  </tr>
  <tr>
    <td>
    -   스포츠 마일리지로 굿즈를 구매할 수 있습니다.
    </td>
  </tr>
</table>

<br/>

### [🖥️ 시연 영상](https://youtu.be/3s1uTFt2rck)
<br/>

## 6. 팀원 소개
### 💃 Front End
| **[팀장, Lead] 이상민** | **이고은** |
| :------: | :------: |
| [<img src="https://avatars.githubusercontent.com/tkdalsss" height=150 width=150> <br/> @tkdalsss](https://github.com/tkdalsss) | [<img src="https://avatars.githubusercontent.com/egon6018" height=150 width=150> <br/> @egon6018](https://github.com/egon6018) |

### 💂‍♂️ Back End
| **[Lead] 정찬수** | **신지연** | **이지후** |
| :------: | :------: | :------: |
| [<img src="https://avatars.githubusercontent.com/iamcharles98" height=150 width=150> <br/> @iamcharles98](https://github.com/iamcharles98) | [<img src="https://avatars.githubusercontent.com/jiyeoon00" height=150 width=150> <br/> @jiyeoon00](https://github.com/jiyeoon00) | [<img src="https://avatars.githubusercontent.com/lee010207" height=150 width=150> <br/> @lee010207](https://github.com/lee010207) |

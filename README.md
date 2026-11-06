<div align="center">

**데이터가 틀리지 않는 서비스를 고민하는 백엔드 개발자**

"확인할 수 없는 값"을 "안전한 값"으로 착각하지 않도록,<br/>
실패와 경계 조건까지 설계하는 것을 중요하게 생각합니다.

</div>

<br/>

## 🛠 Tech Stack

**Backend**<br/>
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
<img src="https://img.shields.io/badge/MyBatis-DC382D?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache%20Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black"/>

**Database**<br/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white"/>

**Frontend**<br/>
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>

**AI · Data**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>

**Tools**<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>

<br/>

## 🚀 Projects

### 🏠 이번집 — 전세사기 위험 분석 서비스
`2026.07 ~ 2026.08` · 5인 팀 · KB IT's Your Life 7기 최종 프로젝트 · **리포트(Report) 도메인 담당**

전세 매물 주소·보증금과 공공/민간 데이터를 결합해 전세사기 위험을 판정하는 서비스

- 외부 API로 매물 자료를 수집하고 위험 판정 결과를 저장하는 리포트 발급 흐름 구현
- 금액 파싱 실패를 0원으로 처리하지 않도록 **데이터 확인 상태와 위험도를 분리**해 "확인 불가"가 "안전"으로 오판되지 않게 설계
- **Redis**로 리포트 발급 진행 상태 관리
- **DB 유일성 제약**과 기존 결과 재사용으로 중복 발급 방지
- 실패·경계 조건 중심의 테스트 작성

`Java 17` `Spring MVC` `MyBatis` `MySQL` `Redis` `Flyway` · [📂 Repository](https://github.com/jjuny0326/second-zip-app)

---

### 📞 단짝 — 고령층 맞춤 금융 단축번호 서비스
`2026.08 ~ 2026.09` · 5인 팀 · **🏆 KB IT's Your Life 해커톤 우수상 (KB국민은행)** · **단축번호·계좌 도메인 FE/BE**

전화 단축번호처럼, 가족이 등록해 둔 금융 업무를 시니어가 번호 하나로 실행하는 서비스

- 음성 명령 실행 전 **확인창**을 두어 잘못 알아들은 명령이 바로 실행되지 않게 처리
- 범위 밖·복수 번호 입력 차단 검증, **취소 후 늦게 도착한 음성 응답 무효화**
- 금액 만·억 단위 한글 보조 표기, 작은 화면·모바일 키보드에서도 버튼과 안내가 가려지지 않는 배치

`Vue 3` `Spring` `MyBatis` `MySQL` `Docker` · [📂 Repository](https://github.com/jjuny0326/danjjak-app)

---

### 🎲 AI Splendor — 실물 보드게임을 두는 AI
`2025.09 ~ 2025.12` · 3인 팀 · 세종대 캡스톤 디자인 · **컴퓨터비전 담당**

카메라로 보드게임 판을 찍으면 상태를 인식해 AI가 다음 수를 두는 시스템

- 카드 식별 방식을 **OCR → ORB → AKAZE**로 개선하며 조명·각도·회전 변화에 강한 인식 구현
- 매 턴 판 전체를 다시 인식해 상태를 재구성하는 방식으로 **오인식이 다음 턴에 누적되지 않게** 설계

`Python` `OpenCV` · [📂 Repository](https://github.com/jjuny0326/ai-splendor-boardgame) · [▶️ 시연 영상](https://youtu.be/FWvdVKT1ijA)

<br/>

## 📜 Certificates & Education

| 구분 | 내용 |
|:---:|---|
| 🎓 학력 | 세종대학교 지능기전공학부 스마트기기전공 |
| 📚 교육 | KB IT's Your Life 7기 (멀티캠퍼스 · 2026.03 ~ 2026.08 · 960시간) |
| 🪪 자격증 | 정보처리기사 · SQLD · ADsP |

<br/>

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=jjuny0326&show_icons=true&theme=default&hide_border=true&rank_icon=github" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jjuny0326&layout=compact&hide_border=true" height="165"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=jjuny0326&hide_border=true" height="165"/>

</div>

<br/>

## 📫 Contact

<a href="mailto:wns0236@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>

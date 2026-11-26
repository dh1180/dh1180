<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0B1020,55:1D4ED8,100:3182F6&text=Donghyeon%20Kim&fontColor=FFFFFF&fontSize=46&fontAlignY=40&animation=fadeIn&desc=Backend%20%C2%B7%20Full-Stack%20%C2%B7%20Data%20%26%20AI%20Simulation&descColor=DBEAFE&descSize=16&descAlignY=63" width="100%" />

<h3>Build · Ship · Operate · Improve</h3>

<p>
  백엔드를 중심으로 <b>실제 운영되는 웹 서비스 · 공개 데이터 파이프라인 · AI 시뮬레이션</b>을 직접 설계하고 배포합니다.
</p>

<p>
  <a href="https://k-unirank.com"><img src="https://img.shields.io/badge/Live%20Service-k--unirank.com-3182F6?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://dong1936.tistory.com"><img src="https://img.shields.io/badge/Tech%20Blog-Tistory-111827?style=for-the-badge&logo=tistory&logoColor=white" /></a>
  <a href="https://solved.ac/dh1180"><img src="https://img.shields.io/badge/Solved.ac-dh1180-17CE3A?style=for-the-badge&logo=solved.ac&logoColor=white" /></a>
</p>

</div>

---

## ⚡ Engineering Focus

<table>
<tr>
<td width="33%" valign="top">

**🏗️ Backend & Architecture**

- **Spring Boot · Django · ASP.NET Core** 기반 프로덕션 API 설계·운영
- **OAuth / JWT / Session** 인증 및 최소 권한 DB 보안 구조
- **PostgreSQL** 스키마 설계 · 대용량 공개 데이터 수집·정규화

</td>
<td width="33%" valign="top">

**🌐 Product & Global SEO**

- **Next.js · React · Astro · TypeScript** 풀스택 서비스 구축
- 다국어(한·영·일·중) SSR 현지화, `hreflang`, 구조화 데이터, 검색 유입 최적화
- **AWS · Railway · Docker · Cloudflare · GitHub Actions** 운영 자동화

</td>
<td width="33%" valign="top">

**🧠 AI & Brain Simulation**

- 공식 PDF/DB 근거 기반 **LLM 검색 파이프라인** 구축
- **Spiking Neural Network · Whole-Connectome** 브라우저 시뮬레이션
- **Web Worker · Canvas** 고성능 실시간 런타임 및 보상 학습

</td>
</tr>
</table>

---

## 🚀 Flagship Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎓 K-unirank

> **전국 363개 대학 입결 · AI 검색 · 선호도 · 공시 지표 통합 플랫폼**

Django 단일 서비스에서 **Spring Boot 3.5 + Next.js 16** 통합 아키텍처로 전면 전환해 실서비스 운영 중입니다.

- **데이터 규모**: 전국 363개 4년제·전문대 · **5.4만+건** 입결 · 실검증 공식 PDF **798건**
- **AI & 랭킹**: 모집요강 PDF 근거 기반 AI 입결 Q&A · **Glicko-2 v2** VS 선호도 랭킹 · 대학알리미 7대 공시 지표
- **글로벌 SEO**: 한·영·일·중 4개 국어 완전 번역 · 양방향 `hreflang` · SSR 현지화 · `sitemap.xml` **11,556 URL**
- **운영 & 보안**: Google/카카오 OAuth · 2단계 회원 탈퇴 · Swagger UI · Railway 무중단 운영

`Java 21` `Spring Boot 3.5` `Next.js 16` `TypeScript` `PostgreSQL` `Docker` `Railway`

<br/>

[![Live](https://img.shields.io/badge/Live-k--unirank.com-3182F6?style=flat-square)](https://k-unirank.com)
[![BackEnd](https://img.shields.io/badge/Repo-BackEnd-181717?style=flat-square&logo=github)](https://github.com/dh1180/K-unirank_BackEnd)
[![FrontEnd](https://img.shields.io/badge/Repo-FrontEnd-181717?style=flat-square&logo=github)](https://github.com/dh1180/K-unirank_FrontEnd)
[![Swagger](https://img.shields.io/badge/API-Swagger%20UI-85EA2D?style=flat-square&logo=swagger&logoColor=000)](https://k-unirank.com/swagger-ui/index.html)

</td>
<td width="50%" valign="top">

### 🪰 FlySwarm

> **Whole-connectome 기반 브라우저 생존 게임**

수백 마리의 Utility AI 초파리와 **FlyWire whole-connectome**에서 유래한 LIF spiking simulation 보스를 브라우저 감각-운동 루프에 결합했습니다.

- **신경망 규모**: **138,639** neuron slots · **15,091,983** directed synaptic pairs
- **실시간 런타임**: Web Worker 기반 whole-brain spiking simulation + 60fps Canvas 렌더링
- **학습 & 기억**: Dopamine-style reward learning · 5단계 Core Boss 이후 Mushroom Body plastic memory 기반 1:1 최종전
- **게임플레이**: 30 Mutations · 15 Synaptic Fusions · Web Audio 프로시저럴 사운드

`React` `TypeScript` `Canvas` `Web Worker` `Web Audio` `Spiking Simulation`

<br/>

[![Play Live](https://img.shields.io/badge/Play%20Live-FlySwarm-10B981?style=flat-square&logo=netlify&logoColor=white)](https://jolly-maamoul-773d3c.netlify.app/)
[![Repo](https://img.shields.io/badge/Repo-FlySwarm-181717?style=flat-square&logo=github)](https://github.com/dh1180/FlySwarm)

</td>
</tr>
</table>

---

## 🧩 Selected Projects

<table>
<tr>
<td width="50%" valign="top">

### ⚡ [HowMuch](https://github.com/dh1180/HowMuch)
**로그인 없이 바로 쓰는 계산 · 단위 변환 웹 도구**  
평·인터넷 속도·데이터 용량·온도·연비·학점 계산기를 정적 웹에 통합. 계산기별 독립 URL·검색·필터·SEO 적용.

`Astro` `TypeScript` `Tailwind CSS` `Cloudflare Pages`  
🔗 [how-much.kro.kr](https://how-much.kro.kr)

</td>
<td width="50%" valign="top">

### 📖 [Read.me](https://github.com/dh1180/Read.me)
**마크다운 기반 독서 기록 & 독서록 공유 플랫폼**  
카카오 도서 검색 연동, 실시간 Markdown 에디터, 카카오 소셜 로그인, Azure 배포 및 GitHub Actions CI/CD 구축.

`C#` `.NET 10` `ASP.NET Core MVC` `EF Core` `Azure`  
🔗 [Azure Web App](https://readme-f7c0beg0gkafe9cp.koreacentral-01.azurewebsites.net)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🇨🇳 [HSK Plus Ultra](https://github.com/dh1180/HSK_Plus_Ultra)
**HSK 3.0 간격 반복(SRS) 모바일 단어 학습 앱**  
30분 → 3일 → 7일 → 21일 → 장기 기억 복습 알고리즘, 급수별 어휘, 중국어 TTS 및 로컬 진행률 저장 구현.

`TypeScript` `React Native` `Expo` `TTS` `Spaced Repetition`

</td>
<td width="50%" valign="top">

### 🧑‍💻 [Devroup](https://github.com/dh1180/Devroup)
**개발자 토이 프로젝트 공유 커뮤니티**  
회원·게시글·검색·정렬·소셜 로그인을 구현하고 MySQL + Docker 기반으로 배포한 Django 커뮤니티 서비스.

`Python` `Django` `MySQL` `JavaScript` `Docker`

</td>
</tr>
</table>

> **Also built:** 🟡 [GoldenDaughter](https://github.com/dh1180/GoldenDaughter_FrontEnd) (Streak·체크인 기록 앱) · 🌌 [APOD](https://github.com/dh1180/APOD) (NASA 오늘의 천문 사진) · 📂 [전체 저장소 보기](https://github.com/dh1180?tab=repositories)

---

## 🏆 Awards & Team Projects

| 성과 | 프로젝트 | 역할 및 내용 |
|---|---|---|
| 🏅 **LIKELION TRACK 입상** | **[Contextory](https://github.com/kau-likelion-14th-hackathon/Contextory_BackEnd)** *(멋사 대학 14기 중앙 해커톤)* | AI 기반 GitHub PR 분석 서비스 — Spring Boot 백엔드 · AWS 배포 |
| 🚀 **2차 예선 진출 (48 / 247팀)** | **HiDaddy** *(멋사 대학 13기 중앙 해커톤)* | Spring Boot 백엔드 · 소셜 로그인 · 사용자 기능 구현 |
| 🥇 **최우승** | **[LOS](https://github.com/dh1180/LOS)** *(2022 슬기로운 코딩생활)* | Arduino/C++ · 초음파 센서 · Ubidots 기반 지하철 잔여좌석 확인 MVP |
| 🏆 **우수상** | **GiTeuk** *(ICT 창업 메이커톤)* | 기부금 흐름 추적 기반 기부 인프라 및 커머스 플랫폼 |

---

## 🧰 Tech Stack

<table>
<tr>
<td width="50%" valign="top">

**Languages**  
<img src="https://skillicons.dev/icons?i=java,python,ts,js,cs,cpp" />

**Backend & Database**  
<img src="https://skillicons.dev/icons?i=spring,django,dotnet,fastapi,postgres,mysql,sqlite" />

</td>
<td width="50%" valign="top">

**Frontend & Runtime**  
<img src="https://skillicons.dev/icons?i=nextjs,react,astro,vite,tailwind,html,css" />

**Cloud, DevOps & Tools**  
<img src="https://skillicons.dev/icons?i=aws,docker,githubactions,cloudflare,vercel,azure,git,linux" />

</td>
</tr>
</table>

---

## 📊 Activity & Problem Solving

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=dh1180&show_icons=true&hide_border=true&rank_icon=github&theme=transparent" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dh1180&layout=compact&hide_border=true&theme=transparent&langs_count=8" />

<br/>

<img height="165" src="https://streak-stats.demolab.com?user=dh1180&hide_border=true&theme=transparent" />
&nbsp;
<a href="https://solved.ac/dh1180">
  <img height="165" src="https://mazassumnida.wtf/api/v2/generate_badge?boj=dh1180" alt="Solved.ac 프로필" />
</a>

</div>

---

<div align="center">

<sub>만들고, 배포하고, 운영하며 다시 개선합니다 — <a href="https://dong1936.tistory.com">dong1936.tistory.com</a></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:0B1020,55:1D4ED8,100:3182F6" width="100%" />

</div>

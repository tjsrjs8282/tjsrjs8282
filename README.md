<div align="center">

<a href="https://geonyworks.com"><img src="./assets/header.svg" width="100%" alt="FULL-STACK HARNESS ENGINEERING — 유선건 · GEONY WORKS 대표" /></a>

<a href="https://geonyworks.com"><img src="https://readme-typing-svg.demolab.com/?font=Noto+Sans+KR&weight=700&size=22&duration=2600&pause=1100&color=FF5B1F&center=true&vCenter=true&width=680&height=46&lines=GEONY%20WORKS%20%EB%8C%80%ED%91%9C%20%C2%B7%20%ED%92%80%EC%8A%A4%ED%83%9D%20%ED%95%98%EB%84%A4%EC%8A%A4%20%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4;%EA%B8%B0%ED%9A%8D%EB%B6%80%ED%84%B0%20%EB%B0%B0%ED%8F%AC%2C%20%EC%8B%A4%EC%82%AC%EC%9A%A9%EC%9E%90%20%EC%9A%B4%EC%98%81%EA%B3%BC%20%EC%88%98%EC%9D%B5%ED%99%94%EA%B9%8C%EC%A7%80;%EB%8D%B0%EB%AA%A8%EA%B0%80%20%EC%95%84%EB%8B%88%EB%9D%BC%2C%20%EA%B2%B0%EC%A0%9C%EA%B0%80%20%EC%9D%BC%EC%96%B4%EB%82%98%EB%8A%94%20%EC%8B%A4%EC%84%9C%EB%B9%84%EC%8A%A4;Web%20%C2%B7%20Android%20%C2%B7%20Payments%20%C2%B7%20Infra" alt="GEONY WORKS 대표 · 풀스택 하네스 엔지니어" /></a>

[![GEONY WORKS](https://img.shields.io/badge/GEONY_WORKS-공식_사이트-FF5B1F?style=for-the-badge)](https://geonyworks.com)
[![Google Play](https://img.shields.io/badge/Google_Play-말랑_모험-01875F?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.geonyworks.mallangadventure)
[![Email](https://img.shields.io/badge/Email-tjsrjs21@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tjsrjs21@gmail.com)

</div>

<br />

## ⚡ About

> **만들고 끝이 아니라, 실제 사용자가 쓰고 결제가 일어나는 제품까지.**

거니웍스(GEONY WORKS) 대표 **유선건**입니다.  
아이디어 한 줄을 **기획 → 디자인 → 개발 → 배포 → 실사용자 운영 → 수익화**까지 끝까지 끌고 갑니다.  
그 전 과정을 **AI 에이전트 하네스** — 서브에이전트 · 스킬 · MCP · 워크플로 — 위에서 돌립니다. 사람은 한 명, 팀은 하네스로.

- 🏢 **GEONY WORKS** — 웹 · 앱 · 게임 개발 스튜디오. 기획 · 브랜딩 · UI/UX부터 로그인 · 결제 연동, 서버 · 배포, SEO까지 한 번에.
- 💰 **실사용자 · 수익화** — Google Play에 출시해 인앱 결제를 붙인 RPG, 실제 고객 결제가 들어오는 청첩장 서비스. 출시 뒤 공지 · 이벤트 · 밸런스 · 고객 응대까지 직접 운영합니다.
- 🎬 **영상 현지화 스튜디오** — 한국어 영상 하나를 나라별 자막 · 게시 글 · 연출 자막으로. 마케팅 회사용으로 직접 만들어 2026년 12월에 엽니다.
- 🧠 **Harness Engineering** — 저장소마다 규칙(`CLAUDE.md` · `AGENTS.md`)과 인계 문서(`HANDOFF.md`), 검증 게이트(`npm run verify`)를 깔고 일을 맡깁니다. "다 했어요"가 아니라 검증이 통과해야 끝.
- 🌏 **한국어 · Tiếng Việt** — 제품 대부분을 두 언어로 설계합니다. 베트남어가 한국어보다 평균 2.9배 길다는 것까지 레이아웃 규칙에 넣어 둡니다.

<br />

## 🧠 How I Build — Harness Engineering

```ts
// 거니웍스 = 사람 1 + 하네스
const geonyworks = {
  plan:    "idea → spec → tasks",
  build:   "AI agents × isolated git worktrees",
  rules:   ["CLAUDE.md", "AGENTS.md", "HANDOFF.md"],
  skills:  ["superpowers", "higgsfield", "typecast"],
  mcp:     ["supabase", "vercel", "playwright", "chrome", "fal"],
  verify:  "npm run verify", // tsc · lint · vitest · playwright
  media:   ["ffmpeg", "libass", "vercel-sandbox"],
  ship:    ["vercel", "google-play", "github-actions"],
  operate: ["notices", "events", "balance", "support"],
  revenue: ["google-play-billing", "toss-payments"],
};
```

- 📜 **규칙은 사고에서 나온다** — 버그 하나가 규칙 한 줄이 됩니다. Doii · 말랑 모험 저장소의 `AGENTS.md`는 *어떤 버그에서 어떤 규칙이 나왔는지* 적어 둔 설계 사례집.
- 🌙 **자리를 비운 밤에도** — Workflow가 Build → Review(3관점) → Fix → 공지 · 인계까지 한 라운드를 끝까지 돌립니다.
- 🧪 **끝은 검증이 정한다** — typecheck · lint · Vitest · Playwright e2e. DB는 PGlite로 마이그레이션과 RLS까지 로컬에서 검증.
- 🔐 **경계는 서버에** — RLS로 막고, 결제 확정 · 보상 정산은 서버 RPC로만. 비밀값은 커밋 · 로그 · 대화에 남기지 않습니다.

<sub>📈 Doii · 말랑 모험 저장소 하나에만 커밋 1,800+ · Supabase 마이그레이션 2,100+ (2026-10 기준) · 거니웍스 저장소 테스트 1,800+ (2026-11 기준)</sub>

<br />

## 🚀 Products — 기획부터 수익화까지, 직접 운영 중

<p align="center">
  <a href="https://capdoii.com/play"><img src="./assets/works/malang.jpg" width="49%" alt="말랑 모험 — 귀엽고 몽글한 성장형 판타지 RPG" /></a>
  <a href="https://dearmio.com"><img src="./assets/works/dearmio.jpg" width="49%" alt="Dearmio — 모바일 청첩장 · 초대장" /></a>
  <a href="https://brickgo.kr"><img src="./assets/works/brickgo.jpg" width="49%" alt="브릭고 — 말 한 줄이면, 진짜 조립되는 브릭 작품" /></a>
  <a href="https://capdoii.com"><img src="./assets/works/doii.jpg" width="49%" alt="Doii — 우리 둘의 시간을, 여기에 담아요" /></a>
  <a href="https://geonyworks.com/studio"><img src="./assets/works/studio.jpg" width="49%" alt="영상 현지화 스튜디오 — 한국어 영상 하나로, 나라마다 자막까지" /></a>
  <a href="https://geonyworks.com"><img src="./assets/works/geonyworks.jpg" width="49%" alt="GEONY WORKS — 기획부터 배포까지, 한 팀으로" /></a>
  <a href="https://geonywony.com"><img src="./assets/works/geonywony.jpg" width="49%" alt="거니워니 공식 홈페이지 — KOREA × VIỆT NAM" /></a>
  <a href="https://ailter.ai"><img src="./assets/works/ailter.jpg" width="49%" alt="AI 일터 — 나만의 AI 오피스" /></a>
</p>

### 🎮 [말랑 모험 · Malang Adventure](https://capdoii.com/play)

[![Google Play](https://img.shields.io/badge/Google_Play-출시-01875F?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.geonyworks.mallangadventure)
[![Web](https://img.shields.io/badge/Web-capdoii.com%2Fplay-FF5B1F?style=flat-square)](https://capdoii.com/play)

두 영웅과 펫을 키우고, 강화 · 재련으로 장비를 다듬으며 층층이 보스를 넘는 귀여운 턴제 RPG. 웹과 Android 앱이 한 계정으로 이어지고 한국어 · 베트남어를 지원합니다.  
세계관 · 전투 연출 · 경제 밸런스 · 사운드부터 **Google Play 출시 · 인앱 결제(서버 검증)** 까지 직접 하고, 출시 뒤에도 이벤트 · 공지 · 밸런스를 계속 운영합니다. 콘텐츠는 전부 DB 표라 월드가 늘어도 코드에 분기가 없습니다.  
`Next.js` `Supabase (RLS · RPC · Realtime · pg_cron)` `Capacitor Android` `Google Play Billing` `Toss Payments` `Web Push` `Kakao` `fal.ai` `Higgsfield` `ElevenLabs` `Typecast`

### 💌 [Dearmio · 디어미오](https://dearmio.com)

감성 모바일 청첩장부터 돌잔치 · 생일 · 환갑 · 집들이 초대장까지 — 먼저 만들어 보고, 마음에 들면 결제하는 **유료 서비스**. 실제 고객 결제(토스페이먼츠)로 운영 중입니다.  
한 커플의 청첩장에서 시작해, 고객이 늘어도 코드를 고치지 않는 **한 저장소 · 한 배포** 서비스로 키웠습니다. 주문 · 결제 · 알림톡 · 식전영상 · 관리자 분석(유입 · 전환)까지.  
`Next.js` `Supabase` `Toss Payments` `Remotion` `Claude API` `Solapi` `Resend`

### 🧱 [브릭고 · BRICKGO](https://brickgo.kr) <sub>대표 개인 프로젝트 · 개발중</sub>

말 한 줄이나 사진 한 장으로 실제로 조립 가능한 브릭 작품을 설계하고, 조립 설명서 · 부품표까지 받아 가는 서비스.
AI가 실제 부품으로 설계한 뒤 모든 연결을 코드가 검사하고, 3D로 조립 순서대로 쌓아 보여 줍니다. 3D 스튜디오에서 직접 고치고, 설명서는 PDF로 받습니다.
`Next.js` `Claude API` `three.js` `Postgres` `Toss Payments` `jsPDF` `Zustand`

### 🎬 [영상 현지화 스튜디오](https://geonyworks.com/studio) <sub>2026-12 고객 오픈</sub>

마케팅 회사를 위한 작업 공간. 한국어 영상을 올리면 **받아쓰기 → 언어마다 번역 · 검수 → 나라별 게시 글 → 휴대폰 승인 → 자막 입히기 → 유튜브 · 인스타그램 · 페이스북 · 틱톡 발행**까지 한 화면에서.
연출 자막은 AI가 언어마다 핵심 낱말을 고르고(과장 표현은 고르지 않게) 말에 맞춰 튀어 오르게 하고, 화면 확대 · 키워드 카드 · 이름표까지 입힙니다. 긴 영상에서 숏츠 구간을 골라 세로로 자르는 것도 같이.
`Next.js` `Supabase (RLS · Storage)` `Claude API` `ElevenLabs Scribe` `Vercel Sandbox` `FFmpeg · libass` `YouTube Data API` `Instagram · Facebook Graph API` `TikTok API`

### 💞 [Doii · 도이](https://capdoii.com)

한국 · 베트남 커플을 위한 모바일 웹앱(PWA). 일정 · 두 통화 생활비 · 추억 · 예약 편지 · 놀이터를 두 사람이 각자의 언어와 시간대로 같이 씁니다. 다른 언어로 쓴 글에는 번역 버튼(Gemini).  
숨겨야 하는 값은 화면이 가리는 게 아니라 **RLS가 SELECT를 막습니다** — 보안 경계는 전부 서버.  
`Next.js` `Supabase Realtime` `RLS · SECURITY DEFINER RPC` `Gemini` `Web Push` `PWA`

### 🤖 [AI 일터 · AILTER](https://ailter.ai)

나만의 AI 직원들과 회의하고, 일을 맡기고, 모든 기록을 남기는 AI 오피스.  
대표(CEO) 에이전트가 일을 DAG로 쪼개 리서처 · 작가 · 디자이너 · 개발자 · 비서에게 넘기고, 직원은 도구를 직접 써서 결과를 확인한 뒤 답합니다. 원격 MCP 연결 · Obsidian 보관소 · 지식 그래프.  
`React` `Express` `Claude API (tool use)` `OpenAI` `Gemini` `Supabase pgvector` `MCP`

### 🏢 [GEONY WORKS · 거니웍스](https://geonyworks.com)

회사 공식 사이트. 15초 쇼릴 인트로, 외부 모델 없이 three.js 도형으로만 만든 3D 캐릭터 「거니」, 스크롤 스토리. 제안서 · 인보이스 · 고객 화면 · 관리자에 영상 스튜디오까지, 수주부터 청구까지 한 저장소에서.  
`Next.js 16` `React Three Fiber` `GSAP` `Lenis` `Supabase` `Typecast` `ElevenLabs Music`

### 🌏 [거니워니 · GeonyWony](https://geonywony.com)

한국 거니와 베트남 워니, 한베커플 이야기를 담은 공식 홈페이지. 카카오 · Google · Facebook 소셜 로그인, 유튜브 영상 · Shorts 허브, 앨범 플레이어, 따라오는 3D 무대와 AR 「내 방에 놓기」.  
`Next.js` `Supabase Auth` `three.js` `PostHog` `Playwright`

### 🎨 More Work

<p align="center">
  <a href="https://todays-meal-five.vercel.app"><img src="./assets/works/todays-meal.jpg" width="49%" alt="오늘의식단 — 담기만 하면 칼로리와 탄단지가 자동으로" /></a>
  <a href="https://knives-out.vercel.app"><img src="./assets/works/knivesout.jpg" width="49%" alt="Knives Out 인터랙티브 페이지" /></a>
  <a href="https://hollowknight-ashy.vercel.app"><img src="./assets/works/hollowknight.jpg" width="49%" alt="Hollow Knight 랜딩 페이지" /></a>
  <a href="https://tjsrjs8282.github.io/hankuk/index.html"><img src="./assets/works/hankuk.jpg" width="49%" alt="한국대학교 메인페이지" /></a>
  <a href="https://tjsrjs8282.github.io/oculus/index.html"><img src="./assets/works/oculus.jpg" width="49%" alt="Oculus 제품 소개 사이트" /></a>
  <a href="https://sungsimdang.co.kr"><img src="./assets/works/sungsimdang.jpg" width="49%" alt="대전 성심당 공식 홈페이지" /></a>
</p>

- **[오늘의식단](https://todays-meal-five.vercel.app)** — 먹은 음식을 검색해 담기만 하면 칼로리와 탄단지가 자동으로 쌓이는 식단 · 운동 기록 앱(PWA).
- **[Knives Out](https://knives-out.vercel.app)** <sub>대표 개인 작업</sub> — 돋보기로 용의자 열 명을 조사하고 AI 블랑에게 일상의 미스터리를 의뢰하는 인터랙티브 페이지. <sub>영화 이미지 · 예고편 저작권 © Lionsgate · MRC · T-Street</sub>
- **[Hollow Knight](https://hollowknight-ashy.vercel.app)** <sub>대표 개인 작업</sub> — 게임 HUD 그대로 내려가는 랜딩 페이지, Web Audio 사운드트랙과 AI 예언자. <sub>게임 · 그림 저작권 © Team Cherry</sub>
- **[한국대학교](https://tjsrjs8282.github.io/hankuk/index.html)** · **[Oculus](https://tjsrjs8282.github.io/oculus/index.html)** <sub>대표 개인 작업</sub> — 2020년에 만든 사이트를 Astro로 다시 지었습니다. <sub>Oculus · Meta Quest 상표 © Meta</sub>
- **[성심당](https://sungsimdang.co.kr)** <sub>대표가 소속 회사에서 참여</sub> — 대전 성심당 공식 홈페이지.

<details>
<summary><b>더 보기 — KOVI · VIKO, Stock Scanner</b></summary>
<br />

**📚 KOVI · VIKO** <sub>출시 준비 중</sub>  
한국인을 위한 베트남어(KOVI)와 베트남인을 위한 한국어(VIKO) — 한 플랫폼, 두 앱. 발음 점수 · SRS 복습 · AI 상황회화 · 관리자 CMS를 같이 씁니다.  
`Expo` `React Native` `npm workspaces` `Supabase` `Vitest` `PGlite`

**📈 [Stock Scanner · 주식스캐너](https://www.stockscanner.co.kr)**  
미국 주식을 주봉 RSI로 스캔하고, 폴더별 워치리스트를 실시간 시세 카드로 봅니다.  
`Vite` `React` `Supabase` `Finnhub` `Vercel Functions` `PWA`

</details>

<br />

## 🧰 Stack & Toolbox

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nextjs%2Creact%2Cts%2Cjs%2Chtml%2Ccss%2Ctailwind%2Castro%2Cvite%2Cthreejs%2Credux%2Cnodejs%2Cexpress%2Csupabase%2Cpostgres%2Cvercel%2Cgithubactions%2Cpython%2Cgit%2Cfigma%2Cps%2Cai%2Candroidstudio%2Cmd&perline=8&theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=nextjs%2Creact%2Cts%2Cjs%2Chtml%2Ccss%2Ctailwind%2Castro%2Cvite%2Cthreejs%2Credux%2Cnodejs%2Cexpress%2Csupabase%2Cpostgres%2Cvercel%2Cgithubactions%2Cpython%2Cgit%2Cfigma%2Cps%2Cai%2Candroidstudio%2Cmd&perline=8&theme=light">
    <img src="https://skillicons.dev/icons?i=nextjs%2Creact%2Cts%2Cjs%2Chtml%2Ccss%2Ctailwind%2Castro%2Cvite%2Cthreejs%2Credux%2Cnodejs%2Cexpress%2Csupabase%2Cpostgres%2Cvercel%2Cgithubactions%2Cpython%2Cgit%2Cfigma%2Cps%2Cai%2Candroidstudio%2Cmd&perline=8&theme=light" alt="Next.js · React · TypeScript · JavaScript · Tailwind CSS · Supabase · PostgreSQL · Vercel · GitHub Actions · Node.js · three.js · Vite · Express · Python · Git · Markdown">
  </picture>
</p>

| 영역 | 도구 |
| :-- | :-- |
| **Harness** | ![Claude](https://img.shields.io/badge/Claude-Opus_·_Sonnet_·_Haiku-30363D?style=flat-square&logo=claude&logoColor=D97757) ![Sub-agents](https://img.shields.io/badge/Sub--agents-30363D?style=flat-square) ![Agent Skills](https://img.shields.io/badge/Agent_Skills-30363D?style=flat-square) ![Hooks](https://img.shields.io/badge/Hooks-30363D?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-30363D?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![Workflows](https://img.shields.io/badge/Workflows-30363D?style=flat-square) ![Superpowers](https://img.shields.io/badge/Superpowers-plugin-30363D?style=flat-square) ![Git worktrees](https://img.shields.io/badge/Git_worktrees-30363D?style=flat-square&logo=git&logoColor=F05032) |
| **MCP** | ![Supabase MCP](https://img.shields.io/badge/Supabase_MCP-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Vercel MCP](https://img.shields.io/badge/Vercel_MCP-30363D?style=flat-square&logo=vercel&logoColor=white) ![Playwright MCP](https://img.shields.io/badge/Playwright_MCP-2EAD33?style=flat-square) ![Claude in Chrome](https://img.shields.io/badge/Claude_in_Chrome-4285F4?style=flat-square&logo=googlechrome&logoColor=white) ![fal.ai MCP](https://img.shields.io/badge/fal.ai_MCP-30363D?style=flat-square) ![Higgsfield MCP](https://img.shields.io/badge/Higgsfield_MCP-30363D?style=flat-square) ![ElevenLabs MCP](https://img.shields.io/badge/ElevenLabs_MCP-30363D?style=flat-square&logo=elevenlabs&logoColor=white) ![LottieFiles MCP](https://img.shields.io/badge/LottieFiles_MCP-00C1A2?style=flat-square&logo=lottiefiles&logoColor=white) ![Context7 MCP](https://img.shields.io/badge/Context7_MCP-30363D?style=flat-square) ![Notion MCP](https://img.shields.io/badge/Notion_MCP-30363D?style=flat-square&logo=notion&logoColor=white) ![Gmail MCP](https://img.shields.io/badge/Gmail_MCP-EA4335?style=flat-square&logo=gmail&logoColor=white) ![Figma MCP](https://img.shields.io/badge/Figma_MCP-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Canva MCP](https://img.shields.io/badge/Canva_MCP-00C4CC?style=flat-square) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-30363D?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-663399?style=flat-square&logo=css&logoColor=white) ![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white) ![Swiper](https://img.shields.io/badge/Swiper-6332F6?style=flat-square&logo=swiper&logoColor=white) |
| **Motion&nbsp;·&nbsp;3D** | ![three.js](https://img.shields.io/badge/three.js-30363D?style=flat-square&logo=threedotjs&logoColor=white) ![React Three Fiber](https://img.shields.io/badge/React_Three_Fiber-30363D?style=flat-square&logo=threedotjs&logoColor=white) ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black) ![Lenis](https://img.shields.io/badge/Lenis-30363D?style=flat-square) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) ![Lottie](https://img.shields.io/badge/Lottie-00C1A2?style=flat-square&logo=lottiefiles&logoColor=white) ![Web Audio API](https://img.shields.io/badge/Web_Audio_API-30363D?style=flat-square) ![AR](https://img.shields.io/badge/AR-30363D?style=flat-square) |
| **Backend&nbsp;·&nbsp;Data** | ![Supabase](https://img.shields.io/badge/Supabase-Postgres_·_Auth_·_Storage_·_Realtime_·_Edge_Functions-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![RLS · RPC](https://img.shields.io/badge/RLS_·_RPC-30363D?style=flat-square) ![pg_cron](https://img.shields.io/badge/pg__cron-30363D?style=flat-square) ![pgvector](https://img.shields.io/badge/pgvector-30363D?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-24-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-30363D?style=flat-square&logo=express&logoColor=white) ![Vercel Functions](https://img.shields.io/badge/Vercel_Functions-30363D?style=flat-square&logo=vercel&logoColor=white) ![Vercel Cron](https://img.shields.io/badge/Vercel_Cron-30363D?style=flat-square&logo=vercel&logoColor=white) ![Vercel Sandbox](https://img.shields.io/badge/Vercel_Sandbox-30363D?style=flat-square&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black) ![Python](https://img.shields.io/badge/Python-3.14-3776AB?style=flat-square&logo=python&logoColor=white) |
| **App&nbsp;·&nbsp;Game** | ![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![Expo](https://img.shields.io/badge/Expo-30363D?style=flat-square&logo=expo&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-149ECA?style=flat-square&logo=react&logoColor=white) ![Google Play](https://img.shields.io/badge/Google_Play-01875F?style=flat-square&logo=googleplay&logoColor=white) ![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white) ![Web Push](https://img.shields.io/badge/Web_Push-VAPID-5A0FC8?style=flat-square) |
| **AI&nbsp;API** | ![Claude API](https://img.shields.io/badge/Claude_API-30363D?style=flat-square&logo=anthropic&logoColor=F0EEE6) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-TTS_·_STT_·_Music-30363D?style=flat-square&logo=elevenlabs&logoColor=white) ![Typecast](https://img.shields.io/badge/Typecast-5B21B6?style=flat-square) ![fal.ai](https://img.shields.io/badge/fal.ai-30363D?style=flat-square) ![Inworld TTS](https://img.shields.io/badge/Inworld_TTS-30363D?style=flat-square) ![리턴제로 STT](https://img.shields.io/badge/%EB%A6%AC%ED%84%B4%EC%A0%9C%EB%A1%9C_STT-30363D?style=flat-square) ![LM Studio](https://img.shields.io/badge/LM_Studio-4F46E5?style=flat-square&logo=lmstudio&logoColor=white) ![ChatGPT](https://img.shields.io/badge/ChatGPT-10A37F?style=flat-square) ![Grok](https://img.shields.io/badge/Grok-30363D?style=flat-square) |
| **Video&nbsp;·&nbsp;Audio** | ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) ![libass](https://img.shields.io/badge/libass-30363D?style=flat-square) ![Remotion](https://img.shields.io/badge/Remotion-0B84F3?style=flat-square) ![Higgsfield](https://img.shields.io/badge/Higgsfield-30363D?style=flat-square) ![Kling](https://img.shields.io/badge/Kling-30363D?style=flat-square) ![Seedance](https://img.shields.io/badge/Seedance-30363D?style=flat-square) ![Morphic](https://img.shields.io/badge/Morphic-7C3AED?style=flat-square) ![Suno](https://img.shields.io/badge/Suno-30363D?style=flat-square&logo=suno&logoColor=white) ![CapCut](https://img.shields.io/badge/CapCut-30363D?style=flat-square) ![Artlist](https://img.shields.io/badge/Artlist-30363D?style=flat-square) ![Pexels](https://img.shields.io/badge/Pexels-05A081?style=flat-square&logo=pexels&logoColor=white) |
| **Design** | ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square) ![Illustrator](https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square) ![Canva](https://img.shields.io/badge/Canva-00C4CC?style=flat-square) ![로고 · 명함 · 리플렛](https://img.shields.io/badge/로고_·_명함_·_리플렛-30363D?style=flat-square) |
| **Pay&nbsp;·&nbsp;Login** | ![Toss Payments](https://img.shields.io/badge/Toss_Payments-0064FF?style=flat-square) ![Google Play Billing](https://img.shields.io/badge/Google_Play_Billing-01875F?style=flat-square&logo=googleplay&logoColor=white) ![Kakao Login](https://img.shields.io/badge/Kakao_Login-FFCD00?style=flat-square&logo=kakaotalk&logoColor=000000) ![Google OAuth](https://img.shields.io/badge/Google_OAuth-4285F4?style=flat-square&logo=google&logoColor=white) ![Facebook Login](https://img.shields.io/badge/Facebook_Login-0866FF?style=flat-square&logo=facebook&logoColor=white) ![TikTok Login Kit](https://img.shields.io/badge/TikTok_Login_Kit-30363D?style=flat-square&logo=tiktok&logoColor=white) ![Supabase Auth](https://img.shields.io/badge/Supabase_Auth-3FCF8E?style=flat-square&logo=supabase&logoColor=white) |
| **SNS&nbsp;·&nbsp;Data&nbsp;API** | ![YouTube Data API](https://img.shields.io/badge/YouTube_Data_API-FF0000?style=flat-square&logo=youtube&logoColor=white) ![Instagram Graph API](https://img.shields.io/badge/Instagram_Graph_API-E4405F?style=flat-square&logo=instagram&logoColor=white) ![Facebook Pages API](https://img.shields.io/badge/Facebook_Pages_API-0866FF?style=flat-square&logo=facebook&logoColor=white) ![TikTok Content Posting](https://img.shields.io/badge/TikTok_Content_Posting-30363D?style=flat-square&logo=tiktok&logoColor=white) ![Kakao SDK](https://img.shields.io/badge/Kakao_SDK-FFCD00?style=flat-square&logo=kakaotalk&logoColor=000000) ![Finnhub](https://img.shields.io/badge/Finnhub-30363D?style=flat-square) ![FatSecret](https://img.shields.io/badge/FatSecret-30363D?style=flat-square) ![OpenWeather](https://img.shields.io/badge/OpenWeather-30363D?style=flat-square) |
| **Message** | ![Solapi](https://img.shields.io/badge/Solapi-%EC%95%8C%EB%A6%BC%ED%86%A1_·_SMS-3B5BDB?style=flat-square) ![Resend](https://img.shields.io/badge/Resend-30363D?style=flat-square&logo=resend&logoColor=white) ![Zoho Mail](https://img.shields.io/badge/Zoho_Mail-30363D?style=flat-square) ![카카오톡 채널](https://img.shields.io/badge/%EC%B9%B4%EC%B9%B4%EC%98%A4%ED%86%A1_%EC%B1%84%EB%84%90-FFCD00?style=flat-square&logo=kakaotalk&logoColor=000000) |
| **SEO&nbsp;·&nbsp;Growth** | ![Google Analytics](https://img.shields.io/badge/Google_Analytics-E37400?style=flat-square&logo=googleanalytics&logoColor=white) ![Search Console](https://img.shields.io/badge/Search_Console-458CF5?style=flat-square&logo=googlesearchconsole&logoColor=white) ![네이버 서치어드바이저](https://img.shields.io/badge/%EB%84%A4%EC%9D%B4%EB%B2%84_%EC%84%9C%EC%B9%98%EC%96%B4%EB%93%9C%EB%B0%94%EC%9D%B4%EC%A0%80-03C75A?style=flat-square&logo=naver&logoColor=white) ![Bing Webmaster](https://img.shields.io/badge/Bing_Webmaster-30363D?style=flat-square) ![IndexNow](https://img.shields.io/badge/IndexNow-30363D?style=flat-square) ![PostHog](https://img.shields.io/badge/PostHog-1D4AFF?style=flat-square&logo=posthog&logoColor=white) ![JSON-LD](https://img.shields.io/badge/JSON--LD-30363D?style=flat-square) ![llms.txt](https://img.shields.io/badge/llms.txt-30363D?style=flat-square) |
| **Test&nbsp;·&nbsp;CI** | ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![PGlite](https://img.shields.io/badge/PGlite-336791?style=flat-square&logo=postgresql&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Infra&nbsp;·&nbsp;Domain** | ![Vercel](https://img.shields.io/badge/Vercel-30363D?style=flat-square&logo=vercel&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-30363D?style=flat-square&logo=github&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-30363D?style=flat-square&logo=github&logoColor=white) ![후이즈](https://img.shields.io/badge/%ED%9B%84%EC%9D%B4%EC%A6%88-30363D?style=flat-square) ![HOSTING.KR](https://img.shields.io/badge/HOSTING.KR-30363D?style=flat-square) ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) |
| **Workbench** | ![Cursor](https://img.shields.io/badge/Cursor-30363D?style=flat-square&logo=cursor&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square) ![GitHub CLI](https://img.shields.io/badge/GitHub_CLI-30363D?style=flat-square&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-30363D?style=flat-square&logo=notion&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square) ![Google Workspace](https://img.shields.io/badge/Google_Workspace-4285F4?style=flat-square&logo=google&logoColor=white) |

<br />

<div align="center">

<sub>기획 → 배포 → 실사용자 → 수익화 · GEONY WORKS</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D15,55:3A4BFF,100:FF5B1F&height=120&section=footer" width="100%" alt="" />

</div>

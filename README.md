<div align="center">

<a href="https://geonyworks.com"><img src="./assets/header.svg" width="100%" alt="FULL-STACK HARNESS ENGINEERING — 유선건 · GEONY WORKS 대표" /></a>

<a href="https://geonyworks.com"><img src="https://readme-typing-svg.demolab.com/?font=Noto+Sans+KR&weight=700&size=22&duration=2600&pause=1100&color=FF5B1F&center=true&vCenter=true&width=680&height=46&lines=GEONY%20WORKS%20%EB%8C%80%ED%91%9C%20%C2%B7%20%ED%92%80%EC%8A%A4%ED%83%9D%20%ED%95%98%EB%84%A4%EC%8A%A4%20%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4;%EC%82%AC%EB%9E%8C%EC%9D%80%20%ED%95%9C%20%EB%AA%85%2C%20%ED%8C%80%EC%9D%80%20Claude%20Code%20%ED%95%98%EB%84%A4%EC%8A%A4%EB%A1%9C;%EC%95%84%EC%9D%B4%EB%94%94%EC%96%B4%20%ED%95%9C%20%EC%A4%84%EC%9D%84%20%EC%8B%A4%EC%84%9C%EB%B9%84%EC%8A%A4%EB%A1%9C%20%E2%80%94%20%EA%B2%B0%EC%A0%9C%C2%B7%EC%B6%9C%EC%8B%9C%C2%B7%EC%9A%B4%EC%98%81%EA%B9%8C%EC%A7%80;Web%20%C2%B7%20Android%20%C2%B7%20Payments%20%C2%B7%20Infra" alt="GEONY WORKS 대표 · 풀스택 하네스 엔지니어" /></a>

[![GEONY WORKS](https://img.shields.io/badge/GEONY_WORKS-공식_사이트-FF5B1F?style=for-the-badge)](https://geonyworks.com)
[![Google Play](https://img.shields.io/badge/Google_Play-말랑_모험-01875F?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.geonyworks.mallangadventure)
[![Blog](https://img.shields.io/badge/Blog-바로가기-ff7f50?style=for-the-badge&logo=tistory&logoColor=white)](https://sg-coding.tistory.com/)
[![Email](https://img.shields.io/badge/Email-dbtjsrjs8282@naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:dbtjsrjs8282@naver.com)

</div>

<br />

## ⚡ About

> **코드를 "치는" 사람이 아니라, 에이전트가 틀리지 않고 일하는 판을 짜는 사람.**

거니웍스(GEONY WORKS) 대표 **유선건**입니다.  
아이디어 한 줄을 **기획 → 디자인 → 개발 → 결제 → 출시 → 운영**까지 끝까지 끌고 가서, 실제로 운영하는 제품으로 만듭니다.  
그 전 과정을 **Claude Code 하네스** — 서브에이전트 · 스킬 · MCP · 워크플로 — 위에서 돌립니다. 사람은 한 명, 팀은 하네스로.

- 🏢 **GEONY WORKS** — 웹 · 앱 · 게임 개발 스튜디오. 기획 · 브랜딩 · UI/UX부터 로그인 · 결제 연동, 서버 · 배포, SEO까지 한 번에.
- 🧠 **Harness Engineering** — 저장소마다 규칙(`CLAUDE.md` · `AGENTS.md`)과 인계 문서(`HANDOFF.md`), 검증 게이트(`npm run verify`)를 깔고 일을 맡깁니다. "다 했어요"가 아니라 검증이 통과해야 끝.
- 🚀 **Shipped, not demo** — Google Play에 출시한 RPG, 결제가 붙은 청첩장 서비스, 한·베 커플 앱, AI 에이전트 오피스. 전부 지금 돌아가는 실서비스.
- 🌏 **한국어 · Tiếng Việt** — 제품 대부분을 두 언어로 설계합니다. 베트남어가 한국어보다 평균 2.9배 길다는 것까지 레이아웃 규칙에 넣어 둡니다.

<br />

## 🧠 How I Build — Harness Engineering

```ts
// 거니웍스 개발팀 = 사람 1 + 하네스
const harness = {
  engine: "Claude Code — Desktop · CLI",
  models: ["Opus", "Sonnet", "Haiku"],
  rules:  ["CLAUDE.md", "AGENTS.md", "HANDOFF.md"],
  agents: "sub-agents × isolated git worktrees",
  skills: ["superpowers", "higgsfield", "typecast"],
  mcp:    ["supabase", "vercel", "playwright",
           "claude-in-chrome", "fal", "lottiefiles"],
  loop:   "plan → build → review → fix → handoff",
  gate:   "npm run verify", // tsc · lint · vitest · playwright
  ship:   ["vercel", "google-play", "github-actions"],
};
```

- 📜 **규칙은 사고에서 나온다** — 버그 하나가 규칙 한 줄이 됩니다. Doii · 말랑 모험 저장소의 `AGENTS.md`는 *어떤 버그에서 어떤 규칙이 나왔는지* 적어 둔 설계 사례집.
- 🌙 **자리를 비운 밤에도** — Workflow가 Build → Review(3관점) → Fix → 공지 · 인계까지 한 라운드를 끝까지 돌립니다.
- 🧪 **끝은 검증이 정한다** — typecheck · lint · Vitest · Playwright e2e. DB는 PGlite로 마이그레이션과 RLS까지 로컬에서 검증.
- 🔐 **경계는 서버에** — RLS로 막고, 결제 확정 · 보상 정산은 서버 RPC로만. 비밀값은 커밋 · 로그 · 대화에 남기지 않습니다.

<sub>📈 Doii · 말랑 모험 저장소 하나에만 커밋 1,800+ · Supabase 마이그레이션 2,100+ (2026-10 기준)</sub>

<br />

## 🚀 Products — 직접 만들고, 직접 운영합니다

<p align="center">
  <a href="https://capdoii.com/play"><img src="./assets/works/malang.jpg" width="49%" alt="말랑 모험 — 귀엽고 몽글한 성장형 판타지 RPG" /></a>
  <a href="https://dearmio.com"><img src="./assets/works/dearmio.jpg" width="49%" alt="Dearmio — 모바일 청첩장 · 초대장" /></a>
  <a href="https://capdoii.com"><img src="./assets/works/doii.jpg" width="49%" alt="Doii — 우리 둘의 시간을, 여기에 담아요" /></a>
  <a href="https://ailter.ai"><img src="./assets/works/ailter.jpg" width="49%" alt="AI 일터 — 나만의 AI 오피스" /></a>
  <a href="https://geonyworks.com"><img src="./assets/works/geonyworks.jpg" width="49%" alt="GEONY WORKS — 기획부터 배포까지, 한 팀으로" /></a>
  <a href="https://geonywony.com"><img src="./assets/works/geonywony.jpg" width="49%" alt="거니워니 공식 홈페이지 — KOREA × VIỆT NAM" /></a>
</p>

### 🎮 [말랑 모험 · Malang Adventure](https://capdoii.com/play)

[![Google Play](https://img.shields.io/badge/Google_Play-출시-01875F?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.geonyworks.mallangadventure)
[![Web](https://img.shields.io/badge/Web-capdoii.com%2Fplay-FF5B1F?style=flat-square)](https://capdoii.com/play)

두 영웅과 펫을 키우고, 강화 · 재련으로 장비를 다듬으며 층층이 보스를 넘는 귀여운 턴제 RPG. 웹과 Android 앱이 한 계정으로 이어지고 한국어 · 베트남어를 지원합니다.  
세계관 · 전투 연출 · 경제 밸런스 · 사운드 · 결제 · 스토어 출시까지 직접. 콘텐츠는 전부 DB 표라 월드가 늘어도 코드에 분기가 없습니다.  
`Next.js` `Supabase (RLS · RPC · Realtime · pg_cron)` `Capacitor Android` `Google Play Billing` `Toss Payments` `Web Push` `Kakao` `fal.ai` `Higgsfield` `ElevenLabs` `Typecast`

### 💌 [Dearmio · 디어미오](https://dearmio.com)

감성 모바일 청첩장부터 돌잔치 · 생일 · 환갑 · 집들이 초대장까지 — 먼저 만들어 보고, 마음에 들면 결제하는 서비스.  
한 커플의 청첩장에서 시작해, 고객이 늘어도 코드를 고치지 않는 **한 저장소 · 한 배포** 서비스로 키웠습니다. 결제 · 알림톡 · 식전영상 · 관리자 분석까지.  
`Next.js` `Supabase` `Toss Payments` `Remotion` `Claude API` `Solapi` `Resend`

### 💞 [Doii · 도이](https://capdoii.com)

한국 · 베트남 커플을 위한 모바일 웹앱(PWA). 일정 · 두 통화 생활비 · 추억 · 예약 편지 · 놀이터를 두 사람이 각자의 언어와 시간대로 같이 씁니다. 다른 언어로 쓴 글에는 번역 버튼(Gemini).  
숨겨야 하는 값은 화면이 가리는 게 아니라 **RLS가 SELECT를 막습니다** — 보안 경계는 전부 서버.  
`Next.js` `Supabase Realtime` `RLS · SECURITY DEFINER RPC` `Gemini` `Web Push` `PWA`

### 🤖 [AI 일터 · AILTER](https://ailter.ai)

나만의 AI 직원들과 회의하고, 일을 맡기고, 모든 기록을 남기는 AI 오피스.  
대표(CEO) 에이전트가 일을 DAG로 쪼개 리서처 · 작가 · 디자이너 · 개발자 · 비서에게 넘기고, 직원은 도구를 직접 써서 결과를 확인한 뒤 답합니다. 원격 MCP 연결 · Obsidian 보관소 · 지식 그래프.  
`React` `Express` `Claude API (tool use)` `OpenAI` `Gemini` `Supabase pgvector` `MCP`

### 🏢 [GEONY WORKS · 거니웍스](https://geonyworks.com)

회사 공식 사이트. 15초 쇼릴 인트로, 외부 모델 없이 three.js 도형으로만 만든 3D 캐릭터 「거니」, 스크롤 스토리. 고객 전용 포털(작업 트리 · 자료 · 청구서)과 관리자까지 한 저장소.  
`Next.js 16` `React Three Fiber` `GSAP` `Lenis` `Supabase` `Typecast` `ElevenLabs Music`

### 🌏 [거니워니 · GeonyWony](https://geonywony.com)

한국 거니와 베트남 워니, 한베커플 이야기를 담은 공식 홈페이지. 카카오 · Google · Facebook 소셜 로그인, 유튜브 영상 · Shorts 허브, 앨범 플레이어, 따라오는 3D 무대와 AR 「내 방에 놓기」.  
`Next.js` `Supabase Auth` `three.js` `PostHog` `Playwright`

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
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nextjs%2Creact%2Cts%2Cjs%2Ctailwind%2Csupabase%2Cpostgres%2Cvercel%2Cgithubactions%2Cnodejs%2Cthreejs%2Cvite%2Cexpress%2Cpython%2Cgit%2Cmd&perline=8&theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=nextjs%2Creact%2Cts%2Cjs%2Ctailwind%2Csupabase%2Cpostgres%2Cvercel%2Cgithubactions%2Cnodejs%2Cthreejs%2Cvite%2Cexpress%2Cpython%2Cgit%2Cmd&perline=8&theme=light">
    <img src="https://skillicons.dev/icons?i=nextjs%2Creact%2Cts%2Cjs%2Ctailwind%2Csupabase%2Cpostgres%2Cvercel%2Cgithubactions%2Cnodejs%2Cthreejs%2Cvite%2Cexpress%2Cpython%2Cgit%2Cmd&perline=8&theme=light" alt="Next.js · React · TypeScript · JavaScript · Tailwind CSS · Supabase · PostgreSQL · Vercel · GitHub Actions · Node.js · three.js · Vite · Express · Python · Git · Markdown">
  </picture>
</p>

| 영역 | 도구 |
| :-- | :-- |
| **🧠 Harness** | ![Claude Code](https://img.shields.io/badge/Claude_Code-Desktop_·_CLI-D97757?style=flat-square&logo=claudecode&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-Opus_·_Sonnet_·_Haiku-30363D?style=flat-square&logo=claude&logoColor=D97757) ![Sub-agents](https://img.shields.io/badge/Sub--agents-30363D?style=flat-square) ![Agent Skills](https://img.shields.io/badge/Agent_Skills-30363D?style=flat-square) ![Hooks](https://img.shields.io/badge/Hooks-30363D?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-30363D?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![Workflows](https://img.shields.io/badge/Workflows-30363D?style=flat-square) ![Superpowers](https://img.shields.io/badge/Superpowers-plugin-30363D?style=flat-square) ![Git worktrees](https://img.shields.io/badge/Git_worktrees-30363D?style=flat-square&logo=git&logoColor=F05032) |
| **🔌 MCP** | ![Supabase MCP](https://img.shields.io/badge/Supabase_MCP-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Vercel MCP](https://img.shields.io/badge/Vercel_MCP-30363D?style=flat-square&logo=vercel&logoColor=white) ![Playwright MCP](https://img.shields.io/badge/Playwright_MCP-2EAD33?style=flat-square) ![Claude in Chrome](https://img.shields.io/badge/Claude_in_Chrome-4285F4?style=flat-square&logo=googlechrome&logoColor=white) ![fal.ai MCP](https://img.shields.io/badge/fal.ai_MCP-30363D?style=flat-square) ![LottieFiles MCP](https://img.shields.io/badge/LottieFiles_MCP-00C1A2?style=flat-square&logo=lottiefiles&logoColor=white) ![Context7 MCP](https://img.shields.io/badge/Context7_MCP-30363D?style=flat-square) |
| **🤖 AI · Media API** | ![Claude API](https://img.shields.io/badge/Claude_API-30363D?style=flat-square&logo=anthropic&logoColor=F0EEE6) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-30363D?style=flat-square&logo=elevenlabs&logoColor=white) ![fal.ai](https://img.shields.io/badge/fal.ai-30363D?style=flat-square) ![Typecast](https://img.shields.io/badge/Typecast-5B21B6?style=flat-square) ![Inworld](https://img.shields.io/badge/Inworld_TTS-30363D?style=flat-square) ![LM Studio](https://img.shields.io/badge/LM_Studio-4F46E5?style=flat-square&logo=lmstudio&logoColor=white) ![ChatGPT](https://img.shields.io/badge/ChatGPT-10A37F?style=flat-square) ![Grok](https://img.shields.io/badge/Grok-30363D?style=flat-square) |
| **🏗 Platform** | ![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![Expo](https://img.shields.io/badge/Expo-30363D?style=flat-square&logo=expo&logoColor=white) ![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white) ![React Three Fiber](https://img.shields.io/badge/React_Three_Fiber-30363D?style=flat-square&logo=threedotjs&logoColor=white) ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-Postgres_·_Auth_·_Storage_·_Realtime_·_Edge_Functions-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![PGlite](https://img.shields.io/badge/PGlite-336791?style=flat-square&logo=postgresql&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black) |
| **💳 Pay · Growth** | ![Toss Payments](https://img.shields.io/badge/Toss_Payments-0064FF?style=flat-square) ![Google Play Billing](https://img.shields.io/badge/Google_Play_Billing-01875F?style=flat-square&logo=googleplay&logoColor=white) ![Kakao SDK](https://img.shields.io/badge/Kakao_SDK-FFCD00?style=flat-square&logo=kakaotalk&logoColor=000000) ![Web Push](https://img.shields.io/badge/Web_Push-VAPID-5A0FC8?style=flat-square) ![Solapi](https://img.shields.io/badge/Solapi-알림톡_·_SMS-3B5BDB?style=flat-square) ![Resend](https://img.shields.io/badge/Resend-30363D?style=flat-square&logo=resend&logoColor=white) ![Google Analytics](https://img.shields.io/badge/Google_Analytics-E37400?style=flat-square&logo=googleanalytics&logoColor=white) ![Search Console](https://img.shields.io/badge/Search_Console-458CF5?style=flat-square&logo=googlesearchconsole&logoColor=white) ![PostHog](https://img.shields.io/badge/PostHog-1D4AFF?style=flat-square&logo=posthog&logoColor=white) |
| **🛠 Workbench** | ![Cursor](https://img.shields.io/badge/Cursor-30363D?style=flat-square&logo=cursor&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square) ![GitHub CLI](https://img.shields.io/badge/GitHub_CLI-30363D?style=flat-square&logo=github&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js_24-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python_3.14-3776AB?style=flat-square&logo=python&logoColor=white) ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) ![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-30363D?style=flat-square&logo=notion&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square) ![Google Workspace](https://img.shields.io/badge/Google_Workspace-4285F4?style=flat-square&logo=google&logoColor=white) |
| **🎬 Creative · Content** | ![Higgsfield](https://img.shields.io/badge/Higgsfield-30363D?style=flat-square) ![Kling](https://img.shields.io/badge/Kling-30363D?style=flat-square) ![Seedance](https://img.shields.io/badge/Seedance-30363D?style=flat-square) ![Morphic](https://img.shields.io/badge/Morphic-7C3AED?style=flat-square) ![Suno](https://img.shields.io/badge/Suno-30363D?style=flat-square&logo=suno&logoColor=white) ![Remotion](https://img.shields.io/badge/Remotion-0B84F3?style=flat-square) ![CapCut](https://img.shields.io/badge/CapCut-30363D?style=flat-square) ![Artlist](https://img.shields.io/badge/Artlist-30363D?style=flat-square) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square) ![Illustrator](https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square) ![Canva](https://img.shields.io/badge/Canva-00C4CC?style=flat-square) ![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white) ![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white) |

<br />

<div align="center">

<sub>Built with Claude Code · 사람 한 명과 하네스가 만듭니다</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D15,55:3A4BFF,100:FF5B1F&height=120&section=footer" width="100%" alt="" />

</div>

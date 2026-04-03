---
theme: default
highlighter: shiki
lineNumbers: false
css: style.css
transition: fade
fonts:
  sans: Noto Sans KR
---

<!-- ══════════════════════════════════════════════
  S1 — 표지
══════════════════════════════════════════════ -->

<div style="display:flex; flex-direction:column; justify-content:center; align-items:center; height:100%;">
  <div class="sub" style="margin-bottom:0.8rem; font-size:0.9rem;">사내 발표 / 기술 조직 공유</div>
  <h1 class="grad" style="font-size:3.4rem; text-align:center; margin:0;">AI Native<br>환경 조성</h1>
  <div v-click style="margin-top:1.5rem; color:#555; font-size:1rem;">
    일하는 방식이 바뀌지 않으면 뒤처진다
  </div>
</div>

---

<!-- ══════════════════════════════════════════════
  S2 — 우리 시간이 어디 가나 (카드 4개 순차)
══════════════════════════════════════════════ -->

<div class="sub">우리 시간이 어디 가나</div>
<h2 class="grad" style="font-size:1.6rem; margin:0 0 0.8rem;">개발 시간의 80%는 여기서 사라진다</h2>

<div v-click class="card red">
  <div class="row" style="border:none; padding:0;">
    <div class="num" style="background:#ef4444; box-shadow:0 0 12px rgba(239,68,68,0.4);">1</div>
    <div class="row-content">
      <div class="row-title">테스트 시나리오 검증</div>
      <div class="row-desc">오류 재현 · 스크린샷 확인 · 반복 실행</div>
    </div>
    <div style="font-size:1.2rem; font-weight:900; color:#ef4444; margin-left:auto;">30%</div>
  </div>
</div>

<div v-click class="card orange">
  <div class="row" style="border:none; padding:0;">
    <div class="num" style="background:#f97316; box-shadow:0 0 12px rgba(249,115,22,0.4);">2</div>
    <div class="row-content">
      <div class="row-title">단순 버그 수정</div>
      <div class="row-desc">같은 유형의 오류를 매번 수동으로</div>
    </div>
    <div style="font-size:1.2rem; font-weight:900; color:#f97316; margin-left:auto;">25%</div>
  </div>
</div>

<div v-click class="card purple">
  <div class="row" style="border:none; padding:0;">
    <div class="num" style="background:#a855f7; box-shadow:0 0 12px rgba(168,85,247,0.4);">3</div>
    <div class="row-content">
      <div class="row-title">기능 오류 수정</div>
      <div class="row-desc">원인 파악에 시간, 수정도 반복</div>
    </div>
    <div style="font-size:1.2rem; font-weight:900; color:#a855f7; margin-left:auto;">25%</div>
  </div>
</div>

<div v-click class="card cyan">
  <div class="row" style="border:none; padding:0;">
    <div class="num" style="background:#06b6d4; box-shadow:0 0 12px rgba(6,182,212,0.4);">4</div>
    <div class="row-content">
      <div class="row-title">실제 개발 — 가치를 만드는 시간</div>
      <div class="row-desc">비즈니스 로직 · 기능 설계 · 성능 개선</div>
    </div>
    <div style="font-size:1.2rem; font-weight:900; color:#06b6d4; margin-left:auto;">20%</div>
  </div>
</div>

<div v-click style="text-align:center; margin-top:0.5rem; color:#ef4444; font-weight:700; font-size:0.9rem;">
  ⚠️ 80%는 반복 작업 — 실제 개발에 쓰는 시간은 20%뿐
</div>

---

<!-- ══════════════════════════════════════════════
  S3 — 국내 실제 사례 (2025~2026)
══════════════════════════════════════════════ -->

<div class="sub">2025~2026 — 국내 기업에서 이미 벌어지는 일</div>
<h2 class="grad" style="font-size:1.6rem; margin:0 0 0.7rem;">Agentic AI, 먼 나라 얘기가 아니다</h2>

<div v-click style="background:#0f0f20; border-left:3px solid #06b6d4; border-radius:0 10px 10px 0; padding:0.65rem 1.1rem; margin-bottom:0.5rem;">
  <div style="font-size:0.65rem; font-weight:700; color:#06b6d4; letter-spacing:0.08em; margin-bottom:0.25rem;">LG CNS · AgenticWorks 도입</div>
  <div style="font-size:0.92rem; font-weight:700; color:#fff; margin-bottom:0.15rem;">LG Display 생산성 10% 향상 → 3년 내 30% 목표 · 연 100억 절감</div>
  <div style="font-size:0.7rem; color:#888;">HR · 일정 · 번역 · 문서관리 에이전트 전사 배포 — 외산 SW 구독 대체</div>
</div>

<div v-click style="background:#0f0f20; border-left:3px solid #a855f7; border-radius:0 10px 10px 0; padding:0.65rem 1.1rem; margin-bottom:0.5rem;">
  <div style="font-size:0.65rem; font-weight:700; color:#a855f7; letter-spacing:0.08em; margin-bottom:0.25rem;">한화 · Copilot Studio 기반 에이전트</div>
  <div style="font-size:0.92rem; font-weight:700; color:#fff; margin-bottom:0.15rem;">정기회의 보고서 · 환경법규 검토 자동화 → 자율형 에이전트로 전사 확대 중</div>
  <div style="font-size:0.7rem; color:#888;">사람이 검토하던 반복 문서 업무를 AI가 초안부터 처리</div>
</div>

<div v-click style="background:#0f0f20; border-left:3px solid #10b981; border-radius:0 10px 10px 0; padding:0.65rem 1.1rem; margin-bottom:0.5rem;">
  <div style="font-size:0.65rem; font-weight:700; color:#10b981; letter-spacing:0.08em; margin-bottom:0.25rem;">네이버 · 카카오 · 에이전트 전략 전환</div>
  <div style="font-size:0.92rem; font-weight:700; color:#fff; margin-bottom:0.15rem;">네이버 분기 역대 최대 매출 · 카카오 첫 분기 영업이익 2,000억 돌파</div>
  <div style="font-size:0.7rem; color:#888;">에이전트 N (검색→예약→결제 자동화) · 카나나 (초개인화 메신저 AI) 전환 후</div>
</div>

<div v-click style="background:#13131f; border:1px solid #2a2a4a; border-radius:10px; padding:0.6rem 1.1rem; display:flex; align-items:center; gap:1rem; margin-top:0.2rem;">
  <div style="font-size:1.5rem;">📊</div>
  <div>
    <span style="color:#a855f7; font-weight:700; font-size:0.88rem;">생성형 AI +30%</span>
    <span style="color:#555; font-size:0.82rem;"> → </span>
    <span style="color:#00FF41; font-weight:900; font-size:0.95rem;">Agentic AI +200%</span>
    <span style="color:#666; font-size:0.72rem; margin-left:0.5rem;">— 글로벌 컨설팅 펌 실측 · 에이전틱 AI 시장 2025년 2조 → 2030년 61조 예측</span>
  </div>
</div>

---

<!-- ══════════════════════════════════════════════
  S4 — 바뀌지 않으면 어떻게 되나
══════════════════════════════════════════════ -->

<div class="sub">바뀌지 않으면</div>
<h2 class="grad" style="font-size:1.6rem; margin:0 0 0.8rem;">세 가지 현실이 온다</h2>

<div v-click class="crisis">
  <div class="crisis-icon">🏢</div>
  <div class="crisis-body">
    <div class="crisis-title">Shopify CEO: "AI로 못 한다는 걸 증명해야 사람을 뽑는다"</div>
    <div class="crisis-desc">2025년 4월 전사 공개 메모 — AI 활용이 인사고과 항목에 추가됨 · Fiverr · Klarna도 동일 방향</div>
  </div>
  <div class="crisis-tag">현실 1</div>
</div>

<div v-click class="crisis">
  <div class="crisis-icon">⚡</div>
  <div class="crisis-body">
    <div class="crisis-title">Goldman Sachs는 AI 에이전트 수천 개를 개발자 옆에 배치하고 있다</div>
    <div class="crisis-desc">6명이 2주 걸리던 IPO 보고서 → AI가 수 분 완료 — 경쟁사의 속도가 이미 달라졌다</div>
  </div>
  <div class="crisis-tag">현실 2</div>
</div>

<div v-click class="crisis">
  <div class="crisis-icon">📈</div>
  <div class="crisis-body">
    <div class="crisis-title">격차는 복리로 쌓인다 — 지금 시작하지 않으면 영영 못 따라잡는다</div>
    <div class="crisis-desc">Cursor가 GitHub Copilot을 2년 만에 추월한 것처럼 — AI Native 팀의 노하우는 돈으로 살 수 없다</div>
  </div>
  <div class="crisis-tag">현실 3</div>
</div>

<div v-click style="background:linear-gradient(135deg,rgba(99,102,241,0.15),rgba(168,85,247,0.15)); border:1.5px solid #6366f1; border-radius:12px; padding:0.85rem 1.4rem; display:flex; align-items:center; gap:1.1rem; margin-top:0.4rem;">
  <div style="font-size:1.6rem; flex-shrink:0;">🚀</div>
  <div>
    <div style="font-size:1.05rem; font-weight:900; color:#fff; margin-bottom:0.1rem;">그래서 우리는 지금 바뀌어야 한다</div>
    <div style="font-size:0.78rem; color:#a5b4fc;">AI Native로 일하는 방식을 바꾸는 팀만이 살아남는다</div>
  </div>
  <div style="margin-left:auto; font-size:0.72rem; font-weight:700; color:#6366f1; border:1px solid #6366f1; border-radius:999px; padding:0.2rem 0.7rem; white-space:nowrap;">우리의 선택</div>
</div>

---

<!-- ══════════════════════════════════════════════
  S5 — AI Native란? (가로 타임라인 + 원칙)
══════════════════════════════════════════════ -->

<div style="display:flex; flex-direction:column; justify-content:center; align-items:center; height:100%; gap:1rem;">

  <div style="text-align:center;">
    <div class="sub">방향</div>
    <h1 class="grad" style="font-size:2rem; margin:0;">AI를 도구가 아니라 동료로</h1>
    <div style="color:#666; font-size:0.88rem; margin-top:0.2rem;">쓰는 게 아니라 — 같이 일하는 것</div>
  </div>

  <!-- 가로 타임라인 -->
  <div class="h-timeline" style="width:100%;">
    <div v-click class="h-tl-item">
      <div class="h-tl-circle c-purple">01</div>
      <div class="h-tl-bar c-purple"></div>
      <div class="h-tl-title t-purple">Embed</div>
      <div class="h-tl-desc">코드 리뷰도<br>AI가 같이 본다</div>
    </div>
    <div v-click class="h-tl-item">
      <div class="h-tl-circle c-cyan">02</div>
      <div class="h-tl-bar c-cyan"></div>
      <div class="h-tl-title t-cyan">Automate</div>
      <div class="h-tl-desc">반복 작업은<br>파이프라인이 처리한다</div>
    </div>
    <div v-click class="h-tl-item">
      <div class="h-tl-circle c-green">03</div>
      <div class="h-tl-bar c-green"></div>
      <div class="h-tl-title t-green">Focus</div>
      <div class="h-tl-desc">사람은 설계와<br>판단만 한다</div>
    </div>
  </div>

  <div v-click style="text-align:center; color:#555; font-size:0.78rem;">
    이게 바로 — <strong style="color:#a5b4fc; font-size:1rem;">AI Native</strong>
  </div>

</div>

---

<!-- ══════════════════════════════════════════════
  S6 — 지금 방식의 한계 (좌우 비교)
══════════════════════════════════════════════ -->

<div style="display:flex;flex-direction:column;justify-content:center;height:100%;">
<div class="sub">지금 방식의 한계</div>
<h2 class="grad" style="font-size:1.6rem; margin:0 0 0.8rem;">AI 도구 활용 vs AI Native</h2>
<div class="vs-grid">
<div class="panel s6-left">
<div class="panel-title s6-left-title">AI 도구 활용 방식</div>
<div v-click class="step-item">🔍 문제 발생 — 오류를 사람이 먼저 인식</div>
<div v-click><div class="step-arr">↓</div><div class="step-item">📋 직접 확인 — 코드 · 로그 수동 추적</div></div>
<div v-click><div class="step-arr">↓</div><div class="step-item">💬 AI에게 질문 — 복붙 후 답변 검토</div></div>
<div v-click class="s6-step4"><div class="step-arr">↓</div><div class="step-item">🔧 수동 적용 — 사람이 직접 수정 · 검증</div><div style="text-align:center; font-size:0.7rem; color:#444; margin-top:0.6rem;">매 작업마다 사람이 개입</div></div>
</div>
<div class="panel active s6-right-panel">
<div class="panel-title" style="color:#a5b4fc;">AI Native</div>
<div style="flex:1;display:flex;flex-direction:column;justify-content:center;">
<div style="display:flex; justify-content:center; gap:0; align-items:flex-start; margin:1rem 0;">
<div v-click class="s6-circle1" style="text-align:center;"><div class="num" style="margin:0 auto 0.4rem; width:2.8rem; height:2.8rem; font-size:1.1rem;">1</div><div style="font-size:0.78rem; color:#a5b4fc; font-weight:700;">감지</div></div>
<div v-click style="display:flex;align-items:flex-start;"><div class="pipe-arr" style="padding:0 0.5rem; margin-top:0.7rem; font-size:1.1rem;">→</div><div style="text-align:center;"><div class="num" style="margin:0 auto 0.4rem; width:2.8rem; height:2.8rem; font-size:1.1rem;">2</div><div style="font-size:0.78rem; color:#a5b4fc; font-weight:700;">분석</div></div></div>
<div v-click style="display:flex;align-items:flex-start;"><div class="pipe-arr" style="padding:0 0.5rem; margin-top:0.7rem; font-size:1.1rem;">→</div><div style="text-align:center;"><div class="num" style="margin:0 auto 0.4rem; width:2.8rem; height:2.8rem; font-size:1.1rem;">3</div><div style="font-size:0.78rem; color:#a5b4fc; font-weight:700;">처리</div></div></div>
<div v-click style="display:flex;align-items:flex-start;"><div class="pipe-arr" style="padding:0 0.5rem; margin-top:0.7rem; font-size:1.1rem;">→</div><div style="text-align:center;"><div class="num" style="margin:0 auto 0.4rem; width:2.8rem; height:2.8rem; font-size:1.1rem;">4</div><div style="font-size:0.78rem; color:#a5b4fc; font-weight:700;">검증</div></div></div>
<div v-click style="display:flex;align-items:flex-start;"><div class="pipe-arr" style="padding:0 0.5rem; margin-top:0.7rem; font-size:1.1rem;">→</div><div style="text-align:center;"><div class="num" style="margin:0 auto 0.4rem; width:2.8rem; height:2.8rem; font-size:1.1rem;">5</div><div style="font-size:0.78rem; color:#a5b4fc; font-weight:700;">반영</div></div></div>
</div>
<div style="text-align:center; font-size:0.85rem; color:#a5b4fc; font-weight:700; margin-top:0.8rem;">한 번 만들면 자동으로 반복</div>
<div style="text-align:center; font-size:1.3rem; font-weight:900; color:#fff; margin-top:0.4rem;">∞ 반복 &nbsp;/&nbsp; 추가 인력 0</div>
</div>
</div>
</div>
</div>

---

<!-- ══════════════════════════════════════════════
  S7 — 사례 1: 쿼리 튜닝
══════════════════════════════════════════════ -->

<div class="sub">사례 1</div>
<h2 class="grad" style="font-size:1.6rem; margin:0 0 0.5rem;">쿼리 튜닝 자동화</h2>

<div class="card" style="border-top-color:#ef4444; margin-bottom:0.6rem; padding:0.6rem 1rem;">
  <span style="font-size:0.7rem; color:#ef4444; font-weight:700;">⚠ 문제 &nbsp;</span>
  <span style="font-size:0.82rem; color:#ccc;">XML 1,500개, 슬로우 쿼리 수십 개 상시 발생 — 수동 튜닝으로는 한계</span>
</div>

<!-- 스테이지 카드 플로우 — 화살표를 다음 카드와 묶음 -->
<div style="display:flex; align-items:stretch; gap:0; margin-bottom:0.6rem;">
  <div v-click style="display:flex;align-items:stretch;flex:1;">
    <div class="stage-card" style="flex:1;">
      <div class="stage-label">STAGE 01</div>
      <div class="stage-icon">🔍</div>
      <div class="stage-title">XML 스캔</div>
      <div class="stage-desc">1,500개 XML<br>슬로우 쿼리 탐지</div>
    </div>
  </div>
  <div v-click style="display:flex;align-items:stretch;flex:1;">
    <div class="stage-arr">→</div>
    <div class="stage-card" style="flex:1;">
      <div class="stage-label">STAGE 02</div>
      <div class="stage-icon">🤖</div>
      <div class="stage-title">AI 분석</div>
      <div class="stage-desc">실행계획 해석<br>병목 원인 파악</div>
    </div>
  </div>
  <div v-click style="display:flex;align-items:stretch;flex:1;">
    <div class="stage-arr">→</div>
    <div class="stage-card" style="flex:1;">
      <div class="stage-label">STAGE 03</div>
      <div class="stage-icon">⚡</div>
      <div class="stage-title">튜닝 생성</div>
      <div class="stage-desc">인덱스 전략<br>쿼리 재작성</div>
    </div>
  </div>
  <div v-click style="display:flex;align-items:stretch;flex:1;">
    <div class="stage-arr">→</div>
    <div class="stage-card" style="flex:1;">
      <div class="stage-label">STAGE 04</div>
      <div class="stage-icon">✅</div>
      <div class="stage-title">검증</div>
      <div class="stage-desc">실행시간 비교<br>결과 동일성 확인</div>
    </div>
  </div>
  <div v-click style="display:flex;align-items:stretch;flex:1;">
    <div class="stage-arr">→</div>
    <div class="stage-card" style="flex:1;">
      <div class="stage-label">STAGE 05</div>
      <div class="stage-icon">🚀</div>
      <div class="stage-title">반영</div>
      <div class="stage-desc">XML 자동 패치<br>성과 기록</div>
    </div>
  </div>
</div>

<!-- 성과 수치 3열 -->
<div v-click style="display:grid; grid-template-columns:repeat(3,1fr); gap:0.6rem; margin-top:0.2rem;">
  <div class="stat-card purple" style="padding:0.6rem 0.8rem;">
    <div class="stat-emoji">🗑️</div>
    <div class="stat-num" style="font-size:1.6rem;">700개</div>
    <div class="stat-label">미사용 쿼리 제거</div>
    <div class="stat-badge">1,500개 중 필터</div>
  </div>
  <div class="stat-card cyan" style="padding:0.6rem 0.8rem;">
    <div class="stat-emoji">🔧</div>
    <div class="stat-num" style="font-size:1.6rem;">77 / 80</div>
    <div class="stat-label">불량 쿼리 자동 수정</div>
    <div class="stat-badge">수동 개입 3건만</div>
  </div>
  <div class="stat-card indigo" style="padding:0.6rem 0.8rem;">
    <div class="stat-emoji">📈</div>
    <div class="stat-num" style="font-size:1.6rem;">95%</div>
    <div class="stat-label">평균 응답속도 개선</div>
    <div class="stat-badge">자동화 파이프라인</div>
  </div>
</div>

---

<!-- ══════════════════════════════════════════════
  S8 — 사례 2: 개발·검증 파이프라인 자동화
══════════════════════════════════════════════ -->

<div class="sub">사례 2</div>
<h2 class="grad" style="font-size:1.6rem; margin:0 0 0.5rem;">개발·검증 파이프라인 자동화</h2>

<div class="card" style="border-top-color:#ef4444; margin-bottom:0.6rem; padding:0.6rem 1rem;">
  <span style="font-size:0.7rem; color:#ef4444; font-weight:700;">⚠ 문제 &nbsp;</span>
  <span style="font-size:0.82rem; color:#ccc;">테스트 시나리오 검증이 개발 시간의 30% 잠식 — 매번 수동으로 반복</span>
</div>

<div style="display:flex; align-items:stretch; gap:0; margin-bottom:0.6rem;">
  <div v-click style="display:flex;align-items:stretch;flex:1;">
    <div class="stage-card" style="flex:1; border-top-color:#a855f7;">
      <div class="stage-label">STAGE 01</div>
      <div class="stage-icon">🏗️</div>
      <div class="stage-title">Harness 설계</div>
      <div class="stage-desc">CLAUDE.md 규칙<br>MCP 서버 연결</div>
    </div>
  </div>
  <div v-click style="display:flex;align-items:stretch;flex:1;">
    <div class="stage-arr">→</div>
    <div class="stage-card" style="flex:1; border-top-color:#6366f1;">
      <div class="stage-label">STAGE 02</div>
      <div class="stage-icon">🤖</div>
      <div class="stage-title">AI 코드 작업</div>
      <div class="stage-desc">Claude Code<br>레거시 분석·수정</div>
    </div>
  </div>
  <div v-click style="display:flex;align-items:stretch;flex:1;">
    <div class="stage-arr">→</div>
    <div class="stage-card" style="flex:1; border-top-color:#06b6d4;">
      <div class="stage-label">STAGE 03</div>
      <div class="stage-icon">🎭</div>
      <div class="stage-title">Playwright 검증</div>
      <div class="stage-desc">E2E 자동 실행<br>GNB · 화면 탐색</div>
    </div>
  </div>
  <div v-click style="display:flex;align-items:stretch;flex:1;">
    <div class="stage-arr">→</div>
    <div class="stage-card" style="flex:1; border-top-color:#10b981;">
      <div class="stage-label">STAGE 04</div>
      <div class="stage-icon">📋</div>
      <div class="stage-title">리포트</div>
      <div class="stage-desc">Markdown 자동 생성<br>노션 업로드</div>
    </div>
  </div>
</div>

<div v-click style="display:grid; grid-template-columns:1fr 1fr; gap:0.8rem;">
  <div class="stat-card cyan" style="padding:1rem 1.2rem;">
    <div class="stat-emoji">⚡</div>
    <div class="stat-num" style="font-size:1.8rem;">하루 만에</div>
    <div class="stat-label">E2E 자동화 구축 완료</div>
    <div style="font-size:0.68rem; color:#666; margin-top:0.4rem; text-align:center; line-height:1.5;">GNB 전체 메뉴 탐색 · 로그인 · 화면 렌더링<br>스크린샷 캡처까지 자동 시나리오 생성</div>
  </div>
  <div class="stat-card green" style="padding:1rem 1.2rem;">
    <div class="stat-emoji">🎯</div>
    <div class="stat-num" style="font-size:1.8rem;">수동 테스트 0</div>
    <div class="stat-label">Playwright가 전부 처리</div>
    <div style="font-size:0.68rem; color:#666; margin-top:0.4rem; text-align:center; line-height:1.5;">반복 클릭 · 입력 · 검증을 코드로 대체<br>배포마다 자동 실행 · 리포트 생성</div>
  </div>
</div>

---

<!-- ══════════════════════════════════════════════
  S9 — Playwright란?
══════════════════════════════════════════════ -->

<div class="sub">Playwright란?</div>
<h2 class="grad" style="font-size:1.6rem; margin:0 0 0.8rem;">웹 브라우저를 코드로 조종한다</h2>

<div class="card-grid" style="margin-bottom:0.7rem;">
  <div v-click class="card cyan" style="margin-bottom:0;">
    <div style="font-size:1.8rem; margin-bottom:0.4rem;">🖥️</div>
    <div style="font-size:0.9rem; font-weight:700; color:#fff; margin-bottom:0.3rem;">브라우저 자동 제어</div>
    <div style="font-size:0.75rem; color:#888;">클릭 · 입력 · 스크롤 · 페이지 이동을<br>사람 대신 코드가 실행</div>
  </div>
  <div v-click class="card purple" style="margin-bottom:0;">
    <div style="font-size:1.8rem; margin-bottom:0.4rem;">🔁</div>
    <div style="font-size:0.9rem; font-weight:700; color:#fff; margin-bottom:0.3rem;">무한 반복 가능</div>
    <div style="font-size:0.75rem; color:#888;">배포할 때마다 전체 시나리오를<br>자동으로 재실행 · 검증</div>
  </div>
  <div v-click class="card indigo" style="margin-bottom:0;">
    <div style="font-size:1.8rem; margin-bottom:0.4rem;">📸</div>
    <div style="font-size:0.9rem; font-weight:700; color:#fff; margin-bottom:0.3rem;">스크린샷 · 리포트 자동 생성</div>
    <div style="font-size:0.75rem; color:#888;">테스트 결과를 시각적으로 기록<br>어디서 깨졌는지 즉시 파악</div>
  </div>
  <div v-click class="card green" style="margin-bottom:0;">
    <div style="font-size:1.8rem; margin-bottom:0.4rem;">🤝</div>
    <div style="font-size:0.9rem; font-weight:700; color:#fff; margin-bottom:0.3rem;">AI와 궁합이 좋다</div>
    <div style="font-size:0.75rem; color:#888;">Claude Code가 테스트 코드를 작성하고<br>Playwright가 실행 · 검증</div>
  </div>
</div>

<div v-click style="text-align:center; font-size:0.88rem; color:#666; margin-top:0.2rem;">
  기존엔 사람이 직접 클릭하며 확인 — 이제 AI가 짜고 Playwright가 돌린다
</div>

---

<!-- ══════════════════════════════════════════════
  S9 — 마무리
══════════════════════════════════════════════ -->

<div style="display:flex;flex-direction:column;justify-content:center;align-items:center;height:100%;gap:1rem;">
<div class="sub">마무리</div>
<h1 class="grad" style="font-size:2.6rem; text-align:center; margin:0;">이미 시작했다</h1>
<div v-click style="display:flex; gap:1rem; margin-top:0.6rem;">
<div class="stat-card purple" style="padding:0.7rem 1.2rem; min-width:12rem;">
<div class="stat-emoji">⚡</div>
<div class="stat-num" style="font-size:1.4rem;">95%</div>
<div class="stat-label">쿼리 응답속도 개선</div>
<div class="stat-badge">자동 튜닝 파이프라인</div>
</div>
<div class="stat-card cyan" style="padding:0.7rem 1.2rem; min-width:12rem;">
<div class="stat-emoji">🎭</div>
<div class="stat-num" style="font-size:1.4rem;">하루 만에</div>
<div class="stat-label">E2E 테스트 자동화 구축</div>
<div class="stat-badge">Playwright + Claude Code</div>
</div>
</div>
<div v-click style="color:#888; font-size:1.05rem; text-align:center; margin-top:0.4rem;">1명이 만든 파이프라인이 이 정도 — <strong style="color:#a5b4fc;">팀 전체가 움직이면?</strong></div>
<div v-click class="pill" style="font-size:1rem; margin-top:0.3rem; padding:0.55rem 2.2rem;">AI Native는 선택이 아니다 — 생존이다</div>
</div>

---
layout: post
title: "AI 데일리 브리핑 — 7월 10일: Anthropic, 비상장 시장서 OpenAI 첫 추월"
date: 2026-07-10 07:00:00 +0900
categories: daily
---

오늘의 가장 큰 소식은 비상장 지분거래(세컨더리) 시장에서 Anthropic의 암묵적 기업가치가 1.2조 달러까지 치솟아 OpenAI를 처음으로 앞질렀다는 것입니다. 같은 날 OpenAI는 정치적 압박 완화를 위해 미 행정부에 지분 5%를 국부펀드 형태로 출연하는 방안을 논의 중인 것으로 알려졌고, EU는 AI법 고위험 규정의 적용 시한을 2027~2028년으로 최종 연기했습니다. 이 외에 구글의 Gemini 3.5 Pro 재연기, 메타의 신규 모델 성능 주장 소식도 있었습니다. 오늘 딥다이브에서는 OpenAI가 제안한 '공공부(富)펀드' 구상을 자세히 살펴봅니다.

## 오늘의 헤드라인

### 1. Anthropic 시가총액 1.2조 달러, 비상장 시장서 OpenAI 첫 추월
세컨더리 시장에서 거래되는 Anthropic 지분 가격을 바탕으로 산출한 암묵적 기업가치가 1.2조 달러까지 올라 약 9080억 달러 수준인 OpenAI를 처음으로 앞질렀습니다. 이는 지난해 대비 550% 급등한 수치로, 지난 5월 시리즈H 라운드(9650억 달러 밸류) 이후 수요가 공급을 크게 초과하면서 실제 거래는 드물게만 체결되고 있는 상황입니다.

Anthropic은 지난 6월 SEC에 비공개 상장(IPO) 신청서를 제출한 상태입니다. 세컨더리 시장의 이번 밸류에이션 급등은 향후 실제 상장이 이뤄질 경우의 흥행 기대를 키우는 신호로 해석되고 있습니다. 다만 세컨더리 시장 가격은 소수 거래를 기준으로 형성되는 만큼 실제 기업가치와는 괴리가 있을 수 있다는 점도 함께 짚어둘 필요가 있습니다.

### 2. OpenAI, 트럼프 행정부에 지분 5% 제공 검토 — '공공부펀드' 구상
OpenAI가 미 행정부에 자사 지분 5%를 국부펀드 방식으로 출연하는 방안을 논의 중이라고 FT 등이 보도했습니다. 자세한 내용은 아래 딥다이브에서 다룹니다.

### 3. EU, AI법 '고위험' 규정 적용 시한 2027~2028년으로 최종 연기
EU 이사회가 6월 29일 'AI 옴니버스' 간소화 패키지에 최종 승인을 내리면서, 원래 2026년 8월 시행 예정이던 고위험 AI 시스템 규정의 적용 시점이 독립형 시스템은 2027년 12월, 제품 내장형 시스템은 2028년 8월로 각각 미뤄졌습니다. 기업들이 기술 표준 등 준수 준비를 갖출 시간을 벌어주기 위한 조치로, 원래 시한인 8월 2일 직전에 공식 관보 게재와 발효가 이뤄질 예정입니다.

고위험 AI 시스템은 채용, 신용평가, 의료기기 등 사람의 권리나 안전에 직접 영향을 미치는 분야에 쓰이는 AI를 가리키며, EU AI법에서 가장 엄격한 의무(위험관리, 데이터 품질, 인간 감독 등)가 적용되는 범주입니다. 이번 연기로 관련 기업들은 준비 기간을 1년 이상 추가로 확보하게 됐습니다.

### 4. 구글, Gemini 3.5 Pro 출시 7월 17일로 연기 — 아키텍처 전면 재설계
구글 딥마인드가 5월 I/O에서 예고했던 Gemini 3.5 Pro의 일반 출시를 7월 17일로 재연기했습니다. 기존 2.5 Pro 아키텍처를 폐기하고 처음부터 다시 설계했으며, 수학적 추론과 SVG 장면 생성, 이미지 품질 개선에 집중했다고 밝혔습니다.

최근 제미나이 공동리드 노암 셰이저가 OpenAI로, 알파폴드 개발자 존 점퍼가 Anthropic으로 각각 이직하는 등 핵심 인재 유출이 이번 지연의 배경으로 지목되고 있습니다.

### 5. 메타 '워터멜론' 모델, GPT-5.5급 성능 주장 — 저커버그는 "AI 가속 못했다" 인정
메타 AI 총괄 알렉산더 왕이 사내 타운홀에서 차세대 모델 '워터멜론'(현재 훈련 중)이 내부 벤치마크에서 GPT-5.5 수준 성능에 도달했다고 밝혔습니다. 이전 모델 대비 10배 많은 연산량을 투입했다고 하나, 구체적인 벤치마크명이나 독립적인 검증 결과는 아직 공개되지 않았습니다.

비슷한 시기 저커버그는 사내 타운홀에서 최근 4개월간 AI 에이전트 개발이 "기대만큼 가속화되지 못했다"고 인정했습니다. 메타는 약 8천 명(전체 인력의 약 10%) 감원과 함께 7천 명을 AI 조직으로 재배치하는 구조조정을 동시에 진행하고 있습니다.

## 오늘의 딥다이브: OpenAI의 '공공부(富)펀드' 구상

OpenAI가 미 행정부에 자사 지분 5%(3월 기준 8520억 달러 밸류에이션으로 환산하면 약 426억 달러 상당)를 국부펀드 형태로 출연하는 방안을 논의하고 있다고 FT를 비롯한 여러 매체가 보도했습니다. 이 구상은 알래스카 영구기금(주 정부가 석유 수익 일부를 기금으로 적립해 매년 주민들에게 배당하는 제도)을 모델로 삼고 있습니다.

배경에는 정치적 압박이 있습니다. OpenAI는 최근 미 행정부와의 관계에서 여러 차례 마찰을 겪어왔고, 이번 지분 출연 방안은 그런 압박을 완화하려는 시도로 해석됩니다. 다만 지분 5%라는 규모 자체가 상당해, 단순한 유화 제스처를 넘어 회사의 지배구조와 향후 자금 조달 방식에도 영향을 미칠 수 있는 사안입니다.

샘 올트먼 CEO는 여기서 한발 더 나아가, Anthropic·구글·메타 등 다른 주요 AI 기업들도 비슷한 규모의 지분을 함께 출연해 시민 전체가 AI 산업 성장의 이익을 나눠 갖는 '공공부펀드'를 만들자고 제안했습니다. AI가 만들어낼 경제적 가치가 소수 기업과 투자자에게만 집중되는 것을 막고, 그 이익을 사회 전체와 공유하자는 취지입니다.

그러나 이 구상이 실제로 시행되려면 의회 입법이 필요할 것으로 보입니다. 미국처럼 다수의 이해관계자와 복잡한 규제 체계를 가진 나라에서, 민간 기업의 지분을 국가 차원의 기금으로 편입시키는 일은 세제·증권법·기업지배구조 등 여러 영역에서 법적 정비가 선행돼야 합니다. 또한 다른 AI 기업들이 실제로 이 제안에 동참할지도 불확실합니다.

만약 이 구상이 현실화된다면, AI 기업과 정부의 관계를 재정의하는 선례가 될 수 있습니다. 반대로 입법 과정에서 좌초되거나 일부 기업만 참여하는 형태로 축소될 가능성도 있어, 앞으로 의회와 다른 AI 기업들의 반응을 지켜볼 필요가 있습니다.

## 소스
- [Yahoo Finance — Anthropic Secondary Market Valuation Hits $1.2 Trillion](https://finance.yahoo.com/markets/stocks/articles/anthropic-secondary-market-valuation-hits-114416290.html)
- [Quartz — Anthropic Secondary Market Valuation $1.2 Trillion](https://qz.com/anthropic-secondary-market-valuation-1-2-trillion-070926)
- [CNBC — OpenAI Proposes US Government Own 5% Stake to Address Political Blowback](https://www.cnbc.com/2026/07/02/openai-proposes-us-government-own-5percent-stake-to-address-political-blowback.html)
- [TechCrunch — OpenAI Proposed Donating 5% of Its Equity to a US Sovereign Wealth Fund](https://techcrunch.com/2026/07/02/openai-proposed-donating-5-of-its-equity-to-a-us-sovereign-wealth-fund/)
- [Council of the EU — Artificial Intelligence: Council Gives Final Green Light to Simplify and Streamline Rules](https://www.consilium.europa.eu/en/press/press-releases/2026/06/29/artificial-intelligence-council-gives-final-green-light-to-simplify-and-streamline-rules/)
- [Gibson Dunn — EU AI Act Omnibus Agreement: Postponed High-Risk Deadlines and Other Key Changes](https://www.gibsondunn.com/eu-ai-act-omnibus-agreement-postponed-high-risk-deadlines-and-other-key-changes/)
- [BiGGo — Gemini 3.5 Pro Targets July 17](https://finance.biggo.com/news/6f0c6bb2-795f-4c57-9d09-6db691d7638a)
- [Tech Times — Gemini 3.5 Pro Targets July 17, DeepSeek's July 24 Deadline Hits Developers Now](https://www.techtimes.com/articles/319877/20260708/gemini-35-pro-targets-july-17-deepseeks-july-24-deadline-hits-developers-now.htm)
- [Tech Times — Meta Watermelon AI Claims GPT-5.5 Parity, Benchmarks Remain Unnamed, Unverified](https://www.techtimes.com/articles/319723/20260704/meta-watermelon-ai-claims-gpt-55-parity-benchmarks-remain-unnamed-unverified.htm)
- [Yahoo Finance Singapore — Meta CEO Sends Warning on AI](https://sg.finance.yahoo.com/news/meta-ceo-sends-warning-ai-023300996.html)

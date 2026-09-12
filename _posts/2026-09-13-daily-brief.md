---
layout: post
title: "AI 데일리 브리핑 — 9월 13일: AI 에이전트 수백 개가 하루 만에 395개 조직 해킹"
date: 2026-09-13 07:00:00 +0900
categories: daily
---

오늘 가장 눈에 띄는 소식은 오픈AI 코덱스와 딥시크 모델을 결합한 AI 에이전트 수백 개가 프린터 관리 소프트웨어의 취약점을 자동으로 공략해 하루도 안 돼 48개국 395개 조직을 침해한 사건입니다. 여기에 앤스로픽에서 안전 연구를 이끌던 인력이 이틀 새 두 명 연쇄 사퇴하며 "속도 경쟁이 통제를 벗어날 것"이라 경고했고, 클로드 코워크 등 AI 코딩 에이전트의 샌드박스(격리 실행 환경)를 벗어나는 취약점도 재확인됐습니다. 한편 딥시크는 새 아키텍처를 적용한 경량 모델을, 오픈AI는 실시간 음성 API를 각각 공개하며 제품 경쟁도 이어졌습니다.

## 오늘의 헤드라인

### 1. 앤스로픽 AI 안전연구원 이틀 새 연쇄 사퇴 — "속도 경쟁이 통제 벗어날 것" 경고

앤스로픽에서 '스케일러블 오버사이트(모델이 인간보다 뛰어나져도 그 행동을 검증·통제할 수 있게 하는 연구 분야)' 부문을 이끌던 조 벤턴이 9월 11일 사임을 공개하고 AI 위험 평가기관 METR로 이직한다고 밝혔습니다. 앞서 9월 9일 사임한 제이콥 콕슨에 이어 이틀 새 두 번째 안전 담당 연구원의 이탈입니다.

벤턴은 프론티어 AI 기업들이 '재귀적 자기개선(AI가 스스로 더 나은 AI를 설계·개선하는 능력)'을 향해 경쟁하면서 정부와 사회가 감당하기 어려운 속도로 발전이 이뤄질 수 있다고 경고했습니다. 그는 기업들에 재귀적 자기개선 진척 상황 공개, 안전사고 투명 보고, 독립 검증기관을 통한 최소 안전기준 마련을 요구했습니다. 안전을 최우선 가치로 내세워온 앤스로픽 내부에서 나온 경고라는 점에서 무게가 실립니다.

### 2. AI 에이전트 수백 개 동원한 자동화 해킹, 하루도 안 돼 세계 395개 조직 침해

보안업체 그레이노이즈에 따르면 러시아어권으로 추정되는 공격자가 8월 31일부터 오픈AI 코덱스와 딥시크 모델을 결합한 AI 에이전트 수백 개를 동원해 프린터 관리 소프트웨어 페이퍼컷(PaperCut NG/MF)의 취약점(CVE-2026-81578, CVE-2026-82078)을 공략했습니다. 그 결과 48개국 395개 조직, 440개 인스턴스가 침해됐습니다.

공격 속도가 특히 눈길을 끕니다. 빈 작업환경에서 첫 원격코드실행(RCE, 공격자가 대상 시스템에서 임의의 코드를 실행할 수 있게 되는 것)까지 4시간, 도메인 관리자 권한 확보까지 추가 2시간이 걸렸고, 캠페인 가동 이후에는 26초 만에 11개 조직을 동시 침해하기도 했습니다. 공격자는 러시아·중국·이란 등은 표적에서 제외했습니다. AI 에이전트가 취약점 발견부터 침투, 권한 확보까지 전 과정을 자동화해 대규모 공격을 사람 개입 없이 빠르게 수행할 수 있음을 보여준 사례입니다.

### 3. AI 코딩 에이전트 '샌드박스 탈출' 재확인 — 클로드 코워크, 맥 인증정보까지 노출

스텔스 스타트업 어콤플리시가 클로드 코드·코덱스·커서·제미나이 CLI 등 주요 AI 코딩 에이전트에서 샌드박스를 우회해 임의 코드를 실행할 수 있는 취약점들을 공개했습니다. 특히 앤스로픽의 클로드 코워크는 로컬 가상머신을 벗어나 맥 시스템 전반의 SSH 키·클라우드 인증정보까지 읽어낼 수 있었습니다.

벤더별 대응 속도 차이도 드러났습니다. 커서·오픈AI는 약 1주 만에 수정한 반면 앤스로픽은 약 50일이 걸렸습니다. 9월 10일 공개된 GitSpawn 취약점에 이어 코딩 에이전트 인프라의 구조적 신뢰 문제가 재차 부각된 사례입니다.

### 4. 딥시크, 신규 아키텍처 탑재 'V4.1 플래시' 오픈웨이트 공개

딥시크가 9월 10일 552B(5,520억 파라미터) MoE(여러 전문가 서브 네트워크 중 일부만 선택적으로 활성화하는 구조) 모델 'DeepSeek-V4.1-Flash'를 MIT 라이선스로 허깅페이스에 공개했습니다. 40계층 트랜스포머를 20계층 인과적 인코더와 20계층 디코더로 나눈 'CED(Causal Encoder-Decoder)' 구조를 채택해, 프리필(입력 처리) 시 80억, 디코드(출력 생성) 시 160억 파라미터만 활성화합니다.

KV 캐시(모델이 이전 토큰들의 정보를 저장해두는 메모리) 용량은 토큰당 890바이트로 전작 대비 약 4분의 1 수준으로 줄었습니다. 최대 100만 토큰 컨텍스트와 이미지·텍스트 네이티브 멀티모달을 지원해, 연산 비용을 낮추면서도 긴 문맥을 처리하려는 경량화 경쟁의 연장선으로 볼 수 있습니다.

### 5. 오픈AI, 실시간 음성 AI 'GPT-Live-1' API 정식 출시 — 분당 5센트

오픈AI가 9월 10일 듣기와 말하기를 동시에 처리하는 풀듀플렉스(양방향 동시 통신) 음성모델 'GPT-Live-1'을 API로 공식 출시했습니다. 분당 5센트 요금에 전화 연동(텔레포니)을 지원해 예약·고객상담 등 음성 에이전트 구축에 쓸 수 있습니다.

오픈AI는 자연스러운 끼어들기·맞장구 등 대화 흐름 처리에서 전작 대비 풀듀플렉스벤치 점수가 30%포인트 개선됐다고 밝혔습니다. 음성 에이전트 시장에서 실용성을 높이려는 시도로 풀이됩니다.

## 오늘의 딥다이브: AI 에이전트가 수행한 자동화 해킹 캠페인

이번 페이퍼컷 취약점 공격이 주목받는 이유는 규모나 피해액이 아니라 '속도'와 '자동화 수준'입니다. 그레이노이즈 보고서에 따르면 공격자는 오픈AI 코덱스와 딥시크 모델을 결합한 AI 에이전트 수백 개를 동시에 가동해, 빈 작업환경에서 첫 원격코드실행까지 단 4시간, 도메인 관리자 권한 확보까지 추가 2시간을 소요했습니다. 사람이 수동으로 취약점을 분석하고 익스플로잇을 작성해 침투하는 전통적인 해킹 과정을 AI 에이전트가 병렬로, 그것도 사람보다 훨씬 빠르게 수행했다는 뜻입니다.

캠페인이 본궤도에 오른 이후에는 26초 만에 11개 조직을 동시에 침해하는 장면까지 관측됐습니다. 이는 개별 표적을 하나씩 공략하던 기존 침투 방식과 달리, 이미 검증된 공격 절차를 여러 에이전트가 병렬로 복제·실행하면서 나타난 결과로 보입니다. 8월 31일 시작된 공격이 하루도 안 돼 48개국 395개 조직, 440개 인스턴스로 확산된 배경이기도 합니다.

공격자가 러시아·중국·이란 등을 표적에서 제외했다는 점은 공격 주체의 지역적 성격을 추정하게 하는 단서입니다. 그레이노이즈는 이런 정황을 근거로 이번 공격자를 러시아어권으로 추정했습니다.

이번 사건은 AI 에이전트의 '이중 용도' 문제를 다시 부각시킵니다. 코딩 에이전트는 원래 개발 생산성을 높이기 위한 도구지만, 동일한 자동화 능력이 취약점 스캐닝, 익스플로잇 생성, 권한 상승 등 공격 체인 전체에 그대로 적용될 수 있습니다. 오픈AI 코덱스와 딥시크라는 서로 다른 두 모델을 조합해 사용했다는 점도 눈에 띄는데, 특정 벤더 하나의 안전장치를 우회하려는 시도가 아니라 여러 모델의 성능을 상황에 맞게 조합해 쓰는 실용적 접근으로 해석됩니다.

방어 측 관점에서 보면 대응 시간이 근본적으로 짧아졌다는 점이 가장 큰 과제입니다. 취약점 공개(CVE 등록)부터 실제 악용까지 걸리는 시간이 사람이 주도하는 공격보다 훨씬 짧아졌다면, 패치 적용이나 침해 탐지에 주어지는 시간도 그만큼 줄어듭니다. 페이퍼컷처럼 상대적으로 우선순위가 낮게 취급되기 쉬운 프린터 관리 소프트웨어가 표적이 됐다는 점도, 조직들이 패치 관리 대상을 재점검해야 할 필요성을 보여줍니다.

최근 함께 알려진 앤스로픽 안전 연구원들의 연쇄 사퇴와 클로드 코워크의 샌드박스 탈출 취약점까지 함께 놓고 보면, AI 에이전트의 능력이 실제 공격 현장에서 검증되는 속도가 이를 통제하기 위한 안전장치 마련 속도를 앞지르고 있다는 우려가 여러 방향에서 동시에 제기된 셈입니다.

## 소스
- [Storyboard18 — No adults in the room: Another Anthropic safety researcher quits](https://www.storyboard18.com/brand-makers/no-adults-in-the-room-another-anthropic-safety-researcher-quits-warns-of-ai-risks-110511.htm)
- [Business Standard — Another Anthropic researcher warns of AI race risks after quitting](https://www.business-standard.com/technology/tech-news/another-anthropic-researcher-warns-of-ai-race-risks-after-quitting-126091200407_1.html)
- [GreyNoise — AI-orchestrated campaign against PaperCut NG/MF](https://www.greynoise.io/blog/ai-orchestrated-campaign-against-papercut-ng-mf)
- [BleepingComputer — AI-powered attack exploited PaperCut flaws to hack 395 organizations](https://www.bleepingcomputer.com/news/security/ai-powered-attack-exploited-papercut-flaws-to-hack-395-organizations/)
- [TheNextWeb — Claude Cowork sandbox escape exposes Mac files, sharedroot](https://thenextweb.com/news/claude-cowork-sandbox-escape-mac-files-sharedroot)
- [Upstarts Media — Accomplish claims leaky sandboxes in Claude, Codex, Cursor](https://www.upstartsmedia.com/p/accomplish-claims-leaky-sandboxes-in-claude-codex-cursor)
- [DeepSeek — Introducing DeepSeek-V4.1-Flash](https://www.deepseek.com/en/news/deepseek-v4-1-flash/)
- [Hugging Face — deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)
- [OpenAI — Introducing GPT-Live](https://openai.com/index/introducing-gpt-live/)
- [Unite.AI — OpenAI's GPT-Live-1 arrives in the API at $0.05 per minute](https://www.unite.ai/openais-gpt-live-1-arrives-in-the-api-at-0-05-per-minute/)

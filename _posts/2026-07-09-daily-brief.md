---
layout: post
title: "AI 데일리 브리핑 — 7월 9일: 오픈AI, GPT-5.6 시리즈 정부 승인 거쳐 정식 출시"
date: 2026-07-09 07:00:00 +0900
categories: daily
---

오늘의 가장 큰 소식은 오픈AI가 트럼프 행정부의 추가 심사를 거쳐 GPT-5.6 시리즈 세 모델을 전 사용자에게 공개한 것입니다. 같은 날 스페이스XAI와 커서(Cursor)는 인수 합의 이후 첫 공동 결과물인 코딩·법률·금융 특화 모델 'Grok 4.5'를 선보였고, Anthropic은 신분증·안면 생체정보를 요구할 수 있는 개정 개인정보 정책을 시행에 들어갔습니다. 이 외에 메타의 이미지 생성 모델 공개, EU의 AI-사이버보안 액션플랜 발표 소식도 있었습니다. 오늘 딥다이브에서는 Anthropic의 새 개인정보 정책이 담고 있는 생체정보 수집과 법 집행기관 데이터 공유 조항을 자세히 살펴봅니다.

## 오늘의 헤드라인

### 1. 오픈AI GPT-5.6 시리즈(Sol·Terra·Luna) 정식 공개, 정부 승인 절차 완료
오픈AI가 7월 9일부터 플래그십 모델 'Sol', 중저가형 'Terra', 초저가·고속형 'Luna'로 구성된 GPT-5.6 시리즈를 모든 사용자에게 공개합니다. 이 세 모델은 애초 트럼프 행정부의 요청으로 출시가 지연돼 소수의 신뢰 파트너에게만 제한적으로 공개돼 있었으나, 미 상무부 산하 AI표준혁신센터(CAISI)의 추가 테스트를 거쳐 전면 출시 승인을 받았습니다.

이번 발표에서 눈여겨볼 점은 세 가지입니다. 첫째, 정부의 공개 승인 절차가 실제로 완료됐다는 것이고 둘째, 가격대가 다른 세 모델이 동시에 출시된다는 것이며 셋째, 일반 사용자를 대상으로 한 구체적 출시일이 확정됐다는 것입니다. 이는 프런티어(최첨단) AI 모델에 대한 미 정부의 사전 승인 절차가 실제로 작동한 사례로 기록될 전망입니다.

### 2. 스페이스XAI-커서, 첫 합작 모델 'Grok 4.5' 출시
스페이스XAI와 커서가 공동 개발한 첫 모델 'Grok 4.5'를 발표했습니다. 이는 스페이스X가 커서를 600억 달러에 인수하기로 합의한 지 몇 주 만에 나온 첫 결과물입니다. 소프트웨어 엔지니어링, 법률, 금융 분석, AI 에이전트(사람 대신 작업을 수행하는 AI 프로그램) 작업에 특화된 MoE(전문가 혼합, 여러 전문 분야별 신경망 중 필요한 부분만 선택적으로 작동시켜 효율을 높이는 방식) 모델로, 커서의 방대한 코드베이스와 사용자 상호작용 데이터를 학습에 활용했습니다.

가격 정책도 눈에 띕니다. 입력 100만 토큰당 2달러, 출력 100만 토큰당 6달러로 책정돼 GPT-5.5나 Fable 5보다 훨씬 저렴합니다. 코딩 에이전트 시장에서 가격 경쟁이 본격화되는 신호로 해석할 수 있습니다.

### 3. Anthropic, 신분증·안면 생체정보 요구 가능한 개인정보 정책 시행
7월 8일부터 시행된 Anthropic의 개정 개인정보 정책에 따라, 규정 위반이 의심되는 무료·Pro·Max 이용자에게 정부 발급 신분증, 실시간 셀피, 안면 기하학 스캔을 요구할 수 있게 됐습니다. 엔터프라이즈·팀·API 계정은 이 정책에서 제외됩니다. 자세한 내용은 아래 딥다이브에서 다룹니다.

### 4. EU 집행위, 'AI-사이버보안 액션플랜' 발표
EU 집행위원회가 7월 7일 AI와 사이버보안을 아우르는 액션플랜을 공개했습니다. AI 역량에 대한 제3자 평가 체계 구축, 사이버보안 목적의 고급 AI '구조화된 접근' 청사진 마련(EU 사이버보안청과 공동), 에너지·교통·보건·금융 등 핵심분야를 위한 ENISA 안전 테스트 플랫폼 구축, AI 사이버보안 '그랜드 챌린지' 출범 등이 담겼습니다.

이 액션플랜은 AI Act(EU의 AI 규제법)의 고위험 AI 시스템 의무조항 대부분이 8월부터 발효되는 시점과 맞물려 나온 후속 조치입니다.

### 5. 메타, 이미지 생성 모델 'Muse Image' 공개
메타 슈퍼인텔리전스랩스가 첫 이미지 생성 모델 'Muse Image'를 출시했습니다. 복잡한 프롬프트를 이해하는 추론 기반 생성과 여러 사진을 자연스럽게 합성하는 기능이 특징이며, 메타 AI 앱에서 무료로 쓸 수 있고 인스타그램 스토리 신규 효과 30여 종과 왓츠앱 대화 내 이미지 생성 기능에도 탑재됩니다. 저커버그가 최근 사내 타운홀에서 "AI 가속이 기대만큼 이뤄지지 않았다"고 인정한 지 며칠 만에 나온 제품 발표입니다.

## 오늘의 딥다이브: Anthropic의 신분증·생체정보 요구 정책

7월 8일부터 시행에 들어간 Anthropic의 개정 개인정보 정책은 챗봇 서비스 업계에서 보기 드문 조치를 담고 있습니다. 일부 규정 위반이 의심되는 무료, Pro, Max 이용자에게 정부 발급 신분증, 실시간 셀피, 안면 기하학 스캔을 요구할 수 있도록 한 것입니다. 다만 엔터프라이즈, 팀, API 계정은 이 요구에서 제외됩니다.

이 정책에서 더 논쟁적인 대목은 법 집행기관에 대한 데이터 제공 조항입니다. Anthropic은 법원 명령 없이도 회사의 '선의의 판단'만으로 이용자의 대화 데이터를 법 집행기관과 공유할 수 있도록 정책을 바꿨습니다. 즉, 사법부의 영장이나 소환장 없이도 회사 자체 판단에 따라 대화 기록이 외부로 넘어갈 수 있는 구조입니다.

오픈AI, 구글, 메타 등 주요 경쟁사는 아직 소비자용 신분증·생체인증을 표준 시행 수단으로 요구하지 않고 있습니다. 이 때문에 Anthropic은 이번 조치로 업계 최초 사례가 됐습니다. 신분증·생체정보 요구는 미성년자 이용을 막거나 규정 위반 계정을 걸러내려는 목적으로 해석될 수 있지만, 안면 기하학 스캔 같은 생체정보를 수집하는 방식 자체가 이용자 프라이버시에 미치는 영향은 작지 않습니다.

특히 눈에 띄는 점은 이 정책이 다른 AI 서비스의 이용 제한(Fable의 접근 금지 등)을 우회하는 수단으로 활용될 여지가 있다는 지적입니다. 신분증 인증을 거친 미국 소비자에게는 다른 플랫폼에서 막힌 접근 경로가 열릴 수 있다는 것인데, 이는 정책의 원래 취지와는 다른 방향으로 해석될 수 있는 지점입니다.

법 집행기관과의 데이터 공유가 법원 명령 없이 이뤄질 수 있다는 조항은 이용자 입장에서 가장 우려스러운 부분입니다. 회사의 자체 판단에 따라 대화 내용이 외부로 넘어갈 수 있다는 것은, AI 챗봇과의 대화가 기존에 상정했던 것보다 훨씬 낮은 수준의 보호만 받을 수 있다는 뜻이기도 합니다. 앞으로 다른 AI 기업들이 이와 유사한 정책을 도입할지, 아니면 Anthropic의 사례가 규제 당국이나 이용자 반발을 촉발하는 계기가 될지는 지켜볼 대목입니다.

## 소스
- [Bloomberg — SpaceXAI, Cursor Unveil Grok AI Model for Legal, Finance Tasks](https://www.bloomberg.com/news/articles/2026-07-08/spacexai-cursor-unveil-grok-ai-model-for-legal-finance-tasks)
- [Cursor Blog — Grok 4.5](https://cursor.com/blog/grok-4-5)
- [OpenAI — Previewing GPT-5.6 Sol](https://openai.com/index/previewing-gpt-5-6-sol/)
- [Engadget — OpenAI Rolls Out GPT-5.6 July 9](https://www.engadget.com/2210308/openai-rolls-out-gpt5-6-july-9/)
- [CIO — Anthropic's New Privacy Policy Offers US Consumers a Way Around Fable Ban](https://www.cio.com/article/4185510/anthropics-new-privacy-policy-offers-us-consumers-a-way-around-fable-ban.html)
- [Anthropic — Updates to Our Privacy Policy](https://privacy.claude.com/en/articles/10301952-updates-to-our-privacy-policy)
- [Meta — Introducing Muse Image](https://about.fb.com/news/2026/07/introducing-muse-image-meta-ai/)
- [European Commission — EU Action Plan on Cybersecurity and Artificial Intelligence](https://digital-strategy.ec.europa.eu/en/news/commission-presents-eu-action-plan-cybersecurity-and-artificial-intelligence)

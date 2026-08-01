---
layout: post
title: "AI 데일리 브리핑 — 8월 2일: 오픈AI·앤스로픽, 정부에 'AI 속도조절' 공식 요청"
date: 2026-08-02 07:00:00 +0900
categories: daily
---

오픈AI와 앤스로픽이 자율적으로 코드를 개선하는 AI의 위험을 경고하며 정부 차원의 개발 속도조절 공조를 공식 요청했습니다. 트럼프 행정부의 '프론티어 AI 프레임워크' 마감 이틀 전에 나온 조치라 업계 전반의 셈법을 보여주는 신호로 읽힙니다. 같은 날 오픈AI는 차세대 모델군 '아스트라'를 워싱턴에서 비공개로 시연하며 10년 넘게 풀리지 않던 수학·이론컴퓨터과학 난제를 풀었다고 주장했고, 독일 법원은 AI 음악 생성 서비스 수노에 유럽 최초의 저작권 침해 패소 판결을 내렸습니다. 국내에서는 화웨이의 대형 오픈소스 모델 공개와 SK하이닉스의 주주환원책 예고가 눈에 띕니다.

## 오늘의 헤드라인

### 1. 오픈AI·앤스로픽, "AI 속도조절" 청원 공식 지지로 전환

오픈AI와 앤스로픽이 7월 28일 공개된 "Pacing the Frontier" 서한(직원 1,171명 서명)에 이어, 회사 차원의 공식 지지 선언으로 입장을 전환했습니다. 두 회사는 자율적으로 자신의 코드를 개선하는(재귀적 자기개선) AI가 인간의 이해와 통제 범위를 벗어날 위험이 있다고 경고하며, 미국 정부에 프론티어 AI 개발 속도를 의도적으로 늦출 수 있는 국제 공조 도구를 마련해달라고 요청했습니다.

이 발표는 트럼프 행정부의 행정명령(EO) 14409에 따른 '프론티어 AI 프레임워크' 마감일인 8월 1일 이틀 전에 나왔습니다. 이 프레임워크는 재무부·국방부·국토안보부가 비공개로 모델을 벤치마킹하고 신모델 출시 전 30일간 사전 접근할 수 있도록 하는 절차를 설계하는 것으로, 두 회사가 정부와 함께 심사 기준을 만드는 위치를 굳히는 동시에 경쟁사를 견제하려는 의도라는 지적도 나옵니다.

### 2. 오픈AI, 차세대 모델군 '아스트라' 워싱턴서 비공개 프리뷰

오픈AI가 8월 1일 워싱턴DC에서 정책 관계자들을 대상으로 차세대 모델 패밀리 '아스트라(Astra)'를 시연했습니다. 아스트라는 여러 에이전트가 협업해 며칠씩 걸리는 연구·코딩·과학 문제를 자율적으로 계획·수정·위임하며 처리하도록 설계됐으며, 오픈AI는 내부 버전이 최소 10년 이상 정체됐던 수학·이론컴퓨터과학 미해결 문제 10개를 풀었다고 주장했습니다.

GPT-6이나 GPT-5.7 중 어느 이름으로 정식 출시될지는 아직 정해지지 않았습니다. 아스트라는 앞선 헤드라인에서 언급한 정부의 프론티어 AI 사전심사 절차를 처음 적용받는 모델이 될 전망이라, 규제와 신모델 출시가 맞물리는 첫 사례로 주목받고 있습니다.

### 3. 독일 법원, AI 음악생성 '수노' 저작권 침해 패소 — 유럽 최초 판례

독일 뮌헨지방법원이 음악저작권관리단체 GEMA가 제기한 소송에서 AI 음악 생성 서비스 수노(Suno)가 저작물을 무단 학습·재생산했다며 저작권 침해를 인정했습니다. EU의 텍스트·데이터마이닝 예외조항(저작물을 데이터 학습에 활용할 수 있도록 허용하는 조항)이 모델 파라미터에 저작물을 재생산 가능한 형태로 저장하는 AI 기업까지 보호하지는 않는다는 점을 유럽 법원 최초로 확정한 판례입니다.

이번 판결에 따라 즉시 집행 가능한 금지명령, 매출 공개, 손해배상 절차가 뒤따를 예정입니다. AI 음악 생성 기업의 유럽 내 라이선싱 의무를 둘러싼 선례로 주목되며, 다른 유럽 국가의 유사 소송에도 영향을 줄 가능성이 있습니다.

### 4. 화웨이, 5050억 파라미터 모델 가중치·추론코드까지 전면 오픈소스 공개

화웨이가 자사 어센드(Ascend) NPU로 학습한 MoE(여러 전문가 네트워크 중 필요한 부분만 선택적으로 사용하는 구조) 대형언어모델 'openPangu-2.0-Pro'를 공개했습니다. 총 5050억 파라미터, 토큰당 활성 파라미터 약 180억, 512K 컨텍스트, 학습데이터 34조 토큰 규모이며, 가중치와 기본 추론 코드, 기술보고서를 동시에 공개했습니다.

화웨이는 어센드 컴퓨팅 환경에서 다른 주요 오픈소스 모델 대비 카드당 처리량이 두 배라고 주장하며, 자사 운영체제 하모니OS의 에이전트 작업 최적화를 강조했습니다. 미국의 대중 반도체 수출규제가 이어지는 가운데 중국이 독자적인 AI 생태계 구축에 속도를 내는 행보로 해석됩니다.

### 5. SK하이닉스, 8월 초 대규모 주주환원책 발표 예고

SK하이닉스가 2분기 실적 콘퍼런스콜에서 "연내 다양한 방식의 추가 주주환원 방안을 검토 중"이라고 밝혔습니다. 미국 ADR(주식예탁증서) 공모와 관련한 법적 제약이 풀리는 8월 초에 자사주 매입이나 특별배당 등 구체안이 나올 것으로 전망됩니다.

이는 최근 고점 대비 최대 55% 넘게 급락한 주가를 달래기 위한 조치로 풀이됩니다. 삼성전자도 특별배당과 자사주 매입·소각 가능성을 시사한 상태로, 반도체 '피크아웃'(수요가 정점을 찍고 꺾인다는 우려) 우려 속에서 국내 양대 메모리 기업의 주주가치 제고 경쟁이 본격화되는 흐름입니다.

## 오늘의 딥다이브: 오픈AI·앤스로픽의 'AI 속도조절' 공식 요청이 의미하는 것

오픈AI와 앤스로픽이 7월 말 회사 차원에서 공식 지지를 선언한 "Pacing the Frontier" 청원의 핵심 주장은 명확합니다. 자율적으로 자신의 코드를 개선할 수 있는 AI, 즉 재귀적 자기개선이 가능한 시스템이 인간의 이해와 통제 범위를 벗어날 위험이 있다는 것입니다. 두 회사는 이 위험에 대응하기 위해 미국 정부가 국제적인 공조 체계를 마련해 프론티어 AI(가장 앞선 성능의 대형 AI 모델) 개발 속도를 의도적으로 늦출 수 있는 도구를 갖춰야 한다고 요청했습니다.

이 청원의 배경에는 이미 직원 1,171명이 서명한 공개서한이 있습니다. 최고 수준의 AI를 만드는 기업 내부에서조차 자사가 개발하는 기술의 통제 가능성에 대한 우려가 커지고 있다는 점을 보여주는 대목입니다. 회사가 이를 개인 차원의 목소리로 남겨두지 않고 공식 입장으로 격상시켰다는 사실은, 안전성 문제를 더 이상 부차적 이슈로 다루지 않겠다는 신호로 읽힙니다.

시점도 눈여겨볼 대목입니다. 이 발표는 트럼프 행정부의 행정명령 14409에 따른 '프론티어 AI 프레임워크'의 마감일인 8월 1일 이틀 전에 나왔습니다. 이 프레임워크는 재무부·국방부·국토안보부가 비공개로 프론티어 모델을 벤치마킹하고, 신모델 출시 전 30일간 사전 접근할 수 있도록 하는 절차를 설계하는 것을 골자로 합니다. 오픈AI와 앤스로픽의 청원 지지 선언은 이 심사 체계가 확정되기 직전에 나왔다는 점에서, 두 회사가 향후 정부와 함께 심사 기준을 설계하는 위치를 선점하려는 움직임으로도 해석됩니다.

실제로 업계 안팎에서는 이런 해석이 나옵니다. 이미 최상위권 모델을 보유한 두 회사가 속도조절을 요청하는 것은, 아직 그 수준에 이르지 못한 경쟁사들의 추격을 늦추는 효과를 낼 수 있다는 지적입니다. 안전을 명분으로 한 규제가 결과적으로 시장 지배력을 가진 기업에 유리하게 작용할 수 있다는 이른바 '규제 포획' 우려가 뒤따르는 이유입니다. 이는 두 회사의 우려가 진정성이 없다는 뜻은 아니지만, 규제 설계 과정에서 이러한 이해관계의 충돌을 어떻게 다룰 것인지가 향후 관건이 될 전망입니다.

공교롭게도 같은 날 오픈AI는 차세대 모델군 '아스트라'를 워싱턴에서 정책 관계자들에게 시연하며, 이 모델이 바로 정부의 사전심사 절차를 처음 적용받는 사례가 될 것이라고 밝혔습니다. 속도조절을 요청하는 회사가 동시에 가장 앞선 모델을 내놓고 있다는 점은 이 논쟁의 복잡성을 잘 보여줍니다. 개발은 계속하되 그 통제 체계를 함께 만들어가겠다는 것이 두 회사의 공식 입장이지만, 실제로 이 프레임워크가 개발 속도에 실질적인 제동을 걸지, 아니면 형식적인 절차에 그칠지는 8월 1일 마감 이후 나올 세부 운영 방식을 지켜봐야 알 수 있을 것입니다.

## 소스
- [Washington Post: OpenAI, Anthropic endorse call for government to pace AI progress](https://www.washingtonpost.com/technology/2026/07/29/openai-anthropic-endorse-call-government-pace-ai-progress/)
- [Tech Times: OpenAI, Anthropic Formally Back Plan To Slow AI That Writes Its Own Code](https://www.techtimes.com/articles/322125/20260729/openai-anthropic-formally-back-plan-slow-ai-that-writes-its-own-code.htm)
- [Vorp Labs: Frontier Model Review Framework](https://vorplabs.com/ai-regulatory-updates/frontier-model-review-framework)
- [The Decoder: OpenAI announces its next major model Astra by dropping ten previously unsolved math solutions](https://the-decoder.com/openai-announces-its-next-major-model-astra-by-dropping-ten-previously-unsolved-math-solutions/)
- [Crypto Briefing: OpenAI Astra AI Model DC Preview](https://cryptobriefing.com/openai-astra-ai-model-dc-preview/)
- [Tech Times: Suno Loses Europe's First AI Music Copyright Ruling](https://www.techtimes.com/articles/322466/20260731/suno-loses-europes-first-ai-music-copyright-ruling-training-without-licensing-infringement.htm)
- [Musically: German collecting society GEMA wins its copyright infringement lawsuit against Suno](https://musically.com/2026/07/31/german-collecting-society-gema-wins-its-copyright-infringement-lawsuit-against-suno/)
- [JUVE Patent: Munich Regional Court stops Suno using GEMA-protected music](https://www.juve-patent.com/cases/munich-regional-court-stops-suno-using-gema-protected-music/)
- [AIbase: 华为openPangu-2.0-Pro 全面开源](https://news.aibase.com/news/30030)
- [KuCoin News: Huawei releases openPangu-2.0 with 50.5B parameters and 512K context](https://www.kucoin.com/news/flash/huawei-releases-openpangu-2-0-with-50-5b-parameters-and-512k-context)
- [PANews: 华为开源openPangu-2.0-Pro](https://www.panewslab.com/en/articles/019ebb7d-77a4-75e9-a5bc-e11af8f55293)
- [뉴시스: SK하이닉스 주주환원책 검토](https://www.newsis.com/view/NISX20260729_0003728198)
- [파이낸셜뉴스: SK하이닉스 주주환원](https://www.fnnews.com/news/202607311633235766)
- [다음뉴스: SK하이닉스 주주환원 방안](https://v.daum.net/v/20260731065949142)

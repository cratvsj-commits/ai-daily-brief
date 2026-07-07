---
layout: post
title: "AI 데일리 브리핑 — 7월 8일: 일리노이, 미 최초 AI 안전 규제법 서명"
date: 2026-07-08 07:00:00 +0900
categories: daily
---

일리노이주가 미국에서 처음으로 대형 AI 개발사에 재해적 위험 평가와 사고 신고 의무를 부과하는 법에 서명하면서, 주(州) 단위 AI 규제가 사실상 표준으로 자리 잡는 흐름이 한층 뚜렷해졌습니다. 한편 연방 차원에서는 FTC가 AI 출력물의 정확도 왜곡을 문제 삼는 정책 성명 초안을 내놓으며 콜로라도주법과의 충돌 가능성을 예고했고, 오픈AI는 세레브라스의 웨이퍼 스케일 칩으로 차세대 모델을 초당 750토큰이라는 이례적인 속도로 서빙한다고 발표했습니다. 중국 즈푸 AI의 GLM-5.2가 코딩 벤치마크에서 GPT-5.5를 앞서는 등 오픈웨이트 모델의 경쟁력도 계속 부각되는 하루였습니다.

## 오늘의 헤드라인

### 1. 일리노이주, 미 최초 'AI 안전 조치법' 서명 — 대형 개발사 연 감사·72시간 사고보고 의무화

JB 프리츠커 일리노이 주지사가 7월 6일 'Artificial Intelligence Safety Measures Act'에 서명했습니다. 연 매출 5억 달러 이상인 '대형 프런티어 개발사'를 대상으로, 재해적 위험(50명 이상의 사상자 또는 100만 달러 이상의 재산피해로 이어질 수 있는 위험)을 평가하는 프레임워크를 공개하도록 하고, 연례 독립 제3자 감사와 사고 발생 시 72시간(임박한 위험의 경우 24시간) 이내 신고 의무를 부과하는 내용입니다. 시행 시점은 2028년 1월 1일입니다.

주목할 점은 오픈AI와 앤트로픽 모두 입법 과정에서 이 법안을 지지했다는 사실입니다. 이는 캘리포니아·뉴욕에 이어 일리노이까지 가세하면서 주 단위 AI 안전 규제가 하나의 흐름으로 굳어지고 있으며, 연방 차원의 입법 공백을 개별 주들이 메워가고 있다는 신호로 읽힙니다.

### 2. 오픈AI GPT-5.6 Sol, 세레브라스 웨이퍼 스케일 칩으로 초당 750토큰 서빙

오픈AI가 정부 승인 파트너 약 20곳에만 제한 공개 중인 차세대 모델 GPT-5.6 Sol을, 세레브라스(Cerebras)의 웨이퍼 스케일 엔진(하나의 대형 실리콘 웨이퍼 전체를 하나의 칩처럼 쓰는 방식) WSE-3에서 초당 최대 750토큰으로 서빙한다고 발표했습니다. 이는 엔비디아 H100 클러스터의 일반적인 서빙 속도(초당 약 70토큰)의 약 10배에 해당하며, 프런티어 모델의 상용 서빙 속도로는 기록적인 수치입니다.

일반 공개(GA) 시점은 아직 정해지지 않았지만, 시장에서는 7월 9일에서 17일 사이가 될 것으로 보고 있습니다. 이번 발표는 모델의 지능 수준 경쟁 못지않게 응답 속도 자체가 에이전트형 워크플로우(AI가 여러 단계를 스스로 처리하는 작업 방식) 채택의 핵심 변수로 떠오르고 있음을 보여줍니다.

### 3. 美 FTC, "AI 출력 정확도 은폐"에 대한 정책 성명 초안 공개 — 주법과의 충돌 예고

미국 연방거래위원회(FTC)가 7월 1일, AI 시스템이 미공개 '이념적 목적'으로 결과물을 왜곡할 경우 FTC법 5조(불공정·기만적 행위 금지)를 위반한 것으로 볼 수 있다는 정책 성명 초안을 2대0으로 의결했습니다. 이 초안은 7월 7일 연방관보에 게재됐고 7월 31일까지 공개 의견을 받습니다.

성명은 콜로라도주의 AI법을 연방 규제와 충돌해 우선 배제(연방법이 주법보다 우선 적용되는 것) 대상이 될 수 있는 사례로 명시했습니다. 일리노이 사례처럼 주 단위 규제가 확산되는 가운데, 연방 기관이 규제 권한을 둘러싼 다툼에 나선 모습이어서 향후 미국 AI 규제 지형을 좌우할 변수가 될 수 있습니다.

### 4. 중국 즈푸 AI 'GLM-5.2', 코딩 벤치마크서 GPT-5.5 앞질러 — 비용은 6분의 1

베이징의 즈푸(Zhipu, 서비스명 Z.ai)가 오픈웨이트(누구나 가중치를 내려받아 쓸 수 있는) MIT 라이선스 모델 GLM-5.2를 공개했습니다. 소프트웨어 엔지니어링 벤치마크인 SWE-bench Pro에서 62.1점을 기록해 GPT-5.5(58.6점)를 앞섰고, 장기 과제 완수 능력을 측정하는 FrontierSWE 벤치마크에서는 Claude Opus 4.8과 1%포인트 차이까지 근접했습니다. 독립 평가기관 Artificial Analysis는 이 모델을 전 세계 오픈웨이트 모델 1위, 종합 순위로는 4위(Claude Fable 5, Opus 4.8, GPT-5.5 다음)로 평가했습니다.

컨텍스트 창(모델이 한 번에 처리할 수 있는 텍스트 분량)도 기존 20만 토큰에서 100만 토큰으로 확장됐습니다. VentureBeat에 따르면 동일 벤치마크 기준 API 비용은 GPT-5.5의 6분의 1 수준이며, 구독료는 앤트로픽 Claude Code/Max의 10분의 1 수준입니다. 중국 오픈모델이 비용과 성능 양면에서 프런티어 모델에 근접했다는 구체적 근거가 하나 더 추가된 셈입니다.

### 5. 마이크로소프트, 25억 달러 투입 'Frontier Company' 출범 — 엔지니어 6천 명 기업 내 상주

마이크로소프트가 7월 2일 신규 사업조직 'Microsoft Frontier Company'를 출범한다고 발표했습니다. 25억 달러를 투자해 산업·엔지니어링 전문가 6천 명을 고객사에 직접 상주시켜 AI 도입과 운영을 지원하는 구조이며, 아시아 총괄 출신 호드리구 케지 리마가 이끕니다. 고객 데이터와 지식재산(IP)을 모델 학습에 사용하지 않겠다는 원칙도 명시했습니다.

이는 이틀 전 아마존웹서비스(AWS)가 10억 달러 규모의 유사한 내부 조직을 공개한 데 이어 나온 발표로, 빅테크들이 모델 개발 경쟁과 별도로 'AI 도입 대행' 서비스를 새로운 경쟁 축으로 삼고 있음을 보여줍니다.

## 오늘의 딥다이브: 일리노이주 AI 안전 조치법이 여는 규제 지형

일리노이주가 7월 6일 서명한 'Artificial Intelligence Safety Measures Act'는 여러 면에서 상징적인 법입니다. 우선 미국에서 처음으로 대형 프런티어 AI 개발사에 재해적 위험 평가, 연례 독립 제3자 감사, 사고 발생 시 신고를 법적으로 의무화한 주법이라는 점입니다. 적용 대상은 연 매출 5억 달러 이상의 개발사로 한정돼 있어, 사실상 오픈AI·앤트로픽·구글 등 소수의 초대형 기업을 겨냥한 법입니다.

법의 핵심은 '재해적 위험'이라는 개념을 구체적인 숫자로 정의했다는 데 있습니다. 50명 이상의 사상자 또는 100만 달러 이상의 재산피해로 이어질 수 있는 위험을 대상으로 삼았고, 이런 위험에 대한 평가 프레임워크를 공개하도록 요구합니다. 또한 사고가 발생하면 72시간 이내에, 위험이 임박한 경우에는 24시간 이내에 신고하도록 못박았습니다. 시행은 2028년 1월 1일부터로, 기업들에 준비 기간을 준 셈입니다.

눈에 띄는 대목은 이 법안이 업계의 반대가 아니라 지지 속에 통과됐다는 점입니다. 오픈AI와 앤트로픽 모두 입법 과정에서 법안을 지지했습니다. 이는 두 회사가 이미 자체적으로 유사한 위험 평가 체계를 운영하고 있어 추가 부담이 크지 않거나, 오히려 규제가 명확해지는 편이 사업 예측 가능성을 높인다고 판단했을 가능성을 시사합니다. 동시에 규모가 작은 경쟁사들에는 상대적으로 높은 진입장벽으로 작용할 수 있다는 해석도 가능합니다.

이번 서명은 고립된 사건이 아닙니다. 캘리포니아와 뉴욕이 이미 유사한 AI 안전 규제를 도입했고, 이제 일리노이가 세 번째 주로 합류하면서 '주 단위 AI 안전 규제'가 하나의 표준적인 흐름으로 굳어지고 있습니다. 미 연방 차원에서 포괄적인 AI 규제 입법이 정체된 상태에서, 개별 주들이 각자의 법으로 그 공백을 메워가고 있는 셈입니다.

다만 이 흐름은 같은 날 부각된 FTC의 움직임과 맞물려 새로운 긴장을 낳고 있습니다. FTC는 콜로라도주의 AI법을 연방 규제와 충돌해 우선 배제될 수 있는 사례로 명시한 정책 성명 초안을 냈습니다. 즉 한쪽에서는 주들이 각자 규제를 강화하고 있고, 다른 한쪽에서는 연방 기관이 그 규제 권한 자체에 의문을 제기하는 모습입니다. 앞으로 몇 년간 미국의 AI 규제는 이런 주-연방 간 권한 다툼 속에서 그 윤곽이 정해질 가능성이 높습니다. 일리노이법의 시행일인 2028년까지, 이 다툼이 어떤 식으로 정리되는지가 프런티어 AI 개발사들의 컴플라이언스 부담을 좌우할 핵심 변수가 될 것으로 보입니다.

## 소스
- [Capitol News Illinois: Pritzker signs landmark AI regulation bill that aims to mitigate risks](https://capitolnewsillinois.com/news/pritzker-signs-landmark-ai-regulation-bill-that-aims-to-mitigate-risks/)
- [Washington Post: Landmark AI regulations, Illinois state-driven national standard](https://www.washingtonpost.com/business/2026/07/07/landmark-ai-regulations-illinois-statedriven-national-standard/b046234a-7a29-11f1-b194-f872dd4ec5aa_story.html)
- [FTC: FTC seeks public comment on policy statement addressing AI accuracy](https://www.ftc.gov/news-events/news/press-releases/2026/07/ftc-seeks-public-comment-policy-statement-addressing-ai-accuracy)
- [Federal Register: Policy statement concerning the suppression of accuracy in artificial intelligence systems](https://www.federalregister.gov/documents/2026/07/07/2026-13628/policy-statement-concerning-the-suppression-of-accuracy-in-artificial-intelligence-systems)
- [ValueAddVC: Cerebras OpenAI GPT-5.6 Sol 750 tokens 2026](https://valueaddvc.com/pulse/cerebras-openai-gpt-5-6-sol-750-tokens-2026)
- [VentureBeat: OpenAI unveils GPT-5.6 Sol, Terra and Luna models](https://venturebeat.com/technology/openai-unveils-gpt-5-6-sol-terra-and-luna-models-but-only-accessible-to-limited-preview-partners-for-now-per-us-gov)
- [VentureBeat: Z.ai's open-weights GLM-5.2 beats GPT-5.5 on long-horizon coding benchmarks for 1/6th the cost](https://venturebeat.com/technology/z-ais-open-weights-glm-5-2-beats-gpt-5-5-on-multiple-long-horizon-coding-benchmarks-for-1-6th-the-cost)
- [Technology.org: GLM-5.2 coding — how good is it really? 2026 benchmarks](https://www.technology.org/2026/07/02/glm-5-2-coding-how-good-is-it-really-2026-benchmarks/)
- [TechCrunch: Microsoft launches its own AI deployment company with $2.5 billion commitment](https://techcrunch.com/2026/07/02/microsoft-launches-its-own-ai-deployment-company-with-2-5-billion-commitment/)
- [Microsoft Blog: Microsoft Frontier Company — AI engineering that amplifies and protects your intelligence](https://blogs.microsoft.com/blog/2026/07/02/microsoft-frontier-company-ai-engineering-that-amplifies-and-protects-your-intelligence/)

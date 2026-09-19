---
layout: post
title: "AI 데일리 브리핑 — 9월 20일: AI 코딩 에이전트 4종 뒤흔든 제로클릭 결함 'Plugin4Shell'"
date: 2026-09-20 07:00:00 +0900
categories: daily
---

클로드 코드, 오픈AI 코덱스, 깃허브 코파일럿, 구글 제미나이 CLI 등 주요 AI 코딩 에이전트 4종에서 클릭 없이 원격코드실행이 가능한 공급망 취약점 'Plugin4Shell'이 공개됐습니다. 그 외에도 알리바바가 100만 토큰 컨텍스트의 옴니모달 에이전트 모델을 내놓았고, 구글 딥마인드는 코딩 에이전트의 자기개선 실험 결과를 논문으로 공개했습니다. 오픈AI는 챗GPT 안에 브랜드 에이전트가 직접 대화하는 광고 포맷을 시범 도입했고, 앤스로픽은 생명과학 연구자를 위해 안전장치를 일부 완화한 검증 프로그램을 시작했습니다. 여기에 젠슨 황 엔비디아 CEO가 내년 칩 판매량이 두 배로 늘 것이라는 전망을 내놓으며 반도체 수요 논쟁에 다시 불을 지폈습니다.

## 오늘의 헤드라인

### 1. AI 코딩 에이전트 4종에서 클릭 없이 뚫리는 'Plugin4Shell' 결함 공개
클로드 코드(2.1.179 이전 버전), 오픈AI 코덱스(0.146.0 이전 버전), 깃허브 코파일럿, 구글 제미나이 CLI 등 4대 AI 코딩 에이전트에서 사용자의 클릭 없이도 원격코드실행(RCE, 공격자가 대상 컴퓨터에서 임의의 코드를 실행할 수 있게 되는 취약점)이 가능한 'Plugin4Shell' 결함이 발견됐습니다. 이 도구들은 플러그인을 설치할 때 특정 커밋(코드 변경 기록의 한 지점)에 버전을 고정하는 SHA 핀닝 검증을 사용하는데, 실제로는 이 검증이 제대로 작동하지 않아 저장소를 장악한 공격자가 플러그인 코드를 악성 코드로 바꿔치기해도 정상적으로 핀닝된 것처럼 보이는 구조적 결함이었습니다.

앤스로픽과 오픈AI는 각각 클로드 코드 2.1.179와 코덱스 0.146.0에서 이 문제를 패치했지만, 구글은 제미나이 CLI 자체를 패치하는 대신 서비스를 단종시키고 후속 도구인 안티그래비티로 전환하도록 유도했습니다. 깃허브 코파일럿은 보도 시점까지 아직 패치되지 않은 상태입니다. 여러 매체는 이번 결함을 AI 코딩 에이전트 생태계에서 확인된 최초의 본격적인 공급망 취약점으로 평가하고 있습니다.

### 2. 알리바바, 100만 토큰 컨텍스트의 옴니모달 에이전트 모델 공개
알리바바가 9월 18일 텍스트·이미지·오디오·비디오를 하나의 100만 토큰 컨텍스트(모델이 한 번에 참고할 수 있는 입력 정보의 양)로 함께 처리하고, 도구 호출과 웹검색까지 수행하는 '큐원3.8-옴니-플래시'를 공개했습니다. 113개 언어·방언의 음성 인식을 지원하며, 공간 오디오와 영상을 결합해 소리가 어느 방향·거리에서 발생했는지 추정하는 '청각 위치추정' 기능을 세계 최초로 탑재했다고 주장합니다.

알리바바는 자체 벤치마크인 OmniVideoBench에서 이 모델이 토큰 사용량을 약 45.7% 줄였다는 결과도 함께 공개했습니다. 여러 모달리티를 하나의 긴 컨텍스트로 묶어 처리하면서도 효율을 높였다는 점에서, 멀티모달 에이전트 모델 경쟁이 다음 단계로 넘어가고 있음을 보여주는 사례입니다.

### 3. 오픈AI, 챗GPT에 브랜드 에이전트가 직접 대화하는 광고 포맷 도입
오픈AI가 챗GPT 내에서 광고주가 운영하는 AI 에이전트가 직접 대화를 이어가는 새 광고 포맷 '스폰서드 에이전트'를 시범 도입했습니다. 이용자가 광고를 탭하면 기존처럼 외부 웹사이트로 이동하는 대신, 라벨이 붙은 브랜드 전용 채팅창이 열리는 방식입니다. 웨이페어, 앤지, 뉴에그, 베스트바이, 로우스 등이 초기 참여 브랜드로 이름을 올렸습니다.

오픈AI의 광고 사업은 출시 200일도 되지 않아 연환산 매출 10억달러에 도달한 것으로 알려졌습니다. 챗봇이 대화형 인터페이스 자체를 광고 플랫폼으로 확장하고 있다는 점에서, AI 챗봇의 수익화 방식이 빠르게 구체화되고 있음을 보여줍니다.

### 4. 앤스로픽, 생명과학 연구자용 안전장치 완화 프로그램 베타 출시
앤스로픽이 신약개발·생물학 연구 등 제한된 목적에 한해 안전장치를 완화한 클로드 접근을 제공하는 초청제 '라이프사이언스 검증 프로그램(LSVP)'을 9월 17일 베타로 시작했습니다. 자이라 테라퓨틱스, 에디슨 사이언티픽, 매니폴드 바이오 등이 첫 참여 기관이며, 참여하려면 조직 단위 검증과 연구 목적 신고를 거쳐야 하고 개인 프로·맥스 계정은 대상에서 제외됩니다.

앤스로픽은 생물무기 오용 우려로 그동안 생물학 관련 안전장치를 엄격히 유지해왔는데, 이번 프로그램은 미국 정부와 공동 설계한 절차를 통해 그 제한을 특정 조건 아래서 부분적으로 완화한 사례입니다.

### 5. 젠슨 황 "내년 엔비디아 칩 판매량 2배로 늘 것"
엔비디아 CEO 젠슨 황이 9월 17일 찰스 3세가 주최한 AI 정상회의를 계기로 한 인터뷰에서 "내년 엔비디아가 올해의 2배에 달하는 칩을 팔 것"이라고 밝혔습니다. 이는 매출이 아닌 판매 단위 기준 전망이며, GPU뿐 아니라 CPU, 스위치칩, 광네트워킹칩까지 포괄하는 수치입니다.

AI 인프라 투자가 계속될지에 대한 시장의 우려가 이어지는 가운데 나온 발언으로, 반도체 수요 사이클을 둘러싼 논쟁에서 투자 지속을 뒷받침하는 근거로 인용되고 있습니다.

## 오늘의 딥다이브: 구글 딥마인드의 재귀적 자기개선 실험 'Dream-RSI'
구글 딥마인드와 메릴랜드대·버지니아대 연구진 17명이 코딩 에이전트의 탐색 전략을 강화하는 재귀적 자기개선(RSI, 시스템이 자기 자신을 반복적으로 개선해 나가는 과정) 기법 'Dream-RSI'를 논문으로 공개했습니다. RSI는 AI 안전 논쟁에서 오랫동안 핵심 쟁점이었던 개념으로, 시스템이 외부 개입 없이 스스로를 계속 개선해 나간다면 성능 향상 속도와 통제 가능성 모두에서 중대한 변화가 생길 수 있다는 우려와 기대가 동시에 따라붙어 왔습니다.

Dream-RSI의 핵심 아이디어는 에이전트가 실제 환경을 매번 반복 탐색하는 대신, 과거 탐색 기록으로 만든 '리플레이 시뮬레이터' 안에서 여러 정책을 가상으로 시험해보고 개선하는 방식입니다. 연구진은 이를 에이전트가 "꿈꾸듯" 시행착오를 겪는 과정에 비유했습니다. 실제 환경에서 매번 행동을 실행하고 결과를 기다리는 대신, 과거 경험을 재활용한 시뮬레이션 안에서 정책을 반복 검증하기 때문에 탐색에 드는 비용을 크게 낮출 수 있다는 것이 연구진의 설명입니다.

여기서 중요한 것은 이 기법이 바꾸는 대상이 모델의 가중치 자체가 아니라 에이전트의 탐색 정책이라는 점입니다. 즉 모델이 스스로 자신의 파라미터를 재작성하는 방식의 자기개선이 아니라, 어떤 행동을 시도할지 결정하는 전략을 반복적으로 다듬어가는 방식입니다. 이 구분은 RSI를 둘러싼 안전성 논의에서 자주 등장하는 지점으로, 모델 가중치 수정형 자기개선보다는 통제된 범위 안에 있다는 평가로 이어질 수 있는 대목입니다.

동시에 이 연구는 RSI 개념이 더 이상 순수한 이론적 논의에 머물지 않고, 실제로 작동하는 초기 실증 사례로 제시됐다는 점에서 주목받고 있습니다. 관련 보도에서는 이번 연구가 구글의 차세대 모델인 제미나이 4 출시를 앞두고 나왔다는 점도 함께 언급되고 있어, 향후 모델 개발 과정에서 이런 자기개선형 탐색 기법이 실제로 어떻게 활용될지가 관심사로 떠오르고 있습니다.

다만 리서치 자료상으로는 Dream-RSI가 구체적으로 어떤 벤치마크에서 어느 정도의 성능 향상을 보였는지, 혹은 실제 제품에 적용될 계획이 있는지까지는 확인되지 않습니다. 탐색 비용을 낮췄다는 점과 정책 개선 방식이라는 접근 자체가 이번 공개의 핵심이며, 후속 연구와 검증을 통해 이 기법이 실제로 코딩 에이전트의 성능이나 안전성에 어떤 영향을 미치는지 지켜볼 필요가 있습니다.

## 소스
- [Help Net Security — Plugin4Shell: AI coding agents vulnerability](https://www.helpnetsecurity.com/2026/09/18/plugin4shell-ai-coding-agents-vulnerability/)
- [InfoWorld — A zero-click RCE flaw in AI coding agents could have exposed enterprise systems](https://www.infoworld.com/article/4223907/a-zero-click-rce-flaw-in-ai-coding-agents-could-have-exposed-enterprise-systems.html)
- [MarkTechPost — Alibaba Qwen releases Qwen3.8-Omni-Flash](https://www.marktechpost.com/2026/09/18/alibaba-qwen-releases-qwen3-8-omni-flash/)
- [arXiv — Dream-RSI 논문](https://arxiv.org/html/2609.14858v1)
- [Analytics India Magazine — Google DeepMind sees early signs of recursive self-improvement ahead of Gemini 4](https://analyticsindiamag.com/ai-news/google-deepmind-sees-early-signs-of-recursive-self-improvement-ahead-of-gemini-4)
- [Forkast — OpenAI's sponsored agents turn ChatGPT into an ad platform where brands are the product](https://forkast.news/openais-sponsored-agents-turn-chatgpt-into-an-ad-platform-where-brands-are-the-product/)
- [Shopifreaks — OpenAI pilots sponsored agent ads in ChatGPT that open a branded chat instead of a website, with Wayfair among the testers](https://www.shopifreaks.com/openai-pilots-sponsored-agent-ads-in-chatgpt-that-open-a-branded-chat-instead-of-a-website-with-wayfair-among-the-testers/)
- [Anthropic — Life Sciences Verification Program](https://www.anthropic.com/news/life-sciences-verification-program)
- [CNBC — Nvidia's Huang: AI chip guidance](https://www.cnbc.com/2026/09/17/nvidia-huang-ai-chip-guidance.html)

---
layout: post
title: "AI 데일리 브리핑 — 8월 25일: 엔비디아, 스페이스X에 첫 에이전트 전용 CPU '베라' 공급"
date: 2026-08-25 07:00:00 +0900
categories: daily
---

엔비디아가 스페이스X 산하 SpaceXAI에 에이전트 작업 전용으로 설계한 첫 CPU '베라'를 공급하며 AI 인프라 경쟁이 궤도 컴퓨팅까지 확장되는 신호를 보였습니다. 같은 날 엔비디아는 텍사스 전력 인프라 기업 랜시엄에 최대 30억달러를 투자하는 파트너십도 발표해, AI 인프라 병목이 GPU 공급에서 전력 확보로 옮겨가고 있음을 보여줍니다. 한편 클로드는 8월 들어 여섯 차례 넘게 반복적인 접속 장애를 겪었고, 오라클은 급증한 자본지출 부담에 추가 대규모 감원을 준비 중이어서 AI 붐 이면의 비용·안정성 압박도 함께 드러났습니다. 마이크로소프트 애저의 AI 매출이 소수 대형 고객에 쏠려 있다는 블룸버그 보도는 오늘의 딥다이브로 다룹니다.

## 오늘의 헤드라인

### 1. 엔비디아, 스페이스XAI에 에이전트 전용 CPU '베라' 첫 공급

엔비디아가 8월 24일 SpaceXAI(전 xAI, 현재는 스페이스X 산하)가 차세대 에이전틱 AI 워크로드 가속을 위해 자사의 '베라(Vera)' CPU를 도입한다고 발표했습니다. 베라는 엔비디아가 AI 에이전트의 도구 조율, 코드 실행, 시뮬레이션 등을 처리하기 위해 설계한 첫 전용 CPU로, 이번 계약은 이 칩의 첫 대형 고객 사례입니다.

SpaceXAI는 그록(Grok) 챗봇을 지원하는 베라 루빈 플랫폼을 확장하는 것은 물론, 스타마인드(Starmind) 위성을 통한 궤도 컴퓨팅에도 이 아키텍처를 적용할 계획입니다. 스페이스X는 인프라 규모를 기가와트급까지 늘릴 방침이라고 밝혀, AI 인프라 경쟁이 지상을 넘어 우주 컴퓨팅으로까지 확장되고 있음을 시사합니다.

### 2. 엔비디아, 전력 인프라 기업 랜시엄에 최대 30억달러 투자

엔비디아가 8월 24일 블랙스톤 계열의 텍사스 전력 인프라 기업 랜시엄과 기가와트급 'AI 팩토리' 개발 파트너십을 공식 발표했습니다. 초기 20억달러(지분 약 20%)를 투자하고, 전력망 연결 마일스톤을 달성하면 최대 10억달러를 추가 투입하는 구조입니다. 랜시엄의 현재 임대 용량은 4GW, 개발 파이프라인은 15GW 이상입니다.

엔비디아는 자사의 DSX 레퍼런스 설계를 적용해 동일한 전력 예산으로 GPU를 최대 40% 더 배치하는 것을 목표로 하고 있습니다. GPU 반도체 자체보다 전력·부지 확보가 AI 데이터센터 확장의 병목으로 떠오르고 있다는 방증입니다.

### 3. 클로드, 8월 들어 반복적 접속 장애 — 신뢰성 우려 확산

앤스로픽의 클로드가 8월 24일(UTC 기준 05시 06분) 오퍼스5, 페이블5, 미소스5, 오퍼스4.8 등 주요 모델 전반에서 오류율이 급증하는 장애를 겪었습니다. 장애는 클로드닷에이아이뿐 아니라 API, 클로드 코드, 클로드 코워크에도 영향을 미쳤으며 약 3시간 만에 해소됐습니다.

업계 트래커에 따르면 앤스로픽은 8월에만 5일, 12일, 13일, 16일, 18일, 20일에도 유사한 장애를 겪은 것으로 나타났습니다. 에이전틱 워크로드(AI가 스스로 여러 단계를 거쳐 작업을 수행하는 사용 방식)가 급증하면서 인프라 부담이 반복적인 불안정성으로 이어지고 있다는 지적이 나옵니다.

### 4. 오라클, AI 인프라 부채 부담에 추가 대규모 감원 계획

오라클이 AI 데이터센터 구축을 위해 수백억 달러를 차입한 상황에서 9월 1일 회계연도 2분기 시작을 앞두고 추가 감원을 계획 중이며, 일부 팀은 두 자릿수 비율의 인력 축소에 직면한 것으로 전해졌습니다. 오라클은 2026회계연도에만 이미 약 2만1000명(약 13%)을 감원했습니다.

자본지출은 전년 212억달러에서 557억달러로 급증해 237억달러의 현금 순유출을 기록했습니다. 클라우드 인프라 매출은 77% 성장했지만 주가는 올해 26% 하락해, AI 투자 확대와 수익성 사이의 긴장이 커지고 있음을 보여줍니다.

### 5. 딥마인드 출신 스타트업 '인히어런트', 연구재현 에이전트로 오픈AI·앤스로픽 추월 주장

구글 딥마인드 출신들이 설립한 런던 AI 랩 '인히어런트(Inherent)'가 8월 22일 연구재현 전용 에이전트 '패러데이(Faraday)'를 공개했습니다. 정답을 알려주지 않은 채 이미 발표된 논문의 실험 결과를 독립적으로 재현하는 과제에서, 패러데이가 오픈AI와 앤스로픽의 더 큰 범용 모델들을 능가했다고 발표했습니다.

특정 과업(과학 연구 재현)에 특화된 소형 에이전트가 범용 프론티어 모델을 뛰어넘을 수 있다는 사례로, AI 연구 자동화 경쟁이 세분화되고 있음을 시사합니다.

## 오늘의 딥다이브: 마이크로소프트 애저의 AI 매출, 소수 대형 고객에 쏠려 있다

블룸버그가 8월 24일 보도한 바에 따르면 메타가 마이크로소프트 애저 파운드리를 통해 매주 수조 개의 토큰을 소비하며 애저의 최대 AI 고객 중 하나로 떠올랐습니다. 마이크로소프트 파운드리는 기업들이 자체 애플리케이션에 AI 모델을 붙여 쓸 수 있도록 하는 애저의 AI 모델 서빙 플랫폼입니다.

수치만 보면 성장세는 뚜렷합니다. 마이크로소프트 파운드리는 지난 7월 기준 고객 10만 곳을 확보했다고 밝혔습니다. 하지만 블룸버그 보도는 이 성장의 이면을 함께 짚었습니다. 실제 매출은 오픈AI, 바이트댄스, 메타 등 소수의 대형 테크기업에 집중돼 있다는 것입니다.

특히 눈에 띄는 대목은 오픈AI가 마이크로소프트 전체 AI 매출의 약 70%를 차지한다는 지적입니다. 마이크로소프트는 오픈AI에 대규모 투자를 해온 만큼 두 회사의 관계가 각별하지만, 그만큼 마이크로소프트의 AI 사업 실적이 사실상 한두 개 초대형 고객의 사용량에 좌우된다는 뜻이기도 합니다.

이는 클라우드 업체들이 흔히 내세우는 "AI 고객 수 급증"이라는 서사와, 실제 매출 구조 사이에 간극이 있을 수 있음을 보여줍니다. 고객 10만 곳이라는 숫자는 플랫폼의 확산을 나타내지만, 매출 기여도로 보면 소수의 초대형 사용자가 대부분을 떠받치는 구조일 수 있다는 것입니다. 이런 매출 집중은 산업 전반에 걸친 AI 채택이 아직 초기 단계에 머물러 있다는 신호로 해석될 여지가 있습니다.

메타의 사례는 앞서 다룬 오라클의 자본지출 부담 이슈와 함께, AI 인프라 붐의 화려한 성장 서사 이면에 숨은 취약점을 보여준다는 공통점이 있습니다. 오라클이 비용 측면에서, 마이크로소프트가 매출 구조 측면에서 각각 AI 투자 확대와 실제 수익성 사이의 간극을 드러내고 있는 셈입니다. 소수 고객에 대한 의존도가 높을수록, 그 고객의 워크로드 변화나 이탈이 클라우드 업체의 실적에 미치는 영향도 커질 수밖에 없습니다. 마이크로소프트를 포함한 클라우드 대형사들이 내세우는 AI 매출 성장 서사가 앞으로 얼마나 더 넓은 고객 기반으로 확산될 수 있을지가 관전 포인트로 남습니다.

## 소스
- [NVIDIA Newsroom - SpaceXAI Adopts NVIDIA Vera CPU to Accelerate Agentic AI at Massive Scale](https://nvidianews.nvidia.com/news/spacexai-adopts-nvidia-vera-cpu-to-accelerate-agentic-ai-at-massive-scale)
- [PR Newswire - Lancium Announces Partnership with NVIDIA to Advance Gigawatt-Scale AI Factory Development](https://www.prnewswire.com/news-releases/lancium-announces-partnership-with-nvidia-to-advance-gigawatt-scale-ai-factory-development-across-its-15-gw-portfolio-302858393.html)
- [Bloomberg - Microsoft AI Business Is Concentrated With OpenAI, TikTok, Meta](https://www.bloomberg.com/news/newsletters/2026-08-24/microsoft-ai-business-is-concentrated-with-openai-tiktok-meta)
- [Cybersecurity News - Claude AI Suffers Outage](https://cybersecuritynews.com/claude-ai-suffers-outage/)
- [TheNextWeb - Oracle August 2026 Layoffs AI Capex](https://thenextweb.com/news/oracle-august-2026-layoffs-ai-capex)
- [TechCrunch - Inherent, Founded by DeepMind Alumni, Says Its AI Teammate Just Outperformed Anthropic and OpenAI at Replicating Research](https://techcrunch.com/2026/08/22/inherent-founded-by-deepmind-alumni-says-its-ai-teammate-just-outperformed-anthropic-and-openai-at-replicating-research/)

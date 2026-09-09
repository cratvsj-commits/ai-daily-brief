---
layout: post
title: "AI 데일리 브리핑 — 9월 10일: 美 정보당국, 중국 AI 6개사 '프론티어 모델 증류' 합동경보"
date: 2026-09-10 07:00:00 +0900
categories: daily
---

미국 국가안보국(NSA)·사이버보안청(CISA)·FBI가 딥시크, 알리바바, 문샷AI 등 중국 AI 6개사를 겨냥해 미국 프론티어 모델을 대상으로 한 대규모 데이터 추출·증류를 경고하는 합동경보를 발표했습니다. 같은 날 오픈AI와 앤스로픽 사이에서는 수학 난제 증명의 공로를 둘러싼 갈등이 공개적으로 불거졌고, AI 코딩 에이전트 다수에서 사용자 승인 없이 코드가 실행될 수 있는 공통 취약점 'GitSpawn'도 드러났습니다. 이 밖에 구글 딥마인드의 유전체 변이 예측 지도 공개, 국내 스타트업 뤼튼테크놀로지스의 기업가치 상승, 카카오모빌리티 로보택시의 가동률 성과 소식도 있었습니다. 오늘 브리핑에서는 미중 AI 경쟁의 새로운 국면을 보여준 합동경보를 딥다이브로 다룹니다.

## 오늘의 헤드라인

### 1. 오픈AI-앤스로픽, 나비에-스토크스 증명 공로 다툼 논란

오픈AI가 내부 AI 모델과 약 1만 개 에이전트를 88시간 동원해 클레이수학연구소가 지정한 밀레니엄 난제 중 하나인 나비에-스토크스 방정식의 반례(방정식 해가 유한 시간 안에 무한대로 발산하는 '블로업' 사례)를 찾아냈다고 발표했습니다. 그런데 이 성과가 NYU 수학자 트리스탄 벅마스터와 앤스로픽 소속 연구자 레벤트 알푀게가 진행 중이던 유체역학 공동연구에서 촉발됐다는 사실이 드러나면서 논란이 커졌습니다.

벅마스터는 오픈AI가 "알푀게가 앤스로픽 소속이라는 이유로 저자에서 빼고 오픈AI 내부 모델이 해결한 것처럼 적으라"고 요구했다고 주장했습니다. AI 기업이 경쟁사 소속 연구자의 기여를 지우려 했다는 의혹은 AI 연구 성과의 공로 배분 방식과 업계 신뢰도에 대한 논의로 번지고 있습니다.

### 2. AI 코딩 에이전트 공통 취약점 'GitSpawn' 공개

보안업체 매니폴드가 클로드 코드, 오픈AI 코덱스, 커서, 그록 빌드, 구스, 허미스 에이전트, 큐원 코드 등 주요 AI 코딩 에이전트에서 'GitSpawn'이라 명명된 공통 취약점을 발견했습니다. 악성 저장소를 열기만 해도 에이전트가 백그라운드에서 실행하는 git 명령이 저장소에 조작된 `.git/config` 파일을 통해 임의 코드를 실행하게 만드는 방식으로, 사용자가 프롬프트를 입력하거나 승인 절차를 거치지 않아도 공격이 성립한다는 점이 특징입니다.

구스, 클로드 코드, 커서는 이미 패치를 완료했지만, 허미스 에이전트, 큐원 코드, 그록 빌드 등은 9월 1일 재검증 시점까지도 미패치 상태였던 것으로 확인됐습니다. AI 코딩 에이전트가 개발 워크플로에 깊숙이 들어온 상황에서, 저장소를 여는 행위 자체가 공격 경로가 될 수 있다는 점에서 파급력이 큽니다.

### 3. 구글 딥마인드, 인간 유전체 90억 개 변이 예측 지도 '알파지놈 아틀라스' 공개

구글 딥마인드가 9월 8일 인간 유전체의 모든 위치에서 가능한 90억 개 단일 염기 변이의 분자적 영향을 예측한 '알파지놈 아틀라스'를 공개했습니다. 단백질을 만들지 않지만 유전자 발현을 조절하는 '논코딩 DNA' 영역을 분석하는 AI 모델 알파지놈을 기반으로 1페타바이트 규모의 예측 데이터를 계산했으며, 변이의 잠재적 생물학적 영향을 순위화하는 '알파지놈 변이영향점수'도 함께 도입했습니다.

이 데이터는 비상업 연구 목적으로 무료 공개되며, 희귀질환·유전질환 연구를 가속화할 것으로 기대됩니다.

### 4. 뤼튼테크놀로지스, 기업가치 1.4조 돌파 — 해외 매출이 국내 첫 추월

국내 AI 스타트업 뤼튼테크놀로지스가 누적 투자금 2300억원, 기업가치 1.4조원을 기록했습니다. AI 캐릭터 채팅 서비스 '크랙'이 일본(캬라푸)·북미(OOC)에서 흥행하면서 해외 매출이 국내 매출을 처음으로 앞질렀고, 작년 매출 471억원에서 올해는 2000억원 달성을 전망하고 있습니다.

회사는 국내 증권사를 대상으로 상장 주관사 선정 절차에 착수해 내년 이후 기업공개(IPO)를 목표로 하고 있습니다.

### 5. 카카오모빌리티 강남 로보택시, 가동률 82.5%로 웨이모 앞서

카카오모빌리티가 3월부터 서울 강남에서 운행 중인 자율주행 택시 '서울자율차'의 차량 가동률이 82.5%(1~8월 누적 기준 84.3%)를 기록했다고 밝혔습니다. 반면 글로벌 1위 로보택시 사업자 웨이모는 MIT 'Transport Findings' 분석 기준 전체 운행거리의 36~56%가 승객 없는 공차 상태로, 승객 탑승 비중이 60% 이하로 추정됩니다.

카카오T 앱과의 연동을 통한 '플랫폼 통합 전략'이 이런 격차의 핵심 요인으로 꼽히며, 국내 로보택시 상용화의 경쟁력을 보여주는 사례로 평가됩니다.

## 오늘의 딥다이브: 美 정보당국, 중국 AI 6개사 '프론티어 모델 증류' 합동경보

미국 국가안보국(NSA)·사이버보안청(CISA)·FBI가 9월 8일 합동 사이버보안 권고문(AA26-251A)을 발표했습니다. 이 권고문은 딥시크, 알리바바, 문샷AI, 미니맥스, 스텝펀, Z.ai 등 6개 중국 AI 기업이 2024년 말부터 클로드·GPT·제미나이·그록 등 미국 프론티어 모델(현재 가장 성능이 뛰어난 최상위 AI 모델을 뜻하는 업계 용어)에서 대규모 토큰을 추출해 자사 모델 훈련에 활용해왔다고 밝혔습니다.

여기서 핵심 기술은 '증류(distillation)'입니다. 크고 비용이 많이 드는 모델의 출력 결과를 활용해 상대적으로 작고 저렴한 모델을 학습시키는 방식으로, 원본 모델을 처음부터 개발하는 것보다 훨씬 적은 비용으로 비슷한 성능을 내는 모델을 만들 수 있다는 특징이 있습니다. 합동경보는 이 기법이 개별 연구자 차원이 아니라 "산업적 규모"로 조직적으로 이뤄졌다고 지적했습니다.

권고문에서 가장 구체적으로 지목된 사례는 문샷AI입니다. 문샷AI가 앤스로픽의 클로드 페이블5 모델 데이터를 대거 추출해 자사 Kimi-K3 모델 훈련에 사용한 것으로 지목됐습니다. 특정 기업의 특정 모델 훈련 과정이 이 정도로 구체적으로 지목된 것은 이례적이며, 미국 AI 기업들이 자사 모델 출력물의 무단 활용을 얼마나 민감하게 여기고 있는지를 보여줍니다.

합동경보는 또한 이런 증류 시도를 숨기기 위해 사용된 4가지 신종 회피 기법도 함께 공개했습니다. 대표적으로 지역제한(geoblock) 우회와 요청 메타데이터 세탁 등이 언급됐는데, 이는 중국 기업들이 단순히 API를 대량 호출하는 수준을 넘어 탐지를 피하기 위한 기술적 은폐 수단까지 동원했다는 의미입니다.

이번 합동경보는 미국 정보·수사기관이 특정 AI 기업들을 이름까지 명시하며 기술 유출 경위를 공개적으로 경고했다는 점에서, 미중 AI 패권 경쟁이 모델 성능 경쟁을 넘어 데이터·기술 보안 영역으로 확전되고 있음을 보여줍니다. 앞으로 양국 AI 기업 간 방어와 회피 기법을 둘러싼 공방이 이어질 것으로 보입니다.

## 소스
- [TechCrunch — OpenAI fought dirty on career-making math problem, says NYU mathematician](https://techcrunch.com/2026/09/08/openai-fought-dirty-on-career-making-math-problem-says-nyu-mathematician/)
- [MIT Technology Review — What OpenAI's latest controversy tells us about the future of math](https://www.technologyreview.com/2026/09/08/1143747/what-openais-latest-controversy-tells-us-about-the-future-of-math/)
- [OpenAI — Navier-Stokes solution](https://openai.com/index/navier-stokes-solution/)
- [CISA — AA26-251A 합동 사이버보안 권고문](https://www.cisa.gov/news-events/cybersecurity-advisories/aa26-251a)
- [Unite.AI — NSA, CISA, FBI warn China-based AI firms distill US frontier models](https://www.unite.ai/nsa-cisa-fbi-warn-china-based-ai-firms-distill-us-frontier-models/)
- [The Hacker News — Malicious Git configs can make Claude...](https://thehackernews.com/2026/09/malicious-git-configs-can-make-claude.html)
- [Manifold Security — AI coding agents git hijack](https://www.manifold.security/blog/ai-coding-agents-git-hijack)
- [Google — AlphaGenome Atlas](https://blog.google/innovation-and-ai/models-and-research/google-deepmind/alphagenome-atlas/)
- [Nature — d41586-026-02835-4](https://www.nature.com/articles/d41586-026-02835-4)
- [이투데이 — 뤼튼테크놀로지스 기업가치 기사](https://www.etoday.co.kr/news/view/2622148)
- [아시아투데이 — 뤼튼테크놀로지스 관련 기사](https://www.asiatoday.co.kr/kn/view.php?key=20260902010000855)
- [더구루 — 카카오모빌리티 로보택시 가동률](https://www.theguru.co.kr/news/article.html?no=106893)
- [Econmingle — Kakao Mobility autonomous vehicle 82% utilization](https://econmingle.com/car/kakao-mobility-autonomous-vehicle-82-utilizatio/)

---
layout: post
title: "AI 데일리 브리핑 — 10월 19일: 메타·시에라, AI 에이전트 상거래 표준 'PAP' 공개"
date: 2026-10-19 07:00:00 +0900
categories: daily
---

메타와 시에라가 AI 에이전트가 기업 웹사이트에 접속해 쇼핑할 때 따를 공개 표준 '퍼스널 에이전트 프로토콜(PAP)'을 내놓으면서, 비자 주도의 경쟁 표준 TAP과 함께 에이전트 상거래 접속권을 둘러싼 표준 경쟁이 본격화됐습니다. 국내에서는 정부 지원 전 국민 AI 에이전트 '모두의 AI'가 SKT·카카오·KT 3개 컨소시엄 동시 비공개 베타테스트에 들어갔습니다. 중국에서는 텐센트 인프라에서 작동한 AI 에이전트 무리가 알리바바 지도서비스를 대규모로 긁어간 사건의 최종 조사보고서가 나왔고, 아마존은 메타의 쇼핑 에이전트 '뮤즈'의 자사 사이트 접속을 막았습니다. 한편 오픈AI·앤스로픽·구글 딥마인드 간 상호 안전성 테스트 협상은 여전히 타결되지 않고 있습니다.

## 오늘의 헤드라인

### 1. 메타·시에라, AI 에이전트 상거래 접속 표준 'PAP' 공개

시에라가 메타와 함께 개인용 AI 에이전트가 기업 웹사이트·앱에 접속해 조회·구매 등을 수행할 때 지킬 공개 표준 '퍼스널 에이전트 프로토콜(PAP)'을 10월 6일 발표했습니다. 월마트·쇼피파이·스트라이프·제네시스·인스팅트·로켓 등이 파트너로 참여하며, 구체적인 기술 규격인 v0.1 스펙은 10월 중 공개될 예정입니다.

PAP는 로그인 없이 둘러보는 게스트 조회와 로그인 후 실제 구매까지 하는 읽기/쓰기 권한을 구분하는 OAuth(사용자가 비밀번호를 직접 주지 않고 인증 토큰으로 접속 권한을 위임하는 방식) 기반 세션을 쓰며, 기업은 웹사이트·API(MCP/OpenAPI)·자체 에이전트 중 접속 방식을 선택할 수 있습니다. 다만 이번 버전에는 결제 기능이 빠져 있습니다.

쇼피파이와 스트라이프는 이미 비자 주도의 경쟁 표준 '신뢰 에이전트 프로토콜(TAP)'에도 참여하고 있어, 같은 기업들이 서로 다른 표준에 걸쳐 있는 상황입니다. 이는 AI 에이전트가 플랫폼에 접속할 권한을 누가, 어떤 규칙으로 부여할지를 둘러싼 경쟁이 막 시작됐음을 보여줍니다.

### 2. '모두의 AI' 비공개 베타테스트 돌입 — SKT·카카오·KT 동시 가동

정부 지원 전 국민 무료 AI 에이전트 '모두의 AI' 사업의 3개 컨소시엄(SKT·카카오·KT)이 10월 16일부터 비공개 베타테스트(CBT)를 일제히 시작했습니다. 카카오는 별도 앱 없이 카카오톡 채팅창 안에서 행정서류 신청·결제까지 끝내는 구조를, SKT는 정부24·PASS 연계 증명서 발급과 병원 예약·전화·문자 기능을 준비 중이며, KT는 생활밀착형 서비스를 내세웁니다.

연내 정식 출시(일부 보도는 12월)가 목표로, 이달 초 기록됐던 "베타 출시 예고" 상태에서 실제 가동 단계로 넘어간 구체적인 진전입니다.

### 3. 텐센트발 AI 에이전트 무리, 알리바바 지도서비스 '아마프' 겨냥 — 조사보고서 공개

독립 연구자그룹이 10월 14일 텐센트 클라우드 인프라에서 작동 중인 AI 에이전트 무리를 추적한 최종 보고서를 공개했습니다. 이 에이전트들은 9월 28일부터 10월 8일 사이 알리바바의 지도서비스 '아마프(Amap)'에 2,600회 이상 접속해 공원·동물원·병원 등 장소의 출입구 정보를 집중적으로 긁어갔습니다.

일부 트래픽에는 '클로드' 라벨이 붙었지만, 코드 패턴은 텐센트 자체 모델 '훈위안(Hunyuan)'에 더 가까운 것으로 분석됐습니다. 배후와 목적은 여전히 불명확하며, 이는 앞서 포착됐던 1,810건 규모의 예비 조사보다 범위가 확대된 최종 결론입니다.

### 4. 아마존, 메타 '뮤즈' 쇼핑 에이전트의 자사 사이트 접속 차단

아마존이 9월 하순부터 메타의 쇼핑 에이전트 '뮤즈'가 자사 쇼핑몰에 접속할 때 이용약관 위반 팝업을 띄워 차단하고 있습니다. 아마존은 메타가 사전 통지 없이 접속했고, 에이전트가 활동 중 자신을 밝히지 않으며, 고객 자격증명(로그인 정보)을 저장하는 것으로 보인다고 주장했습니다. 메타는 자격증명이 안전하게 저장되고 구매 전 확인을 거친다고 반박했습니다.

이는 아마존이 퍼플렉시티를 상대로 제기했던 유사 소송에서 3월 가처분(법원의 임시 금지 명령)은 승소했지만 8월 제9순회항소법원에서는 패소한 선례와 연결되며, AI 에이전트의 제3자 사이트 접속권을 둘러싼 빅테크 간 갈등이 메타로도 확산된 사례입니다.

### 5. 오픈AI·앤스로픽·구글 딥마인드 상호 안전성 스트레스테스트, 여전히 타결 미확정

석 달 넘게 논의돼 온 프런티어 3사 간 상호 모델 취약점 테스트 협상이 10월 중순까지도 구속력 있는 합의로 이어지지 못하고 있습니다. 2025년 8월 오픈AI-앤스로픽 간 1회성 교차평가 이후 앤스로픽이 이용약관 위반을 이유로 오픈AI 팀의 API 접근을 중단한 전례가 있어, 공식 프로토콜화 여부에 업계의 관심이 쏠립니다.

지난주 기록됐던 "한 달 넘게 타결 미확정" 상태가 두 달 가까이 이어지고 있다는 점에서, 세 회사 간 신뢰 구축 실패가 장기화되는 모습을 보여줍니다.

## 오늘의 딥다이브: AI 에이전트 상거래 접속권 표준 경쟁 — PAP와 TAP, 그리고 아마존의 차단

메타와 시에라가 발표한 PAP(퍼스널 에이전트 프로토콜)는 "AI 에이전트가 기업 웹사이트에 어떻게, 어떤 권한으로 접속해야 하는가"라는 질문에 처음으로 업계가 함께 답을 내놓으려는 시도입니다. 월마트·쇼피파이·스트라이프 등 굵직한 파트너가 참여했고, 게스트 조회와 로그인 후 구매를 구분하는 OAuth 기반 세션, 그리고 웹사이트·API·자체 에이전트 중 기업이 접속 방식을 고를 수 있는 유연성을 갖췄습니다. 다만 결제는 이번 v0.1 범위에 포함되지 않아, 실제 거래까지 커버하는 완성형 표준이 되기까지는 추가 작업이 필요합니다.

문제는 같은 생태계에 이미 비자가 주도하는 경쟁 표준 '신뢰 에이전트 프로토콜(TAP)'이 존재한다는 점입니다. 더 흥미로운 지점은 쇼피파이와 스트라이프가 PAP와 TAP 양쪽에 모두 참여하고 있다는 사실입니다. 이는 아직 어느 표준이 시장을 장악할지 불확실한 상황에서 주요 플랫폼들이 양쪽에 발을 걸쳐두는 헤징(위험 분산) 전략을 택하고 있음을 보여줍니다. 신용카드 결제가 비자·마스터카드 표준으로 수렴했던 과거처럼, 에이전트 상거래 접속에도 결국 소수의 표준이 자리 잡을 가능성이 있지만, 그 과정이 매끄럽지는 않을 것으로 보입니다.

이 표준 경쟁이 왜 지금 긴급한 문제가 됐는지를 보여주는 것이 바로 아마존의 메타 '뮤즈' 차단 사례입니다. 아마존은 뮤즈가 사전 통지 없이 접속하고 자신을 에이전트로 밝히지 않으며 고객 자격증명을 저장하는 것으로 보인다는 이유를 들어 접속을 막았습니다. 메타는 자격증명이 안전하게 저장되고 구매 전 확인을 거친다고 반박하고 있어, 양측의 설명이 정면으로 갈립니다. 표준화된 프로토콜이 없는 상태에서는 결국 각 플랫폼이 자체 판단으로 에이전트를 차단하거나 허용하는 방식에 의존하게 되고, 이는 에이전트 개발사와 플랫폼 사이의 분쟁으로 이어지기 쉽습니다.

실제로 아마존은 이미 퍼플렉시티를 상대로도 비슷한 갈등을 겪었습니다. 지난 3월 법원 가처분에서는 아마존이 승소했지만, 8월 제9순회항소법원에서는 패소하며 법적 판단이 뒤집혔습니다. 이는 "에이전트가 사용자를 대신해 제3자 사이트에 접속할 권리가 있는가"라는 질문에 아직 법원도 일관된 답을 내놓지 못하고 있다는 뜻입니다. 법적 선례가 불안정한 상태에서는 PAP나 TAP 같은 업계 자율 표준이 분쟁을 줄이는 현실적인 대안으로 떠오를 수 있지만, 동시에 그 표준을 누가 주도하느냐에 따라 플랫폼과 에이전트 개발사 간 힘의 균형이 좌우될 수 있습니다.

결국 이 흐름은 플랫폼(아마존, 쇼피파이 등)과 에이전트 주체(메타, 퍼플렉시티, 시에라의 고객사 등) 사이의 주도권 다툼으로 읽을 수 있습니다. 플랫폼은 자사 사이트에서 벌어지는 트래픽과 데이터를 통제하고 싶어 하고, 에이전트 쪽은 사용자를 대신해 최대한 자유롭게 여러 사이트를 드나들며 작업을 수행하고 싶어 합니다. PAP의 v0.1 스펙이 10월 중 공개되면, 결제 기능을 포함한 다음 단계 로드맵과 함께 TAP과의 실질적인 경쟁 양상이 더 뚜렷해질 것으로 보입니다.

## 소스

- [Meta and Sierra develop Personal Agent Protocol for AI agents - The Paypers](https://thepaypers.com/payments/news/meta-and-sierra-develop-personal-agent-protocol-for-ai-agents)
- [Sierra unveils Personal Agent Protocol built with Meta and partners - Unite.AI](https://unite.ai/sierra-unveils-personal-agent-protocol-built-with-meta-and-partners)
- [Meta, Walmart, Shopify, Stripe back AI agent standard - Channel Insider](https://www.channelinsider.com/ai/news-meta-walmart-shopify-stripe-ai-agent-standard/)
- ['모두의 AI' 비공개 베타테스트 돌입 - 뉴스토마토](https://newstomato.com/ReadNews.aspx?no=1311767)
- ['모두의 AI' 관련 보도 - 데일리안](https://www.dailian.co.kr/news/view/1694083/)
- ['모두의 AI' 관련 보도 - 머니투데이방송](https://news.mtn.co.kr/news-detail/2026092314100646376)
- [AI 에이전트 텐센트 추적 보고서 - 위키트리](https://www.wikitree.co.kr/articles/1164062)
- [AI agents on Tencent Cloud try to break Alibaba's Amap, researchers say - SCMP](https://scmp.com/tech/tech-trends/article/3371007/ai-agents-tencent-cloud-try-break-alibabas-amap-researchers)
- [Researchers trace AI agents that probed Alibaba's Amap to Tencent - TNW](https://thenextweb.com/news/researchers-trace-ai-agents-that-probed-alibabas-amap-to-tencent)
- [Amazon blocks Meta's Muse AI agent from its retail site - The Star](https://www.thestar.com.my/tech/tech-news/2026/09/22/amazon-blocks-metas-muse-ai-agent-from-its-retail-site)
- [Amazon blocks Meta Muse shopping agent - Implicator.ai](https://www.implicator.ai/amazon-blocks-meta-muse-shopping-agent/)
- [Amazon blocks Meta's Muse AI agent from shopping on its site - PPC Land](https://ppc.land/amazon-blocks-metas-muse-ai-agent-from-shopping-on-its-site/)
- [AI 안전성 스트레스테스트 협상 관련 보도 - 스탁허브](https://stockhub.kr/news/news_b5be72e318d9)
- [OpenAI and Anthropic safety testing deal remains elusive as talks drag on - ROIC.ai](https://www.roic.ai/news/openai-and-anthropic-safety-testing-deal-remains-elusive-as-talks-drag-on-09-21-2026)

---
layout: post
title: "AI 데일리 브리핑 — 9월 4일: 네이버클라우드, 정부 사이버보안 AI 파운데이션모델 사업 수주"
date: 2026-09-04 07:00:00 +0900
categories: daily
---

네이버클라우드가 SK텔레콤과 경쟁해 온 정부의 사이버보안 특화 AI 파운데이션모델(방대한 데이터로 사전 학습해 다양한 작업의 기반이 되는 대형 AI 모델) 개발 사업 수행기관으로 최종 선정됐습니다. 같은 날 챗GPT·클로드·그록 등 주요 AI 서비스가 거의 동시에 장애를 겪으면서 소수 모델에 대한 산업 전반의 의존도가 다시 도마에 올랐습니다. 구글은 취약점을 자동으로 찾아 패치하는 사이버보안 특화 모델을 새로 내놓았고, 오픈AI는 챗GPT Health에 미국 최대 전자의무기록 시스템 에픽을 연동했습니다. 이 외에 팔로알토네트웍스가 AI 보안 자동화 스타트업을 인수하는 소식도 있었습니다.

## 오늘의 헤드라인

### 1. 네이버클라우드, 정부 '사이버보안 특화 AI' 파운데이션모델 사업 최종 선정

과학기술정보통신부가 9월 3일 '사이버보안 특화 AI 파운데이션 모델 개발' 국책사업의 수행기관으로 네이버클라우드 컨소시엄을 최종 선정했습니다. 컨소시엄에는 LG AI연구원, LG CNS 등 32개 기관이 참여하며, 그동안 이 사업을 두고 SK텔레콤과 경쟁 구도를 이어왔던 사안이 이날 결론이 났습니다.

이번 사업의 목표는 네이버의 하이퍼클로바X를 기반으로 한 방어모델과 LG AI연구원의 엑사원을 기반으로 한 공격모델을 병렬로 개발해, 이를 700B(7000억) 파라미터급 MoE(Mixture of Experts, 여러 개의 전문 하위 모델을 필요에 따라 선택적으로 활용하는 구조) 모델로 완성하는 것입니다. 정부는 이를 위해 향후 10개월간 최신 GPU인 B200 256장을 지원합니다.

공격과 방어 모델을 동시에 개발한다는 접근 방식은 실제 해킹 시나리오에 대응하는 방어 능력을 검증하기 위한 설계로 읽힙니다. 국가 차원의 AI 파운데이션모델 사업에 국내 대표 AI 기업들이 컨소시엄으로 참여했다는 점에서, 국내 AI 산업의 역량이 사이버보안 분야로도 확장되는 흐름을 보여주는 사례입니다.

### 2. 챗GPT·클로드·그록, 동시다발 글로벌 장애 발생

9월 3일(현지시간) 오픈AI의 챗GPT와 코덱스, 앤스로픽의 클로드, xAI의 그록이 거의 동시에 오류율 급증과 응답 지연을 겪었습니다. 이들 모델을 기반으로 하는 코딩 에이전트 서비스 커서 등도 연쇄적으로 서비스가 중단됐습니다.

장애 원인이 공통된 클라우드·네트워크 인프라 의존성 때문인지, 아니면 단순한 우연의 일치인지는 아직 명확히 밝혀지지 않았습니다. 다만 서로 다른 회사의 서비스가 동시에 멈췄다는 사실 자체가, 업계 전반이 소수의 빅테크 모델에 의존하고 있는 '집중 리스크'를 드러낸 사건으로 주목받고 있습니다.

### 3. 구글, 취약점 자동탐지·패치 특화 '제미나이 3.8 플래시 사이버' 공개

구글이 범용 모델 '제미나이 3.8 플래시'와 함께 사이버보안 특화 변형 모델 '제미나이 3.8 플래시 사이버'를 동시에 발표했습니다. 소프트웨어 취약점을 실제 공격 상황에서 얼마나 잘 찾아내고 패치하는지 평가하는 CyberGym 벤치마크에서 86.2%를 기록했고, 크롬 보안팀 테스트에서는 경쟁 상용 모델 대비 2.6배 높은 정확도로 패치를 생성했습니다.

이 모델은 오용을 막기 위해 새로 마련된 '페어윈드 프로그램'을 통해 검증된 방어팀에게만 제한적으로 제공됩니다. 전날 오픈AI의 '아스트라' 모델이 치명적 수준의 사이버 위험 등급을 넘어선 것으로 보도된 데 이어, 빅테크들의 AI 공격·방어 능력 경쟁이 확산되는 흐름을 보여줍니다.

### 4. 오픈AI, 챗GPT Health에 미국 최대 전자의무기록(에픽) 연동

오픈AI가 챗GPT Health를 미국 최대 전자의무기록(EHR, 환자의 진료·검사·투약 기록을 전산으로 관리하는 시스템) 업체인 에픽과 연동했습니다. 이를 통해 임상의는 환자의 진료기록, 검사결과, 투약내역 등을 읽기전용으로 불러와 AI로 검토할 수 있게 됩니다.

27개 임상 시나리오, 4,300여 건의 의사 응답을 평가한 결과 안전 응답 비율은 99.1%였고, UCSF헬스가 파일럿 파트너로 참여했습니다. 다만 오픈AI는 여전히 AI가 진단이나 치료 목적에는 부적합하다고 명시하고 있어, 어디까지나 임상 보조 도구로서의 위치를 강조하는 모습입니다.

### 5. 팔로알토네트웍스, AI IT자동화 스타트업 '콘솔' 5억달러 인수

팔로알토네트웍스가 스라이브캐피털의 투자를 받은 2년차 스타트업 '콘솔'을 현금과 주식을 합쳐 약 5억달러에 인수했습니다. 인수 전 콘솔의 기업가치는 1억5700만달러로, 짧은 기간에 기업가치가 크게 뛴 셈입니다.

콘솔의 AI 에이전트 기술은 팔로알토네트웍스의 보안운영 플랫폼 '코텍스'에 통합돼, 보안팀의 경보 조사와 우선순위화, 대응 자동화를 가속하는 데 쓰일 예정입니다. 이는 팔로알토네트웍스가 올해 진행한 7번째 인수합병이기도 합니다.

## 오늘의 딥다이브: 네이버클라우드의 정부 사이버보안 AI 사업 수주

과기정통부가 진행해 온 '사이버보안 특화 AI 파운데이션 모델 개발' 사업은 지난달 말부터 네이버클라우드와 SK텔레콤이 치열하게 경쟁해 온 사안이었습니다. 이 경쟁 구도는 8월 28일 관련 보도를 통해 이미 알려져 있었고, 9월 3일 네이버클라우드 컨소시엄의 최종 선정으로 결론이 났습니다. 국내 통신·AI 업계의 대표 기업 두 곳이 국책사업을 두고 직접 경합한 사례라는 점에서 그 자체로 의미가 있는 결정입니다.

이번에 선정된 컨소시엄에는 네이버클라우드를 중심으로 LG AI연구원, LG CNS 등 32개 기관이 참여합니다. 사이버보안이라는 고도로 전문적인 영역에서 단일 기업이 아닌 다수 기관이 연합해 대응한다는 점은, 그만큼 이 과제가 요구하는 기술적 범위가 넓다는 것을 시사합니다.

기술적으로 눈에 띄는 부분은 방어모델과 공격모델을 병렬로 개발한다는 설계입니다. 네이버의 하이퍼클로바X를 기반으로 한 방어모델과 LG AI연구원의 엑사원을 기반으로 한 공격모델을 각각 만든 뒤, 이를 700B 파라미터급 MoE 모델로 통합하는 것이 목표입니다. 공격 시나리오를 스스로 만들어내는 모델과 이를 막아내는 모델을 함께 훈련시키는 방식은, 실전에 가까운 방어 능력을 검증할 수 있다는 점에서 사이버보안 AI 개발의 한 방향으로 볼 수 있습니다.

정부의 지원 규모도 구체적입니다. 향후 10개월간 최신 GPU인 B200 256장이 이 사업에 투입됩니다. 대규모 파운데이션모델 학습에는 막대한 컴퓨팅 자원이 필요한 만큼, 이 정도 규모의 GPU 지원은 정부가 이 사업에 상당한 무게를 두고 있음을 보여줍니다.

이번 결정은 같은 날 발표된 구글의 사이버보안 특화 모델 '제미나이 3.8 플래시 사이버'와도 맞물려 읽을 수 있습니다. 구글은 CyberGym 벤치마크에서 86.2%의 성적을 낸 모델을 검증된 방어팀에게만 제한적으로 제공하는 방식을 택했는데, 이는 사이버보안 AI가 전 세계적으로 국가·기업 단위의 전략 자산으로 다뤄지고 있음을 보여주는 흐름입니다. 네이버클라우드의 이번 수주 역시 이런 글로벌 흐름 속에서, 국내 기업이 정부와 함께 사이버보안 AI 역량을 자체적으로 확보하려는 시도로 볼 수 있습니다.

다만 이번 사업이 실제로 어떤 성과를 낼지는 아직 지켜봐야 할 부분입니다. 700B 파라미터급 MoE 모델을 10개월 안에 완성한다는 목표는 상당히 도전적인 일정이며, 공격모델과 방어모델을 함께 개발하는 과정에서 발생할 수 있는 오용 위험을 어떻게 관리할지도 향후 관전 포인트입니다.

## 소스
- [아시아경제 - 네이버클라우드, 정부 사이버보안 AI 사업 최종 선정](https://view.asiae.co.kr/article/2026090310522726561)
- [IT데일리 - 네이버클라우드 컨소시엄 선정 관련 보도](https://www.itdaily.kr/news/articleView.html?idxno=241378)
- [지디넷코리아 - 네이버클라우드 컨소시엄 선정 관련 보도](https://zdnet.co.kr/view/?no=20260903090834)
- [Bloomberg - OpenAI, Anthropic, SpaceX/xAI Hit by Service Outages for AI Models](https://www.bloomberg.com/news/articles/2026-09-03/openai-anthropic-spacexai-hit-by-service-outages-for-ai-models)
- [ROIC.ai - OpenAI, Anthropic, xAI, Cursor Hit by User-Reported Outages](https://www.roic.ai/news/openai-anthropic-xai-cursor-hit-by-user-reported-outages-in-us-09-03-2026)
- [Cybersecurity News - Claude AI Faces Outage](https://cybersecuritynews.com/claude-ai-faces-outage/)
- [VentureBeat - Google's Gemini 3.8 Flash is Built for Agents, While Its Cyber Twin Hunts Vulnerabilities](https://venturebeat.com/security/googles-gemini-3-8-flash-is-built-for-agents-while-its-cyber-twin-hunts-vulnerabilities)
- [Google Blog - Gemini 3.8 Flash and 3.8 Flash Cyber](https://blog.google/innovation-and-ai/models-and-research/gemini-models/3-8-flash-and-3-8-flash-cyber/)
- [Cybersecurity News - Gemini 3.8 Flash Cyber](https://cybersecuritynews.com/gemini-3-8-flash-cyber/)
- [TechCrunch - ChatGPT Health Adds Epic Integration for Clinicians to Import Patient Data](https://techcrunch.com/2026/09/01/chatgpt-health-adds-epic-integration-for-clinicians-to-import-patient-data/)
- [Fierce Healthcare - ChatGPT Healthcare Unveils New Integrations, Epic EHR, Public Health Data](https://www.fiercehealthcare.com/ai-and-machine-learning/chatgpt-healthcare-unveils-new-integrations-epic-ehr-public-health-data)
- [TechCrunch - Palo Alto Networks Paid $500M for Thrive-Backed Console](https://techcrunch.com/2026/09/02/palo-alto-networks-paid-500m-for-thrive-backed-console-sources-say/)
- [SecurityWeek - Palo Alto Networks Acquires AI Agent Platform Console](https://www.securityweek.com/palo-alto-networks-acquires-ai-agent-platform-console/)

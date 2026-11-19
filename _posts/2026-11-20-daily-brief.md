---
layout: post
title: "AI 데일리 브리핑 — 11월 20일: 美, 제3국 데이터센터 통한 中 AI칩 '원격접속' 우회 차단"
date: 2026-11-20 07:00:00 +0900
categories: daily
---

미 상무부가 중국 등 우려국이 동남아·중남미 제3국 데이터센터를 거쳐 미국산 AI칩 연산력에 접근하는 경로를 막는 새 수출통제 규칙을 발표했습니다. 같은 주 마이크로소프트는 이그나이트 2026에서 자체 'MAI' 모델 7종을 한꺼번에 공개하며 코딩·보안 영역까지 자체 모델로 채우는 전략을 한 단계 더 밀고 나갔습니다. 이 외에도 구글이 '제미나이 태스크'를 한국 포함 6개국에 무료로 열었고, 알파벳 산하 아이소모픽랩스가 50억달러 시리즈C를 마무리했으며, 구글 딥마인드는 세포별 DNA 변이 예측 모델 '알파게놈 2'를 내놓았습니다. 오늘 딥다이브에서는 미국의 AI칩 원격접속 차단 규칙이 국내 클라우드·데이터센터 사업자에 어떤 영향을 줄 수 있는지 살펴봅니다.

## 오늘의 헤드라인

### 1. 美 상무부, 해외 데이터센터 통한 中 AI칩 '원격접속' 우회 차단 규칙 발표
미 상무부 산업안보국(BIS)이 11월 16일 "Addressing Remote Access to Advanced Semiconductors"라는 잠정 최종 규칙을 발표했습니다. 중국 등 우려국 기업이 싱가포르·말레이시아·태국·인도네시아·브라질 등 제3국 데이터센터를 거쳐 약 1200만 TPP(총처리성능, 반도체 연산력을 가늠하는 지표) 이상의 미국산 AI칩 연산력을 쓰려면 미국 정부의 사전 허가가 필요해졌습니다.

이번 조치로 바이든 행정부 시절 만들어졌던 'AI 확산규칙'은 공식 폐지됐고, 그 대신 해외 클라우드·데이터센터 사업자들은 최종 사용자가 누구인지까지 확인하는 KYC(고객확인) 의무를 새로 지게 됩니다. 미국산 AI칩이 직접 수출되지 않아도 해외 서버를 임대해 원격으로 쓰는 방식으로는 우회할 수 없도록 통제 범위를 넓힌 조치입니다.

### 2. 마이크로소프트 이그나이트 2026, 자체 MAI 모델 7종 공개—코파일럿·보안까지 전면 확장
마이크로소프트가 11월 17일 이그나이트 2026에서 코딩·보안·이미지·음성 등을 아우르는 자체 'MAI' 모델 7종(MAI Code 2·Code 2 Flash, Cyber 2 Flash 등)을 발표했습니다. 사티아 나델라 CEO는 Cyber 2 Flash를 "가장 강력한 보안 모델"이라 칭하며, GPT-6 아스트라와 동급 품질을 2% 미만의 비용으로 낸다고 주장했습니다.

Code 2·Code 2 Flash는 깃허브 코파일럿과 애저 AI 파운드리에 즉시 정식 적용됐습니다. 오픈AI·구글·앤스로픽에 대한 모델 의존도를 낮추려는 마이크로소프트의 자체 모델 전략이 코딩과 보안이라는 핵심 업무 영역까지 확장된 사례입니다.

### 3. 구글 '제미나이 태스크' 무료 전환—한국 포함 6개국, 하이드로젠 모델 탑재
구글이 11월 17일 '제미나이 태스크' 기능을 미국·일본·한국·캐나다·호주·인도 등 6개국 일반 이용자에게 무료로 확대했습니다. 신규 '하이드로젠' 모델을 기반으로 장기 프로젝트나 반복 작업을 백그라운드에서 대신 처리하며, 구글페이와 연동한 쇼핑·재고알림 기능도 지원합니다(결제는 사용자 승인이 필요합니다). 전화·문자 등 실세계 액션 기능은 아직 미국에 우선 적용됐고, EEA·영국·스위스·나이지리아는 이번 확대 대상에서 제외됐습니다.

### 4. 아이소모픽랩스, 50억달러 시리즈C 완료—5개월 만에 2.4배 몸값
알파벳 산하 AI 신약개발 기업 아이소모픽랩스가 11월 17일 세쿼이아캐피털·그린오크스 공동 주도로 50억달러 규모 시리즈C를 마무리했다고 발표했습니다. a16z가 신규 투자자로 합류했고, 스라이브캐피털·MGX·테마섹·영국 소버린AI펀드 등 기존 투자자도 재참여했습니다. 지난 5월 21억달러 시리즈B 대비 약 5개월 만에 몸값이 뛴 셈으로, 조달 자금은 신약 후보물질의 임상 진입과 컴퓨팅 인프라 확충에 쓰입니다.

### 5. 구글 딥마인드, 세포별 DNA 변이 예측 모델 '알파게놈 2' 공개
딥마인드가 11월 11일 차세대 유전체 AI '알파게놈 2'를 발표했습니다. 기존 알파게놈이 여러 조직의 분자활동을 평균적으로 예측했던 것과 달리, 알파게놈 2는 특정 세포 유형·상태를 조건으로 입력해 유전자 발현을 바꾸는 변이를 기존 최고 모델 대비 약 2배 더 많이 찾아냅니다. 1억 개 이상의 단일세포·벌크 프로필(68개 조직)로 학습했으며, 학술 연구용은 API로 무료 공개하고 상업적 이용은 비공개 프리뷰로 제한했습니다.

## 오늘의 딥다이브: 美 AI칩 '원격접속' 차단 규칙이 국내 클라우드 사업자에 던지는 과제

미 상무부가 11월 16일 발표한 "Addressing Remote Access to Advanced Semiconductors" 규칙은 수출통제의 초점을 '칩이 어디로 가는가'에서 '칩의 연산력을 누가 원격으로 쓰는가'로 옮긴 조치입니다. 중국 등 우려국 기업이 자국에 미국산 AI칩을 직접 들여오지 못하더라도, 싱가포르·말레이시아·태국·인도네시아·브라질 같은 제3국에 세운 데이터센터를 거쳐 클라우드로 접속해 미국산 칩의 연산력을 빌려 쓰는 경로가 실제로 존재했기 때문입니다. 이번 규칙은 이런 간접 접근을 약 1200만 TPP(총처리성능) 이상 규모부터 미국 정부 허가 대상으로 규정했습니다.

이 조치가 나오기 전까지 수출통제의 기준이었던 바이든 행정부의 'AI 확산규칙'은 이번 조치로 공식 폐지됐습니다. 확산규칙은 국가를 등급별로 나눠 AI칩 수출을 차등 허용하는 방식이었는데, 트럼프 행정부는 이를 폐지하면서도 제3국을 통한 우회 접근이라는 더 구체적인 허점을 겨냥한 새 규칙으로 대체한 셈입니다. 즉 통제의 틀 자체는 느슨해졌지만, 우회 경로를 메우는 방식은 더 정교해졌다고 볼 수 있습니다.

이번 규칙에서 특히 눈여겨볼 대목은 해외 클라우드·데이터센터 사업자에게 부과되는 KYC(고객확인) 의무입니다. 이제 해외에서 미국산 AI칩 기반 서버를 운영하는 사업자는 자사 서비스를 이용하는 고객이 최종적으로 누구인지, 어느 국가 소속인지까지 확인해야 합니다. 이는 단순히 미국 기업만의 문제가 아니라, 미국산 칩을 들여와 서버를 운용하는 전 세계 클라우드·데이터센터 사업자 전반에 실사 부담을 지우는 조치입니다. 국내에서 미국산 AI칩을 기반으로 클라우드·데이터센터 서비스를 운영하는 사업자 역시 고객 신원과 최종 사용 목적을 확인하는 절차를 새로 갖춰야 할 가능성이 있습니다.

이번 조치는 한미 반도체 공급망에도 변수로 작용할 수 있습니다. 한국은 미국산 AI칩을 활용한 데이터센터 투자와 클라우드 서비스 확장이 활발히 진행되고 있는 시장이기 때문에, 원격접속 규제의 세부 집행 기준이 어떻게 구체화되느냐에 따라 국내 사업자들의 서비스 설계나 해외 고객 유치 전략에 직접 영향을 줄 수 있습니다. 다만 이번 규칙이 구체적으로 어떤 절차와 서류를 요구하는지, 한국이 규제 대상국이 아닌 '허용국'으로 분류돼 있는지 등 세부 내용은 아직 공개된 보도만으로는 전부 확인되지 않았습니다.

앞으로 지켜볼 지점은 두 가지입니다. 첫째, 1200만 TPP라는 기준선이 실제 데이터센터 운영 규모에서 얼마나 자주 발동되는 수준인지, 둘째, 싱가포르·말레이시아·태국 등 이번 규칙에서 거론된 국가들이 실제로 어떤 식으로 미국 정부에 협조하거나 반발하는지입니다. 이 규칙이 단순한 선언적 조치에 머물지, 실제로 중국의 AI 연산력 확보 경로를 눈에 띄게 좁히는 효과를 낼지는 집행 과정에서 드러날 것으로 보입니다.

## 소스
- [TechRepublic — US AI chip cloud access restrictions](https://www.techrepublic.com/article/news-us-ai-chip-cloud-access-restrictions/)
- [Unite.AI — BIS releases rule targeting remote access to advanced AI chips](https://unite.ai/bis-releases-rule-targeting-remote-access-to-advanced-ai-chips)
- [South China Morning Post — US tightens AI chip export curbs to close China's overseas data centre loophole](https://www.scmp.com/tech/article/3374639/us-tightens-ai-chip-export-curbs-close-chinas-overseas-data-centre-loophole)
- [Boston Globe — Trump administration moves to block China's indirect access to American AI technology](https://www.bostonglobe.com/2026/11/16/nation/trump-block-china-indirect-access-american-ai-technology/)
- [Thurrott — Microsoft announces seven new MAI models at Ignite 2026](https://www.thurrott.com/?p=343999)
- [TestingCatalog — Microsoft launches seven MAI models at Ignite 2026](https://www.testingcatalog.com/microsoft-launches-seven-mai-models-at-ignite-2026/)
- [Scalevise — Microsoft Ignite 2026 MAI model lineup](https://scalevise.com/resources/microsoft-ignite-2026-mai-model-lineup/)
- [Crypto Briefing — Google Gemini Tasks free in six countries](https://cryptobriefing.com/google-gemini-free-tasks-six-countries/)
- [DataStudios — Gemini Tasks free six countries, calls, pay bills, Google Pay, Instacart](https://www.datastudios.org/post/gemini-tasks-free-six-countries-calls-pay-bills-google-pay-instacart)
- [9to5Google — Gemini Tasks expansion](https://9to5google.com/?p=738124)
- [The Next Web — Isomorphic Labs $5bn Series C led by Sequoia, Greenoaks](https://thenextweb.com/news/isomorphic-labs-5bn-series-c-sequoia-greenoaks)
- [Tech.eu — Sequoia and Greenoaks lead massive $5bn Series C funding round in Isomorphic Labs](https://tech.eu/2026/11/17/sequoia-and-greenoaks-lead-massive-5bn-series-c-funding-round-in-isomorphic-labs/)
- [Fierce Biotech — Isomorphic Labs raises $5B Series C months after $2.1B round](https://www.fiercebiotech.com/biotech/isomorphic-labs-raises-5b-series-c-months-after-21b-round)
- [Google DeepMind — AlphaGenome 2: deciphering how cells read DNA to better understand disease](https://deepmind.google/blog/alphagenome-2-deciphering-how-cells-read-dna-to-better-understand-disease/)
- [TechRepublic — Google DeepMind AlphaGenome 2 genetic variants](https://www.techrepublic.com/article/news-google-deepmind-alphagenome-2-genetic-variants/)
- [YourStory — Google DeepMind unveils AlphaGenome 2 to study DNA changes](https://yourstory.com/ai-story/google-deepmind-unveils-alphagenome-2-to-study-dna-changes)

---
layout: post
title: "AI 데일리 브리핑 — 11월 28일: 구글 TPU, 메타 10만 개 대량구매 검토로 엔비디아 아성 흔드나"
date: 2026-11-28 07:00:00 +0900
categories: daily
---

오늘 브리핑의 가장 큰 뉴스는 구글의 자체 AI 반도체 TPU(Tensor Processing Unit, 구글이 자체 설계한 AI 연산 전용 칩) 외부 판매 공세입니다. 메타가 TPU 약 10만 개 구매를 검토 중이라는 보도가 나오면서 엔비디아 중심의 AI 칩 시장 구도에 변화 조짐이 보입니다. 이와 함께 지난주 보도된 엔비디아 차기 CEO 후보군이 구체화됐고, 싱가포르 메가스피드의 AI칩 우회수출 의혹에는 말레이시아 정부까지 자체 조사에 착수했습니다. 미국에서는 블랙프라이데이를 맞아 AI 추천 쇼핑이 본격적인 시험대에 올랐습니다.

## 오늘의 헤드라인

### 1. 구글, TPU 외부 판매 공세 — 메타 10만 개 대량구매 검토·미즈호 매출 전망 급상승

구글이 올해 들어 AI 반도체 4종을 잇따라 선보이며 엔비디아 고객사를 겨냥한 TPU 외부 판매를 가속하고 있습니다. 메타가 자체 데이터센터용으로 구글 TPU 약 10만 개(수십억 달러 규모) 구매를 검토 중이라는 보도가 나왔고, 투자은행 미즈호는 구글 TPU 매출이 2026년 280억 달러에서 2027년 670억 달러로 늘어날 것으로 전망했습니다.

이미 앤스로픽은 증권신고서(S-1)에서 구글과의 장기 컴퓨팅 계약(2026년 4월~2033년 7월, 최소 약 1145억 달러)을 공개했는데, 여기에도 TPU 물량이 포함돼 있습니다. 다만 분석가들은 TPU가 초거대 모델보다는 상대적으로 가벼운 워크로드(연산 작업)에 적합해 엔비디아와의 직접 경쟁에는 한계가 있다는 반론도 제기하고 있습니다. 이 사안은 오늘 딥다이브에서 더 자세히 다룹니다.

### 2. [후속] 엔비디아 차기 CEO 후보군 구체화 — 이언 벅·리사 수·르네 하스 등 11명 거론

지난 11/26 브리핑에서 다룬 '엔비디아 리더십 위기'(젠슨 황 사임, 11/11~12)의 후속 전개입니다. 엔비디아 이사회가 외부 헤드헌팅 업체와 함께 영구 CEO를 물색 중인 가운데, 내부 후보로 이언 벅 부사장, 외부 후보로 AMD 리사 수, Arm 르네 하스, 애플 조니 스루지, 마이크론 산제이 메흐로트라 등 총 11명이 거론된다는 보도가 나왔습니다.

트럼프 대통령은 팀 쿡 전 애플 CEO를 공개 추천한 것으로 보도됐습니다. 한편 예측시장 폴리마켓에서는 연내(2026년 말까지) 신임 CEO 선임 확률이 11/13 기준 45%에서 18.5%로 하락했습니다. 현재는 콜레트 크레스 CFO가 임시 CEO를 겸직하고 있어, 후보군이 구체화된 것과 별개로 실제 선임까지는 시간이 걸릴 가능성이 커진 셈입니다.

### 3. AMD, 인스팅트 MI400 시리즈 라인업 확장 — 엔비디아 루빈 대비 추론 30% 우위 자체 주장

AMD가 11월 12일 MI430X 기술 업데이트와 MI455X 추론 성능 결과를 공개하고 신규 모델 MI450X를 추가해 MI400 패밀리를 메모리·정밀도 기준 3종 체계로 재편했습니다. AMD는 자체 측정 기준 MI455X가 DeepSeek-R1 추론에서 GPU당 초당 21,333토큰을 기록, 엔비디아 Vera Rubin NVL72(MLPerf v6.1 기준) 대비 약 30% 빠르다고 주장했습니다.

다만 이는 AMD 자체 성능연구소 측정치로 독립 검증은 아직 이뤄지지 않았습니다. 엔비디아 Vera Rubin의 본격 양산도 비슷한 시점에 겹치면서, 4분기부터 2027년까지 두 회사의 정면 경쟁이 예상됩니다.

### 4. [후속] 메가스피드 AI칩 우회수출 의혹 — 말레이시아도 자체 조사 착수

지난 11/27 브리핑에서 다룬 메가스피드(Megaspeed) 우회수출 의혹의 국가별 후속 전개입니다. 싱가포르 메가스피드의 말레이시아 현지법인 스피드매트릭스(Speedmatrix)를 둘러싼 AI칩 재수출 의혹에 말레이시아 통상산업부(MITI)와 경찰도 자체 조사에 들어갔습니다. 말레이시아 경찰은 2025년 4월부터 AI칩 환적(배를 갈아타듯 화물을 옮겨 싣는 방식) 의혹을 수사해왔다고 밝혔고, MITI는 메가스피드·스피드매트릭스에 어떤 '승인'도 내준 적이 없다고 반박했습니다.

안와르 이브라힘 총리는 엔비디아 AI칩이 메가스피드를 거쳐 제3국으로 재수출됐다는 증거를 아직 발견하지 못했다고 밝혔습니다. 말레이시아는 AI칩 수입 자체에는 허가가 필요 없지만, 2025년 7월부터 미국산 고성능 AI칩의 수출·재수출·환적에는 전략물자거래법상 허가가 필요합니다.

### 5. 美 블랙프라이데이 2026, 'AI 에이전트 쇼핑' 본격 시험대 — 온라인 소비 역대 최대 전망

오늘(11/27)은 미국 블랙프라이데이로, 어도비는 올해 미국 온라인 홀리데이 소비가 2751억 달러(전년 대비 6.7% 증가)로 역대 최대를 기록할 것으로 전망했습니다. 어도비는 블랙프라이데이 당일 AI 추천 트래픽이 전년 대비 95% 늘 것으로 예측했고(추수감사절은 159%), AI 추천을 통해 유입된 방문자의 구매 전환당 가치가 일반 방문자보다 83% 높다고 분석했습니다.

구글은 10/15 여러 쇼핑몰 상품을 한 장바구니에 모으는 '유니버설 카트'(미국 등 일부 국가에서 결제 지원)를 선보였지만, 아마존은 외부 AI 에이전트의 직접 구매를 계속 차단하고 있습니다. 플랫폼별로 AI 쇼핑 에이전트에 대한 대응이 엇갈리고 있는 셈입니다.

## 오늘의 딥다이브: 구글 TPU, 엔비디아 중심 AI 칩 시장 구도를 흔들다

구글이 자체 설계한 AI 반도체 TPU를 외부에 공격적으로 판매하려는 움직임이 올해 들어 뚜렷해지고 있습니다. 구글은 올해 들어 AI 반도체 4종을 잇따라 내놓으며 하드웨어 라인업을 빠르게 넓혔고, 이는 엔비디아가 압도적으로 장악해온 AI 가속기 시장에 구글이 본격적으로 발을 들여놓았다는 신호로 읽힙니다.

가장 눈에 띄는 대목은 메타가 자체 데이터센터용으로 구글 TPU 약 10만 개, 수십억 달러 규모의 구매를 검토 중이라는 보도입니다. 메타는 지금까지 엔비디아 GPU를 대규모로 사들여온 대표적 고객사였기 때문에, 이 보도가 사실로 확인된다면 엔비디아의 최대 고객군 중 한 곳이 공급처를 다변화하기 시작했다는 의미를 갖습니다. 투자은행 미즈호는 이런 흐름을 반영해 구글 TPU 매출이 2026년 280억 달러에서 2027년에는 670억 달러로 2배 이상 늘어날 것으로 전망했습니다.

이런 전망에는 이미 현실화된 선례가 있습니다. 앤스로픽이 증권신고서(S-1)에서 공개한 구글과의 장기 컴퓨팅 계약은 2026년 4월부터 2033년 7월까지 최소 약 1145억 달러 규모인데, 여기에 TPU 물량이 포함돼 있습니다. 즉 TPU 외부 판매는 메타 건이 처음이 아니라, 이미 대형 AI 기업과의 다년 계약 형태로 진행되고 있던 흐름이 메타라는 또 다른 초대형 고객으로 확산되는 모습입니다.

다만 모든 분석가가 TPU를 엔비디아의 직접적 위협으로 보는 것은 아닙니다. TPU는 초거대 모델 훈련보다는 상대적으로 가벼운 연산 작업(워크로드)에 적합하다는 평가가 있어, 엔비디아가 주력으로 삼는 최상위 훈련·추론 시장과는 역할이 다소 다르다는 반론이 제기됩니다. 즉 TPU 확산이 곧바로 엔비디아의 시장 점유율 하락으로 이어진다고 단정하기는 아직 이릅니다.

그럼에도 이번 흐름이 주목받는 이유는 시점입니다. 엔비디아는 젠슨 황 사임 이후 영구 CEO를 아직 선임하지 못한 리더십 공백 상태에 있고, AMD도 MI400 시리즈를 확장하며 성능 우위를 주장하는 등 경쟁사들의 공세가 동시에 이어지고 있습니다. 공급망 다변화를 원하는 대형 AI 기업들의 선택지가 TPU, AMD 인스팅트 등으로 넓어지는 가운데, 엔비디아가 이런 다각적 압박 속에서 시장 지배력을 어떻게 유지할지가 다음 단계의 관전 포인트입니다.

앞으로는 메타의 실제 구매 확정 여부, 구글의 추가 TPU 세대 공개 일정, 그리고 엔비디아 차기 CEO 선임 이후 전략 방향이 이 구도의 향방을 가를 변수가 될 것으로 보입니다.

## 소스
- [뉴스토마토](https://newstomato.com/ReadNews.aspx?no=1319860)
- [Business Insider Japan](https://www.businessinsider.jp/article/2611-news-google-is-turning-its-secret-ai-weapon-into-an-nvidia-problem/)
- [CIO.com](https://www.cio.com/article/4107487/메타-대규모-구매설까지구글-tpu가-촉발한-ai-칩-시장.html)
- [AMD Newsroom](https://newsroom.amd.com/news/aai-2026-mi400-instinct-update/)
- [iTWire](https://itwire.com/business-it-news/data/spectacular-strategic-supremely-timed-amd-s-mi-series-delivers-widened-instinct-mi400-with-the-mi450x-as-mi455x-claims-a-30-inference-lead-over-nvidias-vera-rubin)
- [Axios](https://www.axios.com/2026/11/12/nvidia-next-ceo-jensen-huang-predictions)
- [Fortune](https://fortune.com/2026/11/12/nvidia-next-ceo-the-outside-contenders-to-succeed-jensen-huang/)
- [South China Morning Post](https://www.scmp.com/news/china/diplomacy/article/3374268/nvidias-hunt-jensen-huangs-successor-insiders-rivals-and-trump-pick)
- [The Standard](https://www.thestandard.com.hk/world/article/348415/Malaysia-says-probing-Megaspeed-subsidiary-over-possible-AI-chip-diversion)
- [New Straits Times](https://www.nst.com.my/amp/news/nation/2026/11/1577549/police-have-investigated-suspected-ai-chip-transshipment-april-2025)
- [New Straits Times](https://www.nst.com.my/amp/business/corporate/2026/11/1576692/miti-no-clearance-granted-megaspeed-speedmatrix)
- [Adobe Newsroom](https://news.adobe.com/news/2026/09/adobe-us-holiday-shopping-season-to-hit-record)
- [Retail TouchPoints](https://www.retailtouchpoints.com/news/adobe-forecasts-record-275.1-billion-in-u.s.-holiday-online-sales/621583/)
- [CX Network](https://www.cxnetwork.com/cx-experience/articles/agentic-commerce-retail-golden-quarter-black-friday)

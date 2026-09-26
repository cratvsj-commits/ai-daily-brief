---
layout: post
title: "AI 데일리 브리핑 — 9월 27일: 앤스로픽, 아카마이와 7년 116억달러 클라우드 계약 체결"
date: 2026-09-27 07:00:00 +0900
categories: daily
---

앤스로픽이 아카마이와 7년간 최대 200억달러 규모의 클라우드 인프라 계약을 맺으면서, 인프라 공급계약에 지분 참여를 결합하는 빅테크-AI랩 거래 패턴이 클라우드 업계 전반으로 번지고 있습니다. 마이크로소프트는 코파일럿을 홈·코드·오토파일럿 3축으로 재편해 상시가동 에이전트 시대를 예고했고, 삼성전자는 엔비디아 HBM4 인증을 앞두고 SK하이닉스 단독공급 구도에 균열을 낼 채비를 하고 있습니다. 이 외에 구글의 실시간 영상 에이전트 정식 출시와 깃허브 코파일럿의 로컬 샌드박싱 도입 소식도 눈에 띕니다.

## 오늘의 헤드라인

### 1. 앤스로픽-아카마이, 7년 116억달러 클라우드 계약 체결
아카마이가 앤스로픽과 7년간 116억달러(옵션 행사 시 최대 200억달러) 규모의 클라우드 인프라 공급계약을 체결했다고 발표했습니다. 계약에는 앤스로픽이 아카마이 보통주로 전환 가능한 우선주 신주인수권(최대 지분 약 5%)을 받는 구조가 포함돼 있습니다.

단순한 매출 계약을 넘어 공급사가 고객에게 지분을 내주는 형태는 최근 빅테크와 AI랩 사이에서 반복적으로 나타나던 패턴인데, 이번 계약으로 그 흐름이 클라우드 업계 전반으로 확산되는 모습을 보여줍니다. 발표 직후 아카마이 주가는 15% 급등했습니다.

### 2. MS, 코파일럿 전면 개편 — 상시가동 에이전트 '오토파일럿' 도입
마이크로소프트가 코파일럿을 홈(채팅·코워크)·코드(자연어로 앱을 만드는 기능)·오토파일럿 3축으로 전면 재편했다고 발표했습니다. 오토파일럿은 소유자가 이름·역할·목표를 부여하면 사람 개입 없이 지속적으로 작업을 수행하는 상시가동 에이전트로, 이달 말 비공개 프리뷰로 시작됩니다.

사티아 나델라 CEO는 이를 "모든 모델·기기·업무를 아우르는 일의 새 OS"로 규정했습니다. 앤스로픽의 클로드 코워크, 구글의 제미나이 엔터프라이즈와 경쟁하는 에이전트 플랫폼 시장이 한층 격화되는 신호로 읽힙니다.

### 3. 삼성전자, 엔비디아 HBM4 인증 임박 — SK하이닉스 단독공급 구도 흔들리나
삼성전자가 이달 엔비디아에 HBM4(고대역폭 메모리 4세대, AI 가속기에 필수적인 초고속 메모리 규격) 엔지니어링 샘플을 전달했고, 품질 인증 통과 여부가 9월 중 결정될 예정입니다.

인증이 통과되면 그간 SK하이닉스가 사실상 독점해온 엔비디아 HBM4 공급망에 삼성전자가 이르면 2027년 2분기부터 진입할 수 있습니다. AI 메모리 수요 급증 속에서 국내 반도체 업계의 수출·증설 경쟁과 직결되는 소식입니다.

### 4. 구글, '제미나이 3.8 라이브 + 라이브 아바타' 정식 출시
구글이 근실시간 영상 생성과 음성 대화를 결합한 '라이브 아바타'를 제미나이 3.8 라이브에 탑재해 제미나이 엔터프라이즈에 정식 출시했습니다. 97개 언어 간 전환에도 립싱크와 표정을 실시간으로 맞추며, 대화 중에도 비동기로 도구 호출과 데이터 조회가 가능합니다.

생성된 영상과 음성에는 신원 오남용을 막기 위해 신스ID(SynthID) 워터마크가 삽입됩니다.

### 5. 깃허브 코파일럿, '로컬 샌드박싱' 공개 프리뷰 도입
깃허브가 코파일럿 앱에 '로컬 샌드박싱' 기능을 공개 프리뷰로 추가했습니다. 프로젝트 단위로 파일시스템 읽기·쓰기, 읽기전용, 차단 폴더 설정과 아웃바운드 네트워크, 깃/깃허브 CLI 자격증명 접근을 세밀하게 제어할 수 있으며 기본값은 꺼짐입니다.

최근 코딩 에이전트발 샌드박스 탈출과 자격증명 유출 사고가 잇따른 가운데, 에이전트 실행 안전장치를 표준 기능으로 편입하는 흐름을 보여줍니다.

## 오늘의 딥다이브: 앤스로픽-아카마이 계약과 "인프라+지분" 거래 패턴

아카마이가 발표한 앤스로픽과의 계약은 규모부터 눈길을 끕니다. 7년간 기본 116억달러, 옵션 행사 시 최대 200억달러에 이르는 클라우드 인프라 공급계약으로, 아카마이 입장에서는 사실상 회사의 미래 매출 상당 부분을 하나의 고객에게 걸어둔 셈입니다. 발표 직후 주가가 15% 뛴 것은 시장이 이 계약을 아카마이의 사업 방향 전환으로 받아들였다는 의미로 볼 수 있습니다.

주목할 부분은 계약 구조입니다. 앤스로픽은 단순히 서비스를 사는 고객이 아니라, 아카마이 보통주로 전환 가능한 우선주 신주인수권을 받아 최대 약 5%의 지분을 확보하게 됩니다. 공급사가 대형 고객에게 지분을 내주는 이런 형태는 이미 빅테크와 AI랩 사이에서 여러 차례 확인된 패턴입니다. 이번 계약이 눈에 띄는 이유는 그 대상이 하이퍼스케일러(대형 클라우드 사업자)가 아니라 콘텐츠 전송·보안 인프라 회사인 아카마이라는 점입니다.

이는 AI랩들이 컴퓨팅 자원 확보처를 다변화하고 있다는 신호로 해석할 수 있습니다. 앤스로픽 입장에서는 특정 하이퍼스케일러에 대한 의존도를 낮추면서 추론·훈련에 필요한 인프라를 안정적으로 확보하는 동시에, 계약 상대 회사의 지분까지 얻어 향후 주가 상승분을 챙길 수 있는 이중의 이득을 노린 것으로 보입니다. 아카마이 쪽에서는 AI 인프라 공급이라는 새로운 대형 수익원을 확보했다는 의미가 있습니다.

다만 이런 "인프라+지분" 결합 계약이 늘어날수록 AI랩과 인프라 공급사 간의 상호 얽힘도 커집니다. 계약 상대의 주가가 자사 재무제표에 영향을 미치고, 반대로 AI랩의 성장 여부가 공급사의 기업가치를 좌우하는 구조가 만들어지는 것입니다. 이런 순환출자적 성격의 거래가 늘어나면 AI 산업 전반의 리스크가 몇몇 핵심 관계에 집중될 수 있다는 우려도 함께 제기될 수 있는 대목입니다.

앞으로 관전 포인트는 두 가지입니다. 하나는 이 계약이 실제로 아카마이의 사업 구조를 얼마나 바꿔놓을지이고, 다른 하나는 다른 클라우드·인프라 기업들도 비슷한 구조의 계약을 AI랩들과 맺어나갈지 여부입니다. 마이크로소프트의 코파일럿 오토파일럿 도입이나 구글의 제미나이 엔터프라이즈 확장처럼 AI 에이전트 수요가 계속 늘어나는 만큼, 그 수요를 뒷받침할 컴퓨팅 인프라를 둘러싼 계약 형태도 당분간 이런 방향으로 진화할 가능성이 높아 보입니다.

## 소스
- [TechCrunch - Anthropic to pay Akamai $11.6 billion over seven years in cloud deal](https://techcrunch.com/2026/09/25/anthropic-to-pay-akamai-11-6-billion-over-seven-years-in-cloud-deal/)
- [Akamai Newsroom - Akamai Announces $11.6 Billion Multi-Year Agreement with Anthropic](https://www.akamai.com/newsroom/press-release/akamai-announces-11-6-billion-multi-year-agreement-with-anthropic-to-support-growing-demand)
- [Microsoft Blog - Introducing the new Copilot with Home, Code, and Autopilot](https://blogs.microsoft.com/blog/2026/09/25/introducing-the-new-copilot-with-home-code-and-autopilot/)
- [Fortune - Microsoft unveils Copilot super app targeting business users with AI agents](https://fortune.com/2026/09/25/microsoft-unveils-copilot-super-app-targeting-business-users-with-ai-agents/)
- [Google Blog - Gemini 3.8 Live with Live Avatar](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-live-with-live-avatar/)
- [Google Cloud Blog - Gemini 3.8 Live with Live Avatar is now generally available](https://cloud.google.com/blog/products/ai-machine-learning/gemini-3-8-live-with-live-avatar-is-now-generally-available)
- [GitHub Changelog - Local sandboxing in the GitHub Copilot app](https://github.blog/changelog/2026-09-23-local-sandboxing-in-the-github-copilot-app/)
- [GitHub Docs - Configure local sandboxing](https://docs.github.com/en/copilot/how-tos/github-copilot-app/configure-local-sandboxing)
- [zod.kr - 삼성전자 엔비디아 HBM4 인증 관련 보도](https://zod.kr/news/6733330)
- [G-eNews - 삼성전자 HBM4 공급망 진입 관련 보도](https://www.g-enews.com/article/Global-Biz/2026/09/202609220549544379fbbec65dfb_1)

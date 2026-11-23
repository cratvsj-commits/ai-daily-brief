---
layout: post
title: "AI 데일리 브리핑 — 11월 24일: FBI, 자율 해킹 AI 프레임워크 'ARTEX' 악용 경고"
date: 2026-11-24 07:00:00 +0900
categories: daily
---

FBI가 침투테스트용 AI 프레임워크 'ARTEX'가 범죄조직과 국가 연계 해커들의 자율 해킹 도구로 악용되고 있다고 경고했습니다. AI 코딩 툴 커서(Cursor)는 지난달 발생한 공급망 보안사고의 원인이 외부 AI 인프라 업체 침해였다고 세부 내용을 공개했습니다. 구글 딥마인드는 로봇 전용 모델 '제미나이 로보틱스 2.5'를 선보였고, 통신·전력업계에서는 SKT와 효성중공업이 AI데이터센터용 전력설비 공급을 위한 협력에 나섰습니다. 음악 업계에서는 엘비스 프레슬리 재단과 에미넴 측이 AI 음악생성 서비스 수노를 상대로 저작권 소송을 제기했습니다.

## 오늘의 헤드라인

### 1. FBI, AI 자율해킹 프레임워크 'ARTEX' 악용 전 세계 경고

FBI가 11월 13일 플래시 경보를 통해 공개 침투테스트용 AI 프레임워크 'ARTEX'가 범죄조직과 국가 연계 해커들에 의해 자율 해킹 도구로 악용되고 있다고 경고했습니다. ARTEX는 외부 거대언어모델(LLM)과 연동해 정찰, 취약점 탐색, 침투, 권한상승, 데이터 탈취를 사람의 개입 없이 수행하는 도구로, 최소 8월부터 금융·정부·의료·국방·에너지 등 분야를 노려왔습니다.

원본 깃허브 저장소는 10월에 삭제됐지만 커뮤니티가 만든 복제판과 상용판 'ARTEX PRO'로 계속 확산되고 있으며, 11월 초 기준 외부에 노출된 관리 콘솔이 1600개 이상 확인됐습니다. 마이크로소프트는 10월 발생한 커넥트와이즈 공급망 침해 사고를 중국 연계 조직의 ARTEX 사용과 연결했고, AWS 위협 인텔리전스 팀은 탈취한 AI API 키를 다시 공격에 투입하는 별도 캠페인도 포착했습니다. 사람이 직접 개입하지 않아도 공격 전 과정이 자동으로 돌아가는 '에이전틱 AI'가 실제 공격에 쓰이는 사례라는 점에서 보안 업계가 주시하고 있습니다.

### 2. 커서, 'Claude Code' 확장판 공급망 보안사고 세부 공개

AI 코딩 툴 커서가 11월 13일 보안사고 업데이트를 내고, 10월 29일 발생한 사고의 원인이 외부 AI 인프라 업체 파이어웍스(Fireworks)의 침해였다고 밝혔습니다. 공격자가 파이어웍스에 발급된 접근키를 탈취해 코딩 에이전트의 트레이싱(작업 기록) 데이터 일부를 복사했고, 변질된 Claude Code 확장판이 약 11시간 동안 커서 마켓플레이스 캐시에 노출됐습니다.

커서 측은 프라이버시 모드를 쓰지 않은 사용자 중 0.05% 미만이 영향을 받았으며, 11월 1일 이후로는 공격자 활동이 차단됐다고 설명했습니다. 이번 사고는 AI 코딩 도구가 외부 AI 인프라 업체에 의존하는 구조에서 발생할 수 있는 서드파티(제3자) 공급망 리스크를 보여주는 사례입니다.

### 3. 구글 딥마인드, 로봇 전용 모델 '제미나이 로보틱스 2.5' 공개

구글 딥마인드가 11월 10일 비전-언어-행동(VLA, 영상·언어·동작을 동시에 처리하는) 모델 최신판 '제미나이 로보틱스 2.5'를 발표했습니다. 200개 이상의 개별 작업으로 테스트한 결과 섬세한 물체 취급, 집게로 음식 서빙, 선물 리본 묶기 등에서 기존 모델 대비 20~30% 빠른 과제 수행을 보였다고 회사 측은 밝혔습니다. 메르세데스-벤츠 공장 실증에서는 96% 성공률을 기록했다는 보도도 있습니다.

일반 API나 모델 가중치 공개 없이 어질 로보틱스, 앱트로닉, 보스턴다이내믹스 등 로봇 파트너사에만 우선 제공되며, 로봇이 위험한 지시에 설득되는지를 측정하는 오픈소스 안전 벤치마크 'ASIMOV-Jailbreak'도 함께 공개됐습니다.

### 4. 엘비스 프레슬리·에미넴 측, AI 음악 생성 '수노' 상대 저작권 소송

엘비스 프레슬리 재단과 에미넴의 퍼블리셔 에잇마일스타일이 11월 6일 캘리포니아 북부지법에 AI 음악생성 서비스 수노(Suno)를 상대로 각각 소송을 제기했습니다. 프레슬리 측은 테네시주의 '엘비스법'(ELVIS Act)을 근거로, 수노가 859곡을 무단으로 학습했고 이용자가 엘비스의 목소리를 복제한 신곡을 생성할 수 있게 했다며 저작권과 초상권 침해를 주장했습니다. 수노 출력물에서 엘비스의 음성과 초상이 쓰인 사례를 최소 38건 확인했다고도 밝혔습니다.

청구액은 보도마다 5000만~2억200만달러로 엇갈리며, 에잇마일스타일 측 청구액은 약 4770만달러로 별도 보도됐습니다. AI 음성 복제 문제에 주(州) 단위 법이 적용된 사례로 주목받고 있습니다.

### 5. SKT-효성중공업, GW급 AI데이터센터 전력설비 공급 MOU

SK텔레콤과 효성중공업이 11월 16일 서울 SKT타워에서 AI데이터센터용 345kV 변전소 핵심 전력설비 공급을 위한 전략적 파트너십 MOU를 맺었습니다. 전력설비는 생산부터 납품까지 장기간이 소요돼 AI데이터센터 사업의 최대 불확실성 요인으로 꼽혀왔으며, 양사는 생산·납품 일정을 사전 조율해 공급망을 안정화하기로 했습니다.

변전소 운영·유지보수, 차세대 전력변환 기술 실증, 신규사업 발굴도 협력 범위에 포함됩니다. 국내 통신 3사가 최근 LS일렉트릭, 효성중공업 등과 잇따라 전력설비 확보 협약을 맺는 흐름 속에서 나온 조치입니다.

## 오늘의 딥다이브: AI가 직접 뚫는다 — 자율 해킹 프레임워크 ARTEX가 보여주는 것

FBI가 11월 13일 경보를 낸 'ARTEX'는 원래 보안 업계에서 쓰는 침투테스트(모의 해킹) 도구로 개발된 프레임워크입니다. 침투테스트는 기업이 자사 시스템의 취약점을 미리 찾아내기 위해 허가를 받고 실제 해킹 기법으로 공격을 시도해보는 작업인데, ARTEX는 이 작업을 외부 거대언어모델(LLM)과 연동해 자동화한 도구였습니다. 문제는 이 자동화 능력이 허가받지 않은 공격에도 그대로 적용될 수 있다는 점이었습니다.

FBI 경보에 따르면 ARTEX는 정찰부터 취약점 탐색, 실제 침투, 권한상승, 데이터 탈취까지 전 과정을 사람의 개입 없이 수행합니다. 즉 공격자가 명령을 내리고 지켜보는 기존 해킹과 달리, 한 번 작업을 맡기면 AI가 공격 목표를 스스로 찾아 뚫고 들어가는 구조입니다. 이런 식으로 '에이전틱 AI'가 공격 실행까지 떠맡는 방식이 실전에서 쓰이고 있다는 점이 이번 경보의 핵심입니다. 공격은 최소 8월부터 금융, 정부, 의료, 국방, 에너지 등 여러 분야를 대상으로 이뤄진 것으로 파악됐습니다.

확산 경로도 주목할 만합니다. ARTEX의 원본 깃허브 저장소는 10월에 삭제됐지만, 이미 퍼진 커뮤니티 복제판과 상용으로 판매되는 'ARTEX PRO'를 통해 계속 쓰이고 있습니다. 오픈소스 도구 하나가 삭제됐다고 해서 그 기술이 사라지는 게 아니라는 점을 보여주는 사례입니다. 11월 초 기준으로 인터넷에 외부 노출된 ARTEX 관리 콘솔이 1600개 이상 발견됐다는 점은, 공격자뿐 아니라 방어하는 쪽에서도 이 도구가 얼마나 넓게 퍼져 있는지를 가늠하게 해줍니다.

실제 피해 사례로 연결되는 지점도 있습니다. 마이크로소프트는 10월에 발생한 커넥트와이즈(원격관리 소프트웨어 업체) 공급망 침해 사고를 중국 연계 해킹 조직의 ARTEX 사용과 연결지었습니다. 공급망 침해는 특정 업체 하나를 뚫어서 그 업체의 소프트웨어를 쓰는 다수의 하위 고객사까지 한꺼번에 피해를 입히는 방식인데, 자율 해킹 도구가 이런 대규모 침해의 수단으로 쓰였다는 의미입니다. 여기에 더해 AWS 위협 인텔리전스 팀은 탈취한 AI API 키를 다시 공격에 재투입하는 별도의 캠페인도 포착했는데, 이는 AI 서비스 접근 권한 자체가 새로운 공격 자원으로 거래되고 있음을 보여줍니다.

이번 사례가 중요한 이유는 '사람 개입 없는 공격 자동화'가 더 이상 이론이나 연구실 시연이 아니라 실제 침해 사고의 원인으로 지목되고 있다는 점입니다. 기존에는 해커가 각 단계를 수동으로 수행해야 했기 때문에 공격 속도와 규모에 한계가 있었습니다. ARTEX처럼 정찰부터 탈취까지 자동으로 이어지는 도구가 널리 퍼지면, 적은 인력으로도 더 많은 표적을 동시에 노릴 수 있게 됩니다. 원본 저장소 삭제 이후에도 복제판과 상용판이 살아남고, 노출된 콘솔이 1600개를 넘는 현재 상황은 이 흐름을 억제하기가 쉽지 않다는 것을 보여줍니다.

## 소스

- [BleepingComputer - FBI warns ARTEX AI hacking tool is powering global cyberattacks](https://www.bleepingcomputer.com/news/security/fbi-warns-artex-ai-hacking-tool-is-powering-global-cyberattacks/)
- [IBTimes UK - FBI warns AI ARTEX cyberattacks](https://www.ibtimes.co.uk/fbi-warns-ai-artex-cyberattacks-1833001)
- [Cursor - Security incident update](https://cursor.com/blog/security-incident-update)
- [BleepingComputer - Cursor confirms security breach led to malicious Claude Code extension](https://www.bleepingcomputer.com/news/security/cursor-confirms-security-breach-led-to-malicious-claude-code-extension/)
- [Robotics 247 - Google DeepMind introduces Gemini Robotics 2.5](https://www.robotics247.com/article/google-deepmind-introduces-gemini-robotics-2.5-ai-model-to-improve-robot-dexterity-and-reliability)
- [Digital Today - Google DeepMind launches Gemini Robotics 2.5](https://www.digitaltoday.co.kr/en/view/124565/google-deepmind-launches-gemini-robotics-2-5)
- [Music Business Worldwide - Elvis Presley's rightsholders and other song owners sue Suno](https://musicbusinessworldwide.com/elvis-presleys-rightsholders-and-other-song-owners-sue-suno-for-more-than-202m-alleging-its-ai-imitates-the-kings-voice-eight-mile-style-has-filed-a-separate-47-7m-suit-over-269)
- [ABA Journal - Elvis Presley estate shakes up licensing, copyright lawsuit against AI music generator](https://www.abajournal.com/news/article/elvis-presley-estate-shakes-up-licensing-copyright-lawsuit-against-ai-music-generator)
- [inews24 - SKT-효성중공업 전력설비 공급 MOU](https://inews24.com/view/2026477)
- [Light Reading - SKT, Hyosung Heavy Industries team up for stable AIDC power supply](https://www.lightreading.com/data-centers/skt-hyosung-heavy-industries-team-up-for-stable-aidc-power-supply)

# 마인크래프트 루키서버
* 디스코드 : https://discord.gg/dYW9CAPKCJ
* 서버주소 : ruki.mcv.kr

### Essential is nonEssential
~~야생서버인데 플러그인을 자체개발하는 서버가 있다?~~

**왜 EssentialX 안쓰고 바퀴를 재발명하고있나요?**
* 에센셜은 커스터마이징이 어렵고, 기능이 너무 많습니다.
* 너무 규모가 크고, 이 때문에 버전업이 느려집니다. `Paper 1.20`과 `EssentialX 1.20` 출시 사이에는 한 달의 간극이 존재했습니다.  
  마인크래프트 최신 콘텐츠를 빠르게 반영해야하는 생야생 서버의 경우 치명적입니다.

**목표**
* EssentialX의 주요 기능을 분리해서 가볍게 대체, 각 플러그인간 호환성 보장
  * [X] MOTD : HelloMessage
  * [ ] Spawn, TPA
  * [ ] AFK
* [ ] `/msg`를 확장한 채팅 채널 분리 기능
* [ ] 다이아몬드를 화폐로 사용할 수 있는 상자 상점
* 위 기능들을 편하게 사용할 수 있는 서버 자체 GUI

**부가목표**
* 각 플러그인의 다국어 지원 (영어, 한국어)
* 플러그인이 의존하는 라이브러리에의 기여
  * [Heartbeat Coroutines](https://github.com/monun/heartbeat-coroutines) by monun

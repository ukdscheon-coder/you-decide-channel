# You Decide Channel

양방향 인터랙티브 영상 채널 프로젝트.

원리:
- 유튜브처럼 동영상을 올리면 시청자가 동영상 내 상황·캐릭터 설정을 바꿀 수 있음
- 캐릭터당 1개의 GLB 파일 안에 여러 감정 클립(idle, happy, regret, encourage 등)을 사전에 삽입
- 시청자의 선택에 따라 상황 전개가 바뀜어 재생됨
- 한국 프로그램 '그래 결정했어' 인생극장처럼 결정을 바꾸어 보는 가상 참여 콘텐츠

## 구조
- assets/characters/ : 캐릭터 GLB (다중 클립)
- scenes/ : 장면별 시나리오 정의 (JSON)
- player/ : 인터랙티브 플레이어

## 기존 유사 서비스
- Episode, Choices, FICT, Treezy Play 등 인터랙티브 스토리 앱
- Mindstamp, Stornaway 등 인터랙티브 비디오 도구
- 유튜브 엔드 스크린 기본 브랜칭

이 프로젝트는 사전 삽입된 GLB 감정 반응 + 시청자 선택으로 상황을 전개하는 방식에 집중합니다.

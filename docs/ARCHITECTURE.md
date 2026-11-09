# 아키텍처

## 핵심 원리
1. 캐릭터당 1개 GLB + 여러 AnimationClip (감정별)
2. 장면(scene) JSON이 타이밍 + 선택 가능 지점 + 결과 클립을 정의
3. 시청자가 선택하면 해당 클립 재생 + 다음 장면으로 이동
4. 양방향: 캐릭터가 먼저 감정을 보이거나, 시청자 선택에 반응

## 파일 구조
```
assets/characters/{name}.glb     # 다중 감정 클립 포함
scenes/{episode}/{scene}.json    # 시나리오
player/index.html                # 인터랙티브 플레이어
```

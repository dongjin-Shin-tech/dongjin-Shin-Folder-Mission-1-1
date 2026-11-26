# 주제 : AI Agent에게 일 제대로 시키기

배틀그라운드 총기 성능을 학습하여 다양한 사용자의 특성에 맞는 총기 추천해 주도록 설계하고, 모델 비교와 검증 과정을 기록한 저장소입니다.

- 입력 자료: 배틀그라운드 총기의 성능 평가 및 제원표
- 자료 출처: https://barome.tistory.com/entry/pubg-weapon-tier-list
           https://second-brain-storage.tistory.com/17
- 비교한 모델: ChatGPT 5-5, Gemini 자동 모드, Claude Sonnet 5.5 (모두 무료 요금제)
- 대화에 사용한 모델: ChatGPT 5-5

## 문서 순서

1. [docs/model-comparison.md](docs/model-comparison.md) : 3종의 모델 비교 및 선정 사유
2. [docs/system-design.md](docs/system-design.md): 페르소나, 시스템 프롬프트 v1과 v2, Few-shot 예시, 검증 전략 등
3. [docs/run-log.md](docs/run-log.md): 작업 기록과 20턴 대화 전문
4. [docs/unresolved.md](docs/unresolved.md): 프롬프트를 고쳐도 해결하지 못한 과업

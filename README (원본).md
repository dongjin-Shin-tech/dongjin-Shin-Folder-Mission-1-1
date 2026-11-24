# 롤 패치노트 챔피언 밸런스 정리: AI Agent에게 일 제대로 시키기

롤(리그 오브 레전드) 패치노트의 챔피언 밸런스 부분을 버프 / 너프 / 조정으로 나눠 정리하는 '패치 해설사'를 설계하고, 모델 비교와 검증 과정을 기록한 저장소입니다.

- 입력 자료: LoL 26.22 패치 노트의 소환사의 협곡 챔피언 밸런스 (공식 홈페이지 출처)
- 비교한 모델: ChatGPT 5.5, Gemini 자동 모드, Claude Sonnet 5.5 (모두 무료 요금제)
- 대화에 사용한 모델: Claude Sonnet 5.5

## 문서 순서

1. [docs/model-comparison.md](docs/model-comparison.md): 모델 3종을 같은 기준 4개로 비교한 표와 선정 결론
2. [docs/system-design.md](docs/system-design.md): 페르소나, 시스템 프롬프트 v1과 v2, Few-shot 예시, 검증 전략, 환각 검증 질문과 판정
3. [docs/run-log.md](docs/run-log.md): 작업 기록과 20턴 대화 전문
4. [docs/unresolved.md](docs/unresolved.md): 프롬프트를 고쳐도 해결하지 못한 과업 2건

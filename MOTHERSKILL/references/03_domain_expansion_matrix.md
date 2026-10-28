# 🌐 Mother REA 기반 분야별 파생 REA 확장 매트릭스

## 1. 파생 REA 스캐폴딩 규칙
모든 파생 REA는 본 Mother REA의 코어 모듈을 상속하여 아래 구조로 생성됩니다:

```
[파생 REA]/
├── SKILL.md                 # 해당 도메인 전용 프롬프트 및 트리거
├── domain_inspector.py      # 도메인 특화 추출기 (예: Chrome CDP, Frida, IL2CPP)
├── specialized_tests.py     # 도메인 특화 테스트 러너
└── references/              # 도메인 실무 레퍼런스
```

## 2. 5대 핵심 파생 로드맵
1. **vdan-rea-web**: 웹 SaaS, 결제 모듈, UI 컴포넌트 복제
2. **vdan-rea-sec**: 악성코드 분석, 취약점 진단, 패킹 해제
3. **vdan-rea-game**: 게임 물리 엔진, 아이템 확률 로직 복제
4. **vdan-rea-mobile**: 뱅킹/커머스 앱 보안 및 통신 프로토콜 리버스
5. **vdan-rea-erp**: ERP 웹 그리드, 대량 데이터 송수신 프로토콜 리버스

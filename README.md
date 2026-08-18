# how-gradient-descent-works

경사 하강법(Gradient Descent)은 왜 지그재그로 움직이는가 — 학습률·조건수에 따른 수렴과 발산, GD/Momentum/Adam의 차이를 브라우저에서 직접 실험하며 배우는 인터랙티브 교육 자료입니다.

**🔗 데모: https://dev-jonghoonpark.github.io/how-gradient-descent-works/**

> [how-ai-works](https://github.com/dev-jonghoonpark/how-ai-works) 시리즈의 일부입니다.

## 다루는 내용

| 절 | 주제 |
|---|---|
| §1 | 학습률 하나로 갈리는 네 가지 운명 (수렴·진동·발산) |
| §2 | 비교 실험실 — GD / Momentum / Adam |
| §3 | 지그재그는 왜 생기는가 — 축별 분해 |
| §4 | 조건수 κ와 학습률의 딜레마 |
| §5 | 처방 다섯 가지 |
| §6 | 진단 가이드 — 증상에서 처방까지 |
| §7 | 핵심 정리 카드 |

## 실행

빌드 과정 없는 단일 `index.html`입니다. 브라우저로 열면 됩니다.

```bash
open index.html
```

모든 계산은 순수 JavaScript로 페이지 안에서 수행됩니다 — 외부 라이브러리·서버 없음.

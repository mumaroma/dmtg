# DMTG 표상구조를 반영한 과제

동적 운동 자취 그래프(DMTG, Dynamic Motion Trace Graph) 기반 수학 학습 활동 10종.
순수 HTML/CSS/JS로 작성되어 외부 의존성 없이 GitHub Pages에서 바로 동작합니다.

## 구조

```
index.html              # 활동 목록 (제시형 / 안내형 / 정교화형 ID)
activities/
  activity1.html  …  activity10.html
```

## GitHub Pages 배포

1. 이 폴더 전체를 저장소 루트에 커밋·푸시
2. Settings → Pages → Source: `Deploy from a branch`, Branch: `main` / `(root)`
3. `https://<계정>.github.io/<저장소>/` 에서 확인

`.nojekyll` 파일이 있어 Jekyll 처리 없이 그대로 서빙됩니다.

## 활동 개요

| 활동 | 운동 유형 | 표상체 |
|---|---|---|
| 1 | 등속 2개 | DMTG |
| 2 | 등가속도 2개 | DMTG |
| 3 | 등속 2개 | DMTG ↔ 표 |
| 4 | 구간별 속력 다른 운동 | DMTG ↔ 표 |
| 5 | 등속 5개 | DMTG ↔ s-t |
| 6 | 등속 5개(초기 위치 다름) | DMTG ↔ s-t |
| 7 | 구간별 속력 다른 운동 | DMTG ↔ s-t ↔ v-t ↔ 표 |
| 8 | 등속 2개 | DMTG ↔ s-t ↔ 표 |
| 9 | 등속→가속→등속 | DMTG ↔ s-t ↔ v-t ↔ 표 |
| 10 | 등가속도 | DMTG ↔ s-t ↔ v-t ↔ 표 |

---
전남대학교 수학교육학과 · 재은쌤

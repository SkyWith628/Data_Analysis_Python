# 🐍 Python 데이터 분석 학습 기록

Python으로 데이터 분석의 기초를 익히며 정리한 **chapter별 실습 노트북** 모음입니다.
pandas·numpy를 이용한 데이터 처리부터 시각화까지, 개념을 직접 코드로 확인하며 학습한 기록입니다.

## 📚 다루는 내용

| 영역 | 라이브러리 |
| --- | --- |
| 데이터 핸들링 | `pandas`, `numpy` |
| 시각화 | `matplotlib`, `seaborn` |
| 실행 환경 | Jupyter Notebook |

## 🗂️ 구성

각 노트북(`LHR_Chapter*.ipynb`)은 한 챕터 단위의 실습으로 구성되어 있습니다.

- Chapter 1~5 — 데이터 구조, 인덱싱·선택, 결측치 처리, 기초 통계
- Chapter 6~10 — 그룹 집계, 병합·결합, 시계열, 시각화

> 학습용 실습 저장소입니다. 개념 정리와 손으로 익히는 과정에 초점을 두었습니다.

## 💡 학습 포인트

직접 코드로 확인하며 익힌 핵심 개념들:

- **결측치 처리** — 단순 삭제 vs 대치(평균·중앙값)의 차이와 데이터 왜곡 가능성
- **그룹 집계(`groupby`)** — 분할-적용-결합 패턴으로 범주별 통계를 한 번에 계산
- **데이터 병합(`merge`/`join`)** — 키 기준 결합과 조인 방식(inner/outer)에 따른 행 수 변화
- **시각화** — `matplotlib`/`seaborn`으로 분포·상관·추세를 눈으로 확인하며 해석

## ▶️ 실행

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

원하는 `LHR_Chapter*.ipynb` 파일을 열어 셀을 순서대로 실행하면 됩니다.

# 트럼프 관세 & KORUS FTA 한국 무역 영향 분석
**Trump Tariff & KORUS FTA Impact on Korean Trade — Python Data Analysis**

## 프로젝트 개요
트럼프 행정부의 상호관세 정책과 KORUS FTA 혜택을 실제 데이터로 분석한 포트폴리오입니다.
Python(pandas, matplotlib)을 활용해 UN 무역 데이터, 트럼프 관세 데이터, 미국 HTS 데이터를 분석했습니다.

## 사용 데이터
- UN Comtrade Global Commodity Trade Statistics (1988–2016)
- Trump Tariff Dataset 2025 (Kaggle)
- Trump-Era Tariffs by Country 2025 (Kaggle)
- USITC Harmonized Tariff Schedule 2023 (Kaggle)

## 분석 1: 트럼프 관세가 한국 무역에 미치는 영향
| 분석 항목 | 주요 발견 |
|---|---|
| 글로벌 수출 순위 | 한국 10위 ($5,500억, 2016) |
| 미국 무역적자 순위 | 한국 7위 ($660억) |
| 트럼프 보복관세 | 25% (주장 50%의 절반) |
| 관세 결정 패턴 | 적자 규모보다 지정학·FTA 여부가 변수 |

## 분석 2: KORUS FTA 관세 혜택 정량화
| 분석 항목 | 수치 |
|---|---|
| FTA 적용 품목 수 | 7,123개 |
| 무관세(0%) 적용 품목 | 6,292개 (99.9%) |
| 평균 일반 관세율 | 7.38% |
| 평균 FTA 관세율 | 0.00% |
| 최대 혜택 품목 | 담배(HS 24): 114% → 0% |

## 핵심 결론
- 트럼프 25% 관세 부과 시 KORUS FTA 무관세 혜택 사실상 무력화
- 의류·신발·농산물 업종 타격 가장 클 것으로 예상
- 트럼프 관세는 협상 레버리지 성격 — 전 국가 주장치의 약 50% 수준으로 실제 부과

## 사용 기술
`Python` `pandas` `matplotlib` `re` `Jupyter Notebook`

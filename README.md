# 트럼프 관세가 한국 무역에 미치는 영향 분석
**Trump Tariff Impact on Korean Trade — Python Data Analysis**

## 프로젝트 개요
트럼프 행정부의 상호관세 정책이 한국 수출입에 미치는 영향을 
실제 데이터를 활용해 Python으로 분석한 포트폴리오 프로젝트입니다.

## 사용 데이터
- UN Comtrade Global Commodity Trade Statistics (1988–2016)
- Trump Tariff Dataset 2025 (Kaggle)
- Trump-Era Tariffs by Country 2025 (Kaggle)

## 분석 내용
1. **글로벌 수출 상위 10개국** — 한국 10위 확인 ($5,500억)
2. **미국 무역적자 vs 트럼프 보복관세** — 관세율이 적자 규모에 단순 비례하지 않음을 발견
3. **주장 관세 vs 실제 보복관세 비교** — 트럼프 관세의 협상 레버리지 성격 분석
4. **한국 품목별 25% 관세 영향 시뮬레이션** — 무역탄력성 적용

## 주요 발견
- 한국은 KORUS FTA 체결국임에도 25% 관세 부과 대상
- 트럼프 관세는 주장치의 약 50% 수준으로 실제 부과 → 협상 레버리지 성격
- 캐나다는 USMCA로 10% 유지 — FTA의 관세 방어 효과 확인

## 사용 기술
`Python` `pandas` `matplotlib` `Jupyter Notebook`

## 데이터 한계
UN Comtrade 데이터에 반도체·자동차 등 한국 주력 수출품 미포함
→ 실제 관세 충격은 본 분석보다 클 가능성 있음

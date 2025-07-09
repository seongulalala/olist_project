# 브라질 시장 진출을 위한 Olist 데이터 분석
# Olist Project

> 본 프로젝트는 Olist가 제공하는 E‑Commerce Public Dataset을 활용하여
이커머스 시장의 다양한 데이터 분석을 수행한 결과물입니다.

# Olist 브라질 시장 진출 전략 분석

> 브라질 이커머스 플랫폼 Olist의 데이터를 기반으로 재구매율 문제를 분석하고, 이를 해결하기 위한 데이터 기반 전략을 제시한 프로젝트입니다.

---

## [1] 📌 분석 개요

- **분석 목적**  
  브라질에 진출할 신규 이커머스 플랫폼이 Olist의 문제점을 개선하여 시장 점유율을 확보할 수 있도록, Olist의 데이터를 분석하고 전략을 제시합니다.

- **핵심 문제**  
  Olist 고객의 재구매율이 약 3%로 매우 낮아 충성 고객 확보에 실패하고 있음.

- **분석 목표**  
  - 재구매 저해 요인 파악
  - 데이터 기반 리마케팅 및 구독 전략 제안
  - 배송 및 결제 인프라 개선 방향 제시

---

## [2] 📊 주요 분석 결과

| 항목 | 인사이트 | 전략 제안 |
|------|----------|------------|
| 배송 지연 여부 | 오히려 배송 지연 고객의 재구매율이 더 높음 | ❌ 배송 품질보다 소비 성향 중심 분석이 더 유효 |
| 소비 성향 차이 | 재구매 고객은 생활용품/저가품 집중 | ✅ 저가 카테고리 타겟팅 리마케팅 |
| 재구매 타이밍 | 첫 구매 후 30일 이내 재구매가 집중됨 | ✅ 초기 2~4주 집중 마케팅 (쿠폰 등) |
| 구독 서비스 | 재구매 고객의 70%가 저가 생활용품 구매 | ✅ 정기배송/구독형 모델 제안 |
| 결제 방식 | 상품권(voucher) 사용 고객의 재구매율 높음 | ✅ 바우처 적극 활용해 충성도 확보 |

---

## [3] 🗂 프로젝트 구조

PJT/
├── README.md # 프로젝트 소개 문서
├── 브라질_진출_전략_요약.pdf # 최종 발표용 문서 (PPT → PDF 변환)
├── analysis/
│ └── olist_repurchase_analysis.ipynb # 전체 분석 노트북
├── data/
│ └── olist_sample_data.csv # Olist 데이터 샘플
└── images/
└── repurchase_plot.png # 분석 결과 시각화 이미지


---

## [4] 📂 데이터셋 안내

- 출처: [Olist Brazilian E-commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- 총 9개 CSV 파일로 구성된 약 10만 건의 온라인 쇼핑 거래 기록
- 주요 테이블:
  - `order`, `customer`, `order_items`, `reviews`, `order_payments`, `products`

---

## [5] ⚖ 데이터셋 라이선스 및 사용 조건

- 본 프로젝트는 Kaggle의 **Olist 공개 데이터셋**을 기반으로 하며, 비상업적/학습 목적의 분석에 활용되었습니다.
- 데이터셋 라이선스: [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)
- 상업적 활용이나 배포 시 반드시 Olist 및 Kaggle의 이용 약관을 확인해야 합니다.

---

## 🙋‍♂️ 만든 사람

- 이성우  
- [GitHub Profile](https://github.com/db030dbb)

---

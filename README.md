<p align="center"><img src="assets/banner.svg" width="100%" alt="Yeonju Kim | Quantum Information × AI | From representation to prediction"></p>

<p align="center"><b>양자정보와 AI 사이에서, 정보가 예측에 쓰이는 과정을 살펴봅니다.</b><br>국립한밭대학교 컴퓨터공학과 · AIM Lab. · UST·KISTI 양자정보 연구인턴</p>

<p align="center"><a href="https://kimyeonjuu.github.io">Research Portfolio ↗</a> &nbsp; · &nbsp; <a href="https://kimyeonjuu.github.io/about.html">연구 이야기 ↗</a> &nbsp; · &nbsp; <a href="mailto:yeonjuk8@gmail.com">Email ↗</a></p>

## Research path

| 기반 | 실험 | 방법 설계 | 현재 |
|:---|:---|:---|:---|
| **2023–2024 · 컴퓨터공학과 데이터** | **2025 · 의료영상 AI** | **2025–2026 · 주파수 특징** | **2026 · 양자정보 × AI** |
| 자료구조·알고리즘·확률및통계, 이미지·캡션 데이터 구축 | 대조학습과 증강을 내부·외부 데이터에서 비교 | 선택적 주파수 증강에서 TFM 특징 조절로 확장 | 회로 내부의 차이가 최종 예측까지 남는지 분석 |
| 구현과 데이터 검증 | 비교 실험과 일반화 평가 | 논문 설계·구현·검증 | 양자·고전 하이브리드 연구 |

의료영상에서 필요한 주파수 정보를 선택하는 방법을 연구했습니다. 지금은 양자 회로가 만든 정보가 고전 연산을 통과하며 어떻게 달라지는지 확인하고 있습니다.

## Selected research

<table><tr><td width="55%">

### Targeted Frequency Modulation

**Pattern Recognition · 게재 승인 (2026.09)**<br>
제1저자 · 공동 기여 표기

특징을 주파수 영역으로 바꾼 뒤 샘플별 통계로 조절할 좌표를 골랐습니다. 방법 설계부터 구현·실험·통계 검정·시각화·원고 초안까지 맡았습니다.

[공개 코드 ↗](https://github.com/KimYeonJuu/Targeted-Frequency-Modulation-for-Robust-Neonatal-Respiratory-Distress-Classification)

</td><td width="45%"><img src="assets/tfm-method.png" alt="TFM 주파수 선택과 게이트 구조" width="100%"></td></tr></table>

| AUROC | AUPRC | Accuracy | F1 |
|:---:|:---:|:---:|:---:|
| **88.39 ± 4.46%** | **89.51 ± 3.49%** | **82.45 ± 5.47%** | **83.50 ± 6.09%** |

신생아 흉부 X-ray 632장 · 5-fold 평균 ± 표준편차. Pooled OOF AUROC는 88.21% (MedCLIP 84.57%), paired DeLong p=0.0013입니다.

| 연구 | 직접 확인한 내용 | 성과 |
|:---|:---|:---|
| **블록 FFT 기반 선택적 주파수 증강** | 64×64 블록의 에너지를 분석하고 선택한 대역만 조절. Accuracy 78.95 → 82.63%, F1 80.20 → 84.36% | 2025 동계학술대회 논문 경진대회 **최우수상** |
| **흉부 X-ray 대조학습과 증강** | EfficientNet-B0의 손실함수·증강 조합 비교. CheXpert 정확도 74.65 → 79.45%, 외부 데이터 61.37 → 66.32% | 한국전기전자학회 논문지 **공동제1저자** · [DOI ↗](https://doi.org/10.7471/ikeee.2025.29.3.289) |

## Now · Quantum information × AI

**UST·KISTI 스쿨 양자정보 연구인턴** · 2026.07.06–현재<br>
하계 → 장기 인턴십 · 지도교수 류정희 · 2026.12.24 종료 예정

> 회로의 출력은 달라졌는데 예측은 비슷하다면, 그 차이는 어디에서 작아졌을까?

| 비교하는 요소 | 확인하는 것 |
|:---|:---|
| 데이터 재입력·회로 깊이·얽힘 구조 | 양자 회로 내부 출력의 변화 |
| 시드 | 표현과 성능의 변동 |
| 후속 고전 연산 | 내부 차이가 최종 예측까지 남는 정도 |
| QAOA 기반 실험 | 구현을 검증하며 일부 연산의 변경 탐색 |

회로 내부의 변화가 최종 예측에서 작아지는 경우를 관찰했습니다. 이후에는 성능과 중간 출력을 함께 비교하고 있습니다. **진행 중인 연구**이며 양자 우위가 확정된 결과로 제시하지 않습니다.

## Experience & achievements

| 기간 | 활동 | 역할 / 성과 |
|:---|:---|:---|
| 2024–현재 | AIM Lab. 의료영상 AI 연구 | 학부연구생 · 데이터 구축, 방법 설계와 검증 |
| 2025.04–09 | 사이버안보 정책 도메인에 적합한 대화형 AI 모델 연구 | 학생연구자 |
| 2026.04–현재 | 생성형 AI 기반 이미지 워터마킹 기술 연구 | 학생연구자 · 2026.10.31 종료 예정 |
| 2026.07–현재 | UST·KISTI 양자정보 인턴십 | 양자·고전 하이브리드 모델 연구 |
| 2025 | 소중한 SW·AI 경진대회 · Fake Text Detection | 팀 4im · AI 부문 3등 |
| 2025.12 | 한국방송·미디어공학회 동계학술대회 논문 경진대회 | 최우수상 |

## Foundations

**Python · PyTorch · Computer Vision · FFT · 비교 실험 · 통계 검정**

| 학업 | 연구와의 연결 |
|:---|:---|
| 누적 평점 **4.35 / 4.50** · 석차 **2 / 112** · 130학점 | 2026학년도 1학기까지 |
| 자료구조·알고리즘·시스템프로그래밍 A+ | 실험 코드와 모델 연산 구현 |
| 인공지능·기계학습개론·컴퓨터비전 A+ | 의료영상 모델과 특징 조절 실험 |
| 확률및통계 A0 | 결과의 변동과 모델 간 차이 분석 |
| TOEIC **780** | 2026.08.23 |

## Evidence

<table><tr><td align="center" width="33%"><a href="assets/frequency-award.webp"><img src="assets/frequency-award.webp" height="150" alt="학술대회 최우수상 증빙"></a><br><sub>학술대회 최우수상</sub></td><td align="center" width="33%"><a href="assets/ust-kisti.png"><img src="assets/ust-kisti.png" width="100%" alt="UST·KISTI 양자정보 인턴십 증빙"></a><br><sub>UST·KISTI 양자정보 인턴십</sub></td><td align="center" width="33%"><a href="assets/academic-summary.png"><img src="assets/academic-summary.png" height="150" alt="평점 4.35, 석차 2/112 증빙"></a><br><sub>성적증명서 발췌</sub></td></tr></table>

<details><summary>연구과제 · 국내 논문 · AI 경진대회 증빙 더 보기</summary>

[연구과제 참여](assets/research-projects.png) · [국내 논문 발췌](assets/contrastive-paper.png) · [AI 경진대회 상장](assets/ai-award.png) · [TFM 논문 저자 발췌](assets/tfm-authors.png)

</details>

## Next

| 현재 | 대학원 준비·진학 | 장기 목표 |
|:---|:---|:---|
| 조건별 실험 재현과 중간 출력 분석 | 양자정보이론·수학 심화, 후속 연구 구체화 | 국공립·기업 R&D에서 양자정보·양자머신러닝 알고리즘 설계·구현·검증 |

처음에는 논문 속 방법을 구현하는 일이 가장 어려웠습니다. 지금은 구현 뒤의 결과를 설명하는 일이 더 어렵고 재미있습니다. 결과를 보고 다음에 확인할 것을 정하는 연구자가 되고 싶습니다.

<sub>Updated 2026.10.08 · [Portfolio](https://kimyeonjuu.github.io) · [Email](mailto:yeonjuk8@gmail.com)</sub>

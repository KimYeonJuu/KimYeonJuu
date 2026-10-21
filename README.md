<!-- Banner layout inspired by https://github.com/Kyung-A/2020ver-portfolio; original SVG layout using the supplied portrait. -->
<a href="https://kimyeonjuu.github.io/">
  <img src="assets/profile/banner.png" width="100%" alt="김연주 — 양자정보와 AI를 연구합니다. 증명사진과 코럴·보라 그라데이션 배너">
</a>

<p align="center">
  <a href="https://kimyeonjuu.github.io/#project"><img src="assets/profile/nav-research.svg" width="32%" alt="Project · 연구 보기"></a>
  <a href="https://kimyeonjuu.github.io/#about"><img src="assets/profile/nav-about.svg" width="32%" alt="About Me · 소개 보기"></a>
  <a href="https://kimyeonjuu.github.io/#contact"><img src="assets/profile/nav-contact.svg" width="32%" alt="Contact · 연락처 보기"></a>
</p>

<p align="center"><sub>메뉴를 누르면 포트폴리오 사이트에서 자세히 볼 수 있습니다.</sub></p>

<a name="profile"></a>

<p><img src="assets/profile/heading-who.svg" height="32" alt="Who."></p>

<img src="assets/profile/portrait-circle.png" align="left" width="25%" alt="김연주 증명사진">

<p><img src="assets/profile/research-values.png" width="228" alt="설계 · 구현 · 실험 · 검증"></p>

**김연주 · Yeonju Kim**<br>
국립한밭대학교 컴퓨터공학과 · 학사과정, 2023–현재<br>
AIM Lab. 학부연구생 · UST·KISTI 양자정보 연구인턴

**안녕하세요. 양자정보와 AI를 연구하는 김연주입니다.**<br>
흉부 X-ray 분류 연구를 시작으로, 영상의 주파수 특징을 골라 조절하는 방법을 설계하고 실험해 왔습니다.<br>
저는 성능이 얼마나 좋아졌는지만큼이나 무엇이 그 차이를 만들었는지 이해하는 것을 중요하게 생각합니다.

지금은 UST·KISTI에서 AI 모델의 일부 계산을 양자 회로로 바꾸고, 기존 모델과 같은 조건에서 분류 성능을 비교하고 있습니다.

앞으로는 양자컴퓨팅을 AI의 학습과 추론에 활용하는 연구를 이어가고 싶습니다.<br>
어떤 문제에서 양자 계산이 도움이 되는지 직접 구현하고 확인하며, 실제로 쓸 수 있는 방법을 찾는 것이 제 목표입니다.

**Pattern Recognition · SCIE 제1저자\*** · 2026.09 게재 승인<br>
<sub>* 공동 기여 표기 · [논문과 연구 내용 ↓](#selected-research)</sub>

<br clear="all">

GPA **4.35 / 4.50** · 석차 **2 / 112** <sub>(2026-1)</sub> · TOEIC **780** <sub>(2026.08.23)</sub><br>
[학력·경력 전체 보기 ↗](https://kimyeonjuu.github.io/cv.html)

<a name="skills"></a>

<p><img src="assets/profile/heading-skills.svg" height="32" alt="Skills."></p>

<h4>AI & Computer Vision <img src="assets/profile/divider.svg" width="68%" height="1" alt=""></h4>

<p>
  <img src="assets/profile/skill-python.svg" width="104" alt="Python">
  <img src="assets/profile/skill-pytorch.svg" width="104" alt="PyTorch">
  <img src="assets/profile/skill-vision.svg" width="104" alt="Computer Vision">
  <img src="assets/profile/skill-fft.svg" width="104" alt="Frequency Analysis">
  <img src="assets/profile/skill-contrastive.svg" width="104" alt="Contrastive Learning">
  <img src="assets/profile/skill-statistics.svg" width="104" alt="Statistical Testing">
</p>

<h4>Quantum Computing <img src="assets/profile/divider.svg" width="68%" height="1" alt=""></h4>

<p>
  <img src="assets/profile/skill-circuit.svg" width="104" alt="Quantum Circuits">
  <img src="assets/profile/skill-qaoa.svg" width="104" alt="QAOA">
  <img src="assets/profile/skill-reupload.svg" width="104" alt="Data Re-uploading">
  <img src="assets/profile/skill-hybrid.svg" width="104" alt="Quantum–Classical Hybrid Models">
</p>

<sub>AI 연구에 사용한 도구와 방법입니다. 양자 항목은 UST·KISTI 인턴십에서 구현하며 실험 중인 주제입니다.</sub>

<a name="selected-research"></a>

<p><img src="assets/profile/heading-research.svg" height="32" alt="Research."></p>

### 국제 학술지 논문 · Pattern Recognition

<p>
  <img src="assets/profile/first-author.svg" height="26" alt="SCIE 제1저자 — 공동 기여 표기">
  <img src="assets/profile/journal-metrics.svg" height="26" alt="JCR Top 6.6% · Impact Factor 9.1">
</p>

**Targeted Frequency Modulation for Robust Neonatal Respiratory Distress Classification**<br>
Accepted · 2026.09

신생아 흉부 X-ray에서 호흡곤란증후군을 더 잘 구분하고자 TFM을 만들었습니다.<br>
AI가 추출한 영상 특징을 주파수별로 나눈 뒤 일부를 골라 조절하는 방법입니다.<br>
직접 구현한 모델을 기존 방법과 비교하고 결과를 분석해 논문 초안을 작성했습니다.

<img src="assets/tfm-method.png" width="760" alt="TFM 논문 연구 그림: 모델이 추출한 특징에서 조절할 주파수를 선택하고 채널별 가중치를 적용하는 구조">

**평가:** 신생아 흉부 X-ray 632장 · 5-fold 교차검증<br>
**결과:** AUROC 88.39 ± 4.46% · 정확도 82.45 ± 5.47% <sub>(5회 평가의 평균 ± 표준편차)</sub>

[논문 정보·DOI ↗](https://doi.org/10.1016/j.patcog.2026.115008) · [구현 코드·실행 안내 ↗](https://github.com/KimYeonJuu/Targeted-Frequency-Modulation-for-Robust-Neonatal-Respiratory-Distress-Classification)

<sub>공개 저장소에 TFM 모델 코드와 학습·평가 스크립트가 있습니다. 임상 영상과 학습 가중치는 포함하지 않습니다.</sub>

<sub>제1저자: 저자 목록 첫 번째, 공동 기여 표기. 저널 지표: 2025 JCR · Engineering, Electrical & Electronic · JIF percentile 93.4 기준.</sub>

<details>
<summary><b>논문 저자 표기 확인</b></summary>

<a href="assets/tfm-authors.png"><img src="assets/tfm-authors.png" width="760" alt="TFM 논문의 저자 목록과 공동 기여 표기"></a>

</details>

---

### 국내 학술지 논문 · 공동제1저자

**대조 학습과 데이터 증강을 활용한 흉부 X-Ray 이미지 분류 정확도 향상**<br>
한국전기전자학회 논문지 · 29(3), 289–296 · **2025.09 게재**

비슷한 X-ray 특징은 가깝게 학습하도록 하고 밝기와 잘라내기 증강을 함께 적용했습니다.

| 평가 데이터 | 기존 정확도 | 적용 후 정확도 |
| :--- | ---: | ---: |
| CheXpert | 74.65% | **79.45%** |
| 외부 COVID·Pneumonia | 61.37% | **66.32%** |

[논문 정보·초록 ↗](https://doi.org/10.7471/ikeee.2025.29.3.289)

<details>
<summary><b>게재 정보·공동제1저자 표기 확인</b></summary>

<a href="assets/contrastive-authorship.png"><img src="assets/contrastive-authorship.png" width="760" alt="국내 학술지 논문 첫 페이지: 김연주·오서연의 공동 기여 표기와 2025년 9월 게재 정보"></a>

</details>

---

### 연구인턴 · UST·KISTI

**양자정보 연구인턴 · 2026.07–현재 · 진행 중**<br>
UST·KISTI 스쿨 · 지도교수 류정희

**연구 주제: 양자 회로를 이용한 의료영상 분류**

흉부 X-ray 분류 모델에서 주파수를 고르는 계산과 채널별 가중치를 정하는 계산을 각각 양자 회로로 바꿔 비교하고 있습니다.<br>
학습·평가 데이터에 같은 환자가 섞인 문제를 찾아 환자 단위로 다시 나누고 모델을 재평가했습니다.

<a href="assets/quantum-method.png"><img src="assets/quantum-method.png" width="760" alt="TFM의 주파수 선택과 채널 게이트를 각각 양자 회로로 대체한 두 실험 설정"></a>

<details>
<summary><b>활동보고서 · 데이터 검증과 성능 비교</b></summary>

**환자 단위 재분할 · 5쪽**

<a href="assets/quantum-validation.png"><img src="assets/quantum-validation.png" width="760" alt="15주차 활동보고서 5쪽: 환자 중복을 제거한 학습·검증·평가 데이터 재분할과 재평가"></a>

**3개 시드 성능 비교 · 6쪽**

<a href="assets/quantum-results.png"><img src="assets/quantum-results.png" width="760" alt="15주차 활동보고서 6쪽: MedCLIP, 고전 TFM, 두 QAOA 모델의 성능과 별도 QAOA-SE 실험의 효율 분석"></a>

<sub>QAOA 모델은 고전 TFM과 비슷한 성능을 보였습니다. MedCLIP 대비 일관된 정확도 우위는 확인하지 못했습니다. QAOA-SE의 파라미터 감소는 대부분 중간 차원을 48에서 4로 줄인 데서 발생했습니다.</sub>

</details>

---

<a name="research-experience"></a>

<p><img src="assets/profile/heading-experience.svg" height="32" alt="Experience."></p>

**의료영상 AI → 주파수 특징 연구 → 양자·고전 하이브리드 모델**<br>
<sub>흉부 X-ray 분류와 주파수 조절 연구를 거쳐, 지금은 AI 모델에 양자 회로를 적용하고 있습니다.</sub>

| Experience | Work |
| :--- | :--- |
| **UST·KISTI 스쿨** · 양자정보 연구인턴<br><sub>2026.07–현재</sub> | 하계·장기 인턴십 · 지도교수 류정희<br>의료영상 AI 모델에 양자 회로를 적용하고 분류 결과 비교 |
| **AIM Lab.** · 학부연구생 | 의료영상 분류 · 대조학습 · 데이터 증강<br>선택적 주파수 조절 방법 설계와 검증 |
| **연구과제** · 학생연구자<br><sub>2026.04.01–2026.10.31</sub> | 생성형 AI 기반 이미지 워터마킹 기술 연구 |
| **연구과제** · 학생연구자<br><sub>2025.04.01–2025.09.30</sub> | 사이버안보 정책 도메인에 적합한 대화형 AI 모델 연구 |

<details>
<summary><b>두 연구과제의 참여기간·역할 증빙</b></summary>

<a href="assets/research-projects.png"><img src="assets/research-projects.png" width="760" alt="한밭대학교 산학협력단 연구과제 실적증명서: 김연주, 두 과제의 참여기간과 학생연구자 역할, 발급일과 직인"></a>

<sub>2026.10.02 발급 · 주민등록번호와 발급번호를 가린 공개용 발췌본입니다.</sub>

</details>

<a name="awards"></a>

<p><img src="assets/profile/heading-awards.svg" height="32" alt="Awards."></p>

| Year | Award | Work |
| :--- | :--- | :--- |
| **2025.12** | 🥇 **최우수상**<br>한국방송·미디어공학회 동계학술대회<br>대학생 및 고등학생 논문 경진대회 | 미세 병변 검출을 위한<br>블록 FFT 기반 선택적 주파수 증강<br>[연구 ↗](https://kimyeonjuu.github.io/research/frequency.html) · [상장 ↗](assets/frequency-award.webp) |
| **2025** | 🥉 **AI 부문 3등**<br>소중한 SW·AI 경진대회 | Fake Text Detection · 팀 4im<br>[상장 ↗](assets/ai-award.png) |

<p align="center">
  <a href="assets/frequency-award.webp"><img src="assets/frequency-award.webp" width="520" alt="2025 한국방송·미디어공학회 동계학술대회 논문 경진대회 최우수상 — 김연주 외"></a>
</p>

<details>
<summary><b>활동·성적 증빙 더 보기</b></summary>

**UST·KISTI 장기인턴십 시스템**

<a href="assets/ust-kisti.png"><img src="assets/ust-kisti.png" width="760" alt="UST 장기인턴십 출석부 제출 화면에 표시된 김연주, KISTI 스쿨, 양자정보 전공과 지도교수"></a>

**학업 성적**

<a href="assets/academic-summary.png"><img src="assets/academic-summary.png" width="380" alt="평점 평균 4.35, 석차 2/112 성적 증빙"></a>

**TOEIC · 780점**

<a href="assets/toeic-score.png"><img src="assets/toeic-score.png" width="760" alt="김연주 TOEIC 성적표: 2026년 8월 23일, Listening 365점, Reading 415점, 총점 780점"></a>

**소중한 SW·AI 경진대회 · AI 부문 3등**

<a href="assets/ai-award.png"><img src="assets/ai-award.png" width="220" alt="2025 소중한 SW·AI 경진대회 AI 부문 3등 상장 — 팀 4im, 김연주"></a>

[전체 증빙 보기 ↗](https://kimyeonjuu.github.io/evidence.html)

</details>

<a name="skills--contact"></a>

<p><img src="assets/profile/heading-contact.svg" height="32" alt="Contact."></p>

<p>
  <a href="https://kimyeonjuu.github.io/"><img src="assets/profile/portfolio.svg" height="26" alt="Portfolio"></a>
  <a href="https://kimyeonjuu.github.io/cv.html"><img src="assets/profile/cv.svg" height="26" alt="Curriculum Vitae"></a>
  <a href="mailto:yeonjuk8@gmail.com"><img src="assets/profile/email.svg" height="26" alt="Email"></a>
</p>

✉️ **[yeonjuk8@gmail.com](mailto:yeonjuk8@gmail.com)**

<sub>Last updated · 2026.10.21</sub>

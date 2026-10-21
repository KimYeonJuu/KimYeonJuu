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

흉부 X-ray로 질환을 구분하는 AI 모델을 연구합니다.<br>
UST·KISTI에서는 모델의 일부 계산을 양자 회로로 바꿔 기존 모델과 분류 성능을 비교하고 있습니다.

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

### Pattern Recognition · Elsevier

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

**대조 학습과 데이터 증강을 활용한 흉부 X-Ray 이미지 분류 정확도 향상**<br>
한국전기전자학회 논문지, 29(3), 289–296 · **공동제1저자** · 2025.09<br>
비슷한 X-ray 특징은 가깝게 학습하도록 하고 밝기와 잘라내기 증강을 함께 적용했습니다.<br>
CheXpert 정확도 **74.65% → 79.45%**, 외부 데이터 정확도 **61.37% → 66.32%**를 확인했습니다.<br>
[논문 정보·초록 ↗](https://doi.org/10.7471/ikeee.2025.29.3.289)

**양자 회로를 이용한 의료영상 분류 · 진행 중**<br>
기존 AI 모델의 일부 계산을 양자 회로로 바꾸는 연구입니다.<br>
회로 깊이·데이터 재입력·얽힘 구조를 바꾸며 분류 결과를 비교하고 있습니다. 회로 내부에서 생긴 변화가 이후 AI 계산을 거쳐도 남는지 함께 살펴봅니다.

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

**UST·KISTI 스쿨·전공·지도교수**

<a href="assets/ust-kisti.png"><img src="assets/ust-kisti.png" width="760" alt="UST 인턴십 지원 시스템에 표시된 KISTI 스쿨, 양자정보 전공과 지도교수"></a>

**학업 성적**

<a href="assets/academic-summary.png"><img src="assets/academic-summary.png" width="380" alt="평점 평균 4.35, 석차 2/112 성적 증빙"></a>

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

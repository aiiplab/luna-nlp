<div align="center">

# 🤗 LUNA Lab · 딥러닝응용III 실습 자료

**동덕여자대학교 데이터사이언스전공 | BERT & GPT로 배우는 자연어처리**

<a href="https://colab.research.google.com/github/aiiplab/luna-nlp/blob/main/notebooks/Lecture02_Lab_Student.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
<img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" alt="Python 3.10+"/>
<a href="https://huggingface.co/" target="_blank"><img src="https://img.shields.io/badge/🤗-HuggingFace-yellow" alt="HuggingFace"/></a>
<img src="https://img.shields.io/badge/License-MIT-green" alt="License: MIT"/>
<a href="https://github.com/aiiplab/luna-nlp" target="_blank"><img src="https://img.shields.io/github/stars/aiiplab/luna-nlp?style=social" alt="GitHub stars"/></a>

<br>

> **"코드로 이해하는 트랜스포머 — BERT와 GPT의 원리를 직접 구현하고 실험합니다."**

<br>

[📚 강의 소개](#-강의-소개) · [🗺️ 커리큘럼](#️-커리큘럼-및-실습-자료) · [🚀 시작하기](#-시작하기) · [📖 교재](#-교재) · [🔬 LUNA Lab](#-luna-lab)

</div>

---

## 📚 강의 소개

| 항목 | 내용 |
|------|------|
| **과목명** | 딥러닝응용III (Deep Learning Applications III) |
| **교과코드** | 데사K0014 |
| **대학/전공** | 동덕여자대학교 데이터사이언스전공 |
| **학년/학점** | 4학년 / 3학점 |
| **담당교수** | <a href="mailto:wonsang@dongduk.ac.kr">유원상 교수</a> |
| **강의 시간** | 월·수 4교시 |
| **연구실** | <a href="https://sites.google.com/view/luna-ailab/home" target="_blank">LUNA Lab (AI·영상처리 연구실)</a> |

### 교과목 개요

본 과목은 **트랜스포머 기반 언어모델(BERT, GPT 등)과 전이학습**을 중심으로,  
토큰화 → 임베딩 → 셀프어텐션 → 사전학습·파인튜닝 → 학습·추론 파이프라인을  
**이론과 실습을 병행**하여 학습합니다.

수강생은 텍스트 데이터를 활용해 **5가지 대표 NLP 과제**를 직접 구현합니다:

```
📄 문서 분류  →  🔗 문장쌍 분류  →  🏷️ 개체명 인식  →  ❓ 질의응답  →  ✍️ 문장 생성
```

---

## 🗺️ 커리큘럼 및 실습 자료

### 📓 공개 노트북 목록 (학생용)

---

#### 📘 2주차 — 자연어처리 개요와 전이학습

> NLP 모델 전체 파이프라인, Transfer Learning 개념, KcBERT 감성 분류 파인튜닝 실습

| GitHub → Colab | GitHub 파일 |
|:--------------:|:-----------:|
| <a href="https://colab.research.google.com/github/aiiplab/luna-nlp/blob/main/notebooks/Lecture02_Lab_Student.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> | <a href="notebooks/Lecture02_Lab_Student.ipynb" target="_blank">📄 Lecture02\_Lab\_Student.ipynb</a> |

---

#### 📗 3주차 Part 1 — 토큰화 기초: BPE

> Byte-Level BPE 어휘 집합 구축, `vocab.json` · `merges.txt` 생성,  
> GPT 입력값(`input_ids`, `attention_mask`) 생성, `byte_encoder` / `decode_bbpe_token()` 원리

| GitHub → Colab | GitHub 파일 |
|:--------------:|:-----------:|
| <a href="https://colab.research.google.com/github/aiiplab/luna-nlp/blob/main/notebooks/Lecture03_Lab_Student.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> | <a href="notebooks/Lecture03_Lab_Student.ipynb" target="_blank">📄 Lecture03\_Lab\_Student.ipynb</a> |

---

#### 📙 3주차 Part 2 — 토큰화 기초: WordPiece & BPE vs WP 비교

> `BertWordPieceTokenizer`, `vocab.txt`, `##` prefix 원리,  
> BERT 입력값(`input_ids`, `attention_mask`, `token_type_ids`),  
> BPE vs WordPiece 병합 기준(빈도 vs 우도) 정량 비교

| GitHub → Colab | GitHub 파일 |
|:--------------:|:-----------:|
| <a href="https://colab.research.google.com/github/aiiplab/luna-nlp/blob/main/notebooks/Lecture03P2_Lab_Student.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> | <a href="notebooks/Lecture03P2_Lab_Student.ipynb" target="_blank">📄 Lecture03P2\_Lab\_Student.ipynb</a> |

---

### 📅 전체 강의 일정

| 주차 | 주제 | 실습 |
|:----:|------|:----:|
| 1주 | 오리엔테이션 & 환경 설정 | — |
| **2주** | **자연어처리 개요와 전이학습** | ✅ |
| **3주** | **토큰화 기초 (BPE · WordPiece)** | ✅ |
| 4주 | 서브워드/BPE와 어휘집 심화 | 🔜 |
| 5주 | 사전학습 언어모델과 트랜스포머 | 🔜 |
| 6주 | 셀프어텐션과 트랜스포머 구현 | 🔜 |
| 7주 | BERT/GPT 비교와 임베딩 | 🔜 |
| 8주 | ⚡ **중간고사** | — |
| 9주 | 문서 분류 파인튜닝 | 🔜 |
| 10주 | 문서 분류 성능 개선 | 🔜 |
| 11주 | 문장쌍 분류 (자연어추론) | 🔜 |
| 12주 | 개체명 인식과 시퀀스 라벨링 | 🔜 |
| 13주 | 질의응답 (기계독해) | 🔜 |
| 14주 | 문장 생성과 안전 이슈 | 🔜 |
| 15주 | 조별 미니프로젝트 발표 | — |
| 16주 | ⚡ **기말고사** | — |

---

## 🚀 시작하기

### ✅ 방법 1 — GitHub → Colab (권장)

위 표의 배지를 클릭하면 이 저장소의 최신 노트북이 Colab에서 바로 열립니다.

```
1. 배지 클릭 → Colab 자동 실행 (새 탭)
2. 런타임 → 런타임 유형 변경 → 하드웨어 가속기 → None (CPU)   ← 토큰화 실습
3. 첫 번째 셀 실행 (패키지 자동 설치)
4. 구글 드라이브 연동 셀 실행 (결과물 영구 저장)
```

파일을 수동으로 열고 싶다면 Colab 상단 메뉴:
```
파일 → GitHub에서 노트북 열기 → aiiplab/luna-nlp 검색
```

---

### ✅ 방법 2 — 로컬 실행 (고급)

```bash
# 저장소 클론
git clone https://github.com/aiiplab/luna-nlp.git
cd luna-nlp

# 가상환경 생성 (Python 3.10 이상 권장)
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 패키지 설치
pip install -r requirements.txt

# Jupyter 실행
jupyter notebook notebooks/
```

---

## 📂 저장소 구조

```
luna-nlp/
│
├── 📂 notebooks/
│   ├── Lecture02_Lab_Student.ipynb           # 2주 — NLP 개요 · 전이학습 (학생용)
│   ├── Lecture03_Lab_Student.ipynb           # 3주 Part 1 — BPE 토큰화 (학생용)
│   └── Lecture03P2_Lab_Student.ipynb         # 3주 Part 2 — WordPiece & 비교 (학생용)
│
├── assets/
│   └── textbook.png                          # 교재 이미지
├── requirements.txt
└── README.md
```

---

## 📖 교재

<table>
<tr>
<td width="130">
<a href="https://www.yes24.com/Product/Goods/105218899" target="_blank">
<img src="https://raw.githubusercontent.com/aiiplab/luna-nlp/main/assets/textbook.png" alt="Do it! BERT와 GPT로 배우는 자연어 처리" width="120"/>
</a>
</td>
<td>

### Do it! BERT와 GPT로 배우는 자연어 처리
**트랜스포머 핵심 원리와 허깅페이스 패키지 활용법**

- **저자**: 이기창
- **출판사**: 이지스퍼블리싱 (2021)
- **ISBN**: 9791163033165
- **구매**: <a href="https://www.yes24.com/Product/Goods/105218899" target="_blank">YES24</a> · <a href="https://product.kyobobook.co.kr/detail/S000001842348" target="_blank">교보문고</a>
- **저자 공식 사이트**: <a href="https://ratsgo.github.io/nlpbook/" target="_blank">ratsgo.github.io/nlpbook</a> *(무료 열람 가능)*

> 📌 교재 구매는 필수는 아니지만 수업의 기본 자료이므로 가급적 구비를 권장합니다.

</td>
</tr>
</table>

---

## 🔬 LUNA Lab

이 저장소는 동덕여자대학교 **LUNA Lab (Applied AI & Imaging Lab)** 에서 운영합니다.

| 링크 | 내용 |
|------|------|
| 🌐 <a href="https://sites.google.com/view/luna-ailab/home" target="_blank">LUNA Lab 홈페이지</a> | 연구실 소개 및 연구 활동 |
| 🤗 <a href="https://huggingface.co/wonsangyou" target="_blank">HuggingFace</a> | 공개 모델 및 데이터셋 |
| 📧 <a href="mailto:wonsang@dongduk.ac.kr">wonsang@dongduk.ac.kr</a> | 문의 이메일 |

---

## 📋 수강생 유의사항

| 구분 | 내용 |
|------|------|
| **선수 과목 (필수)** | 파이썬프로그래밍(문공A0019) 또는 동등 수준의 파이썬 역량 |
| **선수 과목 (권장)** | 딥러닝(데사K0034) 또는 동등 수준의 딥러닝 기초 |
| **개인 장비** | 노트북·태블릿 등 개인 컴퓨팅 환경 필수 |
| **타 학과 수강** | 가능하나, 선수지식 수준에 따라 학습 부담이 있을 수 있습니다 |
| **장애학생 지원** | 좌석 우선배정, 강의노트(영상물) 제공 |

---

## ⚡ 자주 묻는 질문 (FAQ)

<details>
<summary><b>Q. Colab 세션이 끊겼을 때 파일이 사라졌어요.</b></summary>

Colab 런타임은 **임시 가상 머신**입니다. 세션 종료 시 `/content/` 아래 파일이 모두 삭제됩니다.  
각 노트북의 **구글 드라이브 연동 셀**을 반드시 실행하여 결과물을 저장하세요.

```python
from google.colab import drive
drive.mount('/gdrive', force_remount=True)
```

</details>

<details>
<summary><b>Q. GPU를 써야 하나요?</b></summary>

- **토큰화 실습 (2~4주차)**: CPU로 충분합니다. 런타임 → **None (CPU)**
- **파인튜닝 실습 (9주차~)**: GPU 권장. 런타임 → **T4 GPU**

</details>

<details>
<summary><b>Q. `No such file or directory` 에러가 나요.</b></summary>

저장 경로가 아직 생성되지 않은 경우입니다. 학습 셀 상단에 아래 코드를 추가하세요:

```python
import os
os.makedirs(SAVE_DIR, exist_ok=True)
```

</details>

<details>
<summary><b>Q. vocab.json에서 한국어가 깨져 보여요.</b></summary>

BPE(BBPE)는 **UTF-8 바이트를 특수 유니코드 문자로 1:1 매핑**합니다 — 오류가 아닙니다.  
노트북의 `decode_bbpe_token()` 함수로 한국어를 복원할 수 있습니다.  
WordPiece(BERT)의 `vocab.txt`는 한국어를 그대로 저장하므로 이 현상이 없습니다.

</details>

---

## 📜 라이선스

이 저장소의 코드는 <a href="LICENSE" target="_blank">MIT License</a> 하에 공개됩니다.  
교재 본문 및 이지스퍼블리싱 저작권물은 해당 출판사의 저작권 정책을 따릅니다.

---

<div align="center">

**동덕여자대학교 데이터사이언스전공 LUNA Lab**  
© 2025 Wonsang You · <a href="https://sites.google.com/view/luna-ailab/home" target="_blank">sites.google.com/view/luna-ailab/home</a>

⭐ 이 저장소가 도움이 되었다면 Star를 눌러주세요!

</div>

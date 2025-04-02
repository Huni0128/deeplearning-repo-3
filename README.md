# DORA

## 프로젝트 소개
본 프로젝트는 사용자의 외로움을 덜어주고, 일상생활에서 필요한 정보를 비서처럼 알려주며, 정신 건강을 챙겨주는 **돌봄 챗봇 GUI 프로그램**입니다. 향후에는 실제 돌봄 로봇과 결합하여 정서적 교감과 실질적 도움을 동시에 제공하는 통합 서비스를 목표로 합니다.

---
## 주제 선정 배경
최근 인공지능(AI) 기술의 급속한 발전과 함께 사용자와 자연스럽게 소통할 수 있는 챗봇(Chatbot)에 대한 관심이 증가하고 있습니다. 특히 고객 서비스, 교육, 의료 및 개인 비서 분야 등에서 챗봇의 활용이 폭발적으로 늘어나고 있으며, 이는 사용자의 편의성과 접근성을 크게 향상시키는 데 기여하고 있습니다.

동시에 사회적 변화로 인해 1인 가구가 증가하면서 정서적 외로움이나 심리적 스트레스 문제도 점차 심각해지고 있습니다. 혼자 사는 사람들은 귀가 후 대화 상대의 부재로 인해 심리적 안정과 정서적 지원이 부족한 상황이 많습니다. 이로 인해 디지털 포용(Digital Inclusion)과 정서적 지원의 중요성이 더욱 부각되고 있습니다.

기존의 챗봇 시스템은 주로 텍스트 기반의 소통에 머무르는 경우가 많았으나, 인간의 감정을 정확히 이해하고 공감하는 능력은 여전히 부족한 상태입니다. 이에 따라 최근에는 음성 및 감정 분석 기술을 접목하여 사용자의 정서를 더 정확히 파악하고, 대화를 통해 심신의 안정감과 편안함을 제공하는 챗봇의 필요성이 높아지고 있습니다.

본 프로젝트는 음성 감정 분석 기반 챗봇을 통해 사용자와의 소통 품질을 한 단계 높이고, 사용자의 감정을 인식하고 공감하는 방식으로 심리적 안정을 제공하고자 합니다. 이를 통해 1인 가구를 포함한 다양한 사용자에게 정서적 위안을 주고, 보다 편안하고 릴렉스한 생활 환경을 조성하는 것이 목표입니다.

이러한 챗봇 기술은 특히 정서적 지원이 필요한 고객 상담, 정신 건강 관리, 개인 맞춤형 서비스 등에서 혁신적이고 효과적인 활용 가능성을 지니고 있어 그 필요성과 가치가 매우 높다고 판단하여 본 주제를 선정하였습니다.

---

## 주요 기능

| 기능 분류         | 세부 내용 |
|------------------|-----------|
| 정서적 돌봄       | - 일상 대화 및 교감 제공<br>- 가상 펫 또는 캐릭터 형태로 정서적 연결 지원 |
| 정보 및 일정 관리 | - 일정 알림, 할 일 목록 제공<br>- 일상 정보 및 유용한 생활 팁 전달 |
| 정신 건강 모니터링 | - 감정 인식 및 상태 모니터링<br>- 위급 상황 감지 시 경고 및 알림 제공 |

---

## 개발 배경
별도의 센서 없이 신체적 건강 상태를 파악하는 데에는 현실적인 한계가 존재합니다. 따라서 본 프로젝트는 사용자의 대화와 감정을 바탕으로 한 **정신 건강 관리와 정서적 돌봄**에 집중하고 있습니다.

---

## 시스템 구성

| 구성 요소           | 설명 |
|--------------------|------|
| 챗봇 인터페이스     | GUI 기반 사용자 대화 창 구성 |
| 자연어 처리 (NLP)   | 사용자 입력의 감정 및 의도 분석 |
| 감정 인식           | 표정(영상) 및 음성 기반의 감정 판단 |
| 대화 페르소나 시스템 | 사용자 맞춤형 대화 스타일 구현 (심심이, Character.AI 유사) |

---

## 참고 서비스

| 분류         | 사례 |
|--------------|------|
| 페르소나 챗봇 | [SimSimi](https://simsimi.com), [Character.AI](https://beta.character.ai/) |
| 로봇 + AI 펫  | Sony AIBO, RoboHon |
| 돌봄 로봇     | Pepper, ElliQ |

---

## **NangMan**팀 구성

| 역할   | 이름       |
|--------|------------|
| 팀장   | 김연우     |
| 팀원   | 나덕윤     |
| 팀원   | 심채훈     |
| 팀원   | 임동욱     |

---

## 기술 스택

| **분류**               | **사용 기술** |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Language**           | ![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat-square&logo=Python&logoColor=white) |
| **GUI Framework**      | ![PyQt5](https://img.shields.io/badge/PyQt5-GUI%20Framework-green?style=flat-square&logo=qt&logoColor=white) &nbsp; ![Tkinter](https://img.shields.io/badge/Tkinter-GUI%20Framework-lightgrey?style=flat-square) |
| **영상/얼굴 인식**      | ![OpenCV](https://img.shields.io/badge/OpenCV-Video%20Processing-orange?style=flat-square&logo=opencv&logoColor=white) &nbsp; ![Mediapipe](https://img.shields.io/badge/Mediapipe-Face%20Landmarks-red?style=flat-square) |
| **음성 처리**          | ![SpeechRecognition](https://img.shields.io/badge/SpeechRecognition-Audio-yellow?style=flat-square) |
| **딥러닝 프레임워크**   | ![TensorFlow](https://img.shields.io/badge/TensorFlow-ML-orange?style=flat-square&logo=tensorflow) &nbsp; ![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red?style=flat-square&logo=pytorch) |
| **자연어 처리 (NLP)**  | ![Transformers](https://img.shields.io/badge/Transformers-HuggingFace-yellow?style=flat-square&logo=huggingface) &nbsp; ![KoBERT](https://img.shields.io/badge/KoBERT-Korean%20NLP-blue?style=flat-square) |
| **Database**           | ![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=flat-square&logo=mysql) &nbsp; ![SQLite](https://img.shields.io/badge/SQLite-LightweightDB-lightblue?style=flat-square&logo=sqlite) |

---

## 설치 및 실행 방법

```bash
# 의존성 설치
pip install -r requirements.txt

# 실행
python main.py

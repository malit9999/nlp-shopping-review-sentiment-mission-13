# Shopping Review Sentiment Analysis

> **Bootcamp Mission 13** | Natural Language Processing

## 미션 소개
쇼핑몰 리뷰 텍스트의 감성을 분류하고, 전체 파인튜닝과 PEFT 방식의 차이를 비교하는 NLP 미션입니다. 모델 성능뿐 아니라 학습 비용과 효율의 관점도 함께 다룹니다.

## 구현 목표
- 리뷰 텍스트를 긍정·부정 감성으로 분류한다.
- Full Fine-Tuning과 PEFT의 학습 방식을 비교한다.
- 성능·자원·재사용성 관점에서 모델을 평가한다.

## 주요 구현 내용
- 쇼핑 리뷰 감성 분류
- 전체 파인튜닝 실험
- PEFT 기반 효율적 파인튜닝 비교

## 사용 기술
- Python
- Transformers
- PEFT
- NLP
- Jupyter Notebook

## 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission13.ipynb
```

> 데이터셋 또는 사전학습 모델이 외부에서 제공되는 경우, 실행 전에 노트북 또는 코드의 데이터 로드 설정을 확인해야 합니다.

## 폴더 구조
```text
notebooks/
  mission13.ipynb
README.md
requirements.txt
.gitignore
```

## 학습 내용
- 파인튜닝 전략에 따라 학습 가능한 파라미터와 자원 요구량이 달라진다는 점
- 감성 분류 결과는 데이터 품질과 레이블 정의에 의존한다는 점

## 트러블슈팅 및 재현 시 참고 사항
사전학습 모델 다운로드와 GPU 환경 여부에 따라 실행 시간이 달라질 수 있습니다.

## 결과 확인
학습 전략별 감성 분류 결과는 노트북에서 확인할 수 있습니다.

## 포트폴리오 관점
이 저장소는 **Natural Language Processing** 역량을 학습·실험한 결과물입니다. 구현 범위와 실행 조건은 코드 및 노트북을 기준으로 확인할 수 있습니다.
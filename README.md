# Bootcamp Mission 13 - 쇼핑몰 리뷰 감성 분석

## 1. 개요
쇼핑몰 리뷰 데이터를 대상으로 Full Fine-Tuning과 PEFT(LoRA)를 비교한 감성 분석 미션입니다.

## 2. 목표
KcELECTRA 기반 감성 분류 모델을 학습하고, 전체 파인튜닝과 LoRA 방식의 성능 및 효율을 비교하는 것을 목표로 했습니다.

## 3. 사용 기술
- Python
- pandas
- numpy
- matplotlib
- scikit-learn
- torch
- transformers
- datasets
- evaluate
- peft
- emoji
- soynlp

## 4. 주요 기능
- AI Hub 리뷰 데이터 전처리
- KcELECTRA Full Fine-Tuning
- PEFT LoRA 학습
- Macro F1 및 모델 크기 비교

## 5. 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission13.ipynb
```

## 6. 주요 파일
- `notebooks/mission13.ipynb`

## 7. 폴더 구조
```text
bootcamp-mission-13
  .gitignore
  notebooks/
    mission13.ipynb
  README.md
  requirements.txt
```

## 8. 학습 내용
감성 분석 모델을 배포 관점에서 비교하며 성능, 저장 용량, 학습 효율의 균형을 학습했습니다.

## 9. 트러블슈팅
미션을 진행하며 발생한 오류와 해결 과정은 노트북 또는 보고서에 정리했습니다.

## 10. 결과 화면
결과 이미지는 노트북 출력, 보고서 또는 `images/` 폴더에서 확인할 수 있습니다.

## 11. 공개 전 확인 사항
- 제출 노트북만 포함했으며, 원본 데이터와 모델 파일은 공개 범위 확인 전 포함하지 않았습니다.

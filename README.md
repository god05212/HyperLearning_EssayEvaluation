# HyperLearning_EssayEvaluation
# 에세이 분석 및 예측 프로젝트

이 프로젝트는 학생들의 에세이 데이터를 분석하여 에세이 점수를 예측하는 모델을 개발하는 것입니다. 데이터는 학생들의 에세이와 평가 정보를 포함하고 있으며, 이를 바탕으로 에세이의 다양한 특성(글자수, 문장 수, 고유 단어 수 등)과 점수 간의 관계를 분석합니다. 최종적으로 여러 회귀 모델을 사용하여 에세이 점수 예측 모델을 구축합니다.

### 각 파일/폴더 설명
- **/src**: 프로젝트의 핵심 코드가 포함된 폴더입니다. 데이터 처리, 모델 학습 및 평가와 관련된 코드가 이 폴더에 저장됩니다.
  - `HyperLearning_EssayEvaluation.ipynb`: 프로젝트 전체 코드가 작성된 Jupyter Notebook 파일입니다. 데이터 전처리, 분석, 모델 학습 및 평가 등의 모든 과정이 이 파일 내에서 이루어집니다.

- **/data**: 실제 데이터는 포함되지 않으며, 샘플 데이터나 데이터 처리에 필요한 스크립트만 포함됩니다.
  - `sample_data.csv`: 예시 데이터를 포함하는 CSV 파일로, 실제 데이터는 포함되지 않습니다.

- **/docs**: 프로젝트와 관련된 문서가 포함된 폴더입니다.
  - `report.pdf`: 프로젝트의 최종 보고서 또는 문서화된 결과물입니다.

- **README.md**: 프로젝트의 개요, 설치 방법, 실행 방법, 사용 방법 등을 설명하는 파일입니다.

- **requirements.txt**: 프로젝트 실행에 필요한 Python 패키지 목록을 나열한 파일입니다. `pip install -r requirements.txt` 명령어로 필요한 패키지를 설치할 수 있습니다.

- **.gitignore**: Git에서 추적하지 않도록 제외할 파일이나 폴더를 나열하는 파일입니다.

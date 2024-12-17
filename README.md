| Folder Name| Description|
|-----------------------------------|-----------------------------------------------------------------------------------------------|
| MNIST                             | E02.ipynb를 통해 다운된 MNIST 데이터셋|
| images                            | 손글씨 관련 이미지들이 저장된 폴더. -cropped_handwritten.jpg : 수집한 손글씨 이미지의 숫자영역만을 남기고 crop한 이미지 -handwritten_my.jpg : 직접 작성한 손글씨 이미지 -handwritten.jpg : 수집한 손글씨 이미지  아래 하위폴더들로 구성되어있음. |
| ├─inf_results                     | 수집한 손글씨의 Inference 결과가 저장됨 -*.png_preprocess_inverted_dilated.png : 파일별 모델 입력 전 후 이미지 -results_summary.csv : Inference의 예측 성공/실패 여부 및 예측 실패한 파일명이 기록된 파일|
| ├─inf_source                      | 수집한 손글씨의 crop된 이미지. 각 숫자별로 폴더링 되어있음. |
| ├─my_cropped                      | 직접 작성한 손글씨의 crop된 이미지 |
| ├─my_results                      | 직접 작성한 손글씨 이미지를 inference하였을 때의 결과 이미지들이 저장되어있음. trial 순서별로 폴더링되어있음.|
| └─교수님 손글씨 인증사진          | 손글씨를 작성해주신 교수님들과의 인증사진|
| Final Project - 나의 해방일지.pdf | 해당 프로젝트의 진행 과정이 기록된 파일|
| model_complete.pth                | 최종적으로 학습된 모델|
| E02.ipynb                         | Train부터 Inference까지의 과정을 수행하는 ipynb파일|
| preprocessing.ipynb               | 손글씨 사진의 전처리를 진행하는 ipynb파일|
| SUBMIT.txt                        | E02 제출을 위한 필수 포함 파일|
| README.md                         | 해당 프로젝트의 폴더 구성을 설명하는 파일|

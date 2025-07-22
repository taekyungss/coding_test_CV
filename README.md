# coding_test_CV

모델의 `.pt` 파일은 GitHub 용량 제한으로 인해 별도로 Google Drive에 업로드했습니다.

📁 [Google Drive - 모델 pt 파일 저장 위치](https://drive.google.com/drive/folders/1Kk4f56kLYzsOA7caMhcb4vKIM4VTzbdE?usp=sharing)

## Result
| Model             | Pretrained | ValAcc | ValPrecision | ValRecall | ValF1  |
| ------------------- | ---------- | ------ | ------------ | --------- | ------ |
| ResNet50            | w/o        | 0.7270 | 0.7444       | 0.7270    | 0.7284 |
| ResNet50            | w/ ImageNet| 0.9236 | 0.9258       | 0.9236    | 0.9234 |
| ViT-S/16            | w/o        | 0.2243 | 0.1864       | 0.2243    | 0.1587 |
| ViT-S/16            | w/ ImageNet| 0.9726 | 0.9730       | 0.9726    | 0.9726 |

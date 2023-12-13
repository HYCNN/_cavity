# cavity

## 실험 모델
EfficientNet-b#~

EfficientNetV2-s (TBA 12/05)

EfficientNetV2-m (TBA 12/06)

## 실험 결과
|Model|n_epochs|batch_size|img_size|Accuracy(%)|
|--|--|--|--|--|
|EfficientNet-b3|28|16|340|88.00|
|EfficientNet-b4|58|10|380|95.20|
|EfficientNet-b5|36|4|456|90.40|
|EfficientNetV2-s|33|16|400|92.80|
|EfficientNetV2-m|23|16|400|91.60|


|Model|n_epochs|batch_size|img_size|Accuracy(%)|
|--|--|--|--|--|
|RD4AD|200|64|256|62.78|


|Model|Accuracy(%)|
|--|--|
|RD4AD|62.78|
|ViTB-16-224|78.93|
|Mobilenet_v2-finetuned|79.23|
|DINOv2-base-finetuned|80.04|
|EfficientNet-b4|95.20|

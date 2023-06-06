# opensw23-team_CWH
오픈소스SW  deep learning 프로젝트

# Team Introduction
 202011381 최우헌 / ID: wooheon00

# Topic Introduction
  
human-pose-estimation-opencv

Recognize each body part of the person in the image.
Each part is connected by a skeleton.

# Results
Skeleton created above image
![output](https://github.com/wooheon00/opensw23-team_CWH/assets/127184013/3917f565-e24c-49ca-a419-04cacd9081aa)


# Analysis/Visualization

1.threshold(임계값)

각각 감지된 키포인트에 대해 신뢰도 점수를 구하고 임계값보다 큰 키포인트 감지만 유효로 간주됩니다.




# Installation

- clone repository
```
    git clone https://github.com/quanhua92/human-pose-estimation-opencv
```
- download input image
download input image
and save image file to [human-pose-estimation-opencv] 

- test image
```
    python openpose.py --input [input image file name]
```
- test with webcam
```
    python openpose.py
```

# Presentation

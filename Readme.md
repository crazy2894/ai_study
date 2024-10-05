### 기본 시각화 코드
<details>
<summary>🧑‍💻code🧑‍💻</summary>

```py
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib as mpl
import matplotlib.pyplot as plt
import matplotlib_inline.backend_inline

matplotlib_inline.backend_inline.set_matplotlib_formats("png2x") # svg, retina, png2x ...
mpl.style.use("seaborn-v0_8")
mpl.rcParams.update({"figure.constrained_layout.use": True})
sns.set_context("paper") 
sns.set_palette("Set2") 
sns.set_style("whitegrid") 

# 시스템 폰트패밀리에 따라 변경
plt.rc("font", family = "NanumSquareRound")
plt.rcParams["axes.unicode_minus"] = False
```
</details>

## AI study
- [Notion 링크](https://royal-offer-53a.notion.site/KDT-2024-05-2024-09-10bf678f80468069b4e1e2f0a631131a?pvs=4)
- [전체 파일 구조](mds/00_files.md)

### 목차
- [1. 머신러닝](mds/01_ml.md)
- [2. 샘플링](mds/02_sampling.md)
- [3. 딥러닝](mds/03_dl.md)
- [4. 모델 평가](mds/04_metrics.md)
- [5. 분류 및 회귀 문제](mds/05_diversity.mds)
- [6. 시계열](mds/06_time_series.md)

## 참고 링크
[roboflow](https://roboflow.com/) <br>
[ultraytics](https://docs.ultralytics.com/integrations/roboflow/) <br>
[Learn open cv](https://learnopencv.com/)  <br>
[supervisely](https://supervisely.com/) <br>
[superb ai](https://superb-ai.com/ko) <br>
[label studio](https://labelstud.io/) -> 오디오에서 감성 분석 가능 <br>

### segmentation tool
[Label Studio](https://labelstud.io/guide/) <br>
[Label Me](https://github.com/labelmeai/labelme) <br>
[Anylabeling](https://github.com/vietanhdev/anylabeling) <br>
[X-Anylabeling](https://github.com/CVHub520/X-AnyLabeling) <br>
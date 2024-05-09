

# 慧眸智行

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<p align="center">
  <a href="https://github.com/shaojintian/Best_README_template/">
    <img src="https://i.postimg.cc/PxRcKZSx/428e9b08439e8a39830b78b635659a8.jpg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">慧眸智行</h3>
  <p align="center">
    基于脑电和眼电多模态融合的疲
劳驾驶检测系统
    <br />
  </p>


 本篇README.md面向所以脑机接口及多模态领域开发者。

## 目录

[TOC]

### 上手指南

###### 开发前的配置要求

1. 配置git命令。

###### **安装步骤**

```sh
git clone https://github.com/echo-carrie/
git clone https://github.com/echo-carrie/Wisegaze.git
cd Wisegaze.
```

### 文件目录说明

```
D:.
│  .gitattributes
│  App.py
│  database.py
│  fire_alarm.ogg
│  my_history.npy
│  README.md
│  requirements.txt
│  View.py
│
├─.idea
│  │  .gitignore
│  │  misc.xml
│  │  modules.xml
│  │  vcs.xml
│  │  Wisegaze_web.iml
│  │
│  └─inspectionProfiles
│          profiles_settings.xml
│
├─.vscode
│      launch.json
│
├─instance
│      Fire_Alerts.db
│      Fire_Location.db
│
├─Models
│      fire_smoke_and_nonfire_detection.h5
│      yolocff.pt
│
├─static
│  │  270078_jesien_jezioro_mgla_drzewa_kamienie.jpg
│  │  4aa4bc94aa4da9048683e315c1b5cb65.jpg
│  │  890814-forest-trees-nature-landscape-tree-autumn.jpg
│  │  About_Image.jpeg
│  │  deforestation.jpg
│  │  Dr-Sarah-Sarkis_Unmistakable-Creative-podcast.png
│  │  Fire_Logo.png
│  │  Fire_logo_title.jpg
│  │  Free-download-Desktop-Fun-Cool-Forest-Wallpapers-1600x1067-.jpg
│  │  jquery-3.6.3.js
│  │  logo.png
│  │  mapsJavaScriptAPI.js
│  │  neural.png
│  │  pexels-photo-1547813.jpeg
│  │  section5bgimg.jpg
│  │  toppng.com-forest-png-image-forest-clip-art-black-and-white-2334x761.png
│  │  tuxpi.com.16803469443.jpg
│  │  tuxpi.com.1681837124.jpg
│  │  wp7287036.jpg
│  │
│  ├─css
│  │      About_Style.css
│  │      FireAlerts.css
│  │      Home_Style.css
│  │      LiveMonitor.css
│  │      Location.css
│  │      ModelTesting.css
│  │      Prediction.css
│  │
│  ├─graphs
│  │      Acc_plot.png
│  │      Capture.JPG
│  │      confusion_matrix_test.png
│  │      confusion_matrix_train.png
│  │      confusion_matrix_val.png
│  │      Fire_test1.jpg
│  │      Loss_plot.png
│  │      Non_fire_test3.jpg
│  │      ROC_curve-test.png
│  │      ROC_curve-train.png
│  │      ROC_curve-val.png
│  │      Smoke_test2.jpg
│  │      testing.jpg
│  │      train_classify.jpg
│  │      val classify.jpg
│  │
│  ├─img
│  │      Bg-Image-1.jpg
│  │      Bg-Image-2.jpg
│  │      Bg-Image-3.jpg
│  │      Bg-Image-4.jpg
│  │
│  ├─shots
│  │      shot_2023-07-09 195056.352779.png
│  │      shot_2023-07-09 195056.953434.png
│  │      shot_2023-07-09 195100.385895.png
│  │      shot_2023-07-09 195101.014111.png
│  │      shot_2023-07-09 195101.738947.png
│  │      shot_2023-07-09 195102.405570.png
│  │      shot_2023-07-09 195103.073078.png
│  │      shot_2023-07-09 195103.760689.png
│  │      shot_2023-07-09 195104.395364.png
│  │      shot_2023-07-09 195105.086017.png
│  │      shot_2023-07-09 195105.768204.png
│  │      shot_2023-07-09 195121.611895.png
│  │      shot_2023-07-09 195123.359254.png
│  │      shot_2023-07-09 195124.577567.png
│  │      shot_2023-07-09 195202.467190.png
│  │      shot_2023-07-09 195203.684164.png
│  │      shot_2023-07-09 195204.524194.png
│  │      shot_2023-07-09 195206.310123.png
│  │      shot_2023-07-09 195207.504363.png
│  │      shot_2023-07-09 195243.993071.png
│  │      shot_2023-07-09 195244.619228.png
│  │      shot_2023-07-09 195245.928107.png
│  │      shot_2023-07-09 195246.580313.png
│  │      shot_2023-07-09 195247.875177.png
│  │      shot_2023-07-09 195248.518345.png
│  │      shot_2023-07-09 195250.362899.png
│  │      shot_2023-07-11 152529.352560.png
│  │      shot_2023-07-11 152530.678616.png
│  │      shot_2023-07-11 152531.347272.png
│  │      shot_2023-07-11 152532.020893.png
│  │      shot_2023-07-11 152533.819058.png
│  │      shot_2023-07-11 152534.445262.png
│  │      shot_2023-07-11 152537.899578.png
│  │      shot_2023-07-11 152539.075439.png
│  │      shot_2023-07-11 152545.265905.png
│  │      shot_2023-07-11 152546.604341.png
│  │      shot_2023-07-11 152548.327854.png
│  │      shot_2023-07-11 152549.526731.png
│  │      shot_2023-07-11 200112.644112.png
│  │      shot_2023-07-11 200438.093926.png
│  │      shot_2023-07-12 201108.477840.png
│  │      shot_2023-07-12 201109.467277.png
│  │      shot_2023-07-12 201111.116836.png
│  │      shot_2023-07-12 201112.075416.png
│  │      shot_2023-07-12 201115.241295.png
│  │      shot_2023-07-12 201117.603258.png
│  │      shot_2023-07-12 201118.495746.png
│  │      shot_2023-07-12 201120.751538.png
│  │      shot_2023-07-12 201127.269518.png
│  │      shot_2023-07-12 201128.234992.png
│  │      shot_2023-07-12 201129.680586.png
│  │      shot_2023-07-12 201130.532113.png
│  │      shot_2023-07-12 201131.502779.png
│  │      shot_2023-07-12 201133.785204.png
│  │      shot_2023-07-12 201136.090384.png
│  │      shot_2023-07-12 201137.009203.png
│  │      shot_2023-07-12 201137.921679.png
│  │      shot_2023-07-12 201138.923107.png
│  │      shot_2023-07-12 201139.778625.png
│  │      shot_2023-07-12 201140.685108.png
│  │      shot_2023-07-12 201140.6851088.png
│  │      shot_2023-07-12 201142.640380.png
│  │      shot_2023-07-12 201143.540865.png
│  │      shot_2023-07-12 201144.396374.png
│  │      shot_2023-07-12 201145.972476.png
│  │      shot_2023-07-12 201148.329129.png
│  │      shot_2023-07-12 201151.940060.png
│  │      shot_2023-07-12 201153.468202.png
│  │      shot_2023-07-12 201155.010306.png
│  │      shot_2023-07-12 201158.119529.png
│  │      shot_2023-07-12 201158.944053.png
│  │      shot_2023-07-12 201201.862453.png
│  │      shot_2023-07-12 201204.734635.png
│  │      shot_2023-07-12 201206.760895.png
│  │      shot_2023-07-12 201208.078140.png
│  │      shot_2023-07-12 201208.799728.png
│  │      shot_2023-07-12 201211.375255.png
│  │      shot_2023-07-12 201212.137820.png
│  │      shot_2023-07-12 201212.867402.png
│  │      shot_2023-07-12 201213.592986.png
│  │      shot_2023-07-12 201215.620570.png
│  │      shot_2023-07-12 201219.611055.png
│  │      shot_2023-07-12 201434.579409.png
│  │      shot_2023-07-12 201435.997607.png
│  │      shot_2023-07-12 201436.121538.png
│  │      shot_2023-07-12 201437.684635.png
│  │      shot_2023-07-12 201438.698351.png
│  │      shot_2023-07-12 201441.310000.png
│  │      shot_2023-07-12 201442.901566.png
│  │      shot_2023-07-12 201450.306620.png
│  │      shot_2023-07-12 201453.516783.png
│  │      shot_2023-07-12 201454.890998.png
│  │      shot_2023-07-12 201456.872735.png
│  │      shot_2023-07-12 201505.669126.png
│  │      shot_2023-07-21 140245.460646.png
│  │      shot_2023-07-21 140246.447870.png
│  │      shot_2023-07-21 140247.271427.png
│  │      shot_2023-07-21 140248.029035.png
│  │      shot_2023-07-21 140248.791773.png
│  │      shot_2023-07-21 140249.559521.png
│  │      shot_2023-07-21 140250.931732.png
│  │      shot_2023-07-21 140251.685470.png
│  │      shot_2023-07-21 140252.472620.png
│  │      shot_2023-07-21 140253.214798.png
│  │      shot_2023-07-21 140253.995005.png
│  │      shot_2023-07-21 140254.847537.png
│  │      shot_2023-07-21 140256.866614.png
│  │      shot_2023-07-21 140257.629690.png
│  │      shot_2023-07-21 140653.875148.png
│  │      shot_2023-07-21 140659.113272.png
│  │      shot_2023-07-21 160439.649775.png
│  │      shot_2023-07-21 160705.714085.png
│  │      shot_2023-07-21 160706.645989.png
│  │      shot_2023-07-21 160707.383422.png
│  │      shot_2023-07-21 160708.104009.png
│  │      shot_2023-07-21 160708.827950.png
│  │      shot_2023-07-21 160710.110927.png
│  │      shot_2023-07-21 160710.856499.png
│  │      shot_2023-07-21 160711.568264.png
│  │      shot_2023-07-21 160712.320834.png
│  │      shot_2023-07-21 160712.494732.png
│  │      shot_2023-07-21 160713.421237.png
│  │      shot_2024-03-02 002858.002521.png
│  │
│  ├─uploads
│  │      0ULOZL0JQ3SN.jpg
│  │      1.png
│  │      9.png
│  │      Fire (36).png
│  │      Non_Fire (1).jpg
│  │      shot_2023-07-21 160710.110927.png
│  │      Smoke (1) - Copy.jpeg
│  │      Smoke (2).jpeg
│  │      Smoke (2).jpg
│  │      Smoke (2).png
│  │      Smoke (3).png
│  │
│  └─video
│          vid_2023-07-07 171226.640097.avi
│          vid_2023-07-11 152500.673205 .avi
│          vid_2023-07-12 201017.647450 .avi
│
└─templates
        About.html
        FireAlerts.html
        index.html
        LiveMonitor.html
        Location.html
        ModelTesting.html
        Prediction.html
```

### 使用到的框架及组件

- [YOLOv5](https://github.com/ultralytics/yolov5)
- [Pytroch]([PyTorch](https://pytorch.org/))
- [jQuery](https://jquery.com)
- [Flask](https://flask.github.net.cn/)
- [高德地图](https://github.com/ultralytics/yolov5)

### 贡献者





### 作者

xxx@xxxx

### 鸣谢


- [SEED-VIG-CNN: 针对上海交大SSED-VIG数据集做的一个融合脑电和眼电的特征信息推断是否疲劳驾驶的网络 ](https://github.com/dttutty/SEED-VIG-CNN)
- [stevenjoezhang/live2d-widget: 把萌萌哒的看板娘抱回家 (ノ≧∇≦)ノ | Live2D widget for web platform](https://github.com/stevenjoezhang/live2d-widget)

[项目地址]:https://github.com/echo-carrie/Wisegaze	"慧眸智行"






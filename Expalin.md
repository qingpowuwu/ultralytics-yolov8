## 设置 ultralytics 到环境变量

把 ultralytics 文件夹设置成环境变量

```
nano ~/.bashrc
export ultralytics=/data/Project_4_Thyroid_Final/11_yolov8/2_ultralytics-main
source ~/.bashrc
```

然后在 .py 代码中填写：

```
# %pip install ultralytics
import sys
sys.path.append('/data/Project_4_Thyroid_Final/11_yolov8/2_ultralytics-main')
import ultralytics
ultralytics.checks()
```

即可调用

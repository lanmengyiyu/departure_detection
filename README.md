本项目是离岗检测的解决方案，检测采用的是[yolov5](https://github.com/ultralytics/yolov5)

## Requirements

Python 3.7 or later with all `requirements.txt` dependencies installed, including `torch >= 1.5`. To install run:
```bash               
$ pip install -U -r requirements.txt
```


## Tutorials

* [departure_detection-Notebook](https://github.com/lanmengyiyu/departure_detection/blob/master/departure_detection.ipynb) <a href="https://colab.research.google.com/github/lanmengyiyu/departure_detection/blob/master/departure_detection.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>


## Inference

Inference can be run on most common media formats. Results are saved to `./inference/output`.To run inference on examples in the `./inference/images` folder
```bash

python detect.py --weights yolov5x.pt
                 --img 460 
                 --conf 0.5 
                 --source "/content/drive/My Drive/video/departure_detection.avi" 
                 

```

## Contact

**Issues should be raised directly in the repository.** email Glenn Jocher at 545277714@qq.com. 

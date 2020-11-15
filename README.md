# gocv-yolov4
GoCV implementation of YOLOv4

## Install
```sh
> go get -u -d gocv.io/x/gocv
> cd $GOPATH/src/gocv.io/x/gocv
> make install
```
## Model Download
**Download [yolov4.weights](https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov4.weights)**  
**Download [yolov4.cfg](https://raw.githubusercontent.com/AlexeyAB/darknet/master/cfg/yolov4.cfg)**

## Preview
```sh
> go run main test.jpg
```
<img src="https://github.com/gron1gh1/gocv-yolov4/blob/main/test.jpg" height="300">
<img src="https://github.com/gron1gh1/gocv-yolov4/blob/main/result.jpg" height="300">

```sh
> go run video.go vtest.avi
```
![preview](https://user-images.githubusercontent.com/41789633/99181680-4e1a4980-2773-11eb-8522-e3765cc9425c.gif)  
**GPU is not used in the test environment😂**  
**So it is very slow but works well😉**  

## Usage
```sh
# VIDEO and URL
> go run video.go {VIDEO_FILE or RTSP URL}

# Picture File
> go run main.go {PICTURE FILE NAME}
```

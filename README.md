#ORＢ feature extraction and matching

This is a basic demo of feature matching<br> 
For more information you can watch this video:<br>
[ＯＲＢ特征提取与匹配](http://v.youku.com/v_show/id_XMjYxMjYwNzAyNA==.html?from=s1.8-1-1.2&spm=a2h0k.8191407.0.0)<br>
#How to Run

##Required Dependencies
####Eigen3<br>
Install with <br>
```
sudo apt-get install libeigen3-dev
```
####OpenCV<br>
Install with <br>
```
sudo apt-get install libopencv-dev
```
##Build and Run
```
cd orb
mkdir build
cd build
cmake ..
make -j4
./feature_extraction 1.png 2.png
```

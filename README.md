# Faster_RCNN_ncnn for the ncnn framework
Papers <br/>
https://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf <br/>
Training set: VOC2007 <br/>
Size: 600x600 (!) <br/>
Prediction time: 26042 mSec(!) (RPi 4) <br/>
<br/>
Special made for a bare Raspberry Pi see: https://qengineering.eu/opencv-c-examples-on-raspberry-pi.html <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/Faster_RCNN_ncnn/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
Traffic.jpg <br/>
ZF_faster_rcnn_final.bin (download this file from: https://drive.google.com/open?id=1w3F4PL03SVtvoS_ux_GfCkY0YLMGH-yA )<br/>
ZF_faster_rcnn_final.proto <br/>
Faster_rcnn.cpb <br/>
fasterrcnn.cpp <br/>
 <br/>
Run Faster_rcnn.cpb with Code::Blocks. Remember, you also need a working OpenCV 4 on your Raspberry. <br/>

![output image]( https://qengineering.eu/images/Faster_rcnn_trafic.jpg )


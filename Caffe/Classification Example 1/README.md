
A simple caffe program for a toy classification problem. A animal or human toy image classification problem is used here. Dataset is prepared by taking the images from standard image datasets. A Lenet like CNN network is used. <br>

To run this example: <br>

Setting up,
1. Download [https://github.com/s9xie/hed](this) version of Caffe into a folder /path/to/caffe/ <br>
2. Install caffe and its dependencies by following the steps [http://caffe.berkeleyvision.org/installation.html](here).  <br>
3. Install pycaffe by running make pycaffe in /path/to/caffe/  <br>
4. Down the folder "Classification Example 1" and place it in /path/to/caffe

For training,
5. run the script example_train_test.py using the command:
$ python example_train_test.py

For testing,
6. ../build/tools/caffe test -model ./example_train_test.prototxt -weights ./logdir/dnn_iter_200000.caffemodel -iterations 100

For deploying,
7.run the script example_deploy.py using the command:
$ python example_train_test.py  (you may specify the image to use inside the python scipt)
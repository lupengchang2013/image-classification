# image-classification
how to run this program:
1. Install python and tensorflow (Mac) -- can skip this step if you have it
run following command in shell
$ sudo easy_install pip

$ sudo pip install --upgrade virtualenv

$ virtualenv --system-site-packages

$ source ~/tensorflow/bin/activate

(tensorflow)$ easy_install -U pip

(tensorflow)$ pip install --upgrade tensorflow 

after running above command, python 2.7 and tensorflow shold be installed in your mac. activate your python virtualenv everytime
when running tensorflow app using command: $ source ~/tensorflow/bin/activate and deactive it by command: (tensorflow)$ deactivate


2. running app
clone the repo to local and cd to it's folder, run following command, you will see the magic:
$ python run_fc_model.py

you can check the visual result by running this command: tensorboard --logdir=tf_logs, then just open your browser and go to
http://localhost:6006, that's it

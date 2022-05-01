机器自己创作诗歌

install tensorflow https://www.geeksforgeeks.org/install-tensorflow-on-macos/

python3 --version
brew --version


https://blog.csdn.net/weixin_44613063/article/details/106815164

migrate tensorflow from 1.x to 2.x

tf_upgrade_v2 --intree tensorflow_poems/ --outtree tensorflow_poems_v2/ --reportfile report.txt

1. install python
2. install tensorflow
3. migrate the code from 1.x to 2.x

brew install virtualenv

virtualenv --system-site-packages -p python3 ./pythonenv
cd ./pythonenv
source bin/activate
pythonenv


Run Tests:
1. python3 train.py
2. python3 test.py

import tensorflow.compat.v1 as tf
tf.compat.v1.disable_eager_execution
placeholder is updated
input_data = tf.compat.v1.placeholder(tf.int32, [FLAGS.batch_size, None])
compose_poem.py
train.py




# tensorflow-1.4.0
TensorFlow 1.4.0 installed version. there also have a Related cuda version 

If you need previous TensorFlow, you can directly use Python command from this director.

Running method: 
First, adding cuda environment

set -euo pipefail
export PATH=../cuda-8.0/bin:${PATH}
export LD_LIBRARY_PATH=../cuda-8.0/lib64:${LD_LIBRARY_PATH}


Second, running TensorFlow on Python

./tensorflow/bin/python

This Version is depend on Python2.7 and cuda 8.0.

You not need any Python or other environments.

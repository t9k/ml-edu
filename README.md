
## Install necessary Python packages using pip.


### TensorFlow

Quick start for Ubunut 16.04 + Python2 + bash

```bash
sudo apt-get install python-pip python-dev python-virtualenv
sudo pip install -U pip

mkdir ~/tensorflow  
cd ~/tensorflow

virtualenv --system-site-packages venv
source ~/tensorflow/venv/bin/activate
pip install -U pip
pip install -U tensorflow
```

### Other dependencies

After activating your virtual env:

```bash
pip install numpy

pip install pandas

pip install matplotlib

pip install -U scikit-learn
```

## Links

* Install tensorflow - <https://www.tensorflow.org/install/>
  * Ubunut virtual env - <https://www.tensorflow.org/install/install_linux#InstallingVirtualenv>

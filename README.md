
Installation
Install PyTorch by selecting your environment on the website and running the appropriate command.
Note: You should use at least PyTorch0.4.0
Clone this repository.
Note: We currently only support Python 3+.
Then download the dataset by following the instructions below.
We now support Visdom for real-time loss visualization during training!
To use Visdom in the browser:
# First install Python server and client
pip install visdom
# Start the server (probably in a screen or tmux)
python -m visdom.server
Then (during training) navigate to http://localhost:8097/ (see the Train section below for training details).
Note: For training, we currently support VOC and COCO, and aim to add ImageNet support soon.

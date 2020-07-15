### 2020/07 BuRnCycL

Simple script to interact with Blinkstick Strip + Square

Just an example. 

Reference: 
- https://www.blinkstick.com/products/blinkstick-square
- https://www.blinkstick.com/products/blinkstick-strip

### Semi-Automated Installation

Assuming a virgin Raspberry Pi running Raspios Buster Lite. Boot and install the following Prerequisites.

Install git
```
sudo apt install git 
```

Clone this repo
```
git clone https://github.com/burncycl/blinkstick-audio-led-visualizer.git
```

Execute `install.sh` to install apt packager maintained dependencies.
```
cd blinkstick-audio-led-visualizer/
sudo ./install.sh
```

### Run

Setup Python Virtual Environment with all Python dependencies
```
source ./init.sh
```

**Run**
```
python3 blinkstick.py 
```


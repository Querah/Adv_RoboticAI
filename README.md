# Adv_RoboticAI
Advanced Robotic AI submission

git clone this repository
```
cd Adv_RoboticAI
conda create -n ARAI python=3.7
conda activate ARAI
pip3 install -r requirements.txt
```

Download and setup CARLA 0.9.10.1
```
chmod +x setup_carla.sh
./setup_carla.sh
easy_install carla/PythonAPI/carla/dist/carla-0.9.10-py3.7-linux-x86_64.egg
```
the setuptools==41 to install because this version has the feature easy_install.
please uninstall setuptools and install the recent setuptools

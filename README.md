# test-py
Goal: package this poetry project to run as a standalone binary using pyoxidizer
Steps:
(1) Installation of packages
    - Install Rust (1.60 or newer) and python (3.8,3.9,3.10)
    - python -m pip install pyoxidizer
    - cargo install pyoxidizer
        - check installation with `pyoxidizer`
(2) Create PyOxidizer config file
    - cd into directory of choice
    - pyoxidizer init-config-file pyapp 
    - cd pyapp
    - pyoxidizer run
    - test with print("hello, world")


# This tutorial helps you successfully intall the Anaconda on Linux server

Reference link: http://zhangshiyu.com/post/47567.html

Step 1: wget https://repo.anaconda.com/archive/Anaconda3-2023.03-1-Linux-x86_64.sh

Step 2: chmod +x Anaconda3-2023.03-1-Linux-x86_64.sh

        ./Anaconda3-2023.03-1-Linux-x86_64.sh
        
Step 3: conda create -n pytorch python=3.8

Step 4: conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia

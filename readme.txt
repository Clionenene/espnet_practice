Hello world!

TO SETUP Dockerfile run this:
$ sudo docker build -t ubuntu:test -f Dockerfile .
https://www.chobits.com/dockerfile-install-ubuntu-18-04/

here are links where you can catch up with this project file!

https://www.sejuku.net/blog/82240#index_id2
https://qiita.com/renesisu727/items/248cb9468a402c622003
https://qiita.com/taiga_tech/items/85828aede99b6f5acd59

about cuda on docker
https://qiita.com/psymonmarkrine/items/c2111d713371dac38653

cuda Toolkit 10.2
```
wget https://developer.download.nvidia.com/compute/cuda/repos/ubuntu1804/x86_64/cuda-ubuntu1804.pinsudo mv cuda-ubuntu1804.pin /etc/apt/preferences.d/cuda-repository-pin-600sudo apt-key adv --fetch-keys https://developer.download.nvidia.com/compute/cuda/repos/ubuntu1804/x86_64/7fa2af80.pubsudo add-apt-repository "deb https://developer.download.nvidia.com/compute/cuda/repos/ubuntu1804/x86_64/ /"sudo apt-get updatesudo apt-get -y install cuda
$ sudo apt-get -y install cuda-drivers

```

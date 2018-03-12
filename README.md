##python sdk 打包 demo
需要先安装  apt-get install python-setuptools  or pip install python-setuptools

然后执行 python setup.py bdist_egg 打包成sdk

会多出以下三个目录   build    cpssdk.egg-info   dist

整个目录压缩打包发给对方

python setup.py install
import cpssdk
cpssdk.test()
即可测试
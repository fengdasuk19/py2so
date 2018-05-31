# py2so
编译py为so文件，更好的隐藏源码

调用方式
  若是 Python3 环境，重命名 `setup-py3.py` 为 `setup.py`
  若是 Python2 环境，重命名 `setup-py2.py` 为 `setup.py`
  将setup.py放到要编译文件夹上层或根目录
  编译当前文件夹：
    python setup.py
  编译某个文件夹：
    python setup.py mydir
    
生成的文件
  build文件夹下即为结果
    
    

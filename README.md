# aliyun-log-python-sdk

## Windows下使用python2.7安装aliyun-log-python-sdk并使用aliyun.log包

### 1.安装VCForPython27.msi。避免出现因为c++9.0报错

### 2. 

```bash
pip install wheel
# 手动安装regex，使用目录下的whl文件，可以根据电脑系统下载对应版本。网址：https://www.lfd.uci.edu/~gohlke/pythonlibs
pip install regex-2020.1.8-cp27-cp27m-win_amd64.whl

```

### 3. 安装aliyun-log-python-sdk

####  [官方文档](https://github.com/aliyun/aliyun-log-python-sdk/blob/master/README_CN.md)

```bash
# 加上了国内清华的源，防止time out
pip install -U aliyun-log-python-sdk -i https://pypi.tuna.tsinghua.edu.cn/simple
# 或者
pip install -U aliyun-log-python-sdk
```



### 4. 在pycharm中生效

​	重新导入一下python解释器即可 [https://blog.csdn.net/wujf90/article/details/79181886](https://blog.csdn.net/wujf90/article/details/79181886)


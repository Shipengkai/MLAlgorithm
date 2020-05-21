# pip换源
    临时使用
    pip install -i https://pypi.tuna.tsinghua.edu.cn/simple some-package
    注意，simple 不能少, 是 https 而不是 http

    设为默认
    升级 pip 到最新的版本 (>=10.0.0) 后进行配置：

    pip install pip -U
    pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
    如果您到 pip 默认源的网络连接较差，临时使用本镜像站来升级 pip：

    pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pip -U


# conda换源
    命令行中直接使用以下命令：

        conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
        conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge 
        conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/msys2/

    # 设置搜索时显示通道地址
        conda config --set show_channel_urls yes

        有时候国内镜像源无法连接，需要恢复原来的源：

        conda config --remove-key channels
        ————————————————
        版权声明：本文为CSDN博主「ACSE-Mayer」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
        原文链接：https://blog.csdn.net/sunmingyang1987/article/details/102851249


# Kaggle


# GitHub
    
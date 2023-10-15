# 初始化项目
django-admin startproject xxxxx

# 安装依赖
brew install watchman
brew upgrade watchman

# 创建 APP
python3 manage.py startapp app01

# 启动 django 项目 (mac 系统需要放在 User 文件夹下！)
python3 manage.py runserver (需要放在 User 文件夹内才有权限)
python3 manage.py runserver --noreload # 不自动刷新
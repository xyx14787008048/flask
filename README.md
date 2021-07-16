# 下载安装flask
pip install flask

# 创建虚拟环境
python3 -m venv venv

# 运行应用程序
export FLASK_APP=flaskr
export FLASK_ENV=development

## 初始化数据库文件
flask init-db

## 指定监听地址是 0.0.0.0
flask run -h 0.0.0.0
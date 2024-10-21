API Key
首先修改.env 的 API KEY

OPENAI_API_KEY 到 API keys - OpenAI API 获取
NINJAS_API_KEY 到 API Ninjas 获取
Server
安装 anaconda 或 miniconda：自行搜索安装方法
创建 Python 虚拟环境
conda create -n cat python=3.11
进入 Python 虚拟环境
conda activate cat
安装项目依赖
cd server
pip install -r requirements.txt
启动后端 server
python run.py
Web
安装 Node.js：自行搜索安装方法
安装依赖
cd web
npm i
# or
yarn
运行前端 web
npm run dev
# or
yarn dev
网页使用
打开浏览器，输入地址：127.0.0.1:3000

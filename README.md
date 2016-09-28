
学习出处: http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001432170937506ecfb2f6adf8e4757939732f3e32b781c000




环境搭建:
    异步框架aiohttp：
    $pip3 install aiohttp

    前端模板引擎jinja2：
    $ pip3 install jinja2


项目结构:
    MyPy3_webApp_Blog/  <-- 根目录
    |
    +- backup/               <-- 备份目录
    |
    +- conf/                 <-- 配置文件
    |
    +- dist/                 <-- 打包目录
    |
    +- www/                  <-- Web目录，存放.py文件
    |  |
    |  +- static/            <-- 存放静态文件
    |  |
    |  +- templates/         <-- 存放模板文件
    |
    +- ios/                  <-- 存放iOS App工程
    |
    +- LICENSE               <-- 代码LICENSE
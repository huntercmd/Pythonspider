# Pythonspider,一个简单的python爬虫
* 原生python+BeautifulSoup4
* **python2.7.10版本**
* 所有脚本要和spider.py放到同一目录下
* 自行下载BeautifulSoup4 的类库

TODO：taobaomm.py 在osx下会出现ssl错误SSLV3_ALERT_HANDSHAKE_FAILURE


需要安装 lxml 解析库，或者将 spider.py 中 11 行 `return BeautifulSoup(req.read().decode(coding), "lxml")` 中 `lxml` 改为 `html.parser`

import http 报错，删掉 http

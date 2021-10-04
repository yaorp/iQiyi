
# 使用方式
1. 打开爱奇艺官网 获取你的authcookie  获取方式 [文字教程](https://www.jianshu.com/p/b3759d78392b) ) authcookie有效期一般三个月
  爱奇艺authcookie基本上用的是爱奇艺cookie中 P00001的值
  1.登入爱奇艺
  2.按F12打开控制台
  3.按F5刷新页面
  4.点击Network
  5.点击第一个缓存文件
  6.右侧找到 COOKIES
  7.复制出 P00001 后面的内容（如：a1O0Cm2dypdOv7hTm3H9khhuyM2r42bzidgJue02voVnm1lim3fsj8bFdrO2hm1F1...）
  9.保存起来，这样我们要用

3. 右上角fork本仓库
4. 点击Settings -> Secrets -> 点击绿色按钮 (如无绿色按钮说明已激活。直接到第四步。)
5. 新增 new secret  参数名IQIYI_COOKIE 值是你刚才获取的authcookie
6. 任意修改仓库内任意文件或点击右上角 Star 即可触发。

**本项目需要设置的 Secrets:**

| 名称     | 内容           |   类型     |  说明|
| -------- | ------------- |  ------ | ----- |
| IQIYI_COOKIE  | 爱奇艺authcookie   | 必写参数 |
| PUSH_KEY | Server酱SCKEY值 | 可选参数 | cookie失效推送[server酱的微信通知](http://sc.ftqq.com/3.version) |
| BARK_PUSH | Bark推送值 | 可选参数 | 此内容支持自建Bark添加整个链接即可(自建链接切记删除最后一个/  比如你的是https://a.a.com/ 只需要填写https://a.a.com即可)|
|BARK_SOUND | BARK app推送铃声|可选参数|BARK app推送铃声,铃声列表去APP查看复制填写|

可使用Star触发，点击自己仓库右上角Star即可激活，如是Unstar状态需要点击两次即可。


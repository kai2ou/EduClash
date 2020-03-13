# EduClash自定义配置
使用方法：clash订阅后面加速  &config=https://raw.githubusercontent.com/kai2ou/EduClash/master/default.ini

节点list过滤  利用正则参数过滤节点：

https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fb0b56ee0-d2dc-416c-ba8d-a794b465323f%2FUntitled.png?table=block&id=b3e21727-0633-44d5-8679-7d692ecaa49a&width=2650&cache=v2
1. 订阅链接请先[urlencode](https://www.urlencoder.org/)之后再接入 sub 参数后；
2. API中的filter的正则参数同样需要先行UrlEncode；
3. 正则过滤请先用 .*开始，比如你想要名字中含 **`游戏`** 的节点，拿 **`.*游戏` 放到 urlencode 网站进行 encode，结果** .%2A%E6%B8%B8%E6%88%8F，那么过滤的正则表达式为：
`filter=.%2A%E6%B8%B8%E6%88%8F`

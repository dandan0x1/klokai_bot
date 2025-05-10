# klokai 项目介绍
一个ai聊天的项目
注册RF：https://klokapp.ai?referral_code=KMLZ7JF7


# klokai bot 1.1 怎么用？
## 1、生成配置文件

修改：eth_addresses.txt，eth_private_keys.txt，proxy.txt，ref_code.txt 4个文件行数必须一样

然后运行脚本->2

将生成的config/output.json内容替换成config.json

## 2、批量注册
然后运行脚本->3->1

## 3、wallets.json 由系统生成，也可以手工创建
```json
[
  {
    "private_key": "密钥1",
    "address": "钱包1",
    "ref_code": "KMLZ7JF7",
    "proxy": "127.0.0.1:7890"
  },
  {
    "private_key": "密钥2",
    "address": "钱包2",
    "ref_code": "KMLZ7JF7",
    "proxy": "127.0.0.1:7891"
  }
]
```

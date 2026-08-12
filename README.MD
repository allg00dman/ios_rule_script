# iOS Rule Script

> 来自 [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script) 的分流规则镜像，每日自动同步。

## 说明

- 保留 `rule` 目录下全部格式：`AdGuard`、`Clash`、`Loon`、`QuantumultX`、`Shadowrocket`、`Surge`
- 每天 UTC 02:00（北京时间 10:00）自动从上游同步，上游新增、修改、删除均会同步
- 规则内容及维护归属原作者 blackmatrix7

## 使用方法

将配置中的规则链接替换为：

```
https://raw.githubusercontent.com/allg00dman/ios_rule_script/master/rule/{格式}/{规则名}/{文件名}
```

各格式示例（以 Netflix 为例）：

| 格式 | 链接 |
| --- | --- |
| Surge | `https://raw.githubusercontent.com/allg00dman/ios_rule_script/master/rule/Surge/Netflix/Netflix.list` |
| QuantumultX | `https://raw.githubusercontent.com/allg00dman/ios_rule_script/master/rule/QuantumultX/Netflix/Netflix.list` |
| Loon | `https://raw.githubusercontent.com/allg00dman/ios_rule_script/master/rule/Loon/Netflix/Netflix.list` |
| Shadowrocket | `https://raw.githubusercontent.com/allg00dman/ios_rule_script/master/rule/Shadowrocket/Netflix/Netflix.list` |
| Clash | `https://raw.githubusercontent.com/allg00dman/ios_rule_script/master/rule/Clash/Netflix/Netflix.yaml` |

`AdGuard` 目录结构不同，为 `Advertising`、`Privacy`、`BlockHttpDNS` 等拦截规则集。

Surge / Egern 等工具原有的 `rule/Surge/...` 链接保持不变，无需调整配置。

## 致谢

- [blackmatrix7](https://github.com/blackmatrix7)

# Web - Week 2

## ezAPI

| 出题人 | 难度 | 环境镜像 |
|--------|------|----------|
| 烨     | 简单 | *内容过多，详见 [metapack.json](../metapack.json#L911-L956)* |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{4a902c8e-a8b5-ecfb-bee3-d6419865647c}</code>
> </details>

qsdz 开发了一个查询网页，但是好像存在一些漏洞？

## IncludeOne

| 出题人 | 难度 | 环境镜像 | 端口 |
|--------|------|----------|------|
| 烨     | 简单 | [newstar-2022:week2_include-1](https://hub.docker.com/r/openctf/newstar-2022/tags?name=week2_include-1) | `80` |

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details >

文件包含漏洞系列第一题，也不知道是不是真的随机？

出题人丢给你了一个工具：https://www.openwall.com/php_mt_seed/

## UnserializeOne

| 出题人 | 难度 | 环境镜像 | 端口 |
|--------|------|----------|------|
| 烨     | 简单 | [newstar-2022:week2_unserialize-1](https://hub.docker.com/r/openctf/newstar-2022/tags?name=week2_unserialize-1) | `80` |

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details >

PHP 反序列化漏洞系列第一题

## Word-For-You (2 Gen)

| 出题人 | 难度 | 环境镜像 | 端口 |
|--------|------|----------|------|
| J1an   | 简单 | [newstar-2022:week2_word-for-you-2](https://hub.docker.com/r/openctf/newstar-2022/tags?name=week2_word-for-you-2) | `80` |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{Ju4t_m2ke_some_err0rs}</code>
> </details>

哇哇哇，我把查询界面改了，现在你们不能从数据库中拿到东西了吧哈哈（不过为了调试的代码似乎忘记删除了

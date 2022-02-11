# EXTP协议标准

EXTP 是一个可扩展的交换协议，旨在通过一套协议完成所有数据交互任务。

!!! tip "提示"

    如果本站有看不懂的词汇，请参考 [术语表](glossary.md)。

## EXTP 协议标准是什么？

EXTP 协议标准是对各种程序所共同使用（必须使用或可能会需要使用）的 参数、API 的一个抽象，是对各种程序 API 的通信方式、传输的数据格式和字段的一个标准化定义。如果将 EXTP 协议标准类比于 C 语言、ECMAScript、POSIX 标准等，则 EXTP 实现对应 GCC、Chrome V8、Linux 等。

## 文档用词

本文档中的 `必须`（MUST）、`不得`（MUST NOT）、`应`/`应该`（SHALL）、`不应`/`不应该`（SHALL NOT）、`建议`（RECOMMENDED）、`不建议`（NOT RECOMMENDED）、`可以`（MAY）和 `可选`（OPTIONAL）等能愿动词按照 [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt) 中的描述进行解释。
# 基础码表

这些代码属于`` 详情 ``，也就是 状态码的后两位。

## 10

|  #   | 注解  |
|  ----  | ----  |
| 10  | 处理继续 |
| 11  | 转换为SEXTP（Secure EXTP） |

## 20

|  #   | 注解  |
|  ----  | ----  |
| 20  | 正常处理完毕 |
| 21  | 已创建展示处理后数据的单独终结点 |
| 22  | 正在处理中，但没处理完成 |
| 23  | 非官方内容，不保证可信度 |
| 24  | 数据处理成功，但无需返回信息 |

## 30

|  #   | 注解  |
|  ----  | ----  |
| 31  | 响应器已被永久移动至其他终结点，需要重新提交至另一个终结点 |
| 32  | 已找到响应器，但被临时移动到了其他终结点，需要重新提交至另一个终结点 |

## 40

|  #   | 注解  |
|  ----  | ----  |
| 40  | 语法错误 |
| 41  | 未授权，无法处理数据 |
| 42  | 没有权限，响应器拒绝处理 |
| 44  | 找不到响应器或响应器处理时找不到上游数据 |

## 50

|  #   | 注解  |
|  ----  | ----  |
| 50  | 内部错误 |
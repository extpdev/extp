## 状态行

### 字段定义

字段位置 | 数据类型 | 说明 | 示例
--- | --- | --- | ---
第1部分 | string | 终结点地址 | /
第2部分 | int16 | 四位状态码 | 2020
第3部分 | string | EXTP协议标准版本 | EXTP/1

### 完整示例

```
/ 2020 EXTP/1
```

## 设置行

### 字段定义

字段位置 | 数据类型 | 说明 | 示例
--- | --- | --- | ---
第1部分 | string | 设置类型 | 应为  ```Set-Header```
第2部分 | string | 设置键 | Example
第3部分 | string | 设置值 | Test

### 完整示例

```
Set-Header Example=Test
```

## 数据区

直接写入数据即可。示例：```Data```

## 全部完整示例

```
/ 2020 EXTP/1
Set-Header Example=Test

Data
```
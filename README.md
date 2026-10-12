# nexa-core

静态编译的代理内核（原名字眼已在构建后移除）。

## 资产

| 文件 | 说明 |
|---|---|
| `nexa-linux-amd64.zip` | linux/amd64 静态二进制，zip 内条目名为 `core` |

## 用法

应用侧会自行下载并落地，无需手动解压。若需手动使用：

```bash
unzip nexa-linux-amd64.zip
chmod +x core
./core version
```

## 校验

```
zip      sha256: 938eeae5a470787b5f4669a210d3e3baec4d46d0c69911bee55ce1a4d9ca002a
binary   sha256: 362091230c9a764a0b8e9cbcdf3177c0e3f09e41940d866c23ca3155fdc092f7
```

## 说明

- 仅 linux/amd64。其他架构请从上游 release 取对应包后自行处理。
- 缩进与日志中不含原始项目特征字眼；协议层标识（流控名等）保持原样以保证客户端兼容。

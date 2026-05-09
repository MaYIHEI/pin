# 📌 pin

代理脚本配套图标库 · 自用收集

> 钉在脚本上的小图标。配合 [paperclip](https://github.com/MaYIHEI/paperclip) 以及其他大佬的脚本使用。

---

## 📂 目录

| 目录 | 内容 | 索引 |
|---|---|---|
| [`app/`](./app/) | 移动端 APP 图标(微信小程序、原生 APP) | [查看](./app/README.md) |
| [`airport/`](./airport/) | 机场代理服务图标 | [查看](./airport/README.md) |
| [`proxy/`](./proxy/) | 代理工具图标(Clash / Loon / Surge 等) | [查看](./proxy/README.md) |

每个子目录的 README 里有该类下所有图标的网格预览。

---

## 🔗 引用方式

所有图标通过 GitHub Raw URL 引用,格式:

```
https://raw.githubusercontent.com/MaYIHEI/pin/main/<分类>/<文件名>.png
```

### 在 Loon / QX / Surge 任务里使用

```ini
[task_local]
0 9 * * * https://raw.githubusercontent.com/MaYIHEI/paperclip/main/miniprogram/ppmt/ppmt.js, tag=泡泡玛特, img-url=https://raw.githubusercontent.com/MaYIHEI/pin/main/app/popmart.png, enabled=true
```

---

## 🎨 命名规范

- **全小写**: `popmart.png` ✅ / `POPMART.png` ❌
- **连字符分隔**: `magic-catling.png` ✅ / `Magic Catling.png` ❌(不允许空格)
- **避免数字版本**: `synet.png` ✅ / `SYN-1.png` ❌(用 `synet-alt.png` 表示备选版)

详见 [`CONTRIBUTING.md`](./CONTRIBUTING.md)。

---

## 🤝 贡献规范

新增图标请遵循 [`CONTRIBUTING.md`](./CONTRIBUTING.md) 中的命名与分类规范。

---

## 📄 License

[MIT](./LICENSE)

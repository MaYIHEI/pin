# 贡献规范

本仓库收录代理脚本配套图标。新增图标请遵循以下规范。

---

## 📁 分类

| 目录 | 内容 |
|---|---|
| `app/` | 移动端 APP / 微信小程序图标(用户使用的应用) |
| `airport/` | 机场代理服务图标(代理订阅服务商) |
| `proxy/` | 代理工具图标(Clash / Loon / Surge / QX 等) |

分类边界:

- 工具属性(代理软件本身) → `proxy/`
- 服务属性(代理订阅商) → `airport/`
- 用户使用的应用 → `app/`

---

## 🎨 命名规范

### 必须遵守

- **全小写**: `popmart.png`,不接受 `POPMART.png` / `PopMart.png`
- **连字符分隔多词**: `magic-catling.png`,不接受空格、下划线、驼峰
- **简短有意义**: 用品牌英文名或拼音缩写,不接受 `11.png` / `IMG_xxx.png` 这种无意义命名

### 推荐做法

- 优先使用品牌英文名: `reddit.png` / `popmart.png`
- 没有英文名用拼音缩写: `wdy.png`(无道云) / `qxej.png`(汽修二局)
- 同一品牌多个版本用语义后缀: `clash.png` / `clash-color.png` / `clash-meta.png`

---

## 📐 图片规范

| 项 | 要求 |
|---|---|
| 格式 | PNG (优先支持透明背景) |
| 尺寸 | 推荐 256×256 或 512×512 正方形 |
| 文件大小 | 不超过 500 KB |
| 透明度 | 优先选择透明背景版本 |

---

## 📝 添加步骤

1. **判断分类**: app / airport / proxy 选一个
2. **重命名**: 按上述命名规范处理
3. **放入对应目录**
4. **更新索引**: 在该目录的 `README.md` 表格里加一行
5. **提交**

Commit message 建议:

```
feat(app): add popmart icon
feat(airport): add new-airport icon
chore: rename xxx.png to xxx.png (规范化)
```

---

## 🚫 不要做的事

- ❌ 不要在文件名里使用空格、大写、下划线、驼峰
- ❌ 不要上传仅大小写不同的同名文件(`oixCloud.png` vs `oixcloud.png` 会在某些系统冲突)
- ❌ 不要上传截图文件(`IMG_0285.png` / `Screenshot.png` 这种)
- ❌ 不要上传 JPG/JPEG(优先用 PNG 保留透明)
- ❌ 不要在主目录放图标(必须按分类放进子目录)

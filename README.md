# SyncweRules

> Syncwe 插件规则仓库，自动同步最新的规则文件


## 项目结构

```
SyncweRules/
├── rules/              # 规则文件目录
│   ├── xxx.json        # 规则文件
├── index.json          # 规则索引文件（自动生成）
```

## 规则文件格式

每个规则文件都是一个 JSON 格式的配置文件，包含以下主要字段：

```json
{
    "name": "",
    "displayName": "",
    "version": "",
    "author": "",
    "baseURL": "",
    "searchURL": "",
    "searchList": "",
    "searchName": "",
    "searchResult": "",
    "chapterRoads": "",
    "chapterResult": "",
    "referer": ""
}
```

> 兼容 Kazumi 规则格式

## 使用

```bash
# 克隆仓库
git clone https://github.com/SyncweApp/SyncweRules.git

# 进入目录
cd SyncweRules

# 同步最新规则
git pull origin main
```

## CMS 导入

- `cms/source.json` 已同步仓库源配置。
- 在 Syncwe 软件内可直接导入该文件使用。

## 贡献

欢迎提交新的规则文件或改进现有规则！

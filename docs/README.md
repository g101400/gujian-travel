# 古建景点打卡 · 工程说明（gujian）

- 包名：`com.gujian.travel`　版本：`3.7.39`（code 39）　数据量：seedCount 1032 / provinces 34
- 独立 Git 仓库：`gujian-travel`（main 分支）
- 百度网盘子目录：`古建景点打卡`

## 目录

```
webroot/        应用源码（编辑边界）
native-shell/   原生壳源码（Win/UOS[/iOS]）
build/          构建脚本
docs/           文档
version.json   版本信息
```

## 快速开始

```bash
cd D:/Users/WorkBuddy/gujian
# 浏览器直接打开 webroot/index.html 即可运行（需本地静态服务或 WebView2/UOS 壳）
```

## 构建四端
详见 [BUILD.md](BUILD.md)。原生壳映射：

- win-gujian-webview2（标题：古建景点打卡）
- uos-gujian-pyqt6

## 已知特性

- 首装地图空白修复：首次安装需正确触发种子数据初始化，避免地图空白。
- 打卡菜单含写游记/导出游记（见近20天经验：菜单保留 0 删除）。
- 类型图形图标升级：塔/庙/宫殿/城墙等专属图形。

> 隔离规范与经验教训见顶层 `D:/Users/WorkBuddy/三项目总览与隔离规范.md`。
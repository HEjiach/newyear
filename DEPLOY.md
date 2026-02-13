# Gitee Pages 部署指南

## 前提条件
- 已注册 [Gitee](https://gitee.com) 账号
- 已安装 Git（[下载](https://git-scm.com/downloads)）

## 部署步骤

### 1. 在 Gitee 创建仓库
1. 登录 Gitee → 右上角 **+** → **新建仓库**
2. 仓库名称填 `newyear`（或任意名称）
3. 勾选 **公开**（Gitee Pages 必须是公开仓库）
4. 点击 **创建**

### 2. 推送代码到 Gitee
在项目文件夹中执行以下命令（替换 `你的用户名` 为你的 Gitee 用户名）：

```bash
cd c:\Users\17819\Desktop\newyear
git init
git add .
git commit -m "新年祝福页面"
git remote add origin https://gitee.com/hejia-village111/newyear.git
git push -u origin master
```

### 3. 开启 Gitee Pages
1. 进入仓库页面 → 顶部菜单 **服务** → **Gitee Pages**
2. 部署分支选 `master`，目录选 `/`
3. 勾选 **强制使用 HTTPS**
4. 点击 **启动**

### 4. 获取链接分享
启动成功后会显示访问地址，格式为：
```
https://你的用户名.gitee.io/newyear/
```
把这个链接发到微信，对方直接点开就能看到完整的新年祝福页面！

## 项目文件清单
| 文件 | 说明 |
|------|------|
| index.html | 主页面（卷轴版） |
| scroll.html | 卷轴版副本 |
| firework.html | 烟花版 |
| a1.png ~ a7.png | 新年插画素材 |
| sp.mp4 | 新年祝福视频 |
| 拜新年.mp3 | 背景音乐 |

> ⚠️ **注意**：Gitee Pages 更新内容后需要手动点击「更新」按钮才会生效。

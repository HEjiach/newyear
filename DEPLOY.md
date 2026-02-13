# GitHub + Vercel 部署指南

## 步骤一：推送代码到 GitHub

```bash
cd c:\Users\17819\Desktop\newyear
git add .
git commit -m "新年祝福页面"
git remote add origin https://github.com/HEjiach/newyear.git
git push -u origin master
```

## 步骤二：Vercel 部署

1. 打开 https://vercel.com → 用 **GitHub 账号** 登录
2. 点击 **Add New** → **Project**
3. 在列表中找到 **newyear** 仓库 → 点击 **Import**
4. Framework Preset 选 **Other**
5. 点击 **Deploy** → 等待几秒
6. 部署完成！拿到链接（如 `https://newyear-xxx.vercel.app`）

## 步骤三：分享

把 Vercel 给的链接直接发到微信，对方点开即可看到完整页面！

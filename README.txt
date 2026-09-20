# 我的课表 PWA

这是可安装到手机桌面的 PWA 版本。

## 文件
- index.html：课表主页
- manifest.webmanifest：PWA 配置
- sw.js：离线缓存
- icon.svg：桌面图标

## 使用要求
PWA 必须通过 http/https 访问，不能直接通过 file:// 本地文件安装。

## 推荐部署方式
1. GitHub 新建仓库，例如 `schedule`
2. 上传这 4 个文件到仓库根目录
3. Settings → Pages
4. Build and deployment → Deploy from a branch
5. 选择 main / root
6. 等待生成 https://用户名.github.io/schedule/
7. 小米手机 Chrome 打开该网址
8. 浏览器菜单 → 添加到主屏幕 / 安装应用

安装后可独立全屏打开，离线也能访问已缓存的课表。

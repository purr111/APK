# 简记账 · 打包 APK 步骤
1. 在 GitHub 新建一个仓库，把本文件夹内所有文件（含 .github 隐藏目录）上传/推送到 main 分支。
2. 打开仓库 Actions 页面，等 "Build APK" 跑完（约 3-5 分钟）。
3. 点进该次运行，在页面底部 Artifacts 下载 ledger-apk.zip，解压得到 app-debug.apk。
4. 发到手机，允许"安装未知来源应用"后安装即可。
数据保存在手机本地，卸载应用会清空。
预览：电脑上直接双击 www/index.html 即可在浏览器体验。

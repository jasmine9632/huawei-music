# huawei-music

打开 Git Bash
mkdir huawei-music
cd huawei-music
git init 本地仓库
npm init -y

在 vscode 开终端
npm install --save-dev parcel bundler
mkdir dist
mkdir src
cd src
mkdir js
mkdir scss
mkdir svg
cd js
touch index.js
cd ..
cd scss
touch index.scss
cd ..
cd ..
touch index.html
npm install --save-dev sass

开发
本地安装启动测试服务器
npx parcel index.html

发布
保存后上传到 github
npx parcel build index.html --public-url="./"

# yarn、npm 更换下载源
npm, yarn查看源和换源：
```bash
npm config get registry  // 查看npm当前镜像源

npm config set registry https://registry.npm.taobao.org/  // 设置npm镜像源为淘宝镜像

yarn config get registry  // 查看yarn当前镜像源

yarn config set registry https://registry.npm.taobao.org/  // 设置yarn镜像源为淘宝镜像
```

镜像源地址部分如下：
```bash
yarn --- https://registry.yarnpkg.com

npm --- https://registry.npmjs.org/

cnpm --- https://r.cnpmjs.org/

taobao --- https://registry.npm.taobao.org/

nj --- https://registry.nodejitsu.com/

rednpm --- https://registry.mirror.cqupt.edu.cn/

npmMirror --- https://skimdb.npmjs.com/registry/

deunpm --- http://registry.enpmjs.org/
```

查看 npm 全局安装的路径
```bash
npm ls -g --depth=0
```

不询问，直接初始化项目
```bash
npm init -y
```

查询 webpack 包在npm上的版本等等信息
```bash
npm info webpack
```

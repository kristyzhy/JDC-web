# jdc

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).



准备好nodejs环境
拉取源码,进入源码目录安装依赖: npm install

修改配置文件.evn.production
.
这里添加了3个节点,必须写在一行，不能回车换行
.
修改打包文件package.json
.
在scripts的build添加参数 --mode production
.
打包 npm run build
.
打包生成的文件夹dist
.
进入文件夹，打包所有生成的文件 zip -r dist.zip *
.

然后就可以复制打包好的dist.zip文件到花语的public目录下解压使用啦（自己复制解压，这里就不展开了）

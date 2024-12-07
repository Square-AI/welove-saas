# welove-saas

weLove 官网

## 部署

### step1 安装依赖

```shell
npm install
```

### step2 打包

```shell
npm run build
```

### step3 部署

将 npm build 后的文件 dist 中的文件 放到你的 nginx 静态文件目录下即可

```shell
cp -r dist/* /usr/share/nginx/html
```
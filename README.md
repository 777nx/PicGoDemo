# PicGoDemo

此仓库用来存储网站的静态资源，如图片、字体、大型js文件等

在本地的`[AssetsRepo]`文件夹下打开终端，运行以下指令，上传新增内容至 github，即可触发部署。

```bash
# 将更改提交
git add .
git commit -m "npm publish"
# 更新package版本号
npm version patch
# 推送至github触发action
git push
```


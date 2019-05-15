# 安装sapper

```bash
# for Rollup
npx degit sveltejs/sapper-template#rollup my-app
# for webpack
npx degit sveltejs/sapper-template#webpack my-app
cd my-app
npm install # or yarn!
npm run dev
```

Open up [localhost:3000](http://localhost:3000) and start clicking around.


# package.json文件
package.json包含您的应用程序的依赖项并定义了许多脚本：
```
npm run dev - 在开发模式下启动应用程序，并观察源文件的更改
npm run build - 在生产模式下构建应用程序
npm run export- 烘焙静态版本（如果适用）（请参阅）
npm start - 在构建应用程序后，以生产模式启动应用程序
npm test- 运行测试（参见）
```

# 部署到now1
```
npm install -g now
now
```
这将源代码上传到now，它会自己执行 `npm run build`，并 `npm start`给你的部署应用程序的URL。
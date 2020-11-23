# cocos-bundle-single-html

将 cocos creator 打包出来的 web 项目，进一步打包为单个 html 文件。

## 流程

1. 将游戏内资源使用 js 表示。其中典型的例如 .png 需要转化为 base64 格式。
2. 修改引擎的下载和解析过程。

## 知识储备

1. html 文件与 js 文件的合并。
2. 图片资源转 base64。
3. 声音资源转 base64。
4. base64 转 blob。
5. 对 require 方法的处理。

## 参考资料

1. 下载与解析 · Cocos Creator [https://docs.cocos.com/creator/manual/zh/asset-manager/downloader-parser.html]

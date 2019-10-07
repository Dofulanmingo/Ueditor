# Ueditor
ueditor1.2完成
插入图片（上传图片功能）也是在服务器上进行，通过地址进行，比如复制黏贴本地图片链接地址，
或者网上图片地址。我感觉最好把图片和文件方同意文件夹下比较好。

对于ueditor公式完整版2：kityformula-plugin
先在index.html中的开头引入公式插件的3个js文件
把ueditor.config.js里toolbars中按键名复制到index.html的toolbars中，
在本地服务器中打开即可。
具体实现查看 UEditor公式编辑器（完整版）2或其他三个版本aspphpnet

,其中本地上传图片不行，可能需要改下image.js源码？

对于ueditor公式版（原版）：导入的是mathquill.js
也是公式插件

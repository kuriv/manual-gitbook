# prism

安装 `prism` 插件来美化代码高亮显示效果，在安装此插件之前，需要在 `book.json` 中移除默认的 `highlight` 插件。

```json
{
    "plugins": [
        "-highlight", "prism"
    ],
    "pluginsConfig": {
        "prism": {
            "css": ["prismjs/themes/prism-okaidia.css"]
        }
    }
}
```

然后执行下面的命令，安装插件依赖。

```
npm install --save gitbook-plugin-prism
```
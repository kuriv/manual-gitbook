# favicon

在 `book.json` 中添加下面的内容。

```json
{
    "plugins": ["favicon"],
    "pluginsConfig": {
        "favicon": {
            "shortcut": "favicon.ico",
            "bookmark": "favicon.ico",
            "appleTouch": "favicon.png",
            "appleTouchMore": {
                "120x120": "favicon-120x120.png",
                "180x180": "favicon-180x180.png"
            }
        }
    }
}
```

然后执行下面的命令，安装插件依赖。

```
npm install --save gitbook-plugin-favicon
```

安装完成后，将小图标存放到上述配置文件中指定的位置，即可修改网站的小图标。
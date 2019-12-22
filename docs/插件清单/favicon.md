# favicon

在 `book.json` 中添加下面的内容。

```json
{
    "plugins": ["favicon"],
    "pluginsConfig": {
        "favicon": {
            "shortcut": "favicon.ico",
            "bookmark": "favicon.ico",
            "appleTouch": "favicon.ico",
            "appleTouchMore": {
                "120x120": "favicon.ico",
                "180x180": "favicon.ico"
            }
        }
    }
}
```

然后执行下面的命令，安装插件依赖。

```shell
npm install --save gitbook-plugin-favicon
```

安装完成后，将小图标图片存放到上述配置文件中指定的位置，即可修改网站的小图标。
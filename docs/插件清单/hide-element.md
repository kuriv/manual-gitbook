# hide-element

在 `book.json` 中添加下面的内容。

```json
{
    "plugins": ["hide-element"],
    "pluginsConfig": {
        "hide-element": {
            "elements": [".gitbook-link"]
        }
    }
}
```

然后执行下面的命令，安装插件依赖。

```
npm install gitbook-plugin-hide-element
```

安装完成后即可隐藏指定的元素。
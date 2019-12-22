# search-pro

安装 `search-pro` 插件来支持中文搜索，不过，在安装此插件之前，需要在 `book.json` 中移除默认的 `search` 和 `lunr` 这两个插件。

```json
{
    "plugins": [
        "-lunr", "-search", "search-pro"
    ]
}
```

然后执行下面的命令，安装插件依赖。

```shell
npm install --save gitbook-plugin-search-pro
```


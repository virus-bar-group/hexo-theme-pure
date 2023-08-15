# pure

A brand new default theme for [[Hexo](https://hexo.io)].  [Preview](http://cofess.github.io/) | [中文说明文档](https://github.com/cofess/hexo-theme-pure/blob/master/README.cn.md) | [iconfont](http://blog.cofess.com/hexo-theme-pure/iconfont/demo_fontclass.html)

![](screenshot/pure.png)

## Forked Version

该仓库由 [cofess/hexo-theme-pure](https://github.com/cofess/hexo-theme-pure) 复刻而来。增加了以下功能：

### 注明转载出处

可用以下 Front-matter 在标题下方注明原文链接及作者信息：

```yaml
source_text: 【转载】从 example.com 转载
source_link: https://example.com
source_author_text: 示例作者
source_author_link: https://example.com
```

修改位于 [source.ejs](./layout/_partial/post/source.ejs) 中。

### 注明特殊许可协议

所有文章在默认情况下使用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh) 协议进行授权，并会在文章底部注明。若有特殊情况，可使用以下 Front-matter 自定义：

```yaml
license: CC BY-NC-ND 4.0
license_link: https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh
```

修改位于 [copyright.ejs](./layout/_partial/post/copyright.ejs) 中。

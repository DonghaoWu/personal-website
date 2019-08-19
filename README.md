### 开发者日记：

#### `8月19日.关于svg的使用：如果你要这样应用svg文件：`

```html
<svg class="search__icon">
  <use xlink:href="img/sprite.svg#icon-magnifying-glass"></use>
</svg>
```

<ol>

- 这种方法叫做跨文件调用，这个在chrome中往往会报安全错误，而且你不会在本地静态开发中看到相应图片
- 解决方法是，使用server，如 live-server，可以通过以下方式安装：

```bash
$ npm install -g live-server
```
- 详细可参考trillo项目的视频。

</ol>


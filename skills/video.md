# # 添加视频

# 媒体标签

本博客系统，为避免和正常的 `HTML5` 音、视频标签 `<video>`、`<audio>` 重复，影响 `HTML5` 技术内容展示。顾在标签前加入 `md-` 进行实现。

# 视频演示


## 横屏演示

```html
<md-video>media/taiyuan.mp4</md-video>
```

## 竖屏演示，设置宽度为 30%

```html
<md-video>media/demo.mp4, 30</md-video>
```

## 远程视频演示

```html
<md-video>`http://vjs.zencdn.net/v/oceans.mp4`</md-video>
```


# 视频 API

参数：`<标签>[视频地址, 视频宽度, 自动播放]</标签>`


## 视频地址

- 相对地址/demo.mp4
- 远程网络地址需用反单引号 **\`https://www.xxx.com/demo.mp4\`** 进行包裹


## 视频宽度

> 视频宽度为 `1-100` 之间的数字。

- 60：表示 60% 的宽度。
- 在移动设备，为增强体验，视频宽度拉伸为 100%，您也可以在 `blog.css` 文件中进行修改。


## 视频自动播放

> 参数：auto

由于大多数浏览器禁用自动播放功能，开启前请确认您的浏览器是否禁用该功能。
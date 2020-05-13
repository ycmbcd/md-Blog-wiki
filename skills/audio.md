# # 添加音频

# 媒体标签

本博客系统，为避免和正常的 `HTML5` 音、视频标签 `<video>`、`<audio>` 重复，影响 `HTML5` 技术内容展示。顾在标签前加入 `md-` 进行实现。

# 音频演示

## aac 音频演示，循环播放

> 牛歌 / 小草 - 相伴一生.acc

```html
<md-audio>media/相伴一生.aac, loop</md-audio>
```

## mp3 音频演示

> Katie Herzig - Forevermore.mp3

```html
<md-audio>media/Forevermore.mp3</md-audio>
```


## 远程音频演示

> 曾轶可 - 最天使.mp3

```html
<md-audio>`http://m10.music.126.net/20200508160923/a2ebdd0e073c7356aa5219943a5bf1be/ymusic/1c3c/b368/490e/375a0b1996f1c3cd02e7d19350574ad8.mp3`</md-audio>
```

# 音频 API

参数：`<标签>[音频地址, 循环, 自动播放]</标签>`

## 音频地址

- 相对地址/demo.mp3
- 远程网络地址需用反单引号 **\`https://www.xxx.com/demo.mp3\`** 进行包裹

## 音频循环播放

> 参数：loop

## 音频自动播放

> 参数：auto

由于大多数浏览器禁用自动播放功能，开启前请确认您的浏览器是否禁用该功能。

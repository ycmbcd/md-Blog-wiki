# # Tips

- 目录名不要出现空格，否则图片会挂；
- **.md** 文件中的空格用  `&nbsp;` 代替；
- 图片格式： `![图片名](图片地址)`，图片地址使用相对路径的图片，请保存在该 `.md` 文件夹内新建的文件夹中，如：`/md/demo/test.md`，图片可以保存在`/md/demo/images/pic.jpg`，请不要与文件同文件夹，否则会生成为一个博客，上传后的 `/md` 文件夹及其图片文件夹请保留，博客图片路径为原图片路径(为节约服务器容量及管理方便)；
```html
![IMAGE](images/pic.jpg)
```
- 对于Windows用户，无法生成以中文开头的文档和栏目的，请修改 /set/api/目录下：read_md.php、read_item.php。 两个文件，将注释切换为中文。默认是 Linux系统；
``` php
setlocale(LC_ALL, 'zh_CN.GBK'); // windows
setlocale(LC_ALL, 'zh_CN.UTF8'); // linux
```
- 如无法生成页面，请将目录赋予Apache来执行；
```bash
chown -R apache:apache * #在站点根目录执行
```

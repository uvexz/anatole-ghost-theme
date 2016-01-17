# Anatole Theme

---

***2015-12-05 11:48:45***

升级至0.0.2，修正了一处bug，新增了对多说的支持。

如何使用多说：

 ![duoshuo](https://ooo.0o0.ooo/2015/12/04/5662605c5141a.png) 

 在后台 `Code Injection` 的 `Blog Footer` 里插入：

     <script type="text/javascript">
     var duoshuoQuery = {short_name:"*****"}; //***** 换成你自己的多说ID
     (function() {
		var ds = document.createElement('script');
		ds.type = 'text/javascript';ds.async = true;
		ds.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') + '//static.duoshuo.com/embed.js';
		ds.charset = 'UTF-8';
		(document.getElementsByTagName('head')[0] 
		 || document.getElementsByTagName('body')[0]).appendChild(ds);
     })();
     </script>

---

Anatole 是由 [hi-caicai](https://github.com/hi-caicai) 制作的一款 Farbox 主题，原地址在： https://github.com/hi-caicai/farbox-theme-Anatole

---

因为很喜欢这个主题就把它移植到了 Ghost，本次移植非完美，没有分页、没有作者页、没有标签页、没加评论。

使用前请在后台设置每页显示文章为 `99` or more

---

现在有效的预览地址： https://yjk.im/

Win下的预览：

![Win](https://ooo.0o0.ooo/2015/11/19/564dd67357b9e.png)



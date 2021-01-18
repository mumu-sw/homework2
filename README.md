# homework2
第二期作业，截止1.26.

## 需求
利用这个api
http://api.hunsh.net/s1/?page=1&q=
做一个搜索

请求方法为Get，两个参数，page是页码，q是查询内容，均可空。返回的是一个json，包含数据和分页信息。

可以参考
http://ocw.ibeike.ustb.edu.cn/search?kw=%E6%95%B0%E5%AD%A6
不过别做的一样

可以做小程序，也可以做一个html单页（进阶需求）

## 指导

先Fork

小程序就`clone`你的fork仓库然后用开发者工具在这个项目目录创建新的小程序开发。这样能够直接流畅的使用git，不用想一期那样搞。

前端项目也是，clone之后在clone下来的目录开发，然后就可以流畅提交了。

前端会涉及跨域，我已经配好cors头，如果还有什么问题直接群里问。

然后这次clone就别用https地址了，用`git://`的地址，你需要在你的[账户设置](https://github.com/settings/keys)里添加ssh key以使用这个功能。

如果是去写html，你可以用原生，也可以用jQuery，也可以Vue.js。

最好写的是Vue，因为需要动态渲染，最懒的是原生和jQuery但是没Vue舒服。从这些年来说jQuery已经在逐渐落后，原生正常是没人去写的（因为兼容太差而且写得还难受）。

弄完之后还是一样，提交pr。

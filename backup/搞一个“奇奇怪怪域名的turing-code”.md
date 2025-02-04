我发现可以用一些奇奇怪怪的域名进turing-code！
比如`a.b/`  , `turing.code`
虽然这很好玩 ~~但你们不行~~
说实话只要改一下`hosts`文件就可以了！

首先，确保你有网，不然[Ping](https://www.cnblogs.com/meiguicong/p/13357735.html)不了
然后，使用 Windows徽标键 和 R 键一起按，打开下面这个窗口
![运行窗口](https://tse1-mm.cn.bing.net/th/id/OIP-C.JwqFS5Tvl-oWRO_8XN2kdwAAAA?rs=1&pid=ImgDetMain)
在里面输入`cmd`，回车
在里面输入
```cmd
ping www.turing-code.com
```

得到turing-code的IP地址
```
47.107.235.224
```
图片：

![Image](https://github.com/user-attachments/assets/1f341b8a-05ac-4c06-a47c-9b75f6310654)
# ↑ 上面的图片可能显示不出来 请谅解

具体以实际为主

得到之后，我们改[hosts](https://blog.csdn.net/nobleman__/article/details/85728156)

hosts文件一般存储在 `C:\Windows\System32\drivers\etc` 中，如不在，请自行在网上寻找位置

请遵循以下步骤更改hosts
1. 打开hosts文件，如需要打开方式，请使用记事本
2. 有些机型可能会显示需要获取[管理员权限](https://blog.csdn.net/zhaomomo0819/article/details/145445000?sharetype=blogdetail&sharerId=145445000&sharerefer=PC&sharesource=zhaomomo0819&spm=1011.2480.3001.8118)，请点击同意
3. 在后面写上这个：
```hosts
47.107.235.224 a.b
```
然后，你就可以用`a.b\`来访问turing-code了

# 好了，你可以走了

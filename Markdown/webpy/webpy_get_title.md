#webpy获取文章标题

在讲解怎样获取文章的标题之前，有必要讲讲每篇文章文件（MD文件）的格式内容：

* 每篇文章标题以'#'号开始（解析成html即为h1标题），且仅有此一个h1标题

所以，有这样的约束后，要获取文章标题就很简单了，直接一行一行读取MD文件，碰到第一个（标题永远是在最前面的嘛）'#'号开头的即为标题内容

文章标题就这样轻而易举的获取到了~

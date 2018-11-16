# go-program-beego
>应用于beego框架

##安装beego框架
###1.安装bee工具
* go env 检查是否配置$GOPATH
* go get github.com/beego/bee
* 安装完之后，bee可执行文件默认存放在$GOPATH/bin里面，所以需要您把$GOPATH/bin添加到您的环境变量中，才可以进行下一步。
* 我们在命令行输入bee，可以看到如下的信息：<br>
```
> bee
Bee is a tool for managing beego framework.

Usage:

    bee command [arguments]

The commands are:

    new         create an application base on beego framework
    run         run the app which can hot compile
    pack        compress an beego project
    api         create an api application base on beego framework
    bale        packs non-Go files to Go source files
    version     show the bee & beego version
    generate    source code generator
    migrate     run database migrations

```

###2.bee version
+ 检查是否安装Beego,安装命令:
 ```
 go get github.com/astaxie/beego
```


## 创建项目
```
cd $GOPATH/src
bee new $program_name

quickstart
|-- conf
|   `-- app.conf
|-- controllers
|   `-- default.go
|-- main.go
|-- models
|-- routers
|   `-- router.go
|-- static
|   |-- css
|   |-- img
|   `-- js
|-- tests
|   `-- default_test.go
`-- views
    `-- index.tpl
`  
quickstart
|-- conf
|   `-- app.conf
|-- controllers
|   `-- default.go
|-- main.go
|-- models
|-- routers
|   `-- router.go
|-- static
|   |-- css
|   |-- img
|   `-- js
|-- tests
|   `-- default_test.go
`-- views
    `-- index.tpl
```


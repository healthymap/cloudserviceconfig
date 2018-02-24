# knowledge_graphy_config_server
knowledge_graphy项目的云端配置


```
仓库中的配置文件会被转换成web接口，访问可以参照以下的规则：

/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties

```

即在浏览器中输入的路径会按照上面的规则，
切割并输入成对应的application,profile和label的值

---

在浏览器中访问 
```$xslt
/{application}/{profile}[/{label}]
```
对应的配置文件存储路径为
```$xslt
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
```

---
在浏览器中访问
```$xslt
/{application}/{profile}[/{label}]
```
对应的配置文件存储路径为
```$xslt
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties
```
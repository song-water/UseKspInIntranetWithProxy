# UseKspInIntranetWithProxy
在公司内网存在代理的情况下配置KSP (Use KSP in intranet with proxy.)  

新版本的 android studio 建议的导入插件的方法是   
```id 'org.jetbrains.kotlin.android' version '1.7.10' apply false```  
这样的，但是如果公司内网（大部分会通过代理访问外网）中这样使用，有可能是会出现找不到源的错误。    

最近在导入google ksp的时候就出现了这种情况，ksp 官方只提供了这种导入方法，没提供传统的导入的方法。   

本仓库照着旧版本改了下，可以使用旧版本方式导入插件，这可以方便的在公司内网中使用。 


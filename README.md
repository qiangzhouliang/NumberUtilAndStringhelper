# NumberUtilAndStringhelper 
使用地址：https://jitpack.io/#qiangzhouliang/NumberUtilAndStringhelper
# 1 如何引入自己的项目
## 1.1 将JitPack存储库添加到您的构建文件中
将其添加到存储库末尾的root（项目） build.gradle中：
~~~
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
~~~
## 1.2 添加依赖项
~~~
dependencies {
	  implementation 'com.github.qiangzhouliang:NumberUtilAndStringhelper:1.0.1'
}
~~~
# 2 如何使用
## 2.1 在要使用的地方写上如下代码
~~~
var numStr = "122.22"
println(NumUtil.doubleToInt(numStr))
~~~
# 3 版本更新说明
## 3.1 1.0.1 版本
封装了字符串和数字转换的一些操作




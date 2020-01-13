# Note : TEMP
SpringCloudRoot\build.gradle 中的 buildscript block:

`buildscript`裡是gradle脚本執行所需依賴，分别是對應的 maven repository 和 plugin

`allprojects`里是项目本身需要的依赖，比如我现在要依赖我自己maven库的toastutils库，那么我应该将maven {url 'https://dl.bintray.com/calvinning/maven'}写在这里，而不是buildscript中，不然找不到

參考資料：https://www.jianshu.com/p/ee57e4de78a3

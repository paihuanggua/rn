# rn
rn 坑总结

http://www.2cto.com/kf/201702/598658.html
react-native init AwesomeProject
cd AwesomeProject
react-native run-android
我在运行时候，出现了这样的问题：
Unzipping /Users/heqiqi/.gradle/wrapper/dists/gradle-2.14.1-all/8bnwg5hd3w55iofp58khbp6yv/gradle-2.14.1-all.zip to /Users/heqiqi/.gradle/wrapper/dists/gradle-2.14.1-all/8bnwg5hd3w55iofp58khbp6yv
Exception in thread "main" java.util.zip.ZipException: error in opening zip file

本地搜索/Users/heqiqi/.gradle/wrapper/dists/
如果出现了这样的问题，有可能是gradle-2.14.1-all.zip的问题，你需要到https://services.gradle.org/distributions 去下载一个gradle-2.14.1-all.zip，替换{用户目录}.gradle\wrapper\dists\gradle-2.4-all\6r4uqcc6ovnq6ac6s0txzcpc0\gradle-2.4-all.zip。这里的用户目录在windows上是C:\Users\你的电脑名称，在macOs上是/Users/你的电脑名称。

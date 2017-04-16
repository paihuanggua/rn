# rn
rn 坑总结

http://www.2cto.com/kf/201702/598658.html
react-native init AwesomeProject
cd AwesomeProject
react-native run-android
我在运行时候，出现了这样的问题：
error in opening zip file

如果出现了这样的问题，有可能是gradle-2.4-all.zip的问题，你需要到https://services.gradle.org/distributions 去下载一个gradle-2.4-all.zip，替换{用户目录}.gradle\wrapper\dists\gradle-2.4-all\6r4uqcc6ovnq6ac6s0txzcpc0\gradle-2.4-all.zip。这里的用户目录在windows上是C:\Users\你的电脑名称，在macOs上是/Users/你的电脑名称。

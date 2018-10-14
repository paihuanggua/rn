## Android

### 设置IP和端口

	-> Dev Settings
	-> Debug server host & port for device
	-> 设置IP和端口
	-> 返回
	-> Reload

### 没有找到assets下文件

	-> 在 android/app/src/main 目录下创建一个 assets空文件夹
	-> 在项目根目录运行 react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res/
	-> 重新react-native run-android


	



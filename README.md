# dimens-compat
尺寸适配module,适配大部分尺寸，快速使用
### 简书选择文章:[点击查看](https://www.jianshu.com/p/1302ad5a4b04)
### 添加屏幕：240dp,340dp,384dp,360dp,400dp,432dp,480dp,720dp,820dp,1024dp,1280dp
### 尺寸：1dp-360dp
### 字体如下：1sp-68sp

### 根目录添加：
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
}
```

### 指定module gradle
```
dependencies {
	        implementation 'com.github.SunnyLine:dimens-compat:v1.0.0'
}
```

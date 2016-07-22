#SnowLayout

---

![](https://jitpack.io/v/shellljx/SnowLayout.svg)

---

> 昨天看了徐医生的[费塞尔曲线艺术](https://github.com/xuyisheng/BezierArt)，然后把上面的例子手打了一遍，受益匪浅.下面的下雪的效果的Layout就是根绝费塞尔三阶曲线画出的轨迹.

---
#How to
---
**Step 1.**  Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:
```
	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```
---
**Step 2.** Add the dependency
```
	dependencies {
	        compile 'com.github.shellljx:SnowLayout:v1.0'
	}
```

<img src="./design/snow.png" width="380px"/>
<img src="./design/snow.gif" width="380"/>

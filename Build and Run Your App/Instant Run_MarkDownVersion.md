# 关于Instant Run的翻译。
原文地址：https://developer.android.com/studio/run/index.html#instant-run（2016.05.31）

<p>自Android Studio2.0引入的Instant Run 显著地减少了**Run**   和**Debug**   在部署app时的时间。不用重新编译一次app就能推送你做出的改动到app,这样代码的修改看起来就像及时的一样。
<p>Introduced in Android Studio 2.0, Instant Run is a behavior for the **Run** and **Debug**  commands that significantly reduces the time between updates to your app. Although your first build may take longer to complete, Instant Run pushes subsequent updates to your app without building a new APK, so changes are visible much more quickly.

<P>Instant Run的使用条件:

	1. 编译调试版本
	2. 使用的Android Gradle插件版本在2.0.0或更高
	3. module的 build.gradle的minSdkVersion 在15及以上
		1. 想要获取最高性能需要minSdkVersion 在21及以上

<p>部署完毕后在**Run**（或者**Debug**）按钮的图标中会出现一个黄色的小闪电图标，这标识Instant Run已经可以使用了，当你下一次使用这两个命令的时候，Android Studio 会推送你所做的更改，在一些情况下甚至不用重启app你能看到新代码的效果。


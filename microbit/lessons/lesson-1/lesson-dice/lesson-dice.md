# 掷骰子

## Introduction @unplugged

康和康妈@boardname@系列教程 **掷骰子**

![你好](https://github.com/ihuanglei/pxt-ylwl-tutorials/blob/master/microbit/assets/dice.gif?raw=true)

## 第一步 @fullscreen

请小朋友们拖出积木块 ``||input:on shake||``

```blocks
input.onGesture(Gesture.Shake, function () {
	
})
```

## 第二步 @fullscreen

请小朋友们拖出积木块 ``||basic:show number||``，放到 ``||input:on shake||``中

```blocks
input.onGesture(Gesture.Shake, function () {
	basic.showNumber(0)
})
```

## 第三步 @fullscreen

请小朋友们拖出积木块 ``||math:pick random||``，放到 ``||basic:show number||`` **0** 的地方

```blocks
input.onGesture(Gesture.Shake, function () {
	basic.showNumber(Math.randomRange(0, 10))
})
```

## 第四步 @fullscreen

请小朋友们把 ``||math:pick random||`` 的 **0** 改成 **1** ，**10** 改成 **6**

```blocks
input.onGesture(Gesture.Shake, function () {
	basic.showNumber(Math.randomRange(1, 6))
})
```

## 第五步 @fullscreen

小朋友们观看左边@boardname@模拟器的展示，然后点击 **SHAKE**，观察数字的变化，是不是很简单:)

## 第六步 @fullscreen

如果小朋友们身边有@boardname@ 点击 ``|Download|`` 下载文件，然后复制到@boardname@中。

# 心跳

## Introduction @unplugged

康和康妈@boardname@系列教程 **心 跳**

![心跳](https://github.com/ihuanglei/pxt-ylwl-tutorials/blob/master/assets/flashheart.gif?raw=true)

## 第一步 @fullscreen

请小朋友们拖出积木块 ``||basic:clear screen||`` 放到 ``||basic:forever||`` 中

```blocks
basic.forever(function () {
    basic.clearScreen()
})
```

## 第二步 @fullscreen

请小朋友们拖出积木块 ``||basic:pause||`` 放到 ``||basic:forever||`` 中

```blocks
basic.forever(function () {
    basic.clearScreen()
    basic.pause(200)
})
```

## 第三步 @fullscreen

请小朋友们把积木块 ``||basic:pause||`` 的时间改成500

```blocks
basic.forever(function () {
    basic.clearScreen()
    basic.pause(500)
})
```

## 第四步 @fullscreen

请小朋友们拖出积木块 ``||basic:show icon||`` 放到 ``||basic:forever||`` 中

```blocks
basic.forever(function () {
    basic.clearScreen()
    basic.pause(500)
    basic.showIcon(IconNames.Heart)
})
```

## 第五步 @fullscreen

小朋友们观看左边@boardname@模拟器的展示，是不是很简单:)

## 第六步 @fullscreen

如果小朋友们身边有@boardname@ 点击 ``|Download|`` 下载文件，然后复制到@boardname@中。

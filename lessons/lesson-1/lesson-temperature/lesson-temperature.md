# 温度计

## Introduction @unplugged

康和康妈@boardname@系列教程 **温度计**

![微笑](https://github.com/ihuanglei/pxt-ylwl-tutorials/blob/master/assets/temperature.gif?raw=true)

## 第一步 @fullscreen

请小朋友们拖出积木块 ``||input:on button A pressed||``

```blocks
input.onButtonPressed(Button.A, function () {

})
```

## 第二步 @fullscreen

请小朋友们找到 ``||variables: variables||`` 点击 ``||variables: make a variable...||``，创建一个变量 **temp** 然后把 ``||variables: set temp to 0||``  拖到 ``||input:on button A pressed||`` 中

```blocks
let temp = 0
input.onButtonPressed(Button.A, function () {
    temp = 0
})
```

## 第三步 @fullscreen

请小朋友们拖出积木块 ``||input: temperature||`` 放到 ``||variables: set temp to 0||`` 中

```blocks
let temp = 0
input.onButtonPressed(Button.A, function () {
    temp = input.temperature()
})
```

## 第四步 @fullscreen

请小朋友们拖出积木块 ``||basic:show string||`` 放到 ``||input:on button A pressed||`` 中

```blocks
let temp = 0
input.onButtonPressed(Button.A, function () {
    temp = input.temperature()
    basic.showString("hello")
})
```

## 第五步 @fullscreen

请小朋友们拖出积木块 ``||variables: temp||`` 放到 ``||basic:show string||`` 中

```blocks
let temp = 0
input.onButtonPressed(Button.A, function () {
    temp = input.temperature()
    basic.showString(temp)
})
```

## 第六步 @fullscreen

小朋友们观看左边@boardname@模拟器的展示，点击 **A** 按钮，LED会显示当前的温度哦！是不是很简单:)

## 第七步 @fullscreen

如果小朋友们身边有@boardname@ 点击 ``|Download|`` 下载文件，然后复制到@boardname@中。

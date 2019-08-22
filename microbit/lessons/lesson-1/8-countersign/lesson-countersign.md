# 暗号

## Introduction @unplugged

康和康妈@boardname@系列教程 **暗 号**

![暗号](https://github.com/ihuanglei/pxt-ylwl-tutorials/blob/master/microbit/assets/countersign.gif?raw=true)

## 第一步 @fullscreen

请小朋友们拖出积木块 ``||radio:set group||`` 放到 ``||basic:on start||`` 中

```blocks
radio.setGroup(1)
```

## 第二步 @fullscreen

请小朋友们拖出积木块 ``||input:on button A pressed||``

```blocks
radio.setGroup(1)
input.onButtonPressed(Button.A, function () {

})
```

## 第三步 @fullscreen

请小朋友们拖出积木块 ``||radio:send string||``，放到 ``||input:on button A pressed||`` 中

```blocks
radio.setGroup(1)
input.onButtonPressed(Button.A, function () {
    radio.sendString("")
})
```

## 第四步 @fullscreen

请小朋友们在 ``||radio:send string||`` 中输入 **hi**

```blocks
radio.setGroup(1)
input.onButtonPressed(Button.A, function () {
    radio.sendString("hi")
})
```

## 第五步 @fullscreen

请小朋友们拖出积木块 ``||radio:on received string||``

```blocks
radio.setGroup(1)
input.onButtonPressed(Button.A, function () {
    radio.sendString("hi")
})
radio.onReceivedString(function (receivedString) {
})
```

## 第六步 @fullscreen

请小朋友们拖出积木块 ``||basic:show string||`` 放到 ``||radio:on received string||`` 中

```blocks
radio.setGroup(1)
input.onButtonPressed(Button.A, function () {
    radio.sendString("hi")
})
radio.onReceivedString(function (receivedString) {
    basic.showString("hello")
})
```

## 第七步 @fullscreen

请小朋友们修改 ``||basic:show string||`` 的值为 **received string**，鼠标选中 ``||radio:on received string||`` 的 **received string** 拖动到 ``||basic:show string||`` 上

```blocks
radio.setGroup(1)
input.onButtonPressed(Button.A, function () {
    radio.sendString("hi")
})
radio.onReceivedString(function (receivedString) {
    basic.showString(receivedString)
})
```

## 第八步 @fullscreen

小朋友们观看左边@boardname@模拟器的展示，有两块@boardname@ ，点击上面的**A**按钮，下面的@boardname@会显示**hi**，是不是很简单:)

## 第九步 @fullscreen

如果小朋友们身边有@boardname@ 点击 ``|Download|`` 下载文件，然后复制到@boardname@中。

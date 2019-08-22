# 变脸

## Introduction @unplugged

康和康妈@boardname@系列教程 **变 脸**


![变脸](https://github.com/ihuanglei/pxt-ylwl-tutorials/blob/master/microbit/assets/button.gif?raw=true)

## 第一步 @fullscreen

请小朋友们拖出积木块 ``||input:on button A pressed||``

```blocks
input.onButtonPressed(Button.A, function () {

})
```

## 第二步 @fullscreen

请小朋友们拖出LED积木块 ``||basic:show leds||`` 放到 ``||input:on button A pressed||`` 中

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showLeds(`
            . . . . .
            . . . . .
            . . . . .
            . . . . .
            . . . . .
            `)
})
```


## 第三步 @fullscreen

请小朋友们在LED积木块上画一个微笑

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        # . . . #
        . # # # .
        . . . . .
        `)
})
```

## 第四步 @fullscreen

请小朋友们拖出积木块 ``||input:on button A pressed||``

```blocks
input.onButtonPressed(Button.A, function () {

})
```

## 第五步 @fullscreen

请小朋友们把 **A** 换成 **B**

```blocks
input.onButtonPressed(Button.B, function () {

})
```

## 第六步 @fullscreen

请小朋友们拖出LED积木块 ``||basic:show leds||`` 放到 ``||input:on button B pressed||`` 中

```blocks
input.onButtonPressed(Button.B, function () {
    basic.showLeds(`
            . . . . .
            . . . . .
            . . . . .
            . . . . .
            . . . . .
            `)
})
```

## 第七步 @fullscreen

请小朋友们在LED积木块上画一个苦笑

```blocks
input.onButtonPressed(Button.B, function () {
    basic.showLeds(`
            . . . . .
            . . . . .
            . # # # .
            # . . . #
            . . . . .
            `)
})
```

## 第八步 @fullscreen

小朋友们观看左边@boardname@模拟器的展示，点击 **A** 按钮，有没有微笑，再点击 **B** 看看呢？是不是很简单:)

## 第九步 @fullscreen

如果小朋友们身边有@boardname@ 点击 ``|Download|`` 下载文件，然后复制到@boardname@中。

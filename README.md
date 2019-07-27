# Basic Led

## Introduction @unplugged

原来网络，康和康妈第一节课

## Step 1 @fullscreen

请小朋友在``||basic:forever||``中间拖出积木``||basic:show leds||``

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})
```

## Step 2 @fullscreen

请小朋友在``||input:on button A pressed||``

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showLeds(`
        . . . . .
        . # # # .
        . # # # .
        . # # # .
        . . . . .
        `)
})
```

## Step 3 @fullscreen

step 3

## Step 4 @fullscreen

If you have a @boardname@ connected, click ``|Download|`` to transfer your code and watch the hearts flash!
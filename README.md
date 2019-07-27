# Basic Led

## Introduction @unplugged

hello!!

## Step 1 @fullscreen

Place the ``||basic:show leds||`` block in the ``||basic:forever||`` block and draw a heart.

## Step 2 @fullscreen

Place another ``||basic:show leds||`` block. You can leave it blank and draw what you want.

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
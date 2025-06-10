# Micro LED

## Toggle an LED

Drag the code to toggle an LED.

```blocks
basic.forever(function () {
    led.toggle(0, 0)
})
```

## All the code

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```
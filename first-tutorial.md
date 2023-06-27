# Create a Character

## Introduction 

Explore with the robot!

## Step One

Add an ``||game:on game update every||`` block to the workspace.

```python
def on_update():
    pass
game.on_update(on_update)
```

## Step Two

Use a ``||sprites:create sprite||`` block to make some enemies.

```python
def on_update():
    my_sprite = sprites.create(img("""
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . 
"""), SpriteKind.player)
game.on_update(on_update)
```

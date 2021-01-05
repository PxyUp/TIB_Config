# TIB_Config

# Validate:

```
t.levels.every(e => e.lifes === e.elements.reduce((p, c) => p + c.life, 0))
```
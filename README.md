# Array 2D

[Gren](https://gren-lang.org/) package for working with 2-dimensional arrays (array of arrays).

Useful in game dev and other architectures where you are often working with a 2-dimensional grid.

```elm
myGrid =
    [ [ Grass, Grass, Grass ]
    , [ Water, Grass, Grass ]
    ]

Array2d.get { x = 0, y = 1 } myGrid == Water
```

[Package docs](https://packages.gren-lang.org/package/blaix/gren-array2d/latest/overview)

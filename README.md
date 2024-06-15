# Array 2D

[Gren](https://gren-lang.org/) package for working with 2-dimensional arrays (array of arrays).

Useful in game dev and other architectures where you are often working with a 2-dimensional grid.

```elm
myGrid =
    [ [ Grass, Grass, Grass ]
    , [ Grass, Grass, Water ]
    ]

-- Functions that take coordinates follow "row, column" semantics:
Array2d.get 1 2 == Water
```

[Package docs](https://packages.gren-lang.org/package/blaix/gren-array2d/latest/overview)

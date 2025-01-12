# 4.0.0 (2025-01-01)

* Update to gren 0.5
* `filter` renamed to `keepIf`.
* `filterMap` renamed to `mapAndKeepJust`.
* findFirst and findLast return `Maybe { index : { x : Int, y : Int }, value : a }` instead of just the value.

# 3.0.0 (2024-07-04)

* Update to gren 0.4

# 2.0.0 (2024-06-16)

* Function passed to `initialize` now takes `{ x, y }` record instead of positional args.

# 1.0.0 (2024-06-16)

* Initial version

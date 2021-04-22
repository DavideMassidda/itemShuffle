# Shuffling of items

R function for random shuffling of items of a psychometric test with constraints.

## Usage

```
item_shuffle(item, id = NULL, scale = NULL, tolerance = 0, fixed = NULL)
```

+ `item` Character vector containing the text of the items.

+ `id` Vector coding the identity of items.

+ `scale` Vector indicating the scale of each item.

+ `tolerance` Maximum number of items of the same scale that can be placed consecutively.

+ `fixed` Positions of fixed items, not to randomize.

If the `scale` argument is specified, items will be randomized within each scale. `fixed` items, if specified, will be left in the same position of the original vector.

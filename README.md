# Fruit Salad with Yogurt — food-picture-01

A natural, homemade-style Asian fruit salad: mango, dragon fruit,
rambutan, mangosteen and lychee with mint leaves and creamy yogurt
drizzled over the top, in a plain bowl on a wooden table.

`main.py` copies `assets/entry.png` (a real PNG, 1024x1024 max,
under 1 MiB) to the output directory as `entry.png`, failing loudly
if the file is not a PNG, is too large, or is truncated.

Run it:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Without `MAKEFUN_OUTPUT_DIR` it writes to `/output`.

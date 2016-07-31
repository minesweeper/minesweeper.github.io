# minesweeper react widget

You can either check out this amazing technology by browsing here https://minesweeper.github.io

Or you can embed any number of minesweeper games in your own page by including the following:

```html
<div class="minesweeper-game" data-preset="expert"></div>
<script src="https://minesweeper.github.io/d427230c9b51c152e09b9242c7acf0e8de5c8728.js"></script>
```

The following presets are available: `beginner`, `intermediate` and `expert`.

If your preference is to embed a minesweeper game that will play itself (to save your users the trouble) then you may include the following:

```html
<div class="minesweeper-game"></div>
<div class="minesweeper-game" data-preset="expert" data-robot="200"></div>
<script src="https://minesweeper.github.io/d427230c9b51c152e09b9242c7acf0e8de5c8728.js"></script>
```

Here `200` is the number of milliseconds the robot player should wait between successive turns.  If your users are really busy or you just want them to be able to cook food using their cpu fan then you may set this value to `0`.


# minesweeper react widget

You can either check out this amazing technology by browsing here https://minesweeper.github.io

Or you can embed any number of minesweeper games in your own page by including the following:

```html
<div class="minesweeper-game" data-preset="expert"></div>
<script src="https://minesweeper.github.io/a70de4b14c0109772a9dc7a4d43a2657210cc7d1.js"></script>
```

The following presets are available: `beginner`, `intermediate` and `expert`.

If your preference is to embed a minesweeper game that will play itself (to save your users the trouble) then you may include the following:

```html
<div class="minesweeper-game" data-preset="expert" data-robot="200"></div>
<script src="https://minesweeper.github.io/a70de4b14c0109772a9dc7a4d43a2657210cc7d1.js"></script>
```

Here `200` is the number of milliseconds the robot player should wait between successive turns.  If your users are really busy or you just want them to be able to cook food using their cpu fan then you may set this value to `0`.

Alternatively, you can add a minesweeper controller which will allow users to stop and start the robot player and adjust the speed:

```html
<div class="minesweeper-game" data-preset="expert" data-name="expert1"></div>
<div class="minesweeper-controller" data-name="expert1"></div>
<script src="https://minesweeper.github.io/a70de4b14c0109772a9dc7a4d43a2657210cc7d1.js"></script>

Note that the name must match or the controller will be unable to locate the minesweeper game.
```



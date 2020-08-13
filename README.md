# a e s t h e t i c

Style-related tools that I re-use across projects in astronomy.

Most relevant are the style sheets, which produce default plots as in the
`/results/` directory.

__install__
Clone + `python setup.py install` from the repo. (or develop!)

__contents__

`aesthetic.plot`
* `set_style`
* `set_style_scatter`
* `savefig`
* `format_ax`

`aesthetic.paper`
* `abbreviate_the_bibliography`

__usage examples__
```
from aesthetic.plot import set_style, set_style_grid
set_style()
```

<img src="https://github.com/lgbouma/aesthetic/blob/master/results/plot_standard.png" width="500">

```
set_style_grid()
```

<img src="https://github.com/lgbouma/aesthetic/blob/master/results/plot_grid.png" width="500">

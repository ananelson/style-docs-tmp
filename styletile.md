<h2>Style Tile</h2>

Note that if you want to include a whole file, you can just do so like this:

{{ d['components/styletile.html'] }}

<h2>Color Pallet</h2>

{{ d['components/color-pallet.html|htmlsections']['color-stack'] }}
{{ d['components/color-pallet.html|htmlsections']['tint-stack'] }}

# SnowyMD 🌨️ *(v2.1)* [BLIZZARD](https://h)

> A html preprocessor designed as a empowered markdown
> <br/> File Extension *.smd*
> <br/> Compiles into a flake.html file
> <br/> Comments are declared with `*`
> <br/> [Website](https://snojs.github.io/snowyMD)<br/>
> For Script tags use $`.SRC


|Commands|HTML equivilant|
|-----------|-----------|
|`$t.TITLE`|`<title>{TITLE}</title>`|
|`&head`|`</head> (MUST USE AFTER THE HEAD CONTENT LIKE TITLE)`|
|`$#.CLASSES\|TEXT`|`<h1 class={CLASSES}>{TEXT}</h1>`|
|`$##.CLASSES\|TEXT`|`<h2 class={CLASSES}>{TEXT}</h2>`|
|`$###.CLASSES\|TEXT`|`<h3 class={CLASSES}>{TEXT}</h3>`|
|`$!.CLASSES\|TEXT`|`<span class={CLASSES}>{TEXT}</span>`|
|`* Comment`|`{nothing}`|
|`$%.CLASSES`|`<div class={CLASSES}>`|
|`$^`|`</div>`|
|`$x.CLASSES\|TEXT`|`Button tag (use $l. for onclick="")`|
|`$=LINK`|`<link rel="stylesheet" href={link}/>`|
|`$&.RGB`|`<style>body{background-color:{RGB};}</style>`|
|`$br0`|`0 is repleaceable with a 1 digit num to <br/>`|
|`$l.HREF`|`(Saves HREF for use in <a> tag)`|
|`$a.CLASSES\|TEXT`|`<a href={L}class={CLASSES}>{TEXT}</a>`|
|`$i.CLASSES\|TEXT`|`<i class={CLASSES}>{TEXT}</i>`|
|`$+.CLASSES\|LINK`|`<img src={LINK} class={CLASSES}`|
|`$f.ICON`|`<link rel="icon" type="x-icon" href={ICON}>`|

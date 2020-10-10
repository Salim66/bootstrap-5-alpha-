## Bootstrap 5 Alpha Learning

### Utilitis

#### Bootstrap Colors
```html
- primary
- secondary
- success
- info 
- warning
- danger
- dark
- light
- white
- white-50
- body
- muted
- black-50
```

#### Text
```javaScript
- text-color
- bg-color
- bg-gradient
- text-align-(left, right, center)
- text-(wrap, nowrap)
- text-break
- text-reset
- text-transform (uppercase, lowercase, capitalize)
- font-weight-(lighter, light, normal, bold, bolder)
- font-italic
- lh-(1, sm, base, lg)
- font-monospace
- text-decoration-(none, underline, line-through)

```

#### Sizing
```javaScript
- w-(25, 50, 75, 100)
- mw-(25, 50, 75, 100)
- h-(25, 50, 75, 100)
- mh-(25, 50, 75, 100)

```

#### Spacing
```javaScript
- p-(1, 2, 3, 4, 5)
- pt-(1, 2, 3, 4, 5)
- pl-(1, 2, 3, 4, 5)
- pr-(1, 2, 3, 4, 5)
- pb-(1, 2, 3, 4, 5)

- m-(1, 2, 3, 4, 5)
- mt-(1, 2, 3, 4, 5)
- ml-(1, 2, 3, 4, 5)
- mr-(1, 2, 3, 4, 5)
- mb-(1, 2, 3, 4, 5)

```

#### Vertical align
```javaScript
- align-(baseline, top, bottom, middle, text-top, text-bottom)

```

#### Visibility
```javaScript
- visible
- invisible

```

#### Shadow
```javaScript
- shadow-(none, sm, lg)
- shadow

```

#### Position
```javaScript
- position-(static, relative, absolute, fixed, sticky)
- top-(0, 50,100)
- bottom-(0, 50,100)
- left-(0, 50,100)
- right-(0, 50,100)
- center elements (translate-middle)

```

#### Overflow
```javaScript
- overflow-(hidden, auto)

```

#### Interactions
```javaScript
- user-select-(all,auto,none)

```

#### Float
```javaScript
- float-(left, right, none)

```

#### Display
```javaScript
- d-(block, inline, inline-block, table)

```

#### Border
```javaScript
- border
- border-color
- border-(1, 2, 3, 4, 5)
- rounded-(top, left, right, bottom, circle, pill, 0)

```

### Helpers
```javaScript
- clearfix
- colored links (link-primary, link-secondary, .....)
- ratio
- ratio-(1x1, 4x3, 16x9, 21x9)
- position (fixed-top, fixed-bottom, sticky-top)
- visibility-(hidden, hidden-focusable)
- text-truncate

```

### Components
```javaScript
- alert
- badge
- breadcrumb

===Button===
- button (btn-color, btn-outline-color, btn-sm, btn-lg, btn-block,)
- btn-group, active, btn-check, btn-toolbar, btn-group-sm, btn-group-lg, btn-group-vertical

===Card===
- card
- card-(header, body, footer, title, text, link)

===Carousel Slide===
- carousel, slide, data-ride='carousel'
- carousel-(inner, item, control-prev, control-next, control-prev-icon, control-next-icon)
- data-slide="prev"
- data-slide="next"
- aria-hidden="true"
- carousel-indicators, data-target="#", data-slide-to="0"
- carousel-fade
- data-interval="times"
- data-pause="true/hover"
- data-wrap="true/false"

===Collapse===
- collapse
- data-toggle="collapse"
- data-target="#"
- accordion
- data-parent="#"

===Dropdown===
- dropdown
- dropdown-(menu, item, toggle)
- data-toggle="dropdown"
- dropdown-divider

===Modal===
- modal, fade
- modal-(dialog, content, header, body, footer)

===Nav===
- nav, nav-item, nav-link
- nav-tabs, nav-pills

===Navbar===
- navbar, navbar-brand, navbar-item, navbar-link, navbar-expand-(sm, md, lg)
- navbar-light, bg-light

===Pagination===
- pagination, page-item, page-link

===PopOver===
- data-toggle="popover", title="", data-content="", data-trigger="focus"

===Progress===
- progress, progress-bar, progress-bar-striped, progress-bar-animated, style="%"

===Scrollspy===
<ul class="nav sticky-top">
		<li class="nav-item"><a class="nav-link" href="#Home">Home</a></li>
		<li class="nav-item"><a class="nav-link" href="#About">About</a></li>
		<li class="nav-item"><a class="nav-link" href="#Blog">Blog</a></li>
		<li class="nav-item"><a class="nav-link" href="#Course">Course</a></li>
		<li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
	</ul>

<div class="content">
		<div id="Home">
			<h1>Home</h1>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad eaque, odio nemo </p>
		</div>
		<div id="About">
			<h1>About</h1>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad eaque, odio nemo ipsam aut?</p>
		</div>
		<div id="Blog">
			<h1>Blog</h1>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad eaque, odio nemo ipsam aut?</p>
		</div>
		<div id="Course">
			<h1>Course</h1>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad eaque, odio nemo ipsam aut?</p>
		</div>
		<div id="Contact">
			<h1>Contact</h1>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad eaque, odio nemo ipsam aut?</p>
		</div>
</div>

===Spinners===
- spinner-(border, grow, border-sm), aria-hidden="true"
- visually-hidden

===Toast===
- toast-(header, body, footer)

===Tooltips==
- data-toggle="tooltip"
- data-placement="top,right,left,bottom"
- title=""

```


###Form
```javaScript
- form-label, form-control, form-control-lg/sm, form-control-color
- form-select, form-select-lg/sm
- form-(check, check-label, check-control, switch, check-inline)
- form-(file, file-input, file-label, file-text, file-button)
- range, form-range
- input-(group, group-text)

```

###Layout
```html
===Grid===
	<div class="container">
	  <div class="row">
	    <div class="col-sm">
	      One of three columns
	    </div>
	    <div class="col-sm">
	      One of three columns
	    </div>
	    <div class="col-sm">
	      One of three columns
	    </div>
	  </div>
	</div>

===Grid Option===
- Extra small(xs) 0px-575px
- Small(sm) 576px-767
- Medium(md) 768px-991px
- Large(lg) 992px-1199px
- Extra Large(xl) 1200px-1399px
- Extra Extra Large(xxl) 1400px......

$grid-columns:      12;
$grid-gutter-width: 1.5rem;

$grid-breakpoints: (
  xs: 0,
  sm: 576px,
  md: 768px,
  lg: 992px,
  xl: 1200px,
  xxl: 1400px
);

$container-max-widths: (
  sm: 540px,
  md: 720px,
  lg: 960px,
  xl: 1140px,
  xxl: 1320px
);


```
